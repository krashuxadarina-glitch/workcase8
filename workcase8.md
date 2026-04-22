# **ЗВІТ ДО WORK-CASE 8**

ОС: Fedora (VirtualBox)  
 Режим роботи: термінал (CLI)

---

# **Частина 1\. Робота без графічної оболонки (CLI-only)**

У цій частині я виконала всі запропоновані варіанти програм для кожного типу задачі, щоб порівняти їх можливості та принцип роботи.

---

## **📂 Перегляд файлів і папок через файловий менеджер у терміналі**

Я протестувала три файлові менеджери: **mc, ranger, nnn**.

---

### **🔹 1\. Midnight Commander (mc)**
<img width="437" height="168" alt="image" src="https://github.com/user-attachments/assets/31ab451e-d195-4571-a436-7f397eee2b00" />

#### **Кроки:**
```
sudo dnf install mc  
mc
```
#### **Результат:**

Відкрився двопанельний інтерфейс.  
 Я змогла:
<img width="827" height="576" alt="image" src="https://github.com/user-attachments/assets/61be58fa-5ac4-4c70-88cf-6b397e67789f" />

* переміщатися між папками  
* копіювати файли (F5)  
* видаляти файли (F8)
<img width="809" height="590" alt="image" src="https://github.com/user-attachments/assets/7fdce8fc-d700-495b-ade1-961f288d9798" />

#### **Висновок:**

Зручний для користувачів, які звикли до класичних файлових менеджерів.

---

### **🔹 2\. ranger**

#### **Кроки:**
```
sudo dnf install ranger  
ranger
```
#### **Результат:**

Відкрився сучасний файловий менеджер з попереднім переглядом файлів.
<img width="809" height="460" alt="image" src="https://github.com/user-attachments/assets/d2f632dd-6462-4535-8d1f-311a41d31112" />

Я змогла:

* переглядати вміст файлів  
* переміщатися за допомогою клавіш hjkl  
* відкривати файли
<img width="802" height="594" alt="image" src="https://github.com/user-attachments/assets/9e330fe6-ab0e-412e-a273-22b28430c228" />

#### **Висновок:**

Більш “просунутий”, підходить для досвідчених користувачів.

---

### **🔹 3\. nnn**

#### **Кроки:**
```
sudo dnf install nnn  
nnn
```
<img width="825" height="496" alt="image" src="https://github.com/user-attachments/assets/64e26d34-5f51-4764-84bd-ba7a266523e6" />

#### **Результат:**

Мінімалістичний файловий менеджер.

<img width="657" height="355" alt="image" src="https://github.com/user-attachments/assets/be2a88ba-78bb-4ba6-8e24-e85d1b854194" />

Я змогла:

* швидко переміщатися по файловій системі  
* відкривати файли

#### **Висновок:**

Дуже швидкий та легкий, підходить для слабких систем.

---

## **🌐 Перегляд веб\-сторінок через браузер у терміналі**

Я використала три браузери: **lynx, w3m, links**.
<img width="409" height="149" alt="image" src="https://github.com/user-attachments/assets/e21ecc44-989b-455e-bb5a-2a0e751a1436" />

---

### **🔹 1\. lynx**
```
sudo dnf install lynx  
lynx google.com
```
<img width="824" height="493" alt="image" src="https://github.com/user-attachments/assets/b4a4dee5-f310-4b3a-a45d-1512002d0691" />

#### **Результат:**

Текстовий вигляд сайту.  
 Можна переходити по посиланнях.
<img width="821" height="603" alt="image" src="https://github.com/user-attachments/assets/70e0a8f2-cf2e-4fcf-af7f-f458afc0f70d" />

---

### **🔹 2\. w3m**
```
sudo dnf install w3m  
w3m google.com
```
<img width="831" height="528" alt="image" src="https://github.com/user-attachments/assets/3e682546-b89f-410b-b20c-2f9865bd678d" />

#### **Результат:**

Схожий на lynx, але підтримує часткове відображення зображень.
<img width="808" height="547" alt="image" src="https://github.com/user-attachments/assets/4d8b8219-fc66-4218-ab36-abc61bc48bfd" />

---



### **Висновок:**

Всі браузери дозволяють працювати з інтернетом без GUI, але мають різний рівень функціональності.

---

## **📧 Перегляд електронної пошти в терміналі**
<img width="466" height="145" alt="image" src="https://github.com/user-attachments/assets/1ab2007f-202d-47c9-b465-ae8e2d2d26bf" />

Я протестувала: **mutt та neomutt**.

---

### **🔹 mutt**
```
sudo dnf install mutt  
mutt
```
<img width="831" height="516" alt="image" src="https://github.com/user-attachments/assets/003731c2-fa9c-4282-b581-73810adab106" />

#### **Результат:**

Інтерфейс для роботи з поштою.

<img width="820" height="575" alt="image" src="https://github.com/user-attachments/assets/730dc864-4bbe-4d90-bb90-ad851f283e21" />

---

### **🔹 neomutt**
```
sudo dnf install neomutt  
neomutt
```
<img width="824" height="498" alt="image" src="https://github.com/user-attachments/assets/d76be22b-4846-45d9-bde0-e4a65ff1b90f" />

#### **Результат:**

Покращена версія mutt.
<img width="825" height="603" alt="image" src="https://github.com/user-attachments/assets/6b5ae6a3-984d-4964-bc1f-3e13312e2c5a" />

---

### **Висновок:**

Обидві програми дозволяють працювати з поштою без графічного інтерфейсу.

---

## **🎵 Слухати музику через термінал**

1. Прослуховування аудіо через консоль
Дія: Встановлення та запуск консольних медіаплеєрів для роботи з аудіофайлами та потоковим мовленням.
Використані утиліти: mpg123, mocp, pyradio.
<img width="823" height="564" alt="image" src="https://github.com/user-attachments/assets/095df4d9-c693-4c66-915e-5e09047fdbe5" />
<img width="821" height="558" alt="image" src="https://github.com/user-attachments/assets/d4b8a151-0292-4fb4-a6c8-69bfb0dcac31" />

Опис: Було протестовано утиліту mpg123, яка дозволяє відтворювати MP3-файли без графічного інтерфейсу. Програма підтримує роботу з потоковим аудіо через HTTP-протокол. Також розглянуто плеєр MOC (Music On Console), що має двопанельний інтерфейс для зручного керування плейлистами, та PyRadio для прослуховування онлайн-радіостанцій прямо в терміналі.
Результат: Підтверджено можливість повного керування мультимедіа через командний рядок, що є критичним для систем без графічної оболонки.
<img width="822" height="544" alt="image" src="https://github.com/user-attachments/assets/a5df31ef-6021-462f-8d19-09f6d1344bfa" />
<img width="822" height="542" alt="image" src="https://github.com/user-attachments/assets/af444a7d-75f5-4e22-a2b0-ead2cca95a42" />





## **⬇️ Скачувати торенти через термінал**

Я використала: **transmission-cli та rtorrent**.

---

### **🔹 transmission-cli**
```
sudo dnf install transmission-cli  
transmission-cli file.torrent  
```
<img width="823" height="553" alt="image" src="https://github.com/user-attachments/assets/c8c26f49-ff69-497f-a991-e913f10b06de" />
<img width="824" height="553" alt="image" src="https://github.com/user-attachments/assets/b398cadc-93f7-4d8a-a131-dacd02a6211e" />


### **🔹 rtorrent**
```
sudo dnf install rtorrent  
rtorrent  
```
<img width="827" height="527" alt="image" src="https://github.com/user-attachments/assets/0ff550e0-676b-432f-ab11-f978fd3672d3" />

<img width="825" height="614" alt="image" src="https://github.com/user-attachments/assets/b4b1b687-3785-4f19-a804-8b85ab26c935" />


### **Висновок:**

Обидві програми дозволяють завантажувати файли без GUI.

---

## **📅 Планувати дії в календарі**

Я використала: **cal та calcurse**.

---

### **🔹 cal**
```
cal
```
<img width="412" height="284" alt="image" src="https://github.com/user-attachments/assets/351627aa-f424-4b4d-beb1-e35529372e52" />

#### **Результат:**

Відображення календаря.

---

### **🔹 calcurse**
```
sudo dnf install calcurse  
calcurse
```
<img width="831" height="518" alt="image" src="https://github.com/user-attachments/assets/87dab23f-681d-472b-a821-f5e0c551feea" />

#### **Результат:**

Повноцінний планувальник.
<img width="821" height="601" alt="image" src="https://github.com/user-attachments/assets/96442f83-f368-4ba3-9c24-329d5b252251" />


---

## **🖼️ Переглядати зображення в терміналі**

Етап 1: Завантаження файлу (через графічний інтерфейс)
Оскільки пряме перетягування файлів (Drag-and-Drop) може потребувати додаткових налаштувань гостьової ОС, було використано найбільш надійний метод — завантаження через веб-інтерфейс:
<img width="748" height="519" alt="image" src="https://github.com/user-attachments/assets/ed2dbb46-a5b7-454e-94e8-84b3b2f3d057" />

У віртуальній машині Fedora було запущено браузер (Firefox).
Здійснено вхід до електронної пошти (або месенджера/хмарного сховища), куди заздалегідь було надіслано власне фото.
<img width="824" height="662" alt="image" src="https://github.com/user-attachments/assets/0ca19137-31de-4ae7-afcf-80e666d08f29" />
<img width="827" height="472" alt="image" src="https://github.com/user-attachments/assets/c2852076-7024-4b07-98e4-b1695c85907c" />

Файл із назвою IMG_1004.jpeg було збережено у стандартну системну директорію для завантажень.
Етап 2: Робота в терміналі (Команди та дії)
Після завантаження файлу було проведено ряд операцій у командному рядку для його пошуку та відображення:
Пошук завантаженого файлу та перевірка шляху:
```
ls ~/Downloads
```
<img width="523" height="62" alt="image" src="https://github.com/user-attachments/assets/c068c78b-273f-4b0d-91c5-060f159bc432" />

Опис: Команда ls (list) з аргументом ~/Downloads дозволила переконатися, що файл IMG_1004.jpeg успішно завантажений і знаходиться саме в цій папці.<img width="792" height="501" alt="image" src="https://github.com/user-attachments/assets/1e974ebd-db8c-46c6-9fe5-4379f4361f43" />

Спроба встановлення інструментів візуалізації:
```
sudo dnf install libcaca-utils
```

Опис: Команда для встановлення набору утиліт, що містять конвертер img2txt. (У звіті можна зазначити, що через обмеження репозиторіїв Live-версії пакети можуть бути недоступні, тому використовуються альтернативні методи).
Запуск візуалізації зображення (ASCII-конвертація):
Bash
img2txt ~/Downloads/IMG_1004.jpeg


Опис: Основна команда для перетворення растрового зображення у текстовий формат. Програма аналізує файл за вказаним шляхом і виводить його в термінал, використовуючи символи різної щільності для передачі напівтонів.
Альтернативна команда для виводу (якщо доступна):
Bash
catimg ~/Downloads/IMG_1004.jpeg


Опис: Використання утиліти catimg для отримання більш чіткого кольорового зображення безпосередньо в полі термінала.
Результат:
В результаті виконання цих дій було продемонстровано повний цикл роботи з даними: від отримання зовнішнього файлу через мережу до його технічної обробки та візуалізації в консольному середовищі. Це підтверджує навички роботи з файловою структурою Linux (/home/liveuser/Downloads) та розуміння принципів ASCII-графіки.
<img width="781" height="518" alt="image" src="https://github.com/user-attachments/assets/c4f86990-9096-4fe6-a369-7b76d301dc1f" />
<img width="785" height="506" alt="image" src="https://github.com/user-attachments/assets/0c574e4e-1bb6-4170-a7cf-118f5213f3ff" />
<img width="734" height="610" alt="image" src="https://github.com/user-attachments/assets/2f3b1a81-dc34-4800-a176-e27e7b3dff55" />

Дія: Демонстрація прихованих можливостей термінала для перевірки мережевого з’єднання та виводу анімації.
Використані команди: curl parrot.live, curl ascii.live/sw.
Опис: Протестовано механізм потокового виводу анімованої ASCII-графіки через мережеві протоколи. Зокрема, продемонстровано відтворення персонажів кіносаги «Зоряні війни» та кольорової анімації «Dancing Parrot».
Результат: Такі інструменти використовуються для тестування підтримки ANSI-кодів кольорів та коректності відображення символів Unicode у різних емуляторах термінала.

<img width="660" height="649" alt="image" src="https://github.com/user-attachments/assets/45f6aab5-885b-4ac0-af0c-fae2d4a3a403" />
<img width="619" height="646" alt="image" src="https://github.com/user-attachments/assets/45fc27a9-6718-4496-aad9-555b497530d8" />
<img width="611" height="584" alt="image" src="https://github.com/user-attachments/assets/0f0cf63d-259a-42e8-94fd-69add25d5630" />
<img width="621" height="514" alt="image" src="https://github.com/user-attachments/assets/9eea1ec8-2a3d-4615-9dc3-2d7f9190092e" />




# **Частина 2\. Інструменти адміністратора**

## **✍️ Редактори тексту**

Я використала: **nano та vim**.

---

### **🔹 nano**
```
sudo dnf install nano  
nano file.txt  
````
<img width="683" height="199" alt="image" src="https://github.com/user-attachments/assets/849e4087-f73e-4dae-aab0-d53add75edd5" />
<img width="822" height="642" alt="image" src="https://github.com/user-attachments/assets/63b782d8-4743-418e-a7f4-7ff42ea8e8b5" />


### **🔹 vim**
```
sudo dnf install vim  
vim file.txt  
```
<img width="823" height="536" alt="image" src="https://github.com/user-attachments/assets/4f587679-f961-4ffb-89b6-c1c9392a64f0" />
<img width="823" height="648" alt="image" src="https://github.com/user-attachments/assets/e30f3d8b-0519-43fd-b353-b2e59fd80981" />


### **Висновок:**

nano — простий, vim — складний, але потужний.

---

## **📊 Моніторинг системи**

Я використала: **top, htop, btop**.

---

### **🔹 top**
```
top  
```
<img width="764" height="178" alt="image" src="https://github.com/user-attachments/assets/0b287ec8-2004-4a1a-afe1-3d8806b39683" />
<img width="822" height="643" alt="image" src="https://github.com/user-attachments/assets/687e43e9-76ac-47cc-a4e5-7641f13ce5d8" />

### **🔹 htop**
```
sudo dnf install htop  
htop  
```
<img width="827" height="522" alt="image" src="https://github.com/user-attachments/assets/3b353b7c-bad6-4454-88ef-f5a456fe3b26" />
<img width="825" height="648" alt="image" src="https://github.com/user-attachments/assets/e505a92c-208e-4f2c-8fb2-54abb362bd5c" />


### **🔹 btop**
```
sudo dnf install btop  
btop  
```
<img width="822" height="521" alt="image" src="https://github.com/user-attachments/assets/d3875050-8b72-4c93-82d8-6d0854d9a82e" />
<img width="824" height="647" alt="image" src="https://github.com/user-attachments/assets/797a991c-3e81-412d-ad9f-5b7c0d10c717" />


### **Висновок:**

btop — найзручніший, top — базовий.

---

# **Частина 3\. Пасхалки**

Я виконала всі інтерактиви:

---

### **🚂 sl**
```
sudo dnf install sl  
sl  
```
<img width="825" height="493" alt="image" src="https://github.com/user-attachments/assets/85a2d7ff-b7ae-41af-9370-f86d696c6efb" />

<img width="819" height="509" alt="image" src="https://github.com/user-attachments/assets/4f339e2f-98e5-457d-8184-e254209197a9" />


### **🐄 cowsay**
```
sudo dnf install cowsay  
cowsay Hello  
```
<img width="818" height="538" alt="image" src="https://github.com/user-attachments/assets/d8f815cd-fd1e-46f3-9376-4890a0025d3e" />
<img width="390" height="285" alt="image" src="https://github.com/user-attachments/assets/170f00c8-1c98-4b51-b6be-674c5ada3770" />


### **🎉 Додатково:**
```
fortune
```
<img width="821" height="533" alt="image" src="https://github.com/user-attachments/assets/266448fd-c166-44fd-b4dd-96edebfc3f17" />
<img width="823" height="552" alt="image" src="https://github.com/user-attachments/assets/f927e96e-11f9-4af0-ac52-1a1f2a50d6ff" />

```
cmatrix
```
<img width="826" height="494" alt="image" src="https://github.com/user-attachments/assets/9ab10ea7-ec2b-4e43-a6ec-cbc11829ae4d" />
<img width="821" height="647" alt="image" src="https://github.com/user-attachments/assets/84fd1289-3175-4e4c-8152-28dafaedf55c" />

```
asciiquarium  
```
<img width="821" height="539" alt="image" src="https://github.com/user-attachments/assets/e12461a4-616e-4fdb-a4c3-b0392a7804f2" />
<img width="829" height="649" alt="image" src="https://github.com/user-attachments/assets/06ff7858-381a-47f9-b442-60984ff858eb" />

# **Conclusion (English)**

In this work, I explored multiple terminal-based tools for performing everyday tasks in Linux. I tested several alternatives for each task and compared their functionality.

The results show that Linux provides many powerful command-line utilities that can fully replace graphical applications. This makes the system flexible, efficient, and suitable for servers and low-resource environments.

---

# **Vocabulary Table (English)**

| Term | Meaning |
| ----- | ----- |
| terminal | command line interface |
| command | instruction |
| package | software unit |
| install | set up program |
| run | execute |
| file manager | tool for files |
| browser | internet tool |
| process | running task |
| monitor | observe system |
| resource | system capacity |
| editor | text tool |
| download | receive data |
| upload | send data |
| server | remote machine |

![][image1]  
Mc  
![][image2]  
![][image3]  
 2  
![][image4]  
![][image5]  
3  
![][image6]  
![][image7]  
Частина 2   
![][image8]  
![][image9]  
![][image10]

![][image11]  
![][image12]  
Частина 3 📧 Перегляд електронної пошти  
![][image13]  
![][image14]  
![][image15]

![][image16]

![][image17]

**Частина 4 Слухати музику через термінал**

### **1\. Прослуховування аудіо через консоль**

Дія: Встановлення та запуск консольних медіаплеєрів для роботи з аудіофайлами та потоковим мовленням.

* Використані утиліти: `mpg123`, `mocp`, `pyradio`.  
* Опис: Було протестовано утиліту mpg123, яка дозволяє відтворювати MP3-файли без графічного інтерфейсу. Програма підтримує роботу з потоковим аудіо через HTTP-протокол. Також розглянуто плеєр MOC (Music On Console), що має двопанельний інтерфейс для зручного керування плейлистами, та PyRadio для прослуховування онлайн-радіостанцій прямо в терміналі.  
* Результат: Підтверджено можливість повного керування мультимедіа через командний рядок, що є критичним для систем без графічної оболонки.

![][image18]  
![][image19]

![][image20]  
![][image21]

Частина 5 ⬇️ Скачування торентів  
![][image22]  
![][image23]

![][image24]  
![][image25]

Частина 6 📅 Планування задач і нагадування  
![][image26]  
![][image27]

![][image28]

**Частина 7 🖼️ Перегляд зображень у терміналі**

#### **Етап 1: Завантаження файлу (через графічний інтерфейс)**

Оскільки пряме перетягування файлів (Drag-and-Drop) може потребувати додаткових налаштувань гостьової ОС, було використано найбільш надійний метод — завантаження через веб\-інтерфейс:

1. У віртуальній машині Fedora було запущено браузер (Firefox).  
2. Здійснено вхід до електронної пошти (або месенджера/хмарного сховища), куди заздалегідь було надіслано власне фото.  
3. Файл із назвою `IMG_1004.jpeg` було збережено у стандартну системну директорію для завантажень.

#### **Етап 2: Робота в терміналі (Команди та дії)**

Після завантаження файлу було проведено ряд операцій у командному рядку для його пошуку та відображення:

**Пошук завантаженого файлу та перевірка шляху:**  
Bash  
ls \~/Downloads

1.   
   * **Опис:** Команда `ls` (list) з аргументом `~/Downloads` дозволила переконатися, що файл `IMG_1004.jpeg` успішно завантажений і знаходиться саме в цій папці.

**Спроба встановлення інструментів візуалізації:**  
Bash  
sudo dnf install libcaca-utils

2.   
   * **Опис:** Команда для встановлення набору утиліт, що містять конвертер `img2txt`. (У звіті можна зазначити, що через обмеження репозиторіїв Live-версії пакети можуть бути недоступні, тому використовуються альтернативні методи).

**Запуск візуалізації зображення (ASCII-конвертація):**  
Bash  
img2txt \~/Downloads/IMG\_1004.jpeg

3.   
   * **Опис:** Основна команда для перетворення растрового зображення у текстовий формат. Програма аналізує файл за вказаним шляхом і виводить його в термінал, використовуючи символи різної щільності для передачі напівтонів.

**Альтернативна команда для виводу (якщо доступна):**  
Bash  
catimg \~/Downloads/IMG\_1004.jpeg

4.   
   * **Опис:** Використання утиліти `catimg` для отримання більш чіткого кольорового зображення безпосередньо в полі термінала.

#### **Результат:**

В результаті виконання цих дій було продемонстровано повний цикл роботи з даними: від отримання зовнішнього файлу через мережу до його технічної обробки та візуалізації в консольному середовищі. Це підтверджує навички роботи з файловою структурою Linux (`/home/liveuser/Downloads`) та розуміння принципів ASCII-графіки.

![][image29]  
![][image30]

![][image31]  
![][image32]  
![][image33]  
![][image34]  
![][image35]  
![][image36]

**Дія:** Демонстрація прихованих можливостей термінала для перевірки мережевого з’єднання та виводу анімації.

* **Використані команди:** `curl parrot.live`, `curl ascii.live/sw`.  
* **Опис:** Протестовано механізм потокового виводу анімованої ASCII-графіки через мережеві протоколи. Зокрема, продемонстровано відтворення персонажів кіносаги «Зоряні війни» та кольорової анімації «Dancing Parrot».  
* **Результат:** Такі інструменти використовуються для тестування підтримки ANSI-кодів кольорів та коректності відображення символів Unicode у різних емуляторах термінала.

![][image37]

![][image38]  
![][image39]  
![][image40]

2\. Класичні інструменти адміністратора  
![][image41]

![][image42]й  
![][image43]  
![][image44]

2.1 📊 Моніторинг системи  
![][image45]  
![][image46]

![][image47]  
![][image48]

![][image49]  
![][image50]

3\. Пасхалки (fun stuff 😄)  
![][image51]  
![][image52]

![][image53]  
![][image54]

🎉 Додаткові інтерактиви  
![][image55]  
![][image56]

![][image57]  
![][image58]

![][image59]

![][image60]
