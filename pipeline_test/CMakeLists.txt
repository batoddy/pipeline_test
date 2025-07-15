# CMakeLists.txt (Ana Dizin)
cmake_minimum_required(VERSION 3.10)

# Ana proje adını tanımlıyoruz.
# Bu proje tüm alt projeleri içerecek.
project(MultiProjectBuild CXX)

# Alt dizinleri derleme sürecine dahil ediyoruz.
# CMake, bu dizinlerdeki CMakeLists.txt dosyalarını otomatik olarak arar ve işler.
add_subdirectory(hello_world)
add_subdirectory(calculator)