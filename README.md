TR
---

# Hitori Puzzle Game (Hitori Bulmaca Oyunu)

Bu proje, mantık tabanlı bir sayı bulmacası olan **Hitori** oyununun Python ile geliştirilmiş bir uygulamasını içerir.

## 🎯 Proje Hakkında

Hitori, bir ızgara (grid) üzerindeki sayıları belirli kurallara göre eleyerek çözülen bir Japon mantık bulmacasıdır. Bu repo, bulmacayı çözmek veya oynamak için gerekli kaynak kodları ve örnek veri dosyalarını barındırır.

### Dosya Yapısı

* `hitori-bulmaca.py`: Projenin ana kaynak kodudur. Oyunun mantığını, kurallarını ve çalışma prensiplerini içerir.
* `hitori_bulmaca.txt`: Bulmaca verilerini içeren dosya. Oyunun başlangıç durumunu veya çözülecek bulmaca matrisini barındırmaktadır.

## 🚀 Kurulum ve Çalıştırma

Bu projeyi yerel makinenizde çalıştırmak için aşağıdaki adımları izleyebilirsiniz.

### Gereksinimler

* [Python 3.x](https://www.python.org/downloads/) (Projenin çalışması için Python yüklü olmalıdır.)

### Adım 1: Depoyu Klonlayın

Terminal veya komut satırını açarak projeyi bilgisayarınıza indirin:

```bash
git clone https://github.com/anenthusiastic/HitoriPuzzleGame.git
cd HitoriPuzzleGame

```

### Adım 2: Uygulamayı Çalıştırın

Proje dizinine girdikten sonra Python dosyasını çalıştırın:

```bash
python hitori-bulmaca.py

```

*Not: Script, `hitori_bulmaca.txt` dosyasını girdi olarak kullanıyor. Bu dosyanın script ile aynı dizinde olduğundan emin olun.*

## 🛠 Kullanım

Uygulama çalıştırıldığında, `hitori_bulmaca.txt` içerisindeki bulmacayı yükleyerek çözümü ekrana yazdırabilir veya interaktif bir oyun deneyimi sunabilir.

**Hitori Kuralları:**

1. Satır veya sütunlarda tekrar eden sayılar olmamalıdır (Tekrar edenleri karalayarak eleyin).
2. Karalanan hücreler yatay veya dikey olarak birbirine değmemelidir (Çapraz değebilir).
3. Geriye kalan (karalanmamış) tüm hücreler birbirine bağlı tek bir alan oluşturmalıdır.

## 🤝 Katkıda Bulunma

Projeye katkıda bulunmak isterseniz, lütfen bir "Pull Request" gönderin veya hataları bildirmek için "Issues" kısmını kullanın.

1. Bu depoyu "Fork"layın.
2. Yeni bir dal (branch) oluşturun (`git checkout -b yeni-ozellik`).
3. Değişikliklerinizi kaydedin (`git commit -m 'Yeni özellik eklendi'`).
4. Dalınızı uzak sunucuya gönderin (`git push origin yeni-ozellik`).
5. Bir Pull Request oluşturun.

## 📝 Lisans

Bu proje açık kaynaklıdır. Kullanım ve dağıtım detayları için depo sahibinin belirttiği lisans koşullarını inceleyiniz.

-----------------------------------------------------------------------------------------------------------------------------------------

EN

Hitori Puzzle Game
This project contains a Python implementation of Hitori, a logic-based number puzzle.

🎯 About the Project
Hitori is a Japanese logic puzzle solved by eliminating numbers on a grid according to specific rules. This repository hosts the source code and sample data files necessary to solve or play the puzzle.

File Structure
hitori-bulmaca.py: The main source code of the project. It contains the game logic, rules, and working principles.

hitori_bulmaca.txt: The file containing puzzle data. It holds the initial game state or the puzzle matrix to be solved.

🚀 Installation and Execution
You can follow the steps below to run this project on your local machine.

Prerequisites
Python 3.x (Python must be installed for the project to run.)

Step 1: Clone the Repository
Download the project to your computer by opening a terminal or command line:

Bash
git clone https://github.com/anenthusiastic/HitoriPuzzleGame.git
cd HitoriPuzzleGame
Step 2: Run the Application
After entering the project directory, run the Python file:

Bash
python hitori-bulmaca.py
Note: The script uses the hitori_bulmaca.txt file as input. Ensure this file is located in the same directory as the script.

🛠 Usage
When the application is run, it may load the puzzle from hitori_bulmaca.txt and either print the solution to the screen or offer an interactive gaming experience.

Hitori Rules:
No duplicate numbers are allowed in rows or columns (eliminate duplicates by shading them).

Shaded cells must not touch each other horizontally or vertically (they may touch diagonally).

All remaining (unshaded) cells must form a single connected area.

🤝 Contributing
If you would like to contribute to the project, please send a "Pull Request" or use the "Issues" section to report bugs.

Fork this repository.

Create a new branch (git checkout -b new-feature).

Commit your changes (git commit -m 'Added new feature').

Push your branch to the remote server (git push origin new-feature).

Create a Pull Request.

📝 License
This project is open source. Please review the license terms specified by the repository owner for usage and distribution details.
