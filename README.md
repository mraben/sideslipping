仿IOS侧滑关闭

Step 1. AAdd it in your root build.gradle at the end of repositories:

	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
Step 2. Add the dependency

	dependencies {
	         implementation 'com.github.mraben:sideslipping:1.0.0'
	}
