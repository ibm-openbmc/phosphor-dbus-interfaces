# Generated file; do not modify.
subdir('Target')
generated_others += custom_target(
    'com/ibm/Host/Target__markdown'.underscorify(),
    input: [ meson.source_root() / 'com/ibm/Host/Target.interface.yaml',  ],
    output: [ 'Target.md' ],
    command: [
        sdbuspp_gen_meson_prog, '--command', 'markdown',
        '--output', meson.current_build_dir(),
        '--tool', sdbusplusplus_prog,
        '--directory', meson.source_root(),
        'com/ibm/Host/Target',
    ],
    build_by_default: true,
)

