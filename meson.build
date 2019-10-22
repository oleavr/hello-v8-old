project('hello-v8', 'cpp',
  version : '1.0.0',
  license : 'mit'
)

v8_dep = dependency('v8-7.0')

sources = [
  'hello.cc',
]

executable('hello-v8', sources,
  dependencies : [v8_dep],
  install : true
)
