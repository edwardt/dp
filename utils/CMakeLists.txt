FILE(GLOB luasrc *.lua)
ADD_TORCH_PACKAGE(dp/utils "${src}" "${luasrc}")
