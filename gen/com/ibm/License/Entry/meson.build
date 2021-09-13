# Generated file; do not modify.
subdir('LicenseEntry')
generated_others += custom_target(
    'com/ibm/License/Entry/LicenseEntry__markdown'.underscorify(),
    input: [ '../../../../../yaml/com/ibm/License/Entry/LicenseEntry.interface.yaml',  ],
    output: [ 'LicenseEntry.md' ],
    command: [
        sdbuspp_gen_meson_prog, '--command', 'markdown',
        '--output', meson.current_build_dir(),
        '--tool', sdbusplusplus_prog,
        '--directory', meson.current_source_dir() / '../../../../../yaml',
        'com/ibm/License/Entry/LicenseEntry',
    ],
)

