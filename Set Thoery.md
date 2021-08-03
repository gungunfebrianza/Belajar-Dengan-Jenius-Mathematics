# Algorithm

# Set Theory

**Set** adalah sebuah **finite** atau **infinite** dari sekumpulan objek dan objek dalam sebuah **set** disebut dengan **element**.

1. x adalah **element** dari A, <img src="https://render.githubusercontent.com/render/math?math=x \in A&mode=inline">
2. a bukan **element** dari A, <img src="https://render.githubusercontent.com/render/math?math=\alpha \notin A&mode=inline">
3. A & B sama, A = B
4. A & B tidak sama, <img src="https://render.githubusercontent.com/render/math?math=A \ne B&mode=inline">

**Number Set :**

1. <img src="https://render.githubusercontent.com/render/math?math=\mathbb{Z}&mode=inline"> adalah **Set of Integer** : <img src="https://render.githubusercontent.com/render/math?math=\{-3,-2,-1,0,1,2,3\}&mode=inline">
2. <img src="https://render.githubusercontent.com/render/math?math=\mathbb{N}&mode=inline">adalah **Set of Natural Number**: <img src="https://render.githubusercontent.com/render/math?math=\{0,1,2,3\}&mode=inline">
3. <img src="https://render.githubusercontent.com/render/math?math=\emptyset&mode=inline"> dan <img src="https://render.githubusercontent.com/render/math?math=\{\}&mode=inline"> adalah simbol dari Empty Set
4. <img src="https://render.githubusercontent.com/render/math?math=\{\emptyset\}&mode=inline"> adalah **set** yang memiliki satu **element**

**Set Builder :**

1. Contoh : <img src="https://render.githubusercontent.com/render/math?math=\{x \ | \ \ x \ \ \has \the \property P\}&mode=inline">
2. Contoh : <img src="https://render.githubusercontent.com/render/math?math=\{n \ | \ \ n \in \mathbb{N} \ \ \and n %3C 108\}&mode=inline">
3. Contoh : <img src="https://render.githubusercontent.com/render/math?math=\{X \ | \ \ X \ \is \person \\over \ \the \age 18\}&mode=inline">

**Set Builder, Short Notation :**

1. Contoh : <img src="https://render.githubusercontent.com/render/math?math=\{x \ | \ \ x \ \ \in A \  \and x \ \has \the \property P\}&mode=inline">di persingkat menjadi Contoh : <img src="https://render.githubusercontent.com/render/math?math=\{x \ \in A \ \ | \ \ x \ \ \has \the \property P\}&mode=inline">

**Example Set Builder :**

ROXI TOKEN

Jika **variable p** adalah nilai dari **Initial Supply**, maka aturan internal **Ethereum Virtual Machine (EVM)** untuk melakukan **pre-minting** jika nilai decimal adalah nol berada pada **set builder** berikut :

<img src="https://render.githubusercontent.com/render/math?math=\{p \ | p \ \in \ \mathbb{Z}* \ \land \ \max(2^256)^-1 \}&mode=inline">

**Roxy Token** menggunakan nilai 18 decimal menggunakan **Standard ERC-20** sehingga nilai **pre-minting** berada pada **set builder** berikut :

<img src="https://render.githubusercontent.com/render/math?math=\{p \ | p \ \in \ \mathbb{Z}* \ \land \ (\max(2^256)^-1)/10^18 \}&mode=inline">

Total **pre-minting** dari **roxy token** sebesar **1.000.000** maka secara internal representasinya adalah 1.000.000.000.000.000.000.000.000 menyerupai unit **Wei** dalam **Currency Standard Metric** dalam **Ethereum Protocol**.

## Subset



# Propositional Logic

Setiap hari kita menggunakan **logic** dan **logical reasoning** seperti saat kita berbicara dengan teman, berdebat dalam diskusi atau merencanakan masa depan dengan pasangan kita. Penilaian logika ditentukan dari sekumpulan informasi yang disebut dengan asumsi.

Selain untuk diri kira **logic** juga menjadi **fundamental** untuk memahami dunia **Computer Science**, seperti **Software Engineering**, **Big Data**, **Cryptography**, **Artificial Intelligence**.

## Proposition

**Proposition** adalah suatu **statement** yang dapat bernilai **true** atau **false**. Jika kita mengetahui kebenaran dari suatu **Proposition** baik itu **true** atau **false** maka kebenaran disebut dengan **Truth Value**.

Contoh **statement** yang valid sebagai **Proposition** :

- 5+5 = 10
- Rumput berwarna hijau
- Maudy artis cantik idaman Mas Gun

Di bawah ini bukan sebuah **statement** yang valid untuk **Proposition** :

- Hahaha
- Kapan nikah ?
- O gitu ya

Di bawah ini adalah **ambiguous statement** sehingga validitas **Proposition** tidak bisa diketahui :

- x > 6
- Susu Beruang rasanya enak
- Anda merasa tampan

Pada statement ketiga bisa jadi sebuah paradox.

### Logical Form

Simbol memerankan peran kritis dalam matematika saat kita mendiskusikan **logic** dari sebuah **propositional** kita harus menggunakan simbol untuk merepresentasikan suatu **statement**. Biasanya menggunakan huruf kapital, sebagai contoh kita dapat menggunakan huruf **M** yang merepresentasikan **"Maudy sedang bersama Mas Gun"** dan kita dapat menggunakan hurug **G** untuk merepresentasikan **"Mas Gun tidak sedang bersama Maudy"**.

**Logical Form** dari **Statement** di atas adalah :

<img src="https://render.githubusercontent.com/render/math?math=M \land \neg G&mode=inline">



Simbol<img src="https://render.githubusercontent.com/render/math?math=\land&mode=inline"> merepresentasikan kalimat "dan", jadi jika **logical form** dalam **mathematical statement** di atas diubah ke dalam bahasa indonesia (**Natural Language**) maknannya adalah :

**"Maudy sedang bersama Mas Gun dan Mas Gun tidak sedang bersama Maudy"**

Jika **Logical Form** dari **Statement** di atas diubah menjadi<img src="https://render.githubusercontent.com/render/math?math=\neg M \land G&mode=inline"> maka dalam bahasa indonesia maknannya adalah :

**"Maudy tidak sedang bersama Mas Gun dan Mas Gun sedang bersama Maudy"**

Jika **Logical Form** dari **Statement** di atas diubah menjadi<img src="https://render.githubusercontent.com/render/math?math=M \land G&mode=inline"> maka dalam bahasa indonesia maknannya adalah :

**"Maudy sedang bersama Mas Gun dan Mas Gun sedang bersama Maudy"**

Simbol<img src="https://render.githubusercontent.com/render/math?math=\neg&mode=inline"> merepresentasikan kalimat "tidak", simbol-simbol ini disebut dengan **connectives**.

### Connectives

**Connectives** adalah bagian dari **Symbolic Language**. Simbol-simbol tersebut akan digunakan untuk menggabungkan sekumpulan **proposition**.

Sekumpulan **proposition** dapat terhubung menggunakan 5 frasa yang disebut dengan **Connectives** :

1. **not** (**negation**) dengan simbol <img src="https://render.githubusercontent.com/render/math?math=\neg&mode=inline">
2. **and** (**conjunction**) dengan simbol <img src="https://render.githubusercontent.com/render/math?math=\land&mode=inline">
3. **or** (**disjunction**) dengan simbol <img src="https://render.githubusercontent.com/render/math?math=\lor&mode=inline">
4. **if-then** (**implication**) dengan simbol <img src="https://render.githubusercontent.com/render/math?math=\to&mode=inline">
5. **if-and-only-if** dengan simbol <img src="https://render.githubusercontent.com/render/math?math=\leftrightarrow&mode=inline">

Jika terdapat **Proposition** **P** = "**Today Is Saturday**" dan **Q** = "**It's Winter**" :

1. ¬p = Today is not Saturday 
2. ¬q = It is not winter.
3. p <img src="https://render.githubusercontent.com/render/math?math=\land&mode=inline"> q = Today is Saturday and it is winter.
4. ¬p <img src="https://render.githubusercontent.com/render/math?math=\land&mode=inline"> q = Today is not Saturday and it is winter.
5. p <img src="https://render.githubusercontent.com/render/math?math=\lor&mode=inline"> q = Today is Saturday or it is winter.
6. p <img src="https://render.githubusercontent.com/render/math?math=\to&mode=inline"> q = If today is Saturday then it is winter.
7. p <img src="https://render.githubusercontent.com/render/math?math=\leftrightarrow&mode=inline"> q = Today is Saturday if-and-only-if it is winter.=

### Truth Tables

Terdapat sebuah **Propositional** dengan simbol **P**,**Q** & **R**, selanjutnya kita dapat menetapkan sebuah truth value pada masing-masing simbol. **Truth Value** yang diberikan untuk **P**,**Q** & **R** adalah **T**, **F**, **T** dimana **T** adalah **True** dan **F** adalah **False**.

**Connectives** menghasilkan nilai **Natural Truth** sebagai berikut :

**Table Conjunction**

|  P   |  Q   | P<img src="https://render.githubusercontent.com/render/math?math=\land&mode=inline">Q |
| :--: | :--: | :----------------------------------------------------------: |
|  T   |  T   |                              T                               |
|  T   |  F   |                              F                               |
|  F   |  T   |                              F                               |
|  F   |  F   |                              F                               |

**Table Disjunction**

|  P   |  Q   | P<img src="https://render.githubusercontent.com/render/math?math=\lor&mode=inline">Q |
| :--: | :--: | :----------------------------------------------------------: |
|  T   |  T   |                              T                               |
|  T   |  F   |                              T                               |
|  F   |  T   |                              T                               |
|  F   |  F   |                              F                               |

**Table Negation**

|  P   |      | <img src="https://render.githubusercontent.com/render/math?math=\neg&mode=inline">P |
| :--: | ---- | :----------------------------------------------------------: |
|  T   |      |                              F                               |
|  F   |      |                              T                               |



### Symbolic Language

Kunci mempelajari matematika adalah tahu kapan harus menggunakan **symbol** dan kapan harus menggunakan kalimat.

### Atomic & Composite Proposition

Biasanya kita akan merecah (**divide**) sebuah **proposition** menjadi semakin kecil dan lebih kecil lagi sampai ke level **atomic**. Pada level **atomic** sebuah **proposition** sudah tidak dapat direcah lagi :

- Jakarta adalah Ibu Kota Thailand
- Mas Gun Tampan
- Seluruh bilangan genap dapat dibagi dengan angka 2
- 9-3 = 2

**Atomic Composition** dalam **Mathematical Logic** itu ditentukan secara bebas,  dari sekumpulan **Atomic Composition** kita dapat membangun **Composite Proposition** menggunakan **Logical Words** seperti **and**, **or** atau **not** dan **if** atau **then**. Di bawah ini adalah contoh **Composite Proposition** :

- Jakarta adalah Ibu Kota Thailand **and** Mas Gun Tampan
- 9-3 = 2 or Seluruh bilangan genap dapat dibagi dengan angka 2

Pertanyaan selanjutnya adalah apakah kebenaran suatu **Composite Proposition** tergantung atau ditentukan dari **Atomic Proposition**?

Sebuah **Composite Proposition** yang tetap **independent** tanpa terpengaruh oleh **truth value** dari **Atomic Proposition** disebut dengan **Tautologies**.

### Atomic & Composite Formula

**Proposition** disederhanakan dengan membuat **abstraction** secara simbolik. **Sebuah Composite Proposition** tersusun dari **Atomic Proposition** dan **Logical Words**. **Symbolic Language** dibuat untuk merepresentasikan **Atomic Proposition** ke dalam sebuah **Propositional Variable**s.

### Propositional Variable 

Contoh **Propositional Variable** adalah **variable** seperti :**x,y,z** dan sebagainya. 

**Propositional Variable** disebut juga sebagai **Atomic Formula**.

Simbol yang digunakan untuk merepresentasikan **Propositional Variable** tidak dianggap terlalu penting. Yang paling penting adalah kita memiliki cukup **variables** untuk merepresentasikan sebuah **expression** yang kita inginkan. **Propositional Variables** merepresentasikan sebuah **Propositions**, seperti di bawah ini : 

<img src="https://render.githubusercontent.com/render/math?math=A \ \cup \ B = B \ \cap \ A&mode=inline">

**Proposition** bersifat **concrete** dan **Variable** bersifat **abstract**.

7. 

## Note URL Encoding 

1. %3C - Encoded Symbol of <
2. %3E - Encoded Symbol of >
3. %22 - Encoded Symbol of "
4. %27 - Encoded Symbol '
5. %2B - Encoded Symbol +

# Function

**Function** digunakan agar kita dapat menerapkan sebuah **rule** yang akan diberi **input** dan menghasilkan sebuah **Output**.

Di bawah ini adalah contoh **Function** :

<img src="https://render.githubusercontent.com/render/math?math=f(x)=x^2&mode=inline">

Jika input x adalah 3 maka :

<img src="https://render.githubusercontent.com/render/math?math=f(3)=3^2&mode=inline">

Hasilnya adalah :

<img src="https://render.githubusercontent.com/render/math?math=f(3)=3\times3&mode=inline">

<img src="https://render.githubusercontent.com/render/math?math==9&mode=inline">

## Example Roxy Function

**Minting Example :**

<img src="https://render.githubusercontent.com/render/math?math=f(x)=P%2Bx&mode=inline">

**Burning Example :**

<img src="https://render.githubusercontent.com/render/math?math=f(x)=P-x&mode=inline">

<img src="https://render.githubusercontent.com/render/math?math=\sum_{n=1}^{18} (250.000)=4.500.000&mode=inline">

<img src="https://render.githubusercontent.com/render/math?math=\sum_{n=1}^{+\infty} n\%2Bn&mode=inline">



# Example Roxy

Terdapat 3 Owner yang direpresentasikan dengan variable a, Owner 1,2 dan 3 adalah pemilik contract yang akan direpresentasikan dengan set O :

O<img src="https://render.githubusercontent.com/render/math?math==  \{a_1,a_2,a_3\}&mode=inline">

Jika simbol U adalah individual user melakukan transaksi maka terdapat dua jenis user :

<img src="https://render.githubusercontent.com/render/math?math=(U \in O) \land (U \notin O)&mode=inline">

Pada <img src="https://render.githubusercontent.com/render/math?math=(U \in O)&mode=inline">terdapat proper subset dan subset owner yang dapat dibentuk sebagai Legitimate Multisig Owners (LMO) untuk melakukan 2 of 3 multisig address :

<img src="https://render.githubusercontent.com/render/math?math=\LMO= \{\{a_1, a_2\},\{a_1, a_3\},\{a_2, a_3\},\{a_1, a_2, a_3\}\}&mode=inline">

Legitimate Multisig Owners (LMO) dapat melakukan transaksi, dengan syarat :

<img src="https://render.githubusercontent.com/render/math?math=((|LMO|\neq \emptyset) \land (|LMO| \gt 1) \land (|LMO| \le 3))&mode=inline">

Variable M merepresentasikan proses penerbitan token yang berhasil dan variable B merepresentasikan proses pembakaran token yang berhasil, maka operasi akan berhasil dilakukan jika :

<img src="https://render.githubusercontent.com/render/math?math=((LMO \to M) \land (LMO \to B))&mode=inline">

Proses penerbitan token dan pembakaran token akan gagal jika :

<img src="https://render.githubusercontent.com/render/math?math=((U \notin O \to \neg M) \land (U \notin O \to \neg B))&mode=inline">

