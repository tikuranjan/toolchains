package(default_visibility = ['//visibility:public'])

filegroup(
  name = 'gcc',
  srcs = [
    'bin/xtensa-esp32-elf-gcc',
  ],
)

filegroup(
  name = 'ar',
  srcs = [
    'bin/xtensa-esp32-elf-ar',
  ],
)

filegroup(
  name = 'ld',
  srcs = [
    'bin/xtensa-esp32-elf-ld',
  ],
)

filegroup(
  name = 'nm',
  srcs = [
    'bin/xtensa-esp32-elf-nm',
  ],
)

filegroup(
  name = 'objcopy',
  srcs = [
    'bin/xtensa-esp32-elf-objcopy',
  ],
)

filegroup(
  name = 'objdump',
  srcs = [
    'bin/xtensa-esp32-elf-objdump',
  ],
)

filegroup(
  name = 'strip',
  srcs = [
    'bin/xtensa-esp32-elf-strip',
  ],
)

filegroup(
  name = 'as',
  srcs = [
    'bin/xtensa-esp32-elf-as',
  ],
)

filegroup(
  name = 'compiler_pieces',
  srcs = glob([
    'xtensa-esp32-elf/**',
    'libexec/**',
    'lib/gcc/xtensa-esp32-elf/**',
    'include/**',
  ]),
)

filegroup(
  name = 'compiler_components',
  srcs = [
    ':gcc',
    ':ar',
    ':ld',
    ':nm',
    ':objcopy',
    ':objdump',
    ':strip',
    ':as',
  ],
)

