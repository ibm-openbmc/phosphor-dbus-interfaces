# Generated file; do not modify.
subdir('PCIeLink')

sdbusplus_current_path = 'com/ibm/Control/Host'

generated_markdown += custom_target(
    'com/ibm/Control/Host/PCIeLink__markdown'.underscorify(),
    input: ['../../../../../yaml/com/ibm/Control/Host/PCIeLink.interface.yaml'],
    output: ['PCIeLink.md'],
    depend_files: sdbusplusplus_depfiles,
    command: [
        sdbuspp_gen_meson_prog,
        '--command',
        'markdown',
        '--output',
        meson.current_build_dir(),
        '--tool',
        sdbusplusplus_prog,
        '--directory',
        meson.current_source_dir() / '../../../../../yaml',
        'com/ibm/Control/Host/PCIeLink',
    ],
    install: should_generate_markdown,
    install_dir: [inst_markdown_dir / sdbusplus_current_path],
    build_by_default: should_generate_markdown,
)

