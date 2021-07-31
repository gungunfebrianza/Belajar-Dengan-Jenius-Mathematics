# Set Theory

**Set** adalah sebuah **finite** atau **infinite** dari sekumpulan objek dan objek dalam sebuah **set** disebut dengan **element**.

1. x adalah element dari A, <img src="https://render.githubusercontent.com/render/math?math=x \in A&mode=inline">
2. a bukan element dari A, <img src="https://render.githubusercontent.com/render/math?math=\alpha \notin A&mode=inline">
3. A & B sama, A = B
4. A & B tidak sama, <img src="https://render.githubusercontent.com/render/math?math=A \ne B&mode=inline">

**Number Set :**

1. <img src="https://render.githubusercontent.com/render/math?math=\mathbb{Z}&mode=inline"> adalah **Set of Integer** : <img src="https://render.githubusercontent.com/render/math?math=\{-3,-2,-1,0,1,2,3\}&mode=inline">
2. <img src="https://render.githubusercontent.com/render/math?math=\mathbb{N}&mode=inline">adalah Set of Natural Number: <img src="https://render.githubusercontent.com/render/math?math=\{0,1,2,3\}&mode=inline">
3. <img src="https://render.githubusercontent.com/render/math?math=\emptyset&mode=inline"> dan <img src="https://render.githubusercontent.com/render/math?math=\{\}&mode=inline"> adalah simbol dari Empty Set
4. <img src="https://render.githubusercontent.com/render/math?math=\{\emptyset\}&mode=inline"> adalah set yang memiliki satu element

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

Setiap hari kita menggunakan **logic** dan **logical reasoning** setiap saat seperti saat kita berbicara dengan teman, berdebat dalam diskusi atau merencanakan masa depan dengan pasangan kita. Penilaian logika ditentukan dari sekumpulan informasi yang disebut dengan asumsi.

## Proposition

**Proposition** adalah sesuatu yang dapat bernilai **true** atau **false**. Dapat berupa suatu **statement**, **utterance** atau sebuah **content of meaning**. 

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
- Nanti pasti hutangnya saya bayar <-- 99.9% FIX

### Atomic & Composite Proposition

Biasanya kita akan merecah (**divide**) sebuah **proposition** menjadi semakin kecil dan lebih kecil lagi sampai ke level **atomic**. Pada level **atomic** sebuah **proposition** sudah tidak dapat direcah lagi :

- Jakarta adalah Ibu Kota Thailand
- Mas Gun Tampan
- Seluruh bilangan genap dapat dibagi dengan angka 2
- 9-3 = 2

**Atomic Composition** dalam **Mathematical Logic** itu ditentukan secara bebas,  dari sekumpulan Atomic Composition kita dapat membangun **Composite Proposition** menggunakan **Logical Words** seperti **and**, **or** atau **not** dan **if** atau **then**. Di bawah ini adalah contoh **Composite Proposition** :

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

### Connective

**Connectives** adalah bagian dari **Symbolic Language**. Simbol-simbol tersebut akan digunakan untuk menggabungkan sekumpulan formula.

Sekumpulan **proposition** dapat terhubung menggunakan 5 frasa yang disebut dengan **Connectives** :

1. **not** (**negation**) dengan simbol <img src="https://render.githubusercontent.com/render/math?math=\neg&mode=inline">
2. **and** (**conjunction**) dengan simbol <img src="https://render.githubusercontent.com/render/math?math=\land&mode=inline">
3. **or** (**disjunction**) dengan simbol <img src="https://render.githubusercontent.com/render/math?math=\lor&mode=inline">
4. **if-then** (**implication**) dengan simbol <img src="https://render.githubusercontent.com/render/math?math=\to&mode=inline">
5. **if-and-only-if** dengan simbol <img src="https://render.githubusercontent.com/render/math?math=\leftrightarrow&mode=inline">



## Symbolic Logic

**Mathematical Object** berwujud **Abstract** contohnya **Equation** dalam **Algebra** atau **Point** dan **Lines** pada **Geometry**. ,

## Inference

## Replacement

## Proof Methods

## The Three Properties

## Note URL Encoding 

1. %3C - Encoded Symbol of <
2. %3E - Encoded Symbol of >
3. %22 - Encoded Symbol of "
4. %27 - Encoded Symbol '
5. %2B - Encoded Symbol +

# Example

Terdapat 3 Owner, Owner 1,2 dan 3 adalah pemilik contract yang akan direpresentasikan dengan set O :

O<img src="https://render.githubusercontent.com/render/math?math==  \{a_1,a_2,a_3\}&mode=inline">

Skema 2 of 3 multisig transaction direpresentasikan dengan 2 notasi tuple, kita harus memilih salah satunya: 

<img src="https://render.githubusercontent.com/render/math?math=(%3C \{x|x \in \ O\}, \{x|x \in \ O\} %3E) \lor (%3C \{x|x \in \ O\}, \{x|x \in \ O\}, \{x|x \in \ O\} %3E)"> 

Dengan syarat representasi Owner contract harus berbeda-beda sehingga  :

<img src="https://render.githubusercontent.com/render/math?math=p_1(e) \neq p_2(e) &mode=inline"> 

Dan pada  3n-tuple

 <img src="https://render.githubusercontent.com/render/math?math=\{x | \ x \ \in O \ \ \}&mode=inline">tuple dalam notasi set builder :



<img src="https://render.githubusercontent.com/render/math?math=\{x \ \in O \ \ | \ \ x \ \ |O|\}&mode=inline">

Jika U adalah User melakukan transaksi, M proses penerbitan token berhasil dan B proses pembakaran token berhasil maka operasi akan berhasil dilakukan jika :

<img src="https://render.githubusercontent.com/render/math?math=((U \subset O \to M) \land ((U \subset O) \to B))&mode=inline">

Proses penerbitan token pembakaran token akan gagal jika :

<img src="https://render.githubusercontent.com/render/math?math=((U \notin O \to \neg M) \land (U \notin O \to \neg B))&mode=inline">

