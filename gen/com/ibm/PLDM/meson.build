# Generated file; do not modify.
subdir('ChapData')
generated_others += custom_target(
    'com/ibm/PLDM/ChapData__markdown'.underscorify(),
    input: [ '../../../../yaml/com/ibm/PLDM/ChapData.interface.yaml',  ],
    output: [ 'ChapData.md' ],
    depend_files: sdbusplusplus_depfiles,
    command: [
        sdbuspp_gen_meson_prog, '--command', 'markdown',
        '--output', meson.current_build_dir(),
        '--tool', sdbusplusplus_prog,
        '--directory', meson.current_source_dir() / '../../../../yaml',
        'com/ibm/PLDM/ChapData',
    ],
)

