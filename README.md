# FelixReadme

repositories {
    maven { url 'https://dl.bintray.com/felix-maven/maven' }
}

# FelixUtils (https://github.com/felix-maven/FelixUtils)

dependencies {
    implementation "com.felix.utils:felix-utils:1.0.5"
}

# FelixArch (https://github.com/felix-maven/FelixArch) depend on FelixUtils

dependencies {
    implementation "com.felix.utils:felix-utils:1.0.3"
}

# FelixDownloader （https://github.com/felix-maven/FelixDownloader） depend on FelixComBase

dependencies {
    implementation "com.felix.downloader:felix-downloader:1.0.0"
}

# FelixComBase （https://github.com/felix-maven/FelixComBase）

dependencies {
    implementation "com.felix.combase:felix-combase:1.0.0"
}
