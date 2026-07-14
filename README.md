cd src/Sophus

mkdir build && cd build  

cmake .. -DBUILD_SOPHUS_TESTS=OFF

make -j4

cd src/livox_ros_driver2

./build.sh humble
