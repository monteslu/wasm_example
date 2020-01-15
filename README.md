## install
`npm install`

## run
`npm run start`


open browser to http://localhost:8080



## wasm
wasm and js modules were built with:  `emcc hello_function.cpp -o function.html -s EXPORTED_FUNCTIONS='["_int_sqrt"]' -s EXTRA_EXPORTED_RUNTIME_METHODS='["ccall", "cwrap"]'`