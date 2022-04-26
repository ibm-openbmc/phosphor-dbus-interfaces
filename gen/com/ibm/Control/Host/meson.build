# Generated file; do not modify.
subdir('PCIeLink')
generated_others += custom_target(
    'com/ibm/Control/Host/PCIeLink__markdown'.underscorify(),
    input: [ '../../../../../yaml/com/ibm/Control/Host/PCIeLink.interface.yaml',  ],
    output: [ 'PCIeLink.md' ],
    command: [
        sdbuspp_gen_meson_prog, '--command', 'markdown',
        '--output', meson.current_build_dir(),
        '--tool', sdbusplusplus_prog,
        '--directory', meson.current_source_dir() / '../../../../../yaml',
        'com/ibm/Control/Host/PCIeLink',
    ],
)

