cmake_minimum_required(VERSION 3.26)
project("Crispy Doom" VERSION 6.0.0 LANGUAGES C)

# Add the source directory submodule
add_subdirectory(src)

# Install the crispy-doom executable as crispy doom itself doesnt provide any 
# install instructions.
install(TARGETS crispy-doom)
