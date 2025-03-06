# Square Root Bisection Method in Python

This project implements the **Square Root Calculation using the Bisection Method** in Python. It uses an iterative approach to approximate the square root of a given number.

## Problem Description

The program calculates the square root of a non-negative number using the **Bisection Method**. This method works by iteratively narrowing the range (low and high values) until the approximate square root is found within a specified tolerance.

## Features
- Calculates the square root of non-negative numbers.
- Uses a bisection approach to find the square root.
- Handles edge cases for `0` and `1` directly.
- Provides an option to set the tolerance for precision.
- Limits the number of iterations to avoid infinite loops.

## Function: `square_root_bisection(square_target, tolerance=1e-7, max_iterations=100)`

### Parameters:
- `square_target`: The number whose square root needs to be calculated.
- `tolerance`: The acceptable error range for the result. The default is `1e-7`.
- `max_iterations`: The maximum number of iterations to attempt. The default is `100`.

### Return:
- The function returns the approximate square root of the input number.

### Example Usage:
```python
N = 16
square_root_bisection(N)
```

This will output:
```
The square root of 16 is approximately 4.0
```

### Error Handling:
- If the `square_target` is negative, a `ValueError` is raised because the square root of negative numbers is undefined in the real number system.
- The program will stop if it converges to a result within the tolerance or if it exceeds the maximum number of iterations.

## Installation

To use this script, just clone the repository and run the Python file.

1. Clone the repository:
    ```bash
    git clone https://github.com/FihriSina/Square-Root-Bisection.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Square-Root-Bisection
    ```
3. Run the script:
    ```bash
    python square_root_bisection.py
    ```

## Contributing

This project was completed as part of my learning journey with **FreeCodeCamp**. Contributions, suggestions, and improvements are always welcome!

## License

This project is open-source and available under the MIT License.



# Kare Kök Bisection Yöntemi ile Hesaplama (Python)

Bu proje, **Bisection Yöntemi** kullanarak bir sayının karekökünü **Python** dilinde hesaplar. Bu yöntem, bir sayının yaklaşık karekökünü bulmak için yinelemeli bir yaklaşım kullanır.

## Problem Tanımı

Program, **Bisection Yöntemi** ile negatif olmayan bir sayının karekökünü hesaplar. Bu yöntem, yaklaşık karekökü, belirtilen toleransa kadar bulana kadar aralığı (düşük ve yüksek değerler) yinelemeli olarak daraltır.

## Özellikler
- Negatif olmayan sayıların karekökünü hesaplar.
- Karekök bulmak için bisection yaklaşımını kullanır.
- `0` ve `1` için kenar durumları doğrudan ele alır.
- Hassasiyet için tolerans belirleme seçeneği sunar.
- Sonsuz döngülerden kaçınmak için maksimum iterasyon sayısını sınırlar.

## Fonksiyon: `square_root_bisection(karekök_hedefi, tolerans=1e-7, max_iterasyon=100)`

### Parametreler:
- `karekök_hedefi`: Karekökü hesaplanacak sayı.
- `tolerans`: Sonuç için kabul edilebilir hata aralığı. Varsayılan olarak `1e-7`'dir.
- `max_iterasyon`: Denenecek maksimum iterasyon sayısı. Varsayılan olarak `100`'dür.

### Döndürülen:
- Fonksiyon, giriş sayısının yaklaşık karekökünü döndürür.

### Örnek Kullanım:
```python
N = 16
square_root_bisection(N)
```

Bu, şu çıktıyı verir:
```
16'nın karekökü yaklaşık olarak 4.0'dır.
```

### Hata Yönetimi:
- Eğer `karekök_hedefi` negatif bir sayıysa, `ValueError` hatası fırlatılır çünkü negatif sayıların karekökü, reel sayı sisteminde tanımlı değildir.
- Program, sonucun toleransa göre yakınsaması veya maksimum iterasyon sayısının aşılması durumunda durur.

## Kurulum

Bu betiği kullanmak için sadece projeyi klonlayın ve Python dosyasını çalıştırın.

1. Depoyu klonlayın:
    ```bash
    git clone https://github.com/FihriSina/Square-Root-Bisection.git
    ```
2. Proje dizinine gidin:
    ```bash
    cd Square-Root-Bisection
    ```
3. Betiği çalıştırın:
    ```bash
    python square_root_bisection.py
    ```

## Katkıda Bulunma

Bu proje, **FreeCodeCamp** ile öğrenim sürecimin bir parçası olarak tamamlanmıştır. Katkılar, öneriler ve iyileştirmeler her zaman hoş karşılanır!

## Lisans

Bu proje açık kaynaklıdır ve MIT Lisansı altında mevcuttur.
