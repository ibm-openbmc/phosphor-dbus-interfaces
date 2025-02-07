# Generated file; do not modify.
subdir('Target')

sdbusplus_current_path = 'com/ibm/Host'

generated_markdown += custom_target(
    'com/ibm/Host/Target__markdown'.underscorify(),
    input: ['../../../../yaml/com/ibm/Host/Target.interface.yaml'],
    output: ['Target.md'],
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
        'com/ibm/Host/Target',
    ],
    install: should_generate_markdown,
    install_dir: [inst_markdown_dir / sdbusplus_current_path],
    build_by_default: should_generate_markdown,
)

