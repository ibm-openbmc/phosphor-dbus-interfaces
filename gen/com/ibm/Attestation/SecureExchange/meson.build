# Generated file; do not modify.
subdir('SecureExchange')

sdbusplus_current_path = 'com/ibm/Attestation/SecureExchange'

generated_markdown += custom_target(
    'com/ibm/Attestation/SecureExchange/SecureExchange__markdown'.underscorify(),
    input: [
        '../../../../../yaml/com/ibm/Attestation/SecureExchange/SecureExchange.errors.yaml',
        '../../../../../yaml/com/ibm/Attestation/SecureExchange/SecureExchange.interface.yaml',
    ],
    output: ['SecureExchange.md'],
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
        'com/ibm/Attestation/SecureExchange/SecureExchange',
    ],
    install: should_generate_markdown,
    install_dir: [inst_markdown_dir / sdbusplus_current_path],
    build_by_default: should_generate_markdown,
)

