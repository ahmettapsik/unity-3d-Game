# unity-3d-Game
#OYNANIŞ
Oyun siyah engellere çarpmadan karekterin elindeki roketi kullanarak en  yukarıdaki mavi kapıya kadar ulaşmasını sağlamak.Mouse sol tuşu ile attığımız roketin patlama açısını,yakınlığı , yönüne bağlı olarak oyuncuya Force uygulamaktadır.Oyuncu roketleri kullanarak en yukarıdaki mavi kapıya ulaşmayı amaçlanmıştır
Eğer oyuncumuz siyah renkli engellere takılırsa yada oyundan aşağıya düşerse karakter hareketi sonlanıcak ve 3 saniye sonra oyun baştan başlatılacaktır. Oyunda ileriye gidildikce sonucu etkilemeyen bir score sayacida bulunmaktadir. Bu oyunu tasarlarken Team Fortress 2 oyunundaki Soldier karakterine benzetilmiştir.

#Oyun İçi görseller
![204592467-efabf0c9-4420-4b80-9a31-9a70bc1df179](https://user-images.githubusercontent.com/64674920/204641712-ede9fe33-182d-456c-a07f-4bb64a2d91a0.png)
![204592602-87889000-441f-453c-be09-abb208b2ce8d](https://user-images.githubusercontent.com/64674920/204644683-94313101-a0fa-4d26-82dd-214ff702b794.png)
![204594079-a24291e1-5108-4f19-a56b-a3a62d96dbb1](https://user-images.githubusercontent.com/64674920/204644772-0ab02d73-2a31-46d0-aef6-bd2bd6e33d99.png)

#Projeye ekleyemediğimiz Menu 

![Ekran görüntüsü 2022-11-30 002437](https://user-images.githubusercontent.com/64674920/204652689-3d5dd8dc-8f38-460b-9175-bc902ef87821.png)
-Mission Completed ibaresi Unity içerisinde hazırladığımız bir animasyondur.

#Tuslar -w,a,s,d tuşları ile genel hareket -space tuşu ile zıplama -mouse sol click tusu ile roket atis
#esc basılınca gelecek olan menu 

#Benim yaptığım kısımlar
#Esc menusu ve diğer menu ayarlamalari yapildi
Pausemenu.cs, MenuControl.cs, GameManager.cs 

#Takım arkadaşım Fatihcan Uslu tarafından yapılan kısımlar
Genel hareket mekanikleri, roket atar tasarimi ve kullanimi, ses efektleri -camerafollowthe_player.cs, EndTrigger.cs, explotion.cs, FPSCamera.cs, Gun.cs, player_collision.cs, player_movement.cs, score.cs,

#oyunu oynamak için aşağıdaki linke tıklayabilirsiniz
https://fatihcan-uslu.itch.io/rocket-jump

