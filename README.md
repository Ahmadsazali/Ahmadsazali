
# Cara Bikin Es Kelapa Muda Ala Algoritma

## Deskripsi

Algoritma ini ngejelasin gimana cara bikin es kelapa muda yang seger banget buat diminum pas panas-panas. Dari mulai nyiapin kelapa muda, nyampurin es sama sirup, sampe akhirnya disajikan dan siap diminum. Simpel tapi seger!

## Langkah-langkah Algoritma

1. **Ambil kelapa muda**: Kelapa mudanya dikerok dulu, ambil dagingnya sama air kelapanya.
2. **Siapin es batu**: Masukin es batu ke dalam gelas.
3. **Campurin air kelapa**: Tuang air kelapa ke dalam gelas yang udah ada es batunya.
4. **Tambahin sirup**: Kalau mau, tambahin sirup rasa sesuai selera, kayak cocopandan biar makin seger.
5. **Sajikan**: Udah deh, es kelapa muda siap diminum! Ayo seger-seger!

## Contoh Kode

Ini kode Python-nya buat bikin es kelapa muda:

```python
def buat_es_kelapa(bahan):
    """
    Fungsi buat bikin es kelapa muda.

    Argumen:
    bahan -- List yang isinya kelapa muda, es batu, dan sirup kalau suka.

    Mengembalikan:
    String hasil es kelapa yang siap diminum.
    """
    if 'kelapa muda' not in bahan or 'es batu' not in bahan:
        return "Gagal bikin es kelapa: Kelapa muda atau es batu nggak ada!"
    
    print("Ambil daging kelapa muda sama air kelapanya.")
    print("Masukin es batu ke gelas.")
    print("Tuangin air kelapa ke gelas.")

    if 'sirup' in bahan:
        print("Tambahin sirup biar makin mantap.")
    
    return "Es kelapa muda siap diminum! Seger banget!"
