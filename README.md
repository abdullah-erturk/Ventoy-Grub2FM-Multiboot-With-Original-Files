# Ventoy & Grub2FM Multiboot (With Original Files)

https://www.tnctr.com/topic/1174848-ventoy-grub2fm-multiboot-orijinal-dosyalarla/

Grub2 File Manager Github: https://github.com/a1ive/grub2-filemanager

credit: Alive

Ventoy Github: https://github.com/ventoy/Ventoy

credit: longpanda 

	1- Türkçe Açıklama

Bu betik dosyası ile orijinal Grub2FM ve Ventoy dosyalarını kullanarak iki multiboot yapısını da beraber kullanabileceksiniz.
	
USB veya HDD disklere kurulum yapmak için 1-2 tıklama yeterlidir.
	
DİKKAT:

Herhangi bir disk işleminin belirli riskleri vardır. Komut dosyası, kullanıcıyı bilgilendirerek mevcut verileri güvende tutmaya çalışır, ancak çok önemli veriler için önce bir yedekleme yapılması şiddetle tavsiye edilir.

İlk kurulumda Ventoy üzerinden tahribatsız kurulum seçeneği ile kurulum yapmayacaksanız USB/HDD diskiniz tamamen formatlanacaktır. Veri kaybı için önleminizi alın.
	
Hem Ventoy hem de Grub2FM efi modunda secureboot uyumludur.

Secureboot açık iken kullanabilmek için ilk kullanımda .cer dosyasının BIOS'a tanıtılması gerekmektedir.

Tam kurulum veya Tahribatsız Kurulum yöntemlerinden hangisi seçilirse seçilsin "Bölüm Yapısı" nın MBR olması şarttır, MBR ile kurulmuş Ventoy ve Grub2FM'in UEFI desteği vardır ayrıca geriye dönük eski pclerde de sorunsuz çalışır.

"Bölüm Yapısı" GPT seçilirse Grub2FM kurulumu olmayacaktır ve betik dosyası hata verecektir.

Güncelleme İşlemi:

Ventoy ve Grub2FM'in yeni versiyonları çıktığında:
	
Ventoy güncel dosyaları indirildikten sonra ilgili dosyalar Ventoy klasörüne 
	
Grub2FM güncel dosyaları indirildikten sonra ilgili dosyalar Grub2FM klasörüne 
	
kopyalanır ve Grub2FM_Ventoy_TR.bat dosyası çalıştırılarak 2. seçenek ile kolay bir şekilde her iki multiboot yapısı da güncellenebilir.
	
Ventoy'dan Grub2FM'e geçiş kısayolu: F6

Grub2FM'den Ventoy'a geçiş kısayolu: F5 > V

Kurulum klasörleri içindeki

Ventoy v1.0.87 sürümüdür.

Grub2FM 9 Mart 2022 tarihinde oluşturulan Pre-Release sürümdür.

Kurulum yapmak istediğiniz zaman Ventoy ve Grub2FM'in yeni versiyonları çıkmışsa kurulum dosyalarını sizin değiştirmeniz gerekmektedir.

Kodlama konusunda yardımlarını esirgemeyen MyDigitallife sitesinden abbodi1406 ve BAU'ya fikirleriyle bana destek veren @By_FaRuK 'a, video anlatımı yapan @crasadure 'ya çok teşekkür ederim.

Grub2FM Suite Tanıtım videosu crasadure TNCTR.com
https://www.youtube.com/watch?v=CAXZgPGpmUk
	
	
		
	
	2- English Explanation

With this script you will be able to use both multiboot builds together using the original Grub2FM and Ventoy files.
	
Installing to USB or disks is enough for 1-2 clicks.	
	
	ATTENTION:
  
Any disk operation has certain risks. The script file tries to keep the existing data safe by notifying the user, but it is highly recommended to make a backup first for very important data.

In the first installation, if you do not install with the non-destructive installation option your USB/HDD disk will be completely formatted.

Both Ventoy and Grub2FM are secure boot compatible in efi mode.

In order to be able to use it with Secureboot turned on, the .cer file must be introduced  into the BIOS on first use.
	
Regardless of whether Full installation or Non-Destructive Installation is chosen, the "Partition Structure" must be MBR. Ventoy and Grub2FM installed with MBR have UEFI support and also run smoothly on backwards old PCs.

If "Partition Structure" GPT is selected, Grub2FM will not be installed and the script will fail.

Update Process:

When new versions of Ventoy and Grub2FM are released:
	
After the Ventoy updated files are downloaded, the related files are copied to the Ventoy folder. 
	
After the Grub2FM updated files are downloaded, the related files are copied to the Grub2FM folder. 
		
By running the Grub2FM_Ventoy_EN.bat file with the 2nd option both multiboot builds can be easily updated.	

Hotkey from Ventoy to Grub2FM: F6

Hotkey from Grub2FM to Ventoy: F5 > V

Ventoy is version v1.0.87.

Grub2FM is the Pre-Release version created on March 9, 2022.

If there are new versions of Ventoy and Grub2FM when you want to install, you have to change the installation files yourself.

Thanks to abbodi1406 and BAU of MyDigitallife for their help with coding, @By_FaRuK of TNCTR for their ideas and support, and @crasadure for the video narration.

Grub2FM Suite Trailer (Turkish Language) by crasadure from TNCTR.com
https://www.youtube.com/watch?v=CAXZgPGpmUk

