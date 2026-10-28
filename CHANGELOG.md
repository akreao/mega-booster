# Changelog

Each `## <version>` section is that version's release notes: the release
workflow publishes it as the GitHub Release text, which the Ragnarok Offline
app shows players under "What's new". Write it for players.

## 0.2.7
- The Karnos booster items now have English names and descriptions: the
  Gust Hail Booster Dagger and Slash Chop Chop Booster Axe in the
  Exchanger's Booster Weapon shop, and the Karnos Booster Shadow Weapon in
  its Booster Shadow shop. They showed as "undefined" before. Restart the
  app after updating so the client picks up the new text.

## 0.2.6
- New setting "Job quest gifts and skills from the Job Agent", off by
  default. With it off, the Job Agent only changes your job: no
  job-change gifts (which 0.2.5 gave every time) and no quest skills.
- With it on, the Job Agent gives the job quest's gift as in 0.2.5 and
  also teaches your job's quest skills, the skills you'd otherwise learn
  from the skill quests: Fatal Blow and Berserk for a Swordman, Arrow
  Crafting for an Archer, Charge Attack for a Knight, and so on. A 2nd
  job also gets its 1st job's quest skills, and a new Sage picks one
  Elemental Change. After a rebirth, the transcended jobs get their quest
  skills back, as at Valhalla.

## 0.2.5
- The Job Agent now gives the same gift the official job quest gives when
  you change job with it. A new Swordman, Mage, Archer, Acolyte, Merchant
  or Thief gets their Novice weapon (Archers also get three arrow quivers),
  a Taekwon a Guard, a Ninja an Asura, a Gunslinger a Novice Rifle with
  bullets, and a Super Novice the famous Panties. 2nd jobs get their Job
  Lv 50 gift, such as 7 Awakening Potions for a Knight, a Bible for a
  Priest or a Hunter Bow for a Hunter; a new Assassin picks one of four
  weapons. Sage and Bard get nothing, as in their quests.
- Transcended job changes get no gift, as at Valhalla and Juno.
- A new Druid gets a Novice Mace. There's no Druid job quest to copy, so
  this one is the mod's own choice.

## 0.2.4
- Needs app 1.7.0 or newer. 0.2.3 should have said so: on an older app its
  Job Agent stops with a script error. Update the app, or stay on 0.2.2.

## 0.2.3
- iRO players who set a kRO data.grf as their fallback GRF can become a
  Druid, Karnos or Alitea again: the fallback has the art. Without a kRO
  fallback, iRO still gets no Druid-line job changes.

## 0.2.2
- On an iRO client, the Job Agent no longer offers Druid, Karnos or Alitea.
  iRO's game files have no art or skills for the Druid line, so a Druid
  there was invisible. On a kRO client nothing changes. This also applies
  when a kRO data.grf is only set as the fallback GRF.

## 0.2.1
- Playing the Druid line? Install the regional-items mod from Find Mods for
  English names and descriptions of the Druid-only items. They work without
  it, but their text isn't in English.

## 0.2.0
- Needs app 1.6.4 or newer, the first with the Druid job line.
- Druids can use the Mega Booster too. Booster Pack (1) gives the Druid line
  a Metal Mace instead of the Metal Dagger they can't equip.
- The Job Agent changes a Novice into a Druid, a Druid into a Karnos at Base
  99 / Job 70, and a Karnos into an Alitea at Base 200 / Job 70. kRO has job
  quests for these; rAthena doesn't yet, so this is the mod's own shortcut.
- The Booster Exchanger has the Druid Booster Dagger and Booster Axe (one
  Booster Weapon Voucher each) and the Druid booster shadow weapon (15
  Booster Coins). Both weapons take the booster enchants, and the shadow
  weapon has its set bonus with the other five booster shadow pieces.

## 0.1.1
- Doram now get a Metal Foxtail from Booster Pack (1), instead of a Metal
  Dagger they can't equip.

## 0.1.0
- First release: kRO's Mega Booster promotion.
- New characters get a Booster Box from the Booster Guide in Izlude (Doram:
  Lasagna), once per account. Settings can make it once per character, or the
  Premium Booster Box.
- Use the Booster Call to summon Lime Evenor wherever you are. A second Lime
  waits in Prontera's Adventurer Convenience Center.
- Lime runs the Booster Coin Shop, the Booster Mission Shop and the currency
  exchange, the Lv 1–80 hunting requests, booster enchants from Lv 100, Level
  Up Tickets, and the milestone rewards at Episodes 17.1, 17.2, 18 and 19 and
  at Lv 230 and 250.
- 13 Booster Missions from Lv 80: memorial dungeons (Half Moon in the
  Daylight, Sara's Memories, Ghost Palace, Old Glast Heim) and the Illusion
  Investigation Team. Nine more are listed but need dungeons this server
  doesn't have yet.
- Upgrade to the Premium Booster Call for 50 Booster Coins (a setting can
  change the price, or switch to kRO's 150 Nyangvine Fruit).
- In the Convenience Center: the Job Agent (free rebirth and level boosts),
  the Reset Service and the Booster Exchanger for Booster Weapons, Illusion,
  Automatic and shadow gear. The Booster Enchanters are in sp_cor and
  ba_maison.
- English quest log text for every booster quest, signs over the booster
  NPCs, and up-to-date text for the Booster Call, Booster Coin and vouchers.
- Known issue: the Attacker Booster Manteau has no icon in this app version.
  The picture is in the game client; an app update will make it show.
