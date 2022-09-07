# VSAirdropSignal ![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")
Rocketmod 4 plugin to summon a airdrop with a item of your choice.




# Configuration

```C#

<?xml version="1.0" encoding="utf-8"?>
<Config xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
  <SupplyAnnounce>true</SupplyAnnounce>
  <SupplyPermission>VS.supply</SupplyPermission>
  <AnnouncMessage>{color=yellow}%PLAYERNAME%{/color} {color=white}called air drop.{/color}</AnnouncMessage>
  <AnnouncImgUrl />
  <SignalSmokes>
    <SignalIDs>261</SignalIDs>
  </SignalSmokes>
</Config>
