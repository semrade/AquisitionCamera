project('aravis-c-examples', 'c', version: '0.0.1')

aravis_dep = dependency('aravis-0.8')
libpng_dep = dependency('libpng')
examples = [
  '01-single-acquisition',
  '02-multiple-acquisition',
  '02-multiple-acquisition-signal',
  '03-camera-api',
  '04-camera-features',
  '05-chunk-parser'
]

foreach e: examples
  exe = executable (e, e + '.c', dependencies: [aravis_dep,libpng_dep])
endforeach
