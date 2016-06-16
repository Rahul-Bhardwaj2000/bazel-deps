workspace(name = "com_github_pgr0ss_bazel_deps")

git_repository(
    name = "io_bazel_rules_scala",
    remote = "git://github.com/bazelbuild/rules_scala",
    commit = "6d39791d26d3f2e1d15cd6538a4767e3cc0d8993", # update this as needed
)
load("@io_bazel_rules_scala//scala:scala.bzl", "scala_repositories")
scala_repositories()

# --------- Add these lines to your WORKSPACE file ---------

maven_jar(name = "args4j_args4j", artifact = "args4j:args4j:jar:2.32")
maven_jar(name = "asm_asm", artifact = "asm:asm:jar:3.3.1")
maven_jar(name = "com_google_code_findbugs_jsr305", artifact = "com.google.code.findbugs:jsr305:jar:1.3.9")
maven_jar(name = "com_google_guava_guava", artifact = "com.google.guava:guava:jar:18.0")
maven_jar(name = "commons_codec_commons_codec", artifact = "commons-codec:commons-codec:jar:1.6")
maven_jar(name = "javax_annotation_jsr250_api", artifact = "javax.annotation:jsr250-api:jar:1.0")
maven_jar(name = "javax_enterprise_cdi_api", artifact = "javax.enterprise:cdi-api:jar:1.0")
maven_jar(name = "javax_inject_javax_inject", artifact = "javax.inject:javax.inject:jar:1")
maven_jar(name = "org_apache_httpcomponents_httpclient", artifact = "org.apache.httpcomponents:httpclient:jar:4.2.6")
maven_jar(name = "org_apache_httpcomponents_httpcore", artifact = "org.apache.httpcomponents:httpcore:jar:4.2.5")
maven_jar(name = "org_apache_maven_maven_aether_provider", artifact = "org.apache.maven:maven-aether-provider:jar:3.1.0")
maven_jar(name = "org_apache_maven_maven_model", artifact = "org.apache.maven:maven-model:jar:3.1.0")
maven_jar(name = "org_apache_maven_maven_model_builder", artifact = "org.apache.maven:maven-model-builder:jar:3.1.0")
maven_jar(name = "org_apache_maven_maven_repository_metadata", artifact = "org.apache.maven:maven-repository-metadata:jar:3.1.0")
maven_jar(name = "org_codehaus_plexus_plexus_classworlds", artifact = "org.codehaus.plexus:plexus-classworlds:jar:2.4.2")
maven_jar(name = "org_codehaus_plexus_plexus_component_annotations", artifact = "org.codehaus.plexus:plexus-component-annotations:jar:1.5.5")
maven_jar(name = "org_codehaus_plexus_plexus_interpolation", artifact = "org.codehaus.plexus:plexus-interpolation:jar:1.16")
maven_jar(name = "org_codehaus_plexus_plexus_utils", artifact = "org.codehaus.plexus:plexus-utils:jar:3.0.10")
maven_jar(name = "org_eclipse_aether_aether_api", artifact = "org.eclipse.aether:aether-api:jar:1.0.2.v20150114")
maven_jar(name = "org_eclipse_aether_aether_connector_basic", artifact = "org.eclipse.aether:aether-connector-basic:jar:1.0.2.v20150114")
maven_jar(name = "org_eclipse_aether_aether_impl", artifact = "org.eclipse.aether:aether-impl:jar:1.0.2.v20150114")
maven_jar(name = "org_eclipse_aether_aether_spi", artifact = "org.eclipse.aether:aether-spi:jar:1.0.2.v20150114")
maven_jar(name = "org_eclipse_aether_aether_transport_file", artifact = "org.eclipse.aether:aether-transport-file:jar:1.0.2.v20150114")
maven_jar(name = "org_eclipse_aether_aether_transport_http", artifact = "org.eclipse.aether:aether-transport-http:jar:1.0.2.v20150114")
maven_jar(name = "org_eclipse_aether_aether_util", artifact = "org.eclipse.aether:aether-util:jar:1.0.2.v20150114")
maven_jar(name = "org_eclipse_sisu_org_eclipse_sisu_inject", artifact = "org.eclipse.sisu:org.eclipse.sisu.inject:jar:0.0.0.M2a")
maven_jar(name = "org_eclipse_sisu_org_eclipse_sisu_plexus", artifact = "org.eclipse.sisu:org.eclipse.sisu.plexus:jar:0.0.0.M2a")
maven_jar(name = "org_slf4j_jcl_over_slf4j", artifact = "org.slf4j:jcl-over-slf4j:jar:1.6.2")
maven_jar(name = "org_slf4j_slf4j_api", artifact = "org.slf4j:slf4j-api:jar:1.6.2")
