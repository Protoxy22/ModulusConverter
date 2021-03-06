# Config reference for GunType (extends [BaseType](https://github.com/Unknown025/ModulusConverter/blob/master/docs/BaseType.md))

For each type, the table will list each config and potentially its purpose and default values.

| Keyword | Type | Default | Purpose |
|---|---|---|---|
| weaponType | WeaponType | - | Used for default weapon animations. |
| scopeType | WeaponScopeType | N/A | Not currently implemented. |
| gunDamage | Float | 0 | Damage inflicted per bullet. Multiplied by the bullet damage value. |
| gunDamageHeadshotBonus | Float | 2 | Damage inflicted is multiplied by this value. |
| weaponMaxRange | Integer | 100 | Maximum weapon block range. |
| weaponEffectiveRange | Integer | 50 | Maximum weapon effectiveness block range. |
| numBullets | Integer | 1 | The number of bullets fired by each shot. |
| bulletSpread | Float | - | The amount bullets spread out when fired. |
| sneakMod | Float | 0.8F | The modifier for bullet spread when sneaking. |
| aimMod | Float | 0.2F | The modifier for bullet spread when aiming. |
| roundsPerMin | Integer | 1 | The fire rate of this weapon. |
| numBurstRounds | Integer | 3 | The number of bullets to fire per burst in burst mode. |
| consumeGunUponUse | Boolean | false | If this weapon should be consumed upon use. |
| recoilPitch | Float | 10.0F | Base value for upwards view recoil. |
| recoilYaw | Float | 1.0F | Base value for sideways view recoil. |
| randomRecoilPitch | Float | 0.5F | Modifier for setting the maximum pitch divergence when randomizing recoil (Recoil 2 + rndRecoil 0.5 == 1.5-2.5 Recoil range) |
| randomRecoilYaw | Float | 0.5F | Modifier for setting the maximum yaw divergence when randomizing recoil (Recoil 2 + rndRecoil 0.5 == 1.5-2.5 Recoil range) |
| crouchRecoilModifier | Float | 0.8F | Modifier for reducing recoil if crouched. |
| fireMods | WeaponFireMode[] | WeaponFireMode.SEMI | Available fire modes for this weapon. |
| acceptedAttachments | Map<AttachmentEnum, ArrayList\<String\>> | - | Not currently implemented. |
| reloadTime | Integer | 40 | The time (in ticks) it takes to reload this weapon. |
| chargeTime | Integer | 40 | The time (in ticks) it takes to charge this weapon. |
| offhandReloadTime | Integer | - | The time (in ticks) it takes to offhand reload this weapon. |
| ammoNumBullets | Boolean | false | If the number of bullets should be determined by the loaded ammo. |
| ammoBulletSpeed | Boolean | false | If the bullet speed should be determined by the loaded ammo. |
| ammoBulletSpread | Boolean | false | If the bullet spread should be determined by the loaded ammo. |
| ammoReloadTime | Boolean | false | If the bullet reload time should be determined by the loaded ammo. |
| ammoRecoilPitch | Boolean | false | If the bullet recoil pitch should be determined by the loaded ammo. |
| ammoRecoilYaw | Boolean | false | If the bullet recoil yaw should be determined by the loaded ammo. |
| acceptedAmmo | String[] | - | Accepted ammunition for this weapon. |
| dynamicAmmo | Boolean | false | If true &amp;&amp; != null, ammo model will be set by ammo type used. Used built-in ammo model by default. |
| internalAmmoStorage | Integer | - | - |
| acceptedBullets | String[] | - | Accepted bullets for this weapon. |
| allowSpringFiring | Boolean | false | Whether this weapon permits firing while sprinting. |
| allowDefaultSounds | Boolean | true | Whether default Modulus sounds should also be used for firing. |
| emptyPitch | Float | 0.05F | - |
| weaponSoundMap | Map<WeaponSoundType, ArrayList\<SoundEntry\>> | - | Map of weapon sounds. | 