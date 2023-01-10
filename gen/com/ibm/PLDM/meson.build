# Generated file; do not modify.
subdir('PCIeTopology')
generated_others += custom_target(
    'com/ibm/PLDM/PCIeTopology__markdown'.underscorify(),
    input: [ '../../../../yaml/com/ibm/PLDM/PCIeTopology.interface.yaml',  ],
    output: [ 'PCIeTopology.md' ],
    depend_files: sdbusplusplus_depfiles,
    command: [
        sdbuspp_gen_meson_prog, '--command', 'markdown',
        '--output', meson.current_build_dir(),
        '--tool', sdbusplusplus_prog,
        '--directory', meson.current_source_dir() / '../../../../yaml',
        'com/ibm/PLDM/PCIeTopology',
    ],
)

