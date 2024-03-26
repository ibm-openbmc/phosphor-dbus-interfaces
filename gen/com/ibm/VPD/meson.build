# Generated file; do not modify.
subdir('Manager')
generated_others += custom_target(
    'com/ibm/VPD/Manager__markdown'.underscorify(),
    input: [ '../../../../yaml/com/ibm/VPD/Manager.interface.yaml',  ],
    output: [ 'Manager.md' ],
    depend_files: sdbusplusplus_depfiles,
    command: [
        sdbuspp_gen_meson_prog, '--command', 'markdown',
        '--output', meson.current_build_dir(),
        '--tool', sdbusplusplus_prog,
        '--directory', meson.current_source_dir() / '../../../../yaml',
        'com/ibm/VPD/Manager',
    ],
)

subdir('Parser')
generated_others += custom_target(
    'com/ibm/VPD/Parser__markdown'.underscorify(),
    input: [ '../../../../yaml/com/ibm/VPD/Parser.errors.yaml',  ],
    output: [ 'Parser.md' ],
    depend_files: sdbusplusplus_depfiles,
    command: [
        sdbuspp_gen_meson_prog, '--command', 'markdown',
        '--output', meson.current_build_dir(),
        '--tool', sdbusplusplus_prog,
        '--directory', meson.current_source_dir() / '../../../../yaml',
        'com/ibm/VPD/Parser',
    ],
)

