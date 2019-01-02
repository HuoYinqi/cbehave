sources = files(['cbehave.c'])

incdir = include_directories('.')
		
lib = static_library('cbehave', sources,
			include_directories : incdir)

lib_dep = declare_dependency(link_with : lib, include_directories: incdir)