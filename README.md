Usage
-----

    buildscript {
        repositories {
            mavenCentral()
        }
        dependencies {
            classpath 'com.android.tools.build:gradle:0.4.2'
        }
    }
    
    apply plugin: 'android'
    
    repositories {
        mavenCentral()
            maven {
                url "https://github.com/dahlgren/holoeverywhere-aar/raw/master"
            }
    }
    
    dependencies {
        compile 'org.holoeverywhere:library:1.6.2-SNAPSHOT'
        compile 'org.holoeverywhere:addon-preferences:1.6.2-SNAPSHOT'
        compile 'org.holoeverywhere:addon-slider:1.6.2-SNAPSHOT'
    }


