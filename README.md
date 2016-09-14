# mp3bpm

Toolchain for stretch mp3 bpm(beats per minutes).


# Usage

1. `git clone https://github.com/renyufu/mp3bpm.git`

2. `cd mp3bpm/ubuntu`

3. `docker build -t ubuntu:buildbase .`

4. `cd ../lame`

5. `docker build -t lame .`

6. `cd ../soundtouch`

7. `docker build -t soundtouch .`

8. `cd ..`

9. `chmod +x bpm`

10. `./bpm input.mp3 out.mp3 bpm`  
    for example: `./bpm 160.mp3 180.mp3 180`
