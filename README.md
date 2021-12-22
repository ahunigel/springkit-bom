# springkit-bom
[![](https://jitpack.io/v/ahunigel/springkit-bom.svg)](https://jitpack.io/#ahunigel/springkit-bom)

## How to use

### Step 1. Add the JitPack repository to your build file
```groovy
allprojects {
    repositories {
        ...
        maven { url 'https://jitpack.io' }
    }
}
```
## Step 2. Add the dependency
```groovy
dependencies {
    implementation platform('com.github.ahunigel:springkit-bom:{version}')
}
```