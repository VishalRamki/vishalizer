# vishalizer

A Rust based Audio Visualizer inspired by WinAmp and MilkDrop

# Why?

I loved Winamp and the MilkDrop visualizers growing up. I would spend hours and hours staring at it. It was always something that fascinated me to no end. MilkDrop was discontinued (to my knowledge, I could be wrong) alongside Winamp in 2013. There have been rumblings that Winamp will ressurect itself. I patiently await that day. 

Until then, I am dedicating some time to recreating my favourite memories with MilkDrop and Winamp in this project. 

MilkDrop remains extremly powerful, and if you are in need of an Audio Visualizer, then visit the [MilkDrop Homepage](www.geisswerks.com/milkdrop/).

# Current Stack

1. SDL2 - Originally I wanted to use either Glutin or raw GL. But In all honesty, I had a hard time following the Glutin docs, so I returned to  an old project I did while following a Rust-based Tutorial, and ripped out what I wanted from there.

# Building

I used the `sdl2` create for windowing and easy access to OpenGL, because I'm for the most party lazy.

You'll have to follow the instructions under here [SDL2 Setup](https://github.com/Rust-SDL2/rust-sdl2#windows-msvc). I am building this on a Windows 10 Build 1607 with SDL2 using Visual Studio 2019.