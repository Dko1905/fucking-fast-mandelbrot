project(
	'ffm',
	'cpp',
	license: 'GPL-3.0-or-later',
	default_options: [
		'cpp_std=c++17',
		'warning_level=1',
		'werror=false'
	],
)

threads = dependency('threads')

executable(
	'ffm',
	[
		'src/main.cpp',
	],
	dependencies: [
		threads
	],
	include_directories: [
		include_directories('src')
	]
)
