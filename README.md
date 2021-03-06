# Tugas Kecil Strategi Algoritma : A*-PathFinder
> Pada tugas kali ini, akan menentukan lintasan terpendek berdasarkan peta Google Map jalan-jalan di kota Bandung dengan menggunakan algoritma A* (dibaca A star). Dari ruas-ruas jalan di peta dibentuk graf. Simpul menyatakan persilangan jalan atau ujung jalan. Asumsikan jalan dapat dilalui dari dua arah. Bobot graf menyatakan jarak (m atau km) antar simpul. Jarak antara dua simpul dapat dihitung dari koordinat kedua simpul menggunakan rumus jarak Euclidean (berdasarkan koordinat) atau dapat menggunakan ruler di Google Map, atau cara lainnya yang disediakan oleh Google Map.

## Table of contents
* [General info](#general-info)
* [Screenshots](#screenshots)
* [Technologies](#technologies)
* [Setup](#setup)
* [Features](#features)
* [Status](#status)
* [Inspiration](#inspiration)
* [Contact](#contact)

### General info
> Algoritma A* atau A star adalah salah satu algoritma yang baik dalam menemukan  solusi proses pathfinding (pencari jalan). Algoritma ini mencari jarak rute terpendek yang akan ditempuh suatu point awal (starting point) sampai ke objek tujuan. Teknik pencarian yang digunakan dalam simulasi ini adalah menggunakan Algoritma A* dengan fungsi heuristic. Tujuan utama penelitian ini mempelajari cara kerja algoritma A* dalam mencari jarak tercepat, yang disimulasikan seperti kondisi ketika seorang mencari rute dalam keadaan jalanan macet. Simulasi ini memberikan gambaran yang lebih realistis terhadap perilaku algoritma A* dalam pencarian jarak rute terpendek

### Screenshots
![Example screenshot](https://github.com/chrslex/Astar-PathFinder/blob/main/screenshot/MicrosoftTeams-image.png)

### Technologies
python 3.6+

# Setup
Disarankan menggunakan vscode, agar menggunakan python environment yang sama

di cmd masing:

pip install networkx

pip install matplotlib

pip install geopy

pip install gmaps

pip install request


## Untuk masukan file biasa : Langsung jalankan Main.py 
## Untuk berinteraksi dengan Google Map API : Jalankan test.ipynb


### Features
List of features 
* Mengukur Jarak 2 Graf (Daklam hal ini adalah 2 titik pada maps)

### Status
Project is finished

### Inspiration
http://informatika.stei.itb.ac.id/~rinaldi.munir/Stmik/2020-2021/Route-Planning-Bagian2-2021.pdf

### Contact
Dibuat oleh :
 - 13519109 - Christian Alexandro Tobing
 - 13519199 - Christian Gunawan

## Notes:
disarankan menjalankan dengan vs code, biar environmentnya sama, ga ngulang"
kalo anaconda beda env soalnya :)

