#~/.bashrc - one time setup
export ANDROID_HOME=$HOME/Library/Android/sdk
export ANDROID_SDK_ROOT=$ANDROID_HOME
export PATH=$ANDROID_HOME/tools/bin:$ANDROID_HOME/platform-tools:$PATH

#shell - every time
export JAVA_HOME=`/usr/libexec/java_home -v 11`
export ANDROID_NDK=$HOME/Library/Android/sdk/ndk/28.0.13004108

#All Android - Inference only with RelWithDebInfo option:
./build_lgfx.sh
