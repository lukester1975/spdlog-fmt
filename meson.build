project('spdlog-fmt', 'cpp', version: '0.0.0')

spdlog = dependency('spdlog', static: true, default_options: ['compile_library=true', 'external_fmt=enabled'])
fmt = dependency('fmt', static: true)

executable('spdlog-fmt', 'main.cpp', dependencies: [fmt, spdlog])
