# AbirMathLibrary
This is simple library for basic Arithmatic operations, sum, subtraction, multiplication,Division

## To use this library just add follow instructions

### Step1 : Add my dependency to Android studio App Level build.gradle files in dependency block

`dependencies {
    implementation fileTree(dir: 'libs', include: ['*.jar'])
    implementation 'com.android.support:appcompat-v7:27.1.1'
    implementation 'com.android.support.constraint:constraint-layout:1.1.3'
    testImplementation 'junit:junit:4.12'
    androidTestImplementation 'com.android.support.test:runner:1.0.2'
    androidTestImplementation 'com.android.support.test.espresso:espresso-core:3.0.2'
    //----------------Use below line to access my library-----//
    **implementation 'com.github.abircse:MyMathOperationsLibrary:1.0'**
}`

# HOW TO WRITE CODE
### Step 3 : In you class or Activity file just call my operations method, & only put int value using comma's for specific operations.
      
  
        int a = abirmath.Plus(10, 20);
        int b = abirmath.Division(20, 30);
        int c = abirmath.Minus(20,10);
        int d = abirmath.Multiplication(20,10);

