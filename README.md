# SkiBuddy

build.gradle

android {
    compileSdkVersion 21
    buildToolsVersion "22.0.1"

    defaultConfig {
        applicationId "edu.sjsu.qi.onlinecommunity"
        minSdkVersion 19
        targetSdkVersion 21
        versionCode 1
        versionName "1.0"
    }
    buildTypes {
        release {
            minifyEnabled false
            proguardFiles getDefaultProguardFile('proguard-android.txt'), 'proguard-rules.pro'
        }
    }
}

dependencies {
    compile fileTree(dir: 'libs', include: ['*.jar'])
    compile 'com.android.support:appcompat-v7:22.1.0'
}
