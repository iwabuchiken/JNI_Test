-Djava.library.path="${workspace_loc}/com.example.jni/resources;${env_var:PATH}"
-Djava.library.path="${workspace_loc:/JNI_Test/resources};${env_var:PATH}"

java com.example.jni.JNITest
java -Djava.library.path=../resources com.example.jni.JNITest
