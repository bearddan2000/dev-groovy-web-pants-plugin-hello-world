jvm_artifact(
    name='groovy-all',
    group="org.apache.groovy",
    artifact="groovy",
    version="4.0.12",
)

files(
    name="groovy-src",
    sources=[
        'groovy/example/*.groovy',
    ]
)

java_sources(
    name="bin",
    sources=['java/example/*.java'],
    dependencies=[':groovy-src'],
)