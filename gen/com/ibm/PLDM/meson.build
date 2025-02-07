# Generated file; do not modify.
subdir('ChapData')
subdir('PCIeTopology')

sdbusplus_current_path = 'com/ibm/PLDM'

generated_markdown += custom_target(
    'com/ibm/PLDM/ChapData__markdown'.underscorify(),
    input: ['../../../../yaml/com/ibm/PLDM/ChapData.interface.yaml'],
    output: ['ChapData.md'],
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
        meson.current_source_dir() / '../../../../yaml',
        'com/ibm/PLDM/ChapData',
    ],
    install: should_generate_markdown,
    install_dir: [inst_markdown_dir / sdbusplus_current_path],
    build_by_default: should_generate_markdown,
)

generated_markdown += custom_target(
    'com/ibm/PLDM/PCIeTopology__markdown'.underscorify(),
    input: ['../../../../yaml/com/ibm/PLDM/PCIeTopology.interface.yaml'],
    output: ['PCIeTopology.md'],
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
        meson.current_source_dir() / '../../../../yaml',
        'com/ibm/PLDM/PCIeTopology',
    ],
    install: should_generate_markdown,
    install_dir: [inst_markdown_dir / sdbusplus_current_path],
    build_by_default: should_generate_markdown,
)

