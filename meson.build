project('tutorial', 'c',
	version: 'IDLES Ultra Mono: War',
	license: 'Unlicence'
)

inc = include_directories('include')

subdir('src')

gtkdep = dependency('gtk4')

exe = executable(
	'app',
	sources,
	dependencies: gtkdep,
	include_directories: inc
)

test('testing if works', exe)
