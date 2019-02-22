EconomyLand ın temel komutları

commands:
 startp:
  description: Sets start position
  usage: /startp
  permission: economyland.command.startp
 endp:
  description: Sets second position
  usage: /endp
  permission: economyland.command.endp
 land:
  description: Manage land
  usage: /land <buy|move|list|whose|give|here|[r:]invite|kick|invitee>
  permission: economyland.command.land;economyland.command.land.buy;economyland.command.land.move;economyland.command.land.list;economyland.command.land.whose;economyland.command.land.give;economyland.command.land.here;economyland.command.land.invite;economyland.command.land.invite.remove;economyland.command.land.invitee
 landsell:
  description: Sell land
  usage: /landsell <here|land num>
  permission: economyland.command.landsell;economyland.command.landsell.here;economyland.command.landsell.number


EconomyLand a eklenmesi gerekenler

- /land offer <price/revoke> landı satılığa çıkarır bu komutu yazınca landınızın tabelasına tıklayın yazıcak sonra landın tabelasında line1=satılık line2=price line3=sahibi 
revoke de landı satmaktan vazgeçtiğini ifade eder /land offer revoke yazına tabelaya tıklayınca tabela satılıksa satılıklıktan çıkacak

- Landların tabelaları olmalı
  
   tabela
   line1  SuperAdam46
   line2  {PURECHAT_GROUP}
   line3  {landid}
   line4  02.02.2019 (Evi ne zaman satın aldığını gösteren tarih)
