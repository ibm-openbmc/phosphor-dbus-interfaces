# Generated file; do not modify.
generated_sources += custom_target(
    'xyz/openbmc_project/Control/Host__cpp'.underscorify(),
    input: [ '../../../../../yaml/xyz/openbmc_project/Control/Host.interface.yaml',  ],
    output: [ 'error.cpp', 'error.hpp', 'server.cpp', 'server.hpp', 'client.hpp',  ],
    command: [
        sdbuspp_gen_meson_prog, '--command', 'cpp',
        '--output', meson.current_build_dir(),
        '--tool', sdbusplusplus_prog,
        '--directory', meson.current_source_dir() / '../../../../../yaml',
        'xyz/openbmc_project/Control/Host',
    ],
)

subdir('NMI')
generated_others += custom_target(
    'xyz/openbmc_project/Control/Host/NMI__markdown'.underscorify(),
    input: [ '../../../../../yaml/xyz/openbmc_project/Control/Host/NMI.interface.yaml',  ],
    output: [ 'NMI.md' ],
    command: [
        sdbuspp_gen_meson_prog, '--command', 'markdown',
        '--output', meson.current_build_dir(),
        '--tool', sdbusplusplus_prog,
        '--directory', meson.current_source_dir() / '../../../../../yaml',
        'xyz/openbmc_project/Control/Host/NMI',
    ],
)

subdir('TurboAllowed')
generated_others += custom_target(
    'xyz/openbmc_project/Control/Host/TurboAllowed__markdown'.underscorify(),
    input: [ '../../../../../yaml/xyz/openbmc_project/Control/Host/TurboAllowed.interface.yaml',  ],
    output: [ 'TurboAllowed.md' ],
    command: [
        sdbuspp_gen_meson_prog, '--command', 'markdown',
        '--output', meson.current_build_dir(),
        '--tool', sdbusplusplus_prog,
        '--directory', meson.current_source_dir() / '../../../../../yaml',
        'xyz/openbmc_project/Control/Host/TurboAllowed',
    ],
)

