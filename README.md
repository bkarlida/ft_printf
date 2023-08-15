# FT_PRİNTF Projesi Anlatımı

Bu proje, standart C dilindeki `printf` işlevini yeniden oluşturmayı amaçlar. Bu projede, formatlı çıktı oluşturmak için kullanılan değişken argümanlar (`...`) ve format dizesi işlenir.

## Proje Açıklaması

- "ft_printf" projesi, özel bir `ft_printf` işlevini içerir. Bu işlev, C dilinde yaygın olarak kullanılan `printf` işlevini taklit eder.
- Format dizesi içinde yer alan değişkenlerin doğru şekilde işlenmesi ve çıktının oluşturulması amaçlanır.
- Bu proje, string işleme, karakter işleme, sayı işleme ve diğer özelleştirilmiş biçimlendirme yeteneklerini içerir.

## Ayağa Kaldırma Adımları

1. Öncelikle projenin kaynak kodlarını indirin.

2. İndirdiğiniz kaynak kodlarını bir dizine çıkarın.

3. Terminale gidin ve projenin ana dizinine gidin:

    ```bash
    cd /path/to/ft_printf
    ```

4. Projeyi derlemek için aşağıdaki komutları kullanabilirsiniz:

    ```bash
    make
    ```

    Bu komut, projeyi derleyecek ve "libftprintf.a" adlı bir kütüphane dosyasını oluşturacaktır.

5. Derleme tamamlandıktan sonra projeyi kullanmak istediğiniz programın derlemesinde "libftprintf.a" kütüphanesini ve başlık dosyalarını dahil edebilirsiniz.

6. Projeyi temizlemek ve derleme artıklarını kaldırmak için aşağıdaki komutu kullanabilirsiniz:

    ```bash
    make clean
    ```

    Bu komut, derleme sırasında oluşturulan geçici dosyaları temizler.

7. Projeyi sıfırlamak ve derleme sonrası oluşan tüm dosyaları kaldırmak için aşağıdaki komutu kullanabilirsiniz:

    ```bash
    make fclean
    ```

    Bu komut, derleme sonrası oluşan dosyaları ve oluşturulan kütüphane dosyasını siler.

Bu adımları izleyerek "ft_printf" projesini derleyebilir ve ayağa kaldırabilirsiniz.
