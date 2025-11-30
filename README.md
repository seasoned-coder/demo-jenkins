## Notes

- Dependency versions for `guava` and `commons-lang3` are declared in the parent POM under `dependencyManagement` and used by both modules.
- The Jenkins pipeline used for releases is configured separately in `Jenkinsfile.release`.
This needs the following plugins installed into Jenkins:
- Pipeline Maven Integration
- AnsiColor
- Managed files