# RUST-api-helloworld
api hosted in shuttle.rs that print a hello world 

obs.: no need to copy the main.rs file here, shuttle will create the hello world file in this case.

How to Build & Deploy a Rust App in Under 60 Seconds
https://www.youtube.com/watch?v=-t7Aa6Dr4pI

cargo install cargo-shuttle

choose a directory where you want to create the project

cargo shuttle init (need to have a shuttle account, because will ask the api key) 

Will ask a unique project name and the directory

will be asked the framework. Can be choosen between a basic hello world or another options. Choose hello world and after choose axum.

cd [project directory name]

code . (or open the file/project manually)

(the code in the video is different of the basic hello world now)

cargo shuttle deploy --allow-dirty

curl (url created)

you can also see the hello world by the browser

and by the shuttle site control panel you can stop the deploy
