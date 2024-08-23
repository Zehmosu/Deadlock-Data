# Heroes and NPCs Data Export

## Heroes

# Hero: hero_base

- **_not_pickable**: 2
- **_class**: CitadelHeroData_t
- **m_bPlayerSelectable**: False
- **m_bDisabled**: False
- **m_bInDevelopment**: False
- **m_bNeedsTesting**: False
- **m_bAssignedPlayersOnly**: False
- **m_bBotSelectable**: False
- **m_bLimitedTesting**: False
- **m_nComplexity**: 3
- **m_nReadability**: 0
- **m_HeroID**: 0
- **m_strModelName**: resource_name:"models/heroes_staging/gen_man/gen_man.vmdl"
- **m_hDamageTakenParticle**: resource_name:"particles/generic/player_damage_screen.vpcf"
- **m_hGroundDamageTakenParticle**: resource_name:"particles/generic/player_ground_damage_screen.vpcf"
- **m_hDeathParticle**: resource_name:"particles/generic/player_death_screen.vpcf"
- **m_hLowHealthParticle**: resource_name:"particles/generic/player_low_health_screen.vpcf"
- **m_hRespawnParticle**: resource_name:"particles/generic/player_respawn_deploy.vpcf"
- **m_nModelSkin**: 0
- **m_mapStartingStats**:
  - **EMaxMoveSpeed**: 7
  - **ESprintSpeed**: 0
  - **ECrouchSpeed**: 4.75
  - **EMoveAcceleration**: 4
  - **ELightMeleeDamage**: 63
  - **EHeavyMeleeDamage**: 116
  - **EMaxHealth**: 550
  - **EWeaponPower**: 0
  - **EReloadSpeed**: 1
  - **EWeaponPowerScale**: 1
  - **EProcBuildUpRateScale**: 1
  - **EStamina**: 3
  - **EBaseHealthRegen**: 2.0
  - **EStaminaRegenPerSecond**: 0.2
  - **EAbilityResourceMax**: 0
  - **EAbilityResourceRegenPerSecond**: 0
  - **ECritDamageReceivedScale**: 1.0
  - **ETechDuration**: 1
  - **ETechRange**: 1
- **m_flCollisionRadius**: 20
- **m_flCollisionHeight**: 80
- **m_flStepHeight**: 32
- **m_mapBoundAbilities**:
  - **ESlot_Weapon_Primary**: citadel_weapon_inferno_set
  - **ESlot_Weapon_Melee**: ability_melee_inferno
  - **ESlot_Ability_Mantle**: citadel_ability_mantle
  - **ESlot_Ability_Jump**: citadel_ability_jump
  - **ESlot_Ability_Slide**: citadel_ability_slide
  - **ESlot_Ability_ZipLine**: citadel_ability_zip_line
  - **ESlot_Ability_ZipLineBoost**: citadel_ability_zipline_boost
  - **ESlot_Ability_Innate_1**: citadel_ability_dash
  - **ESlot_Ability_Innate_2**: citadel_ability_sprint
  - **ESlot_Ability_Innate_3**: citadel_ability_melee_parry
- **m_mapItemSlotInfo**:
  - **EItemSlotType_WeaponMod**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
  - **EItemSlotType_Armor**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
  - **EItemSlotType_Tech**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
- **m_mapPurchaseBonuses**:
  - **EItemSlotType_WeaponMod**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 6 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 2 | 10 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 3 | 14 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 4 | 18 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
  - **EItemSlotType_Armor**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 11 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 2 | 14 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 3 | 17 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 4 | 20 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
  - **EItemSlotType_Tech**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 4 | MODIFIER_VALUE_TECH_POWER |
    | 2 | 8 | MODIFIER_VALUE_TECH_POWER |
    | 3 | 12 | MODIFIER_VALUE_TECH_POWER |
    | 4 | 16 | MODIFIER_VALUE_TECH_POWER |
- **m_mapLevelInfo**:
  - **1**:
    - **m_unRequiredGold**: 0
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **2**:
    - **m_unRequiredGold**: 400
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
      - **EAbilityPoints**: 1
  - **3**:
    - **m_unRequiredGold**: 800
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **4**:
    - **m_unRequiredGold**: 1200
    - **m_bUseStandardUpgrade**: True
  - **5**:
    - **m_unRequiredGold**: 1500
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **6**:
    - **m_unRequiredGold**: 2200
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **7**:
    - **m_unRequiredGold**: 3000
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **8**:
    - **m_unRequiredGold**: 4500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **9**:
    - **m_unRequiredGold**: 6000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **10**:
    - **m_unRequiredGold**: 7500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **11**:
    - **m_unRequiredGold**: 9000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **12**:
    - **m_unRequiredGold**: 10500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **13**:
    - **m_unRequiredGold**: 12000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **14**:
    - **m_unRequiredGold**: 13000
    - **m_bUseStandardUpgrade**: True
  - **15**:
    - **m_unRequiredGold**: 14000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **16**:
    - **m_unRequiredGold**: 15000
    - **m_bUseStandardUpgrade**: True
  - **17**:
    - **m_unRequiredGold**: 16000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **18**:
    - **m_unRequiredGold**: 18000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **19**:
    - **m_unRequiredGold**: 20000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **20**:
    - **m_unRequiredGold**: 22000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **21**:
    - **m_unRequiredGold**: 24000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **22**:
    - **m_unRequiredGold**: 27000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **23**:
    - **m_unRequiredGold**: 30000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **24**:
    - **m_unRequiredGold**: 33000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **25**:
    - **m_unRequiredGold**: 36000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **26**:
    - **m_unRequiredGold**: 39000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **27**:
    - **m_unRequiredGold**: 42000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **28**:
    - **m_unRequiredGold**: 45000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **29**:
    - **m_unRequiredGold**: 48000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
- **m_hFootstepSounds**: sweetener_default
- **m_strFootstepSoundEventDefault**: soundevent:"Hero.Default.Footstep"
- **m_flStealthSpeedMetersPerSecond**: 4
- **m_flFootstepSoundTravelDistanceMeters**: 20
- **m_flStepSoundTime**: 0.3
- **m_vecAnimGraphDefaultValueOverrides**:
  | m_strParamName | m_strParamValue |
  | --- | --- |
  | e_SWITCH_4wayRoll_ON/OFF | 0 |
  | e_SWITCH_Recoil_ON/OFF | 0 |
  | e_SWITCH_ZiplinePhysicsSway_ON/OFF | 0 |
  | e_SWITCH_ShootStyle | 0 |
- **m_strLastHitSound**: soundevent:"LastHit.Default"
- **m_strLowHealthSound**: soundevent:"PlayerAlert.LowHealth"
- **m_colorUI**:
  - 255
  - 255
  - 255
- **m_colorGlowFriendly**:
  - 255
  - 239
  - 215
- **m_colorGlowEnemy**:
  - 255
  - 0
  - 0
- **m_colorGlowTeam1**:
  - 231
  - 182
  - 89
- **m_colorGlowTeam2**:
  - 91
  - 121
  - 230
- **m_vecAmbientParticleSettings**:
  | m_eAttachmentType | m_nCP |
  | --- | --- |
  | PATTACH_ABSORIGIN_FOLLOW | 0 |
  | PATTACH_POINT_FOLLOW | 1 |
- **m_heroStatsUI**:
  - **m_vecDisplayStats**:
    | m_eStatType | m_eStatCategory |
    | --- | --- |
    | EMaxHealth | ECitadelStat_Vitality |
    | EBaseHealthRegen | ECitadelStat_Vitality |
    | EBulletArmorDamageReduction | ECitadelStat_Vitality |
    | ETechArmorDamageReduction | ECitadelStat_Vitality |
    | ETechPower | ECitadelStat_Spirit |
    | EWeaponDPS | ECitadelStat_Weapon |
    | EBulletDamage | ECitadelStat_Weapon |
    | EClipSize | ECitadelStat_Weapon |
    | ERoundsPerSecond | ECitadelStat_Weapon |
    | ELightMeleeDamage | ECitadelStat_Weapon |
    | EHeavyMeleeDamage | ECitadelStat_Weapon |
    | EMaxMoveSpeed | ECitadelStat_Vitality |
    | ESprintSpeed | ECitadelStat_Vitality |
    | EStamina | ECitadelStat_Vitality |
  - **m_eWeaponStatDisplay**: EMeleeDamage_DEPRECATED
- **m_mapScalingStats**:
- **m_heroStatsDisplay**:
  - **m_vecHealthHeaderStats**:
    - EMaxHealth
    - EBaseHealthRegen
  - **m_vecHealthStats**:
    - EBulletArmorDamageReduction
    - ETechArmorDamageReduction
    - EBulletShieldHealth
    - ETechShieldHealth
    - EBulletLifesteal
    - ETechLifesteal
    - EMaxMoveSpeed
    - ESprintSpeed
    - EStamina
    - EHealingOutput
  - **m_vecWeaponHeaderStats**:
    - EWeaponDPS
    - EBulletDamage
  - **m_vecWeaponStats**:
    - ELightMeleeDamage
    - EHeavyMeleeDamage
    - EFireRate
    - EClipSize
  - **m_vecMagicHeaderStats**:
    - ETechPower
  - **m_vecMagicStats**:
    - ETechCooldown
    - ETechRange
    - ETechDuration
- **m_mapStandardLevelUpUpgrades**:
  - **MODIFIER_VALUE_BASE_BULLET_DAMAGE_FROM_LEVEL**: 0.0
  - **MODIFIER_VALUE_BASE_MELEE_DAMAGE_FROM_LEVEL**: 3.4
  - **MODIFIER_VALUE_BASE_HEALTH_FROM_LEVEL**: 41.0
  - **MODIFIER_VALUE_TECH_DAMAGE_PERCENT**: 0.0
  - **MODIFIER_VALUE_BULLET_ARMOR_DAMAGE_RESIST**: 0.0
- **m_eAbilityResourceType**: EResourceType_None
- **m_ShopStatDisplay**:
  - **m_eWeaponStatsDisplay**:
    - **m_vecDisplayStats**:
      - EBulletDamage
      - EBaseWeaponDamageIncrease
      - ERoundsPerSecond
      - EFireRate
      - EClipSize
      - EClipSizeIncrease
      - EReloadTime
      - EReloadSpeed
      - EBulletSpeed
      - EBulletSpeedIncrease
      - EBulletLifesteal
    - **m_vecOtherDisplayStats**:
      - ELightMeleeDamage
      - EHeavyMeleeDamage
  - **m_eVitalityStatsDisplay**:
    - **m_vecDisplayStats**:
      - EMaxHealth
      - EBaseHealthRegen
      - EBulletArmorDamageReduction
      - ETechArmorDamageReduction
      - EBulletShieldHealth
      - ETechShieldHealth
      - ECritDamageReceivedScale
    - **m_vecOtherDisplayStats**:
      - EMaxMoveSpeed
      - ESprintSpeed
      - EStaminaCooldown
      - EStaminaRegenIncrease
      - EStamina
  - **m_eSpiritStatsDisplay**:
    - **m_vecDisplayStats**:
      - ETechCooldown
      - ETechDuration
      - ETechRange
      - ETechLifesteal
      - EMaxChargesIncrease
      - ETechCooldownBetweenChargeUses

---

# Hero: hero_inferno

- **_class**: CitadelHeroData_t
- **m_bPlayerSelectable**: True
- **m_bDisabled**: False
- **m_bInDevelopment**: False
- **m_bNeedsTesting**: False
- **m_bAssignedPlayersOnly**: False
- **m_bBotSelectable**: False
- **m_bLimitedTesting**: False
- **m_nComplexity**: 1
- **m_nReadability**: 6
- **m_HeroID**: 1
- **m_strModelName**: resource_name:"models/heroes_staging/inferno_v4/inferno.vmdl"
- **m_hDamageTakenParticle**: resource_name:"particles/generic/player_damage_screen.vpcf"
- **m_hGroundDamageTakenParticle**: resource_name:"particles/generic/player_ground_damage_screen.vpcf"
- **m_hDeathParticle**: resource_name:"particles/generic/player_death_screen.vpcf"
- **m_hLowHealthParticle**: resource_name:"particles/generic/player_low_health_screen.vpcf"
- **m_hRespawnParticle**: resource_name:"particles/generic/player_respawn_deploy.vpcf"
- **m_nModelSkin**: 0
- **m_mapStartingStats**:
  - **EMaxMoveSpeed**: 6.5
  - **ESprintSpeed**: 0
  - **ECrouchSpeed**: 4.75
  - **EMoveAcceleration**: 4
  - **ELightMeleeDamage**: 63
  - **EHeavyMeleeDamage**: 116
  - **EMaxHealth**: 625
  - **EWeaponPower**: 0
  - **EReloadSpeed**: 1
  - **EWeaponPowerScale**: 1
  - **EProcBuildUpRateScale**: 1
  - **EStamina**: 3
  - **EBaseHealthRegen**: 2.0
  - **EStaminaRegenPerSecond**: 0.2
  - **EAbilityResourceMax**: 0
  - **EAbilityResourceRegenPerSecond**: 0
  - **ECritDamageReceivedScale**: 1.0
  - **ETechDuration**: 1
  - **ETechRange**: 1
- **m_flCollisionRadius**: 20
- **m_flCollisionHeight**: 80
- **m_flStepHeight**: 32
- **m_mapBoundAbilities**:
  - **ESlot_Weapon_Primary**: citadel_weapon_inferno_set
  - **ESlot_Weapon_Melee**: ability_melee_inferno
  - **ESlot_Ability_Mantle**: citadel_ability_mantle
  - **ESlot_Ability_Jump**: citadel_ability_jump
  - **ESlot_Ability_Slide**: citadel_ability_slide
  - **ESlot_Ability_ZipLine**: citadel_ability_zip_line
  - **ESlot_Ability_ZipLineBoost**: citadel_ability_zipline_boost
  - **ESlot_Ability_Innate_1**: citadel_ability_dash
  - **ESlot_Ability_Innate_2**: citadel_ability_sprint
  - **ESlot_Ability_Innate_3**: citadel_ability_melee_parry
  - **ESlot_Signature_1**: ability_incendiary_projectile
  - **ESlot_Signature_2**: ability_flame_dash
  - **ESlot_Signature_3**: ability_afterburn
  - **ESlot_Signature_4**: ability_fire_bomb
- **m_mapItemSlotInfo**:
  - **EItemSlotType_WeaponMod**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
  - **EItemSlotType_Armor**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
  - **EItemSlotType_Tech**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
- **m_mapPurchaseBonuses**:
  - **EItemSlotType_WeaponMod**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 6 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 2 | 10 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 3 | 14 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 4 | 18 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
  - **EItemSlotType_Armor**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 11 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 2 | 14 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 3 | 17 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 4 | 20 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
  - **EItemSlotType_Tech**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 4 | MODIFIER_VALUE_TECH_POWER |
    | 2 | 8 | MODIFIER_VALUE_TECH_POWER |
    | 3 | 12 | MODIFIER_VALUE_TECH_POWER |
    | 4 | 16 | MODIFIER_VALUE_TECH_POWER |
- **m_mapLevelInfo**:
  - **1**:
    - **m_unRequiredGold**: 0
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **2**:
    - **m_unRequiredGold**: 400
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
      - **EAbilityPoints**: 1
  - **3**:
    - **m_unRequiredGold**: 800
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **4**:
    - **m_unRequiredGold**: 1200
    - **m_bUseStandardUpgrade**: True
  - **5**:
    - **m_unRequiredGold**: 1500
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **6**:
    - **m_unRequiredGold**: 2200
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **7**:
    - **m_unRequiredGold**: 3000
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **8**:
    - **m_unRequiredGold**: 4500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **9**:
    - **m_unRequiredGold**: 6000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **10**:
    - **m_unRequiredGold**: 7500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **11**:
    - **m_unRequiredGold**: 9000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **12**:
    - **m_unRequiredGold**: 10500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **13**:
    - **m_unRequiredGold**: 12000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **14**:
    - **m_unRequiredGold**: 13000
    - **m_bUseStandardUpgrade**: True
  - **15**:
    - **m_unRequiredGold**: 14000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **16**:
    - **m_unRequiredGold**: 15000
    - **m_bUseStandardUpgrade**: True
  - **17**:
    - **m_unRequiredGold**: 16000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **18**:
    - **m_unRequiredGold**: 18000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **19**:
    - **m_unRequiredGold**: 20000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **20**:
    - **m_unRequiredGold**: 22000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **21**:
    - **m_unRequiredGold**: 24000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **22**:
    - **m_unRequiredGold**: 27000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **23**:
    - **m_unRequiredGold**: 30000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **24**:
    - **m_unRequiredGold**: 33000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **25**:
    - **m_unRequiredGold**: 36000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **26**:
    - **m_unRequiredGold**: 39000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **27**:
    - **m_unRequiredGold**: 42000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **28**:
    - **m_unRequiredGold**: 45000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **29**:
    - **m_unRequiredGold**: 48000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
- **m_hFootstepSounds**: sweetener_default
- **m_strFootstepSoundEventDefault**: soundevent:"Inferno.Footsteps"
- **m_flStealthSpeedMetersPerSecond**: 4
- **m_flFootstepSoundTravelDistanceMeters**: 20
- **m_flStepSoundTime**: 0.34
- **m_vecAnimGraphDefaultValueOverrides**:
  | m_strParamName | m_strParamValue |
  | --- | --- |
  | e_SWITCH_4wayRoll_ON/OFF | 0 |
  | e_SWITCH_Recoil_ON/OFF | 1 |
  | e_SWITCH_ZiplinePhysicsSway_ON/OFF | 0 |
  | e_SWITCH_ShootStyle | 0 |
- **m_strLastHitSound**: soundevent:"LastHit.Default"
- **m_strLowHealthSound**: soundevent:"PlayerAlert.LowHealth"
- **m_colorUI**:
  - 255
  - 70
  - 45
- **m_colorGlowFriendly**:
  - 255
  - 239
  - 215
- **m_colorGlowEnemy**:
  - 255
  - 0
  - 0
- **m_colorGlowTeam1**:
  - 231
  - 182
  - 89
- **m_colorGlowTeam2**:
  - 91
  - 121
  - 230
- **m_vecAmbientParticleSettings**:
  | m_eAttachmentType | m_nCP |
  | --- | --- |
  | PATTACH_ABSORIGIN_FOLLOW | 0 |
  | PATTACH_POINT_FOLLOW | 1 |
- **m_heroStatsUI**:
  - **m_vecDisplayStats**:
    | m_eStatType | m_eStatCategory |
    | --- | --- |
    | EMaxHealth | ECitadelStat_Vitality |
    | EBaseHealthRegen | ECitadelStat_Vitality |
    | EBulletArmorDamageReduction | ECitadelStat_Vitality |
    | ETechArmorDamageReduction | ECitadelStat_Vitality |
    | ETechPower | ECitadelStat_Spirit |
    | EWeaponDPS | ECitadelStat_Weapon |
    | EBulletDamage | ECitadelStat_Weapon |
    | EClipSize | ECitadelStat_Weapon |
    | ERoundsPerSecond | ECitadelStat_Weapon |
    | ELightMeleeDamage | ECitadelStat_Weapon |
    | EHeavyMeleeDamage | ECitadelStat_Weapon |
    | EMaxMoveSpeed | ECitadelStat_Vitality |
    | ESprintSpeed | ECitadelStat_Vitality |
    | EStamina | ECitadelStat_Vitality |
  - **m_eWeaponStatDisplay**: EMeleeDamage_DEPRECATED
- **m_mapScalingStats**:
- **m_heroStatsDisplay**:
  - **m_vecHealthHeaderStats**:
    - EMaxHealth
    - EBaseHealthRegen
  - **m_vecHealthStats**:
    - EBulletArmorDamageReduction
    - ETechArmorDamageReduction
    - EBulletShieldHealth
    - ETechShieldHealth
    - EBulletLifesteal
    - ETechLifesteal
    - EMaxMoveSpeed
    - ESprintSpeed
    - EStamina
    - EHealingOutput
  - **m_vecWeaponHeaderStats**:
    - EWeaponDPS
    - EBulletDamage
  - **m_vecWeaponStats**:
    - ELightMeleeDamage
    - EHeavyMeleeDamage
    - EFireRate
    - EClipSize
  - **m_vecMagicHeaderStats**:
    - ETechPower
  - **m_vecMagicStats**:
    - ETechCooldown
    - ETechRange
    - ETechDuration
- **m_mapStandardLevelUpUpgrades**:
  - **MODIFIER_VALUE_BASE_BULLET_DAMAGE_FROM_LEVEL**: 0.36
  - **MODIFIER_VALUE_BASE_MELEE_DAMAGE_FROM_LEVEL**: 3.4
  - **MODIFIER_VALUE_BASE_HEALTH_FROM_LEVEL**: 33.0
  - **MODIFIER_VALUE_TECH_DAMAGE_PERCENT**: 0.0
  - **MODIFIER_VALUE_BULLET_ARMOR_DAMAGE_RESIST**: 0.0
- **m_eAbilityResourceType**: EResourceType_None
- **m_ShopStatDisplay**:
  - **m_eWeaponStatsDisplay**:
    - **m_vecDisplayStats**:
      - EBulletDamage
      - EBaseWeaponDamageIncrease
      - ERoundsPerSecond
      - EFireRate
      - EClipSize
      - EClipSizeIncrease
      - EReloadTime
      - EReloadSpeed
      - EBulletSpeed
      - EBulletSpeedIncrease
      - EBulletLifesteal
    - **m_vecOtherDisplayStats**:
      - ELightMeleeDamage
      - EHeavyMeleeDamage
    - **m_eWeaponAttributes**: EWeaponAttribute_RapidFire | EWeaponAttribute_MediumRange
    - **m_strWeaponImage**: panorama:"file://{images}/heroes/guns/inferno_gun.psd"
  - **m_eVitalityStatsDisplay**:
    - **m_vecDisplayStats**:
      - EMaxHealth
      - EBaseHealthRegen
      - EBulletArmorDamageReduction
      - ETechArmorDamageReduction
      - EBulletShieldHealth
      - ETechShieldHealth
      - ECritDamageReceivedScale
    - **m_vecOtherDisplayStats**:
      - EMaxMoveSpeed
      - ESprintSpeed
      - EStaminaCooldown
      - EStaminaRegenIncrease
      - EStamina
  - **m_eSpiritStatsDisplay**:
    - **m_vecDisplayStats**:
      - ETechCooldown
      - ETechDuration
      - ETechRange
      - ETechLifesteal
      - EMaxChargesIncrease
      - ETechCooldownBetweenChargeUses
- **_base**: hero_base
- **m_bNewPlayerRecommended**: True
- **m_bLaneTestingRecommended**: True
- **m_strSelectionImage**: panorama:"file://{images}/heroes/inferno.psd"
- **m_strIconImageSmall**: panorama:"file://{images}/heroes/inferno_sm.psd"
- **m_strMinimapImage**: panorama:"file://{images}/heroes/inferno_mm.psd"
- **m_strUIAnimGraph**: resource_name:"models/heroes_staging/inferno_v4/ui_inferno.vanmgrph"
- **m_strWIPModelName**: resource_name:"models/heroes_staging/inferno_v4/inferno.vmdl"
- **m_strDeathSound**: soundevent:"Inferno.Death"
- **m_hGameSoundEventScript**: resource_name:"soundevents/hero/inferno.vsndevts"
- **m_hVOEventScript**: resource_name:"soundevents/vo/vo_hero_inferno.vsndevts"
- **m_strRosterSelectedSound**: soundevent:"Inferno.VO.HeroPick"
- **m_strIconHeroCard**: panorama:"file://{images}/heroes/inferno_card.psd"
- **m_hGeneratedVOEventScript**: resource_name:"soundevents/vo/generated_vo_hero_inferno.vsndevts"
- **m_strRosterRemovedSound**: soundevent:"Inferno.VO.HeroRemove"
- **m_strTopBarImage**: panorama:"file://{images}/hud/hero_portraits/inferno_hud.psd"
- **m_hAmbientParticle**: resource_name:"particles/abilities/inferno/inferno_hand_ambient.vpcf"
- **m_RecommendedUpgrades**:
  - upgrade_clip_size
  - upgrade_endurance
  - upgrade_rapid_rounds
  - upgrade_improved_spirit
  - upgrade_resilience
  - upgrade_magic_vulnerability
  - upgrade_quick_silver
  - upgrade_arcane_extension
  - upgrade_bullet_armor
  - upgrade_tech_armor
  - upgrade_tech_defense_shredders
  - upgrade_soaring_spirit
  - upgrade_toxic_bullets
  - upgrade_damage_recycler
  - upgrade_ricochet
- **m_strUIPortraitMap**: maps/ui/hero_prefabs/inferno.vmap
- **m_strTopBarVertical**: panorama:"file://{images}/heroes/inferno_vertical.psd"
- **m_strUIShopAnimGraph**: resource_name:"models/heroes_staging/inferno_v4/ui_shop_inferno.vanmgrph"
- **m_strUIShoppingMap**: maps/ui/hero_shop/inferno_shop.vmap

---

# Hero: hero_gigawatt

- **_class**: CitadelHeroData_t
- **m_bPlayerSelectable**: True
- **m_bDisabled**: False
- **m_bInDevelopment**: False
- **m_bNeedsTesting**: False
- **m_bAssignedPlayersOnly**: False
- **m_bBotSelectable**: True
- **m_bLimitedTesting**: False
- **m_nComplexity**: 1
- **m_nReadability**: 4
- **m_HeroID**: 2
- **m_strModelName**: resource_name:"models/heroes_staging/gigawatt_prisoner/gigawatt_prisoner.vmdl"
- **m_hDamageTakenParticle**: resource_name:"particles/generic/player_damage_screen.vpcf"
- **m_hGroundDamageTakenParticle**: resource_name:"particles/generic/player_ground_damage_screen.vpcf"
- **m_hDeathParticle**: resource_name:"particles/generic/player_death_screen.vpcf"
- **m_hLowHealthParticle**: resource_name:"particles/generic/player_low_health_screen.vpcf"
- **m_hRespawnParticle**: resource_name:"particles/generic/player_respawn_deploy.vpcf"
- **m_nModelSkin**: 0
- **m_mapStartingStats**:
  - **EMaxMoveSpeed**: 7
  - **ESprintSpeed**: 0
  - **ECrouchSpeed**: 4.75
  - **EMoveAcceleration**: 4
  - **ELightMeleeDamage**: 63
  - **EHeavyMeleeDamage**: 116
  - **EMaxHealth**: 550
  - **EWeaponPower**: 0
  - **EReloadSpeed**: 1
  - **EWeaponPowerScale**: 1
  - **EProcBuildUpRateScale**: 1
  - **EStamina**: 3
  - **EBaseHealthRegen**: 1.5
  - **EStaminaRegenPerSecond**: 0.2
  - **EAbilityResourceMax**: 0
  - **EAbilityResourceRegenPerSecond**: 0
  - **ECritDamageReceivedScale**: 0.75
  - **ETechDuration**: 1
  - **ETechRange**: 1
  - **EBulletArmorDamageReduction**: 8.0
- **m_flCollisionRadius**: 20
- **m_flCollisionHeight**: 80
- **m_flStepHeight**: 32
- **m_mapBoundAbilities**:
  - **ESlot_Weapon_Primary**: citadel_weapon_gigawatt_set
  - **ESlot_Weapon_Melee**: citadel_ability_melee_gigawatt
  - **ESlot_Ability_Mantle**: citadel_ability_mantle
  - **ESlot_Ability_Jump**: citadel_ability_jump
  - **ESlot_Ability_Slide**: citadel_ability_slide
  - **ESlot_Ability_ZipLine**: citadel_ability_zip_line
  - **ESlot_Ability_ZipLineBoost**: citadel_ability_zipline_boost
  - **ESlot_Ability_Innate_1**: citadel_ability_dash
  - **ESlot_Ability_Innate_2**: citadel_ability_sprint
  - **ESlot_Ability_Innate_3**: citadel_ability_melee_parry
  - **ESlot_Signature_1**: citadel_ability_lightning_ball
  - **ESlot_Signature_2**: citadel_ability_static_charge
  - **ESlot_Signature_3**: ability_power_surge
  - **ESlot_Signature_4**: citadel_ability_storm_cloud
- **m_mapItemSlotInfo**:
  - **EItemSlotType_WeaponMod**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
  - **EItemSlotType_Armor**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
  - **EItemSlotType_Tech**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
- **m_mapPurchaseBonuses**:
  - **EItemSlotType_WeaponMod**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 6 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 2 | 10 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 3 | 14 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 4 | 18 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
  - **EItemSlotType_Armor**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 11 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 2 | 14 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 3 | 17 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 4 | 20 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
  - **EItemSlotType_Tech**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 4 | MODIFIER_VALUE_TECH_POWER |
    | 2 | 8 | MODIFIER_VALUE_TECH_POWER |
    | 3 | 12 | MODIFIER_VALUE_TECH_POWER |
    | 4 | 16 | MODIFIER_VALUE_TECH_POWER |
- **m_mapLevelInfo**:
  - **1**:
    - **m_unRequiredGold**: 0
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **2**:
    - **m_unRequiredGold**: 400
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
      - **EAbilityPoints**: 1
  - **3**:
    - **m_unRequiredGold**: 800
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **4**:
    - **m_unRequiredGold**: 1200
    - **m_bUseStandardUpgrade**: True
  - **5**:
    - **m_unRequiredGold**: 1500
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **6**:
    - **m_unRequiredGold**: 2200
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **7**:
    - **m_unRequiredGold**: 3000
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **8**:
    - **m_unRequiredGold**: 4500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **9**:
    - **m_unRequiredGold**: 6000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **10**:
    - **m_unRequiredGold**: 7500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **11**:
    - **m_unRequiredGold**: 9000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **12**:
    - **m_unRequiredGold**: 10500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **13**:
    - **m_unRequiredGold**: 12000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **14**:
    - **m_unRequiredGold**: 13000
    - **m_bUseStandardUpgrade**: True
  - **15**:
    - **m_unRequiredGold**: 14000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **16**:
    - **m_unRequiredGold**: 15000
    - **m_bUseStandardUpgrade**: True
  - **17**:
    - **m_unRequiredGold**: 16000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **18**:
    - **m_unRequiredGold**: 18000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **19**:
    - **m_unRequiredGold**: 20000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **20**:
    - **m_unRequiredGold**: 22000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **21**:
    - **m_unRequiredGold**: 24000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **22**:
    - **m_unRequiredGold**: 27000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **23**:
    - **m_unRequiredGold**: 30000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **24**:
    - **m_unRequiredGold**: 33000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **25**:
    - **m_unRequiredGold**: 36000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **26**:
    - **m_unRequiredGold**: 39000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **27**:
    - **m_unRequiredGold**: 42000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **28**:
    - **m_unRequiredGold**: 45000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **29**:
    - **m_unRequiredGold**: 48000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
- **m_hFootstepSounds**: sweetener_default
- **m_strFootstepSoundEventDefault**: soundevent:"Gigawatt.Footstep.Multi"
- **m_flStealthSpeedMetersPerSecond**: 4
- **m_flFootstepSoundTravelDistanceMeters**: 20
- **m_flStepSoundTime**: 0.28
- **m_vecAnimGraphDefaultValueOverrides**:
  | m_strParamName | m_strParamValue |
  | --- | --- |
  | e_SWITCH_4wayRoll_ON/OFF | 0 |
  | e_SWITCH_Recoil_ON/OFF | 0 |
  | e_SWITCH_ZiplinePhysicsSway_ON/OFF | 0 |
  | e_SWITCH_ShootStyle | 0 |
- **m_strLastHitSound**: soundevent:"LastHit.Default"
- **m_strLowHealthSound**: soundevent:"PlayerAlert.LowHealth"
- **m_colorUI**:
  - 237
  - 149
  - 60
- **m_colorGlowFriendly**:
  - 255
  - 239
  - 215
- **m_colorGlowEnemy**:
  - 255
  - 0
  - 0
- **m_colorGlowTeam1**:
  - 231
  - 182
  - 89
- **m_colorGlowTeam2**:
  - 91
  - 121
  - 230
- **m_vecAmbientParticleSettings**:
  | m_eAttachmentType | m_nCP |
  | --- | --- |
  | PATTACH_ABSORIGIN_FOLLOW | 0 |
  | PATTACH_POINT_FOLLOW | 1 |
- **m_heroStatsUI**:
  - **m_vecDisplayStats**:
    | m_eStatType | m_eStatCategory |
    | --- | --- |
    | EMaxHealth | ECitadelStat_Vitality |
    | EBaseHealthRegen | ECitadelStat_Vitality |
    | EBulletArmorDamageReduction | ECitadelStat_Vitality |
    | ETechArmorDamageReduction | ECitadelStat_Vitality |
    | ETechPower | ECitadelStat_Spirit |
    | EWeaponDPS | ECitadelStat_Weapon |
    | EBulletDamage | ECitadelStat_Weapon |
    | EClipSize | ECitadelStat_Weapon |
    | ERoundsPerSecond | ECitadelStat_Weapon |
    | ELightMeleeDamage | ECitadelStat_Weapon |
    | EHeavyMeleeDamage | ECitadelStat_Weapon |
    | EMaxMoveSpeed | ECitadelStat_Vitality |
    | ESprintSpeed | ECitadelStat_Vitality |
    | EStamina | ECitadelStat_Vitality |
  - **m_eWeaponStatDisplay**: EMeleeDamage_DEPRECATED
- **m_mapScalingStats**:
  - **EMaxMoveSpeed**:
    - **eScalingStat**: ETechPower
    - **flScale**: 0.028
- **m_heroStatsDisplay**:
  - **m_vecHealthHeaderStats**:
    - EMaxHealth
    - EBaseHealthRegen
  - **m_vecHealthStats**:
    - EBulletArmorDamageReduction
    - ETechArmorDamageReduction
    - EBulletShieldHealth
    - ETechShieldHealth
    - EBulletLifesteal
    - ETechLifesteal
    - EMaxMoveSpeed
    - ESprintSpeed
    - EStamina
    - EHealingOutput
  - **m_vecWeaponHeaderStats**:
    - EWeaponDPS
    - EBulletDamage
  - **m_vecWeaponStats**:
    - ELightMeleeDamage
    - EHeavyMeleeDamage
    - EFireRate
    - EClipSize
  - **m_vecMagicHeaderStats**:
    - ETechPower
  - **m_vecMagicStats**:
    - ETechCooldown
    - ETechRange
    - ETechDuration
- **m_mapStandardLevelUpUpgrades**:
  - **MODIFIER_VALUE_BASE_BULLET_DAMAGE_FROM_LEVEL**: 0.76
  - **MODIFIER_VALUE_BASE_MELEE_DAMAGE_FROM_LEVEL**: 3.4
  - **MODIFIER_VALUE_BASE_HEALTH_FROM_LEVEL**: 31.0
  - **MODIFIER_VALUE_TECH_DAMAGE_PERCENT**: 0.0
  - **MODIFIER_VALUE_BULLET_ARMOR_DAMAGE_RESIST**: 1.0
- **m_eAbilityResourceType**: EResourceType_None
- **m_ShopStatDisplay**:
  - **m_eWeaponStatsDisplay**:
    - **m_vecDisplayStats**:
      - EBulletDamage
      - EBaseWeaponDamageIncrease
      - ERoundsPerSecond
      - EFireRate
      - EClipSize
      - EClipSizeIncrease
      - EReloadTime
      - EReloadSpeed
      - EBulletSpeed
      - EBulletSpeedIncrease
      - EBulletLifesteal
    - **m_vecOtherDisplayStats**:
      - ELightMeleeDamage
      - EHeavyMeleeDamage
    - **m_eWeaponAttributes**: EWeaponAttribute_BurstFire | EWeaponAttribute_MediumRange
    - **m_strWeaponImage**: panorama:"file://{images}/heroes/guns/gigawatt_gun.psd"
  - **m_eVitalityStatsDisplay**:
    - **m_vecDisplayStats**:
      - EMaxHealth
      - EBaseHealthRegen
      - EBulletArmorDamageReduction
      - ETechArmorDamageReduction
      - EBulletShieldHealth
      - ETechShieldHealth
      - ECritDamageReceivedScale
    - **m_vecOtherDisplayStats**:
      - EMaxMoveSpeed
      - ESprintSpeed
      - EStaminaCooldown
      - EStaminaRegenIncrease
      - EStamina
  - **m_eSpiritStatsDisplay**:
    - **m_vecDisplayStats**:
      - ETechCooldown
      - ETechDuration
      - ETechRange
      - ETechLifesteal
      - EMaxChargesIncrease
      - ETechCooldownBetweenChargeUses
- **_base**: hero_base
- **m_bNewPlayerRecommended**: True
- **m_bLaneTestingRecommended**: True
- **m_strSelectionImage**: panorama:"file://{images}/heroes/gigawatt.psd"
- **m_strIconImageSmall**: panorama:"file://{images}/heroes/gigawatt_sm.psd"
- **m_strMinimapImage**: panorama:"file://{images}/heroes/gigawatt_mm.psd"
- **m_strUIAnimGraph**: resource_name:"models/heroes_staging/gigawatt_prisoner/ui_gigawatt_prisoner.vanmgrph"
- **m_strWIPModelName**: resource_name:"models/heroes_staging/gigawatt_prisoner/gigawatt_prisoner.vmdl"
- **m_strDeathSound**: soundevent:"Gigawatt.Death"
- **m_hGameSoundEventScript**: resource_name:"soundevents/hero/gigawatt.vsndevts"
- **m_hVOEventScript**: resource_name:"soundevents/vo/vo_hero_gigawatt.vsndevts"
- **m_strRosterSelectedSound**: soundevent:"Gigawatt.VO.HeroPick"
- **m_strIconHeroCard**: panorama:"file://{images}/heroes/gigawatt_card.psd"
- **m_hGeneratedVOEventScript**: resource_name:"soundevents/vo/generated_vo_hero_gigawatt.vsndevts"
- **m_strRosterRemovedSound**: soundevent:"Gigawatt.VO.HeroRemove"
- **m_strTopBarImage**: panorama:"file://{images}/hud/hero_portraits/gigwatt_hud.psd"
- **m_cameraSequenceLatched**:
  - **m_vecDistanceOperations**:
    | m_bLerpEndAtDefault | m_flLerpEnd | m_flLerpDuration | m_eCameraOperation |
    | --- | --- | --- | --- |
    | False | 150.0 | 0.3 | k_ECameraOp_Lerp |
    |  |  |  | k_ECameraOp_Maintain |
  - **m_vecFOVOperations**:
    | m_bLerpEndAtDefault | m_flLerpEnd | m_flLerpDuration | m_eCameraOperation |
    | --- | --- | --- | --- |
    | False | 120.0 | 0.3 | k_ECameraOp_Lerp |
    |  |  |  | k_ECameraOp_Maintain |
- **m_cameraSequenceAttached**:
  - **m_vecDistanceOperations**:
    | m_bLerpEndAtDefault | m_flLerpEnd | m_flLerpDuration | m_eCameraOperation |
    | --- | --- | --- | --- |
    | False | 71.0 | 0.4 | k_ECameraOp_Lerp |
  - **m_vecFOVOperations**:
    | m_flLerpDuration | m_eCameraOperation |
    | --- | --- |
    | 5.0 | k_ECameraOp_Lerp |
- **m_cameraSequenceClear**:
- **m_strUIPortraitMap**: maps/ui/hero_prefabs/gigawatt.vmap
- **m_RecommendedUpgrades**:
  - upgrade_non_player_bonus
  - upgrade_resilience
  - upgrade_improved_spirit
  - upgrade_magic_reach
  - upgrade_tech_defense_shredders
  - upgrade_health_stealing_magic
  - upgrade_tech_armor
  - upgrade_bullet_armor
  - upgrade_magic_vulnerability
  - upgrade_suppressor
  - upgrade_rocket_booster
  - upgrade_chain_lightning
  - upgrade_magic_slow
  - upgrade_soaring_spirit
  - upgrade_tech_purge
  - upgrade_damage_recycler
  - upgrade_escalating_exposure
- **m_strTopBarVertical**: panorama:"file://{images}/heroes/gigawatt_vertical.psd"
- **m_strUIShopAnimGraph**: resource_name:"models/heroes_staging/gigawatt_prisoner/ui_shop_gigawatt_prisoner.vanmgrph"
- **m_strUIShoppingMap**: maps/ui/hero_shop/gigawatt_shop.vmap

---

# Hero: hero_hornet

- **_class**: CitadelHeroData_t
- **m_bPlayerSelectable**: True
- **m_bDisabled**: False
- **m_bInDevelopment**: False
- **m_bNeedsTesting**: False
- **m_bAssignedPlayersOnly**: False
- **m_bBotSelectable**: True
- **m_bLimitedTesting**: False
- **m_nComplexity**: 1
- **m_nReadability**: 3
- **m_HeroID**: 3
- **m_strModelName**: resource_name:"models/heroes_staging/hornet_v3/hornet.vmdl"
- **m_hDamageTakenParticle**: resource_name:"particles/generic/player_damage_screen.vpcf"
- **m_hGroundDamageTakenParticle**: resource_name:"particles/generic/player_ground_damage_screen.vpcf"
- **m_hDeathParticle**: resource_name:"particles/generic/player_death_screen.vpcf"
- **m_hLowHealthParticle**: resource_name:"particles/generic/player_low_health_screen.vpcf"
- **m_hRespawnParticle**: resource_name:"particles/generic/player_respawn_deploy.vpcf"
- **m_nModelSkin**: 0
- **m_mapStartingStats**:
  - **EMaxMoveSpeed**: 8
  - **ESprintSpeed**: 0
  - **ECrouchSpeed**: 4.75
  - **EMoveAcceleration**: 4
  - **ELightMeleeDamage**: 63
  - **EHeavyMeleeDamage**: 116
  - **EMaxHealth**: 550
  - **EWeaponPower**: 0
  - **EReloadSpeed**: 1
  - **EWeaponPowerScale**: 1
  - **EProcBuildUpRateScale**: 1
  - **EStamina**: 2
  - **EBaseHealthRegen**: 2.0
  - **EStaminaRegenPerSecond**: 0.2
  - **EAbilityResourceMax**: 0
  - **EAbilityResourceRegenPerSecond**: 0
  - **ECritDamageReceivedScale**: 1.0
  - **ETechDuration**: 1
  - **ETechRange**: 1
  - **EBulletArmorDamageReduction**: -10.0
- **m_flCollisionRadius**: 20
- **m_flCollisionHeight**: 80
- **m_flStepHeight**: 32
- **m_mapBoundAbilities**:
  - **ESlot_Weapon_Primary**: citadel_weapon_hornet_set
  - **ESlot_Weapon_Melee**: citadel_ability_melee_hornet
  - **ESlot_Ability_Mantle**: citadel_ability_mantle
  - **ESlot_Ability_Jump**: citadel_ability_jump
  - **ESlot_Ability_Slide**: citadel_ability_slide
  - **ESlot_Ability_ZipLine**: citadel_ability_zip_line
  - **ESlot_Ability_ZipLineBoost**: citadel_ability_zipline_boost
  - **ESlot_Ability_Innate_1**: citadel_ability_dash
  - **ESlot_Ability_Innate_2**: citadel_ability_sprint
  - **ESlot_Ability_Innate_3**: citadel_ability_melee_parry
  - **ESlot_Signature_1**: citadel_ability_hornet_chain
  - **ESlot_Signature_2**: citadel_ability_hornet_leap
  - **ESlot_Signature_3**: citadel_ability_hornet_sting
  - **ESlot_Signature_4**: citadel_ability_hornet_snipe
- **m_mapItemSlotInfo**:
  - **EItemSlotType_WeaponMod**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
  - **EItemSlotType_Armor**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
  - **EItemSlotType_Tech**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
- **m_mapPurchaseBonuses**:
  - **EItemSlotType_WeaponMod**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 6 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 2 | 10 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 3 | 14 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 4 | 18 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
  - **EItemSlotType_Armor**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 11 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 2 | 14 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 3 | 17 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 4 | 20 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
  - **EItemSlotType_Tech**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 4 | MODIFIER_VALUE_TECH_POWER |
    | 2 | 8 | MODIFIER_VALUE_TECH_POWER |
    | 3 | 12 | MODIFIER_VALUE_TECH_POWER |
    | 4 | 16 | MODIFIER_VALUE_TECH_POWER |
- **m_mapLevelInfo**:
  - **1**:
    - **m_unRequiredGold**: 0
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **2**:
    - **m_unRequiredGold**: 400
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
      - **EAbilityPoints**: 1
  - **3**:
    - **m_unRequiredGold**: 800
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **4**:
    - **m_unRequiredGold**: 1200
    - **m_bUseStandardUpgrade**: True
  - **5**:
    - **m_unRequiredGold**: 1500
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **6**:
    - **m_unRequiredGold**: 2200
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **7**:
    - **m_unRequiredGold**: 3000
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **8**:
    - **m_unRequiredGold**: 4500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **9**:
    - **m_unRequiredGold**: 6000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **10**:
    - **m_unRequiredGold**: 7500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **11**:
    - **m_unRequiredGold**: 9000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **12**:
    - **m_unRequiredGold**: 10500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **13**:
    - **m_unRequiredGold**: 12000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **14**:
    - **m_unRequiredGold**: 13000
    - **m_bUseStandardUpgrade**: True
  - **15**:
    - **m_unRequiredGold**: 14000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **16**:
    - **m_unRequiredGold**: 15000
    - **m_bUseStandardUpgrade**: True
  - **17**:
    - **m_unRequiredGold**: 16000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **18**:
    - **m_unRequiredGold**: 18000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **19**:
    - **m_unRequiredGold**: 20000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **20**:
    - **m_unRequiredGold**: 22000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **21**:
    - **m_unRequiredGold**: 24000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **22**:
    - **m_unRequiredGold**: 27000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **23**:
    - **m_unRequiredGold**: 30000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **24**:
    - **m_unRequiredGold**: 33000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **25**:
    - **m_unRequiredGold**: 36000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **26**:
    - **m_unRequiredGold**: 39000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **27**:
    - **m_unRequiredGold**: 42000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **28**:
    - **m_unRequiredGold**: 45000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **29**:
    - **m_unRequiredGold**: 48000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
- **m_hFootstepSounds**: sweetener_soft
- **m_strFootstepSoundEventDefault**: soundevent:"Hornet.Footstep"
- **m_flStealthSpeedMetersPerSecond**: 4
- **m_flFootstepSoundTravelDistanceMeters**: 20
- **m_flStepSoundTime**: 0.4
- **m_vecAnimGraphDefaultValueOverrides**:
  | m_strParamName | m_strParamValue |
  | --- | --- |
  | e_SWITCH_4wayRoll_ON/OFF | 0 |
  | e_SWITCH_Recoil_ON/OFF | 0 |
  | e_SWITCH_ZiplinePhysicsSway_ON/OFF | 0 |
  | e_SWITCH_ShootStyle | 0 |
- **m_strLastHitSound**: soundevent:"LastHit.Default"
- **m_strLowHealthSound**: soundevent:"PlayerAlert.LowHealth"
- **m_colorUI**:
  - 156
  - 205
  - 236
- **m_colorGlowFriendly**:
  - 255
  - 239
  - 215
- **m_colorGlowEnemy**:
  - 255
  - 0
  - 0
- **m_colorGlowTeam1**:
  - 231
  - 182
  - 89
- **m_colorGlowTeam2**:
  - 91
  - 121
  - 230
- **m_vecAmbientParticleSettings**:
  | m_eAttachmentType | m_nCP |
  | --- | --- |
  | PATTACH_ABSORIGIN_FOLLOW | 0 |
  | PATTACH_POINT_FOLLOW | 1 |
- **m_heroStatsUI**:
  - **m_vecDisplayStats**:
    | m_eStatType | m_eStatCategory |
    | --- | --- |
    | EMaxHealth | ECitadelStat_Vitality |
    | EBaseHealthRegen | ECitadelStat_Vitality |
    | EBulletArmorDamageReduction | ECitadelStat_Vitality |
    | ETechArmorDamageReduction | ECitadelStat_Vitality |
    | ETechPower | ECitadelStat_Spirit |
    | EWeaponDPS | ECitadelStat_Weapon |
    | EBulletDamage | ECitadelStat_Weapon |
    | EClipSize | ECitadelStat_Weapon |
    | ERoundsPerSecond | ECitadelStat_Weapon |
    | ELightMeleeDamage | ECitadelStat_Weapon |
    | EHeavyMeleeDamage | ECitadelStat_Weapon |
    | EMaxMoveSpeed | ECitadelStat_Vitality |
    | ESprintSpeed | ECitadelStat_Vitality |
    | EStamina | ECitadelStat_Vitality |
  - **m_eWeaponStatDisplay**: EMeleeDamage_DEPRECATED
- **m_mapScalingStats**:
- **m_heroStatsDisplay**:
  - **m_vecHealthHeaderStats**:
    - EMaxHealth
    - EBaseHealthRegen
  - **m_vecHealthStats**:
    - EBulletArmorDamageReduction
    - ETechArmorDamageReduction
    - EBulletShieldHealth
    - ETechShieldHealth
    - EBulletLifesteal
    - ETechLifesteal
    - EMaxMoveSpeed
    - ESprintSpeed
    - EStamina
    - EHealingOutput
  - **m_vecWeaponHeaderStats**:
    - EWeaponDPS
    - EBulletDamage
  - **m_vecWeaponStats**:
    - ELightMeleeDamage
    - EHeavyMeleeDamage
    - EFireRate
    - EClipSize
  - **m_vecMagicHeaderStats**:
    - ETechPower
  - **m_vecMagicStats**:
    - ETechCooldown
    - ETechRange
    - ETechDuration
- **m_mapStandardLevelUpUpgrades**:
  - **MODIFIER_VALUE_BASE_BULLET_DAMAGE_FROM_LEVEL**: 1.0
  - **MODIFIER_VALUE_BASE_MELEE_DAMAGE_FROM_LEVEL**: 3.4
  - **MODIFIER_VALUE_BASE_HEALTH_FROM_LEVEL**: 20.0
  - **MODIFIER_VALUE_TECH_DAMAGE_PERCENT**: 0.0
  - **MODIFIER_VALUE_BULLET_ARMOR_DAMAGE_RESIST**: 0.0
- **m_eAbilityResourceType**: EResourceType_None
- **m_ShopStatDisplay**:
  - **m_eWeaponStatsDisplay**:
    - **m_vecDisplayStats**:
      - EBulletDamage
      - EBaseWeaponDamageIncrease
      - ERoundsPerSecond
      - EFireRate
      - EClipSize
      - EClipSizeIncrease
      - EReloadTime
      - EReloadSpeed
      - EBulletSpeed
      - EBulletSpeedIncrease
      - EBulletLifesteal
    - **m_vecOtherDisplayStats**:
      - ELightMeleeDamage
      - EHeavyMeleeDamage
    - **m_eWeaponAttributes**: EWeaponAttribute_RapidFire | EWeaponAttribute_LongRange
    - **m_strWeaponImage**: panorama:"file://{images}/heroes/guns/hornet_gun.psd"
  - **m_eVitalityStatsDisplay**:
    - **m_vecDisplayStats**:
      - EMaxHealth
      - EBaseHealthRegen
      - EBulletArmorDamageReduction
      - ETechArmorDamageReduction
      - EBulletShieldHealth
      - ETechShieldHealth
      - ECritDamageReceivedScale
    - **m_vecOtherDisplayStats**:
      - EMaxMoveSpeed
      - ESprintSpeed
      - EStaminaCooldown
      - EStaminaRegenIncrease
      - EStamina
  - **m_eSpiritStatsDisplay**:
    - **m_vecDisplayStats**:
      - ETechCooldown
      - ETechDuration
      - ETechRange
      - ETechLifesteal
      - EMaxChargesIncrease
      - ETechCooldownBetweenChargeUses
- **_base**: hero_base
- **m_bNewPlayerRecommended**: True
- **m_bLaneTestingRecommended**: True
- **m_strSelectionImage**: panorama:"file://{images}/heroes/hornet.psd"
- **m_strIconImageSmall**: panorama:"file://{images}/heroes/hornet_sm.png"
- **m_strMinimapImage**: panorama:"file://{images}/heroes/hornet_mm.psd"
- **m_strWIPModelName**: resource_name:"models/heroes_staging/hornet_v3/hornet.vmdl"
- **m_strUIAnimGraph**: resource_name:"models/heroes_staging/hornet_v3/ui_hornet.vanmgrph"
- **m_strDeathSound**: soundevent:"Hornet.Death"
- **m_hGameSoundEventScript**: resource_name:"soundevents/hero/hornet.vsndevts"
- **m_hVOEventScript**: resource_name:"soundevents/vo/vo_hero_hornet.vsndevts"
- **m_strRosterSelectedSound**: soundevent:"Vindicta.VO.HeroPick"
- **m_strIconHeroCard**: panorama:"file://{images}/heroes/hornet_card.psd"
- **m_hGeneratedVOEventScript**: resource_name:"soundevents/vo/generated_vo_hero_hornet.vsndevts"
- **m_strRosterRemovedSound**: soundevent:"Vindicta.VO.HeroRemove"
- **m_strTopBarImage**: panorama:"file://{images}/hud/hero_portraits/hornet_hud.psd"
- **m_strUIPortraitMap**: maps/ui/hero_prefabs/hornet.vmap
- **m_RecommendedUpgrades**:
  - upgrade_endurance
  - upgrade_hollow_point_rounds
  - upgrade_headshot_booster
  - upgrade_improved_spirit
  - upgrade_extra_charge
  - upgrade_long_range
  - upgrade_slowing_bullets
  - upgrade_magic_shield
  - upgrade_regenerating_bullet_shield
  - upgrade_quick_silver
  - upgrade_sharpshooter
  - upgrade_rapid_recharge
  - upgrade_chonky
  - upgrade_soaring_spirit
  - upgrade_critshot
  - upgrade_mega_spirit
  - upgrade_silencer
- **m_strTopBarVertical**: panorama:"file://{images}/heroes/hornet_vertical.psd"
- **m_strUIShopAnimGraph**: resource_name:"models/heroes_staging/hornet_v3/ui_shop_hornet.vanmgrph"
- **m_strUIShoppingMap**: maps/ui/hero_shop/hornet_shop.vmap

---

# Hero: hero_ghost

- **_class**: CitadelHeroData_t
- **m_bPlayerSelectable**: True
- **m_bDisabled**: False
- **m_bInDevelopment**: False
- **m_bNeedsTesting**: False
- **m_bAssignedPlayersOnly**: False
- **m_bBotSelectable**: True
- **m_bLimitedTesting**: False
- **m_nComplexity**: 2
- **m_nReadability**: 1
- **m_HeroID**: 4
- **m_strModelName**: resource_name:"models/heroes_staging/ghost/ghost.vmdl"
- **m_hDamageTakenParticle**: resource_name:"particles/generic/player_damage_screen.vpcf"
- **m_hGroundDamageTakenParticle**: resource_name:"particles/generic/player_ground_damage_screen.vpcf"
- **m_hDeathParticle**: resource_name:"particles/generic/player_death_screen.vpcf"
- **m_hLowHealthParticle**: resource_name:"particles/generic/player_low_health_screen.vpcf"
- **m_hRespawnParticle**: resource_name:"particles/generic/player_respawn_deploy.vpcf"
- **m_nModelSkin**: 0
- **m_mapStartingStats**:
  - **EMaxMoveSpeed**: 6
  - **ESprintSpeed**: 1
  - **ECrouchSpeed**: 4.75
  - **EMoveAcceleration**: 4
  - **ELightMeleeDamage**: 63
  - **EHeavyMeleeDamage**: 116
  - **EMaxHealth**: 650
  - **EWeaponPower**: 0
  - **EReloadSpeed**: 1
  - **EWeaponPowerScale**: 1
  - **EProcBuildUpRateScale**: 1
  - **EStamina**: 3
  - **EBaseHealthRegen**: 1.0
  - **EStaminaRegenPerSecond**: 0.2
  - **EAbilityResourceMax**: 0
  - **EAbilityResourceRegenPerSecond**: 0
  - **ECritDamageReceivedScale**: 1.0
  - **ETechDuration**: 1
  - **ETechRange**: 1
- **m_flCollisionRadius**: 20
- **m_flCollisionHeight**: 80
- **m_flStepHeight**: 32
- **m_mapBoundAbilities**:
  - **ESlot_Weapon_Primary**: citadel_weapon_ghost_set
  - **ESlot_Weapon_Melee**: ability_melee_ghost
  - **ESlot_Ability_Mantle**: citadel_ability_mantle
  - **ESlot_Ability_Jump**: citadel_ability_jump
  - **ESlot_Ability_Slide**: citadel_ability_slide
  - **ESlot_Ability_ZipLine**: citadel_ability_zip_line
  - **ESlot_Ability_ZipLineBoost**: citadel_ability_zipline_boost
  - **ESlot_Ability_Innate_1**: citadel_ability_dash
  - **ESlot_Ability_Innate_2**: citadel_ability_sprint
  - **ESlot_Ability_Innate_3**: citadel_ability_melee_parry
  - **ESlot_Signature_1**: ability_blood_bomb
  - **ESlot_Signature_2**: ability_life_drain
  - **ESlot_Signature_3**: ability_blood_shards
  - **ESlot_Signature_4**: ability_health_swap
- **m_mapItemSlotInfo**:
  - **EItemSlotType_WeaponMod**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
  - **EItemSlotType_Armor**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
  - **EItemSlotType_Tech**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
- **m_mapPurchaseBonuses**:
  - **EItemSlotType_WeaponMod**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 6 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 2 | 10 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 3 | 14 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 4 | 18 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
  - **EItemSlotType_Armor**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 11 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 2 | 14 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 3 | 17 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 4 | 20 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
  - **EItemSlotType_Tech**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 4 | MODIFIER_VALUE_TECH_POWER |
    | 2 | 8 | MODIFIER_VALUE_TECH_POWER |
    | 3 | 12 | MODIFIER_VALUE_TECH_POWER |
    | 4 | 16 | MODIFIER_VALUE_TECH_POWER |
- **m_mapLevelInfo**:
  - **1**:
    - **m_unRequiredGold**: 0
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **2**:
    - **m_unRequiredGold**: 400
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
      - **EAbilityPoints**: 1
  - **3**:
    - **m_unRequiredGold**: 800
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **4**:
    - **m_unRequiredGold**: 1200
    - **m_bUseStandardUpgrade**: True
  - **5**:
    - **m_unRequiredGold**: 1500
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **6**:
    - **m_unRequiredGold**: 2200
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **7**:
    - **m_unRequiredGold**: 3000
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **8**:
    - **m_unRequiredGold**: 4500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **9**:
    - **m_unRequiredGold**: 6000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **10**:
    - **m_unRequiredGold**: 7500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **11**:
    - **m_unRequiredGold**: 9000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **12**:
    - **m_unRequiredGold**: 10500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **13**:
    - **m_unRequiredGold**: 12000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **14**:
    - **m_unRequiredGold**: 13000
    - **m_bUseStandardUpgrade**: True
  - **15**:
    - **m_unRequiredGold**: 14000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **16**:
    - **m_unRequiredGold**: 15000
    - **m_bUseStandardUpgrade**: True
  - **17**:
    - **m_unRequiredGold**: 16000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **18**:
    - **m_unRequiredGold**: 18000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **19**:
    - **m_unRequiredGold**: 20000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **20**:
    - **m_unRequiredGold**: 22000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **21**:
    - **m_unRequiredGold**: 24000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **22**:
    - **m_unRequiredGold**: 27000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **23**:
    - **m_unRequiredGold**: 30000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **24**:
    - **m_unRequiredGold**: 33000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **25**:
    - **m_unRequiredGold**: 36000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **26**:
    - **m_unRequiredGold**: 39000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **27**:
    - **m_unRequiredGold**: 42000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **28**:
    - **m_unRequiredGold**: 45000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **29**:
    - **m_unRequiredGold**: 48000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
- **m_hFootstepSounds**: sweetener_default
- **m_strFootstepSoundEventDefault**: soundevent:"Ghost.Footstep"
- **m_flStealthSpeedMetersPerSecond**: 4
- **m_flFootstepSoundTravelDistanceMeters**: 20
- **m_flStepSoundTime**: 0.25
- **m_vecAnimGraphDefaultValueOverrides**:
  | m_strParamName | m_strParamValue |
  | --- | --- |
  | e_SWITCH_4wayRoll_ON/OFF | 0 |
  | e_SWITCH_Recoil_ON/OFF | 0 |
  | e_SWITCH_ZiplinePhysicsSway_ON/OFF | 0 |
  | e_SWITCH_ShootStyle | 0 |
- **m_strLastHitSound**: soundevent:"LastHit.Default"
- **m_strLowHealthSound**: soundevent:"PlayerAlert.LowHealth"
- **m_colorUI**:
  - 9
  - 137
  - 89
- **m_colorGlowFriendly**:
  - 255
  - 239
  - 215
- **m_colorGlowEnemy**:
  - 255
  - 0
  - 0
- **m_colorGlowTeam1**:
  - 231
  - 182
  - 89
- **m_colorGlowTeam2**:
  - 91
  - 121
  - 230
- **m_vecAmbientParticleSettings**:
  | m_eAttachmentType | m_nCP |
  | --- | --- |
  | PATTACH_ABSORIGIN_FOLLOW | 0 |
  | PATTACH_POINT_FOLLOW | 1 |
- **m_heroStatsUI**:
  - **m_vecDisplayStats**:
    | m_eStatType | m_eStatCategory |
    | --- | --- |
    | EMaxHealth | ECitadelStat_Vitality |
    | EBaseHealthRegen | ECitadelStat_Vitality |
    | EBulletArmorDamageReduction | ECitadelStat_Vitality |
    | ETechArmorDamageReduction | ECitadelStat_Vitality |
    | ETechPower | ECitadelStat_Spirit |
    | EWeaponDPS | ECitadelStat_Weapon |
    | EBulletDamage | ECitadelStat_Weapon |
    | EClipSize | ECitadelStat_Weapon |
    | ERoundsPerSecond | ECitadelStat_Weapon |
    | ELightMeleeDamage | ECitadelStat_Weapon |
    | EHeavyMeleeDamage | ECitadelStat_Weapon |
    | EMaxMoveSpeed | ECitadelStat_Vitality |
    | ESprintSpeed | ECitadelStat_Vitality |
    | EStamina | ECitadelStat_Vitality |
  - **m_eWeaponStatDisplay**: EMeleeDamage_DEPRECATED
- **m_mapScalingStats**:
- **m_heroStatsDisplay**:
  - **m_vecHealthHeaderStats**:
    - EMaxHealth
    - EBaseHealthRegen
  - **m_vecHealthStats**:
    - EBulletArmorDamageReduction
    - ETechArmorDamageReduction
    - EBulletShieldHealth
    - ETechShieldHealth
    - EBulletLifesteal
    - ETechLifesteal
    - EMaxMoveSpeed
    - ESprintSpeed
    - EStamina
    - EHealingOutput
  - **m_vecWeaponHeaderStats**:
    - EWeaponDPS
    - EBulletDamage
  - **m_vecWeaponStats**:
    - ELightMeleeDamage
    - EHeavyMeleeDamage
    - EFireRate
    - EClipSize
  - **m_vecMagicHeaderStats**:
    - ETechPower
  - **m_vecMagicStats**:
    - ETechCooldown
    - ETechRange
    - ETechDuration
- **m_mapStandardLevelUpUpgrades**:
  - **MODIFIER_VALUE_BASE_BULLET_DAMAGE_FROM_LEVEL**: 2.1
  - **MODIFIER_VALUE_BASE_MELEE_DAMAGE_FROM_LEVEL**: 3.4
  - **MODIFIER_VALUE_BASE_HEALTH_FROM_LEVEL**: 41.0
  - **MODIFIER_VALUE_TECH_DAMAGE_PERCENT**: 0.0
  - **MODIFIER_VALUE_BULLET_ARMOR_DAMAGE_RESIST**: 0.0
- **m_eAbilityResourceType**: EResourceType_None
- **m_ShopStatDisplay**:
  - **m_eWeaponStatsDisplay**:
    - **m_vecDisplayStats**:
      - EBulletDamage
      - EBaseWeaponDamageIncrease
      - ERoundsPerSecond
      - EFireRate
      - EClipSize
      - EClipSizeIncrease
      - EReloadTime
      - EReloadSpeed
      - EBulletSpeed
      - EBulletSpeedIncrease
      - EBulletLifesteal
    - **m_vecOtherDisplayStats**:
      - ELightMeleeDamage
      - EHeavyMeleeDamage
    - **m_eWeaponAttributes**: EWeaponAttribute_MediumRange | EWeaponAttribute_HeavyHitter
    - **m_strWeaponImage**: panorama:"file://{images}/heroes/guns/spectre_gun.psd"
  - **m_eVitalityStatsDisplay**:
    - **m_vecDisplayStats**:
      - EMaxHealth
      - EBaseHealthRegen
      - EBulletArmorDamageReduction
      - ETechArmorDamageReduction
      - EBulletShieldHealth
      - ETechShieldHealth
      - ECritDamageReceivedScale
    - **m_vecOtherDisplayStats**:
      - EMaxMoveSpeed
      - ESprintSpeed
      - EStaminaCooldown
      - EStaminaRegenIncrease
      - EStamina
  - **m_eSpiritStatsDisplay**:
    - **m_vecDisplayStats**:
      - ETechCooldown
      - ETechDuration
      - ETechRange
      - ETechLifesteal
      - EMaxChargesIncrease
      - ETechCooldownBetweenChargeUses
- **_base**: hero_base
- **m_strSelectionImage**: panorama:"file://{images}/heroes/spectre.psd"
- **m_strIconImageSmall**: panorama:"file://{images}/heroes/spectre_sm.psd"
- **m_strMinimapImage**: panorama:"file://{images}/heroes/spectre_mm.psd"
- **m_strUIAnimGraph**: resource_name:"models/heroes_staging/ghost/ui_ghost.vanmgrph"
- **m_strDeathSound**: soundevent:"Ghost.Death"
- **m_hGameSoundEventScript**: resource_name:"soundevents/hero/geist.vsndevts"
- **m_hVOEventScript**: resource_name:"soundevents/vo/vo_hero_ghost.vsndevts"
- **m_strRosterSelectedSound**: soundevent:"Geist.VO.HeroPick"
- **m_strIconHeroCard**: panorama:"file://{images}/heroes/spectre_card.psd"
- **m_hGeneratedVOEventScript**: resource_name:"soundevents/vo/generated_vo_hero_ghost.vsndevts"
- **m_strRosterRemovedSound**: soundevent:"Geist.VO.HeroRemove"
- **m_strTopBarImage**: panorama:"file://{images}/hud/hero_portraits/spectre_hud.psd"
- **m_strUIPortraitMap**: maps/ui/hero_prefabs/geist.vmap
- **m_RecommendedUpgrades**:
  - upgrade_medic_bullets
  - upgrade_headshot_booster
  - upgrade_magic_burst
  - upgrade_resilience
  - upgrade_magic_reach
  - upgrade_crackshot
  - upgrade_tech_defense_shredders
  - upgrade_bullet_armor
  - upgrade_healbane
  - upgrade_tech_armor
  - upgrade_magic_shock
  - upgrade_tech_purge
  - upgrade_improved_bullet_armor
  - upgrade_fervor
  - upgrade_critshot
- **m_strTopBarVertical**: panorama:"file://{images}/heroes/spectre_vertical.psd"
- **m_flStepSoundTimeSprinting**: 0.255
- **m_strUIShopAnimGraph**: resource_name:"models/heroes_staging/ghost/ui_shop_ghost.vanmgrph"
- **m_strUIShoppingMap**: maps/ui/hero_shop/ghost_shop.vmap

---

# Hero: hero_atlas

- **_class**: CitadelHeroData_t
- **m_bPlayerSelectable**: True
- **m_bDisabled**: False
- **m_bInDevelopment**: False
- **m_bNeedsTesting**: False
- **m_bAssignedPlayersOnly**: False
- **m_bBotSelectable**: True
- **m_bLimitedTesting**: False
- **m_nComplexity**: 1
- **m_nReadability**: 4
- **m_HeroID**: 6
- **m_strModelName**: resource_name:"models/heroes_staging/atlas_detective_v2/atlas_detective.vmdl"
- **m_hDamageTakenParticle**: resource_name:"particles/generic/player_damage_screen.vpcf"
- **m_hGroundDamageTakenParticle**: resource_name:"particles/generic/player_ground_damage_screen.vpcf"
- **m_hDeathParticle**: resource_name:"particles/generic/player_death_screen.vpcf"
- **m_hLowHealthParticle**: resource_name:"particles/generic/player_low_health_screen.vpcf"
- **m_hRespawnParticle**: resource_name:"particles/generic/player_respawn_deploy.vpcf"
- **m_nModelSkin**: 0
- **m_mapStartingStats**:
  - **EMaxMoveSpeed**: 6.5
  - **ESprintSpeed**: 0
  - **ECrouchSpeed**: 4.75
  - **EMoveAcceleration**: 4
  - **ELightMeleeDamage**: 63
  - **EHeavyMeleeDamage**: 116
  - **EMaxHealth**: 600
  - **EWeaponPower**: 0
  - **EReloadSpeed**: 1
  - **EWeaponPowerScale**: 1
  - **EProcBuildUpRateScale**: 1
  - **EStamina**: 3
  - **EBaseHealthRegen**: 1.0
  - **EStaminaRegenPerSecond**: 0.2
  - **EAbilityResourceMax**: 0
  - **EAbilityResourceRegenPerSecond**: 0
  - **ECritDamageReceivedScale**: 1.0
  - **ETechDuration**: 1
  - **ETechRange**: 1
- **m_flCollisionRadius**: 20
- **m_flCollisionHeight**: 80
- **m_flStepHeight**: 32
- **m_mapBoundAbilities**:
  - **ESlot_Weapon_Primary**: citadel_weapon_bull_set
  - **ESlot_Weapon_Melee**: citadel_ability_melee_bull
  - **ESlot_Ability_Mantle**: citadel_ability_mantle
  - **ESlot_Ability_Jump**: citadel_ability_jump
  - **ESlot_Ability_Slide**: citadel_ability_slide
  - **ESlot_Ability_ZipLine**: citadel_ability_zip_line
  - **ESlot_Ability_ZipLineBoost**: citadel_ability_zipline_boost
  - **ESlot_Ability_Innate_1**: citadel_ability_dash
  - **ESlot_Ability_Innate_2**: citadel_ability_sprint
  - **ESlot_Ability_Innate_3**: citadel_ability_melee_parry
  - **ESlot_Signature_1**: citadel_ability_bull_heal
  - **ESlot_Signature_2**: citadel_ability_bull_charge
  - **ESlot_Signature_3**: citadel_ability_passive_beefy
  - **ESlot_Signature_4**: citadel_ability_bull_leap
- **m_mapItemSlotInfo**:
  - **EItemSlotType_WeaponMod**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
  - **EItemSlotType_Armor**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
  - **EItemSlotType_Tech**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
- **m_mapPurchaseBonuses**:
  - **EItemSlotType_WeaponMod**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 6 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 2 | 10 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 3 | 14 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 4 | 18 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
  - **EItemSlotType_Armor**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 11 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 2 | 14 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 3 | 17 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 4 | 20 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
  - **EItemSlotType_Tech**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 4 | MODIFIER_VALUE_TECH_POWER |
    | 2 | 8 | MODIFIER_VALUE_TECH_POWER |
    | 3 | 12 | MODIFIER_VALUE_TECH_POWER |
    | 4 | 16 | MODIFIER_VALUE_TECH_POWER |
- **m_mapLevelInfo**:
  - **1**:
    - **m_unRequiredGold**: 0
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **2**:
    - **m_unRequiredGold**: 400
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
      - **EAbilityPoints**: 1
  - **3**:
    - **m_unRequiredGold**: 800
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **4**:
    - **m_unRequiredGold**: 1200
    - **m_bUseStandardUpgrade**: True
  - **5**:
    - **m_unRequiredGold**: 1500
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **6**:
    - **m_unRequiredGold**: 2200
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **7**:
    - **m_unRequiredGold**: 3000
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **8**:
    - **m_unRequiredGold**: 4500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **9**:
    - **m_unRequiredGold**: 6000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **10**:
    - **m_unRequiredGold**: 7500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **11**:
    - **m_unRequiredGold**: 9000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **12**:
    - **m_unRequiredGold**: 10500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **13**:
    - **m_unRequiredGold**: 12000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **14**:
    - **m_unRequiredGold**: 13000
    - **m_bUseStandardUpgrade**: True
  - **15**:
    - **m_unRequiredGold**: 14000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **16**:
    - **m_unRequiredGold**: 15000
    - **m_bUseStandardUpgrade**: True
  - **17**:
    - **m_unRequiredGold**: 16000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **18**:
    - **m_unRequiredGold**: 18000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **19**:
    - **m_unRequiredGold**: 20000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **20**:
    - **m_unRequiredGold**: 22000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **21**:
    - **m_unRequiredGold**: 24000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **22**:
    - **m_unRequiredGold**: 27000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **23**:
    - **m_unRequiredGold**: 30000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **24**:
    - **m_unRequiredGold**: 33000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **25**:
    - **m_unRequiredGold**: 36000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **26**:
    - **m_unRequiredGold**: 39000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **27**:
    - **m_unRequiredGold**: 42000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **28**:
    - **m_unRequiredGold**: 45000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **29**:
    - **m_unRequiredGold**: 48000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
- **m_hFootstepSounds**: sweetener_default
- **m_strFootstepSoundEventDefault**: soundevent:"Abrams.Footstep"
- **m_flStealthSpeedMetersPerSecond**: 4
- **m_flFootstepSoundTravelDistanceMeters**: 20
- **m_flStepSoundTime**: 0.4
- **m_vecAnimGraphDefaultValueOverrides**:
  | m_strParamName | m_strParamValue |
  | --- | --- |
  | e_SWITCH_4wayRoll_ON/OFF | 0 |
  | e_SWITCH_Recoil_ON/OFF | 0 |
  | e_SWITCH_ZiplinePhysicsSway_ON/OFF | 0 |
  | e_SWITCH_ShootStyle | 0 |
- **m_strLastHitSound**: soundevent:"LastHit.Default"
- **m_strLowHealthSound**: soundevent:"PlayerAlert.LowHealth"
- **m_colorUI**:
  - 32
  - 146
  - 174
- **m_colorGlowFriendly**:
  - 255
  - 239
  - 215
- **m_colorGlowEnemy**:
  - 255
  - 0
  - 0
- **m_colorGlowTeam1**:
  - 231
  - 182
  - 89
- **m_colorGlowTeam2**:
  - 91
  - 121
  - 230
- **m_vecAmbientParticleSettings**:
  | m_eAttachmentType | m_nCP |
  | --- | --- |
  | PATTACH_ABSORIGIN_FOLLOW | 0 |
  | PATTACH_POINT_FOLLOW | 1 |
- **m_heroStatsUI**:
  - **m_vecDisplayStats**:
    | m_eStatType | m_eStatCategory |
    | --- | --- |
    | EMaxHealth | ECitadelStat_Vitality |
    | EBaseHealthRegen | ECitadelStat_Vitality |
    | EBulletArmorDamageReduction | ECitadelStat_Vitality |
    | ETechArmorDamageReduction | ECitadelStat_Vitality |
    | ETechPower | ECitadelStat_Spirit |
    | EWeaponDPS | ECitadelStat_Weapon |
    | EBulletDamage | ECitadelStat_Weapon |
    | EClipSize | ECitadelStat_Weapon |
    | ERoundsPerSecond | ECitadelStat_Weapon |
    | ELightMeleeDamage | ECitadelStat_Weapon |
    | EHeavyMeleeDamage | ECitadelStat_Weapon |
    | EMaxMoveSpeed | ECitadelStat_Vitality |
    | ESprintSpeed | ECitadelStat_Vitality |
    | EStamina | ECitadelStat_Vitality |
  - **m_eWeaponStatDisplay**: EMeleeDamage_DEPRECATED
  - **m_eWeaponType**: ECitadelWeapon_Invalid
- **m_mapScalingStats**:
- **m_heroStatsDisplay**:
  - **m_vecHealthHeaderStats**:
    - EMaxHealth
    - EBaseHealthRegen
  - **m_vecHealthStats**:
    - EBulletArmorDamageReduction
    - ETechArmorDamageReduction
    - EBulletShieldHealth
    - ETechShieldHealth
    - EBulletLifesteal
    - ETechLifesteal
    - EMaxMoveSpeed
    - ESprintSpeed
    - EStamina
    - EHealingOutput
  - **m_vecWeaponHeaderStats**:
    - EWeaponDPS
    - EBulletDamage
  - **m_vecWeaponStats**:
    - ELightMeleeDamage
    - EHeavyMeleeDamage
    - EFireRate
    - EClipSize
  - **m_vecMagicHeaderStats**:
    - ETechPower
  - **m_vecMagicStats**:
    - ETechCooldown
    - ETechRange
    - ETechDuration
- **m_mapStandardLevelUpUpgrades**:
  - **MODIFIER_VALUE_BASE_BULLET_DAMAGE_FROM_LEVEL**: 0.32
  - **MODIFIER_VALUE_BASE_MELEE_DAMAGE_FROM_LEVEL**: 3.4
  - **MODIFIER_VALUE_BASE_HEALTH_FROM_LEVEL**: 32.0
  - **MODIFIER_VALUE_TECH_DAMAGE_PERCENT**: 0.0
  - **MODIFIER_VALUE_BULLET_ARMOR_DAMAGE_RESIST**: 0.0
- **m_eAbilityResourceType**: EResourceType_None
- **m_ShopStatDisplay**:
  - **m_eWeaponStatsDisplay**:
    - **m_vecDisplayStats**:
      - EBulletDamage
      - EBaseWeaponDamageIncrease
      - ERoundsPerSecond
      - EFireRate
      - EClipSize
      - EClipSizeIncrease
      - EReloadTime
      - EReloadSpeed
      - EBulletSpeed
      - EBulletSpeedIncrease
      - EBulletLifesteal
    - **m_vecOtherDisplayStats**:
      - ELightMeleeDamage
      - EHeavyMeleeDamage
    - **m_eWeaponAttributes**: EWeaponAttribute_Spreadshot | EWeaponAttribute_CloseRange
    - **m_strWeaponImage**: panorama:"file://{images}/heroes/guns/bull_gun.psd"
    - **m_strWeaponDescLocString**: #citadel_weapon_hero_atlas_set_desc
  - **m_eVitalityStatsDisplay**:
    - **m_vecDisplayStats**:
      - EMaxHealth
      - EBaseHealthRegen
      - EBulletArmorDamageReduction
      - ETechArmorDamageReduction
      - EBulletShieldHealth
      - ETechShieldHealth
      - ECritDamageReceivedScale
    - **m_vecOtherDisplayStats**:
      - EMaxMoveSpeed
      - ESprintSpeed
      - EStaminaCooldown
      - EStaminaRegenIncrease
      - EStamina
  - **m_eSpiritStatsDisplay**:
    - **m_vecDisplayStats**:
      - ETechCooldown
      - ETechDuration
      - ETechRange
      - ETechLifesteal
      - EMaxChargesIncrease
      - ETechCooldownBetweenChargeUses
- **_base**: hero_base
- **m_strSelectionImage**: panorama:"file://{images}/heroes/bull.psd"
- **m_strIconImageSmall**: panorama:"file://{images}/heroes/bull_sm.psd"
- **m_strMinimapImage**: panorama:"file://{images}/heroes/bull_mm.psd"
- **m_strUIAnimGraph**: resource_name:"models/heroes_staging/atlas_detective_v2/ui_atlas_detective.vanmgrph"
- **m_strWIPModelName**: resource_name:"models/heroes_staging/atlas_detective_v2/atlas_detective.vmdl"
- **m_strDeathSound**: soundevent:"Abrams.Death"
- **m_bNewPlayerRecommended**: True
- **m_bLaneTestingRecommended**: False
- **m_hGameSoundEventScript**: resource_name:"soundevents/hero/abrams.vsndevts"
- **m_hVOEventScript**: resource_name:"soundevents/vo/vo_hero_atlas.vsndevts"
- **m_strRosterSelectedSound**: soundevent:"Abrams.VO.HeroPick"
- **m_strIconHeroCard**: panorama:"file://{images}/heroes/bull_card.psd"
- **m_strRosterRemovedSound**: soundevent:"Abrams.VO.HeroRemove"
- **m_hGeneratedVOEventScript**: resource_name:"soundevents/vo/generated_vo_hero_atlas.vsndevts"
- **m_strTopBarImage**: panorama:"file://{images}/hud/hero_portraits/bull_hud.psd"
- **m_RecommendedUpgrades**:
  - upgrade_close_range
  - upgrade_lifestrike_gauntlets
  - upgrade_health
  - upgrade_berserker
  - upgrade_cold_front
  - upgrade_bullet_armor
  - upgrade_tech_armor
  - upgrade_chonky
  - upgrade_close_quarter_combat
  - upgrade_improved_bullet_armor
  - upgrade_tech_purge
  - upgrade_bullet_armor_reduction_aura
  - upgrade_fervor
- **m_strUIPortraitMap**: maps/ui/hero_prefabs/abrams.vmap
- **m_strTopBarVertical**: panorama:"file://{images}/heroes/bull_vertical.psd"
- **m_flStepSoundTimeSprinting**: 0.33
- **m_strUIShoppingMap**: maps/ui/hero_shop/abrams_shop.vmap
- **m_strUIShopAnimGraph**: resource_name:"models/heroes_staging/atlas_detective_v2/ui_shop_atlas_detective.vanmgrph"

---

# Hero: hero_wraith

- **_class**: CitadelHeroData_t
- **m_bPlayerSelectable**: True
- **m_bDisabled**: False
- **m_bInDevelopment**: False
- **m_bNeedsTesting**: False
- **m_bAssignedPlayersOnly**: False
- **m_bBotSelectable**: True
- **m_bLimitedTesting**: False
- **m_nComplexity**: 1
- **m_nReadability**: 3
- **m_HeroID**: 7
- **m_strModelName**: resource_name:"models/heroes_staging/wraith_gen_man/wraith_gen_man.vmdl"
- **m_hDamageTakenParticle**: resource_name:"particles/generic/player_damage_screen.vpcf"
- **m_hGroundDamageTakenParticle**: resource_name:"particles/generic/player_ground_damage_screen.vpcf"
- **m_hDeathParticle**: resource_name:"particles/generic/player_death_screen.vpcf"
- **m_hLowHealthParticle**: resource_name:"particles/generic/player_low_health_screen.vpcf"
- **m_hRespawnParticle**: resource_name:"particles/generic/player_respawn_deploy.vpcf"
- **m_nModelSkin**: 1
- **m_mapStartingStats**:
  - **EMaxMoveSpeed**: 7
  - **ESprintSpeed**: 0
  - **ECrouchSpeed**: 4.75
  - **EMoveAcceleration**: 4
  - **ELightMeleeDamage**: 63
  - **EHeavyMeleeDamage**: 116
  - **EMaxHealth**: 550
  - **EWeaponPower**: 0
  - **EReloadSpeed**: 1
  - **EWeaponPowerScale**: 1
  - **EProcBuildUpRateScale**: 1
  - **EStamina**: 3
  - **EBaseHealthRegen**: 2.0
  - **EStaminaRegenPerSecond**: 0.2
  - **EAbilityResourceMax**: 0
  - **EAbilityResourceRegenPerSecond**: 0
  - **ECritDamageReceivedScale**: 1.0
  - **ETechDuration**: 1
  - **ETechRange**: 1
- **m_flCollisionRadius**: 20
- **m_flCollisionHeight**: 80
- **m_flStepHeight**: 32
- **m_mapBoundAbilities**:
  - **ESlot_Weapon_Primary**: citadel_weapon_wraith_set
  - **ESlot_Weapon_Melee**: citadel_ability_melee_wraith
  - **ESlot_Ability_Mantle**: citadel_ability_mantle
  - **ESlot_Ability_Jump**: citadel_ability_jump
  - **ESlot_Ability_Slide**: citadel_ability_slide
  - **ESlot_Ability_ZipLine**: citadel_ability_zip_line
  - **ESlot_Ability_ZipLineBoost**: citadel_ability_zipline_boost
  - **ESlot_Ability_Innate_1**: citadel_ability_dash
  - **ESlot_Ability_Innate_2**: citadel_ability_sprint
  - **ESlot_Ability_Innate_3**: citadel_ability_melee_parry
  - **ESlot_Signature_1**: citadel_ability_card_toss
  - **ESlot_Signature_2**: citadel_ability_projectmind
  - **ESlot_Signature_3**: citadel_ability_wraith_rapidfire
  - **ESlot_Signature_4**: citadel_ability_psychic_lift
- **m_mapItemSlotInfo**:
  - **EItemSlotType_WeaponMod**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
  - **EItemSlotType_Armor**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
  - **EItemSlotType_Tech**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
- **m_mapPurchaseBonuses**:
  - **EItemSlotType_WeaponMod**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 6 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 2 | 10 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 3 | 14 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 4 | 18 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
  - **EItemSlotType_Armor**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 11 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 2 | 14 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 3 | 17 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 4 | 20 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
  - **EItemSlotType_Tech**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 4 | MODIFIER_VALUE_TECH_POWER |
    | 2 | 8 | MODIFIER_VALUE_TECH_POWER |
    | 3 | 12 | MODIFIER_VALUE_TECH_POWER |
    | 4 | 16 | MODIFIER_VALUE_TECH_POWER |
- **m_mapLevelInfo**:
  - **1**:
    - **m_unRequiredGold**: 0
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **2**:
    - **m_unRequiredGold**: 400
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
      - **EAbilityPoints**: 1
  - **3**:
    - **m_unRequiredGold**: 800
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **4**:
    - **m_unRequiredGold**: 1200
    - **m_bUseStandardUpgrade**: True
  - **5**:
    - **m_unRequiredGold**: 1500
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **6**:
    - **m_unRequiredGold**: 2200
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **7**:
    - **m_unRequiredGold**: 3000
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **8**:
    - **m_unRequiredGold**: 4500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **9**:
    - **m_unRequiredGold**: 6000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **10**:
    - **m_unRequiredGold**: 7500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **11**:
    - **m_unRequiredGold**: 9000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **12**:
    - **m_unRequiredGold**: 10500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **13**:
    - **m_unRequiredGold**: 12000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **14**:
    - **m_unRequiredGold**: 13000
    - **m_bUseStandardUpgrade**: True
  - **15**:
    - **m_unRequiredGold**: 14000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **16**:
    - **m_unRequiredGold**: 15000
    - **m_bUseStandardUpgrade**: True
  - **17**:
    - **m_unRequiredGold**: 16000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **18**:
    - **m_unRequiredGold**: 18000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **19**:
    - **m_unRequiredGold**: 20000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **20**:
    - **m_unRequiredGold**: 22000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **21**:
    - **m_unRequiredGold**: 24000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **22**:
    - **m_unRequiredGold**: 27000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **23**:
    - **m_unRequiredGold**: 30000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **24**:
    - **m_unRequiredGold**: 33000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **25**:
    - **m_unRequiredGold**: 36000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **26**:
    - **m_unRequiredGold**: 39000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **27**:
    - **m_unRequiredGold**: 42000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **28**:
    - **m_unRequiredGold**: 45000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **29**:
    - **m_unRequiredGold**: 48000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
- **m_hFootstepSounds**: sweetener_default
- **m_strFootstepSoundEventDefault**: soundevent:"Wraith.Footstep.Multi"
- **m_flStealthSpeedMetersPerSecond**: 4
- **m_flFootstepSoundTravelDistanceMeters**: 20
- **m_flStepSoundTime**: 0.3
- **m_vecAnimGraphDefaultValueOverrides**:
  | m_strParamName | m_strParamValue |
  | --- | --- |
  | e_SWITCH_4wayRoll_ON/OFF | 0 |
  | e_SWITCH_Recoil_ON/OFF | 0 |
  | e_SWITCH_ZiplinePhysicsSway_ON/OFF | 0 |
  | e_SWITCH_ShootStyle | 0 |
- **m_strLastHitSound**: soundevent:"LastHit.Default"
- **m_strLowHealthSound**: soundevent:"PlayerAlert.LowHealth"
- **m_colorUI**:
  - 148
  - 77
  - 120
- **m_colorGlowFriendly**:
  - 255
  - 239
  - 215
- **m_colorGlowEnemy**:
  - 255
  - 0
  - 0
- **m_colorGlowTeam1**:
  - 231
  - 182
  - 89
- **m_colorGlowTeam2**:
  - 91
  - 121
  - 230
- **m_vecAmbientParticleSettings**:
  | m_eAttachmentType | m_nCP |
  | --- | --- |
  | PATTACH_ABSORIGIN_FOLLOW | 0 |
  | PATTACH_POINT_FOLLOW | 1 |
- **m_heroStatsUI**:
  - **m_vecDisplayStats**:
    | m_eStatType | m_eStatCategory |
    | --- | --- |
    | EMaxHealth | ECitadelStat_Vitality |
    | EBaseHealthRegen | ECitadelStat_Vitality |
    | EBulletArmorDamageReduction | ECitadelStat_Vitality |
    | ETechArmorDamageReduction | ECitadelStat_Vitality |
    | ETechPower | ECitadelStat_Spirit |
    | EWeaponDPS | ECitadelStat_Weapon |
    | EBulletDamage | ECitadelStat_Weapon |
    | EClipSize | ECitadelStat_Weapon |
    | ERoundsPerSecond | ECitadelStat_Weapon |
    | ELightMeleeDamage | ECitadelStat_Weapon |
    | EHeavyMeleeDamage | ECitadelStat_Weapon |
    | EMaxMoveSpeed | ECitadelStat_Vitality |
    | ESprintSpeed | ECitadelStat_Vitality |
    | EStamina | ECitadelStat_Vitality |
  - **m_eWeaponStatDisplay**: EMeleeDamage_DEPRECATED
- **m_mapScalingStats**:
  - **ESprintSpeed**:
    - **eScalingStat**: ETechPower
    - **flScale**: 0.06
- **m_heroStatsDisplay**:
  - **m_vecHealthHeaderStats**:
    - EMaxHealth
    - EBaseHealthRegen
  - **m_vecHealthStats**:
    - EBulletArmorDamageReduction
    - ETechArmorDamageReduction
    - EBulletShieldHealth
    - ETechShieldHealth
    - EBulletLifesteal
    - ETechLifesteal
    - EMaxMoveSpeed
    - ESprintSpeed
    - EStamina
    - EHealingOutput
  - **m_vecWeaponHeaderStats**:
    - EWeaponDPS
    - EBulletDamage
  - **m_vecWeaponStats**:
    - ELightMeleeDamage
    - EHeavyMeleeDamage
    - EFireRate
    - EClipSize
  - **m_vecMagicHeaderStats**:
    - ETechPower
  - **m_vecMagicStats**:
    - ETechCooldown
    - ETechRange
    - ETechDuration
- **m_mapStandardLevelUpUpgrades**:
  - **MODIFIER_VALUE_BASE_BULLET_DAMAGE_FROM_LEVEL**: 0.48
  - **MODIFIER_VALUE_BASE_MELEE_DAMAGE_FROM_LEVEL**: 3.4
  - **MODIFIER_VALUE_BASE_HEALTH_FROM_LEVEL**: 31.0
  - **MODIFIER_VALUE_TECH_DAMAGE_PERCENT**: 0.0
  - **MODIFIER_VALUE_BULLET_ARMOR_DAMAGE_RESIST**: 0.0
- **m_eAbilityResourceType**: EResourceType_None
- **m_ShopStatDisplay**:
  - **m_eWeaponStatsDisplay**:
    - **m_vecDisplayStats**:
      - EBulletDamage
      - EBaseWeaponDamageIncrease
      - ERoundsPerSecond
      - EFireRate
      - EClipSize
      - EClipSizeIncrease
      - EReloadTime
      - EReloadSpeed
      - EBulletSpeed
      - EBulletSpeedIncrease
      - EBulletLifesteal
    - **m_vecOtherDisplayStats**:
      - ELightMeleeDamage
      - EHeavyMeleeDamage
    - **m_eWeaponAttributes**: EWeaponAttribute_RapidFire | EWeaponAttribute_MediumRange
    - **m_strSecondaryWeaponDescLocString**: 
    - **m_strWeaponImage**: panorama:"file://{images}/heroes/guns/wraith_gun.psd"
  - **m_eVitalityStatsDisplay**:
    - **m_vecDisplayStats**:
      - EMaxHealth
      - EBaseHealthRegen
      - EBulletArmorDamageReduction
      - ETechArmorDamageReduction
      - EBulletShieldHealth
      - ETechShieldHealth
      - ECritDamageReceivedScale
    - **m_vecOtherDisplayStats**:
      - EMaxMoveSpeed
      - ESprintSpeed
      - EStaminaCooldown
      - EStaminaRegenIncrease
      - EStamina
  - **m_eSpiritStatsDisplay**:
    - **m_vecDisplayStats**:
      - ETechCooldown
      - ETechDuration
      - ETechRange
      - ETechLifesteal
      - EMaxChargesIncrease
      - ETechCooldownBetweenChargeUses
- **_base**: hero_base
- **m_bNewPlayerRecommended**: True
- **m_bLaneTestingRecommended**: True
- **m_strSelectionImage**: panorama:"file://{images}/heroes/wraith.psd"
- **m_strIconImageSmall**: panorama:"file://{images}/heroes/wraith_sm.psd"
- **m_strMinimapImage**: panorama:"file://{images}/heroes/wraith_mm.psd"
- **m_strWIPModelName**: resource_name:"models/heroes_staging/wraith/wraith.vmdl"
- **m_strUIAnimGraph**: resource_name:"models/heroes_staging/wraith_gen_man/ui_wraith_gen_man.vanmgrph"
- **m_strDeathSound**: soundevent:"Player.DeathFemale"
- **m_hGameSoundEventScript**: resource_name:"soundevents/hero/wraith.vsndevts"
- **m_hVOEventScript**: resource_name:"soundevents/vo/vo_hero_wraith.vsndevts"
- **m_strRosterSelectedSound**: soundevent:"Wraith.VO.HeroPick"
- **m_strIconHeroCard**: panorama:"file://{images}/heroes/wraith_card.psd"
- **m_hGeneratedVOEventScript**: resource_name:"soundevents/vo/generated_vo_hero_wraith.vsndevts"
- **m_strRosterRemovedSound**: soundevent:"Wraith.VO.HeroRemove"
- **m_strTopBarImage**: panorama:"file://{images}/hud/hero_portraits/wraith_hud.psd"
- **m_strUIPortraitMap**: maps/ui/hero_prefabs/wraith.vmap
- **m_RecommendedUpgrades**:
  - upgrade_endurance
  - upgrade_clip_size
  - upgrade_non_player_bonus
  - upgrade_vampire
  - upgrade_slowing_bullets
  - upgrade_magic_shield
  - upgrade_regenerating_bullet_shield
  - upgrade_bullet_resist_shredder
  - upgrade_quick_silver
  - upgrade_chain_lightning
  - upgrade_bullet_armor_reduction_aura
  - upgrade_chonky
  - upgrade_critshot
- **m_strTopBarVertical**: panorama:"file://{images}/heroes/wraith_vertical.psd"
- **m_mapWIPAbilities**:
  - **ESlot_Signature_3**: citadel_ability_psychic_pulse
- **m_strUIShopAnimGraph**: resource_name:"models/heroes_staging/wraith_gen_man/ui_shop_wraith_gen_man.vanmgrph"
- **m_strUIShoppingMap**: maps/ui/hero_shop/wraith_shop.vmap

---

# Hero: hero_forge

- **_class**: CitadelHeroData_t
- **m_bPlayerSelectable**: True
- **m_bDisabled**: False
- **m_bInDevelopment**: False
- **m_bNeedsTesting**: False
- **m_bAssignedPlayersOnly**: False
- **m_bBotSelectable**: True
- **m_bLimitedTesting**: False
- **m_nComplexity**: 1
- **m_nReadability**: 5
- **m_HeroID**: 8
- **m_strModelName**: resource_name:"models/heroes_staging/engineer/engineer.vmdl"
- **m_hDamageTakenParticle**: resource_name:"particles/generic/player_damage_screen.vpcf"
- **m_hGroundDamageTakenParticle**: resource_name:"particles/generic/player_ground_damage_screen.vpcf"
- **m_hDeathParticle**: resource_name:"particles/generic/player_death_screen.vpcf"
- **m_hLowHealthParticle**: resource_name:"particles/generic/player_low_health_screen.vpcf"
- **m_hRespawnParticle**: resource_name:"particles/generic/player_respawn_deploy.vpcf"
- **m_nModelSkin**: 0
- **m_mapStartingStats**:
  - **EMaxMoveSpeed**: 6.5
  - **ESprintSpeed**: 0
  - **ECrouchSpeed**: 4.75
  - **EMoveAcceleration**: 4
  - **ELightMeleeDamage**: 63
  - **EHeavyMeleeDamage**: 116
  - **EMaxHealth**: 550
  - **EWeaponPower**: 0
  - **EReloadSpeed**: 1
  - **EWeaponPowerScale**: 1
  - **EProcBuildUpRateScale**: 1
  - **EStamina**: 2
  - **EBaseHealthRegen**: 2
  - **EStaminaRegenPerSecond**: 0.2
  - **EAbilityResourceMax**: 0
  - **EAbilityResourceRegenPerSecond**: 0
  - **ECritDamageReceivedScale**: 1.0
  - **ETechDuration**: 1
  - **ETechRange**: 1
  - **ETechArmorDamageReduction**: 25.0
- **m_flCollisionRadius**: 20
- **m_flCollisionHeight**: 80
- **m_flStepHeight**: 32
- **m_mapBoundAbilities**:
  - **ESlot_Weapon_Primary**: citadel_weapon_engineer_set
  - **ESlot_Weapon_Melee**: citadel_ability_melee_engineer
  - **ESlot_Ability_Mantle**: citadel_ability_mantle
  - **ESlot_Ability_Jump**: citadel_ability_jump
  - **ESlot_Ability_Slide**: citadel_ability_slide
  - **ESlot_Ability_ZipLine**: citadel_ability_zip_line
  - **ESlot_Ability_ZipLineBoost**: citadel_ability_zipline_boost
  - **ESlot_Ability_Innate_1**: citadel_ability_dash
  - **ESlot_Ability_Innate_2**: citadel_ability_sprint
  - **ESlot_Ability_Innate_3**: citadel_ability_melee_parry
  - **ESlot_Signature_1**: citadel_ability_shieldedsentry
  - **ESlot_Signature_2**: citadel_ability_mobile_resupply
  - **ESlot_Signature_3**: citadel_ability_fissure_wall
  - **ESlot_Signature_4**: citadel_ability_rocket_barrage
- **m_mapItemSlotInfo**:
  - **EItemSlotType_WeaponMod**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
  - **EItemSlotType_Armor**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
  - **EItemSlotType_Tech**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
- **m_mapPurchaseBonuses**:
  - **EItemSlotType_WeaponMod**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 6 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 2 | 10 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 3 | 14 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 4 | 18 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
  - **EItemSlotType_Armor**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 11 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 2 | 14 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 3 | 17 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 4 | 20 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
  - **EItemSlotType_Tech**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 4 | MODIFIER_VALUE_TECH_POWER |
    | 2 | 8 | MODIFIER_VALUE_TECH_POWER |
    | 3 | 12 | MODIFIER_VALUE_TECH_POWER |
    | 4 | 16 | MODIFIER_VALUE_TECH_POWER |
- **m_mapLevelInfo**:
  - **1**:
    - **m_unRequiredGold**: 0
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **2**:
    - **m_unRequiredGold**: 400
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
      - **EAbilityPoints**: 1
  - **3**:
    - **m_unRequiredGold**: 800
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **4**:
    - **m_unRequiredGold**: 1200
    - **m_bUseStandardUpgrade**: True
  - **5**:
    - **m_unRequiredGold**: 1500
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **6**:
    - **m_unRequiredGold**: 2200
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **7**:
    - **m_unRequiredGold**: 3000
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **8**:
    - **m_unRequiredGold**: 4500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **9**:
    - **m_unRequiredGold**: 6000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **10**:
    - **m_unRequiredGold**: 7500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **11**:
    - **m_unRequiredGold**: 9000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **12**:
    - **m_unRequiredGold**: 10500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **13**:
    - **m_unRequiredGold**: 12000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **14**:
    - **m_unRequiredGold**: 13000
    - **m_bUseStandardUpgrade**: True
  - **15**:
    - **m_unRequiredGold**: 14000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **16**:
    - **m_unRequiredGold**: 15000
    - **m_bUseStandardUpgrade**: True
  - **17**:
    - **m_unRequiredGold**: 16000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **18**:
    - **m_unRequiredGold**: 18000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **19**:
    - **m_unRequiredGold**: 20000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **20**:
    - **m_unRequiredGold**: 22000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **21**:
    - **m_unRequiredGold**: 24000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **22**:
    - **m_unRequiredGold**: 27000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **23**:
    - **m_unRequiredGold**: 30000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **24**:
    - **m_unRequiredGold**: 33000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **25**:
    - **m_unRequiredGold**: 36000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **26**:
    - **m_unRequiredGold**: 39000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **27**:
    - **m_unRequiredGold**: 42000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **28**:
    - **m_unRequiredGold**: 45000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **29**:
    - **m_unRequiredGold**: 48000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
- **m_hFootstepSounds**: sweetener_default
- **m_strFootstepSoundEventDefault**: soundevent:"Forge.Footstep"
- **m_flStealthSpeedMetersPerSecond**: 4
- **m_flFootstepSoundTravelDistanceMeters**: 20
- **m_flStepSoundTime**: 0.315
- **m_vecAnimGraphDefaultValueOverrides**:
  | m_strParamName | m_strParamValue |
  | --- | --- |
  | e_SWITCH_4wayRoll_ON/OFF | 0 |
  | e_SWITCH_Recoil_ON/OFF | 1 |
  | e_SWITCH_ZiplinePhysicsSway_ON/OFF | 0 |
  | e_SWITCH_ShootStyle | 0 |
- **m_strLastHitSound**: soundevent:"LastHit.Default"
- **m_strLowHealthSound**: soundevent:"PlayerAlert.LowHealth"
- **m_colorUI**:
  - 70
  - 104
  - 155
- **m_colorGlowFriendly**:
  - 255
  - 239
  - 215
- **m_colorGlowEnemy**:
  - 255
  - 0
  - 0
- **m_colorGlowTeam1**:
  - 231
  - 182
  - 89
- **m_colorGlowTeam2**:
  - 91
  - 121
  - 230
- **m_vecAmbientParticleSettings**:
  | m_eAttachmentType | m_nCP |
  | --- | --- |
  | PATTACH_ABSORIGIN_FOLLOW | 0 |
  | PATTACH_POINT_FOLLOW | 1 |
- **m_heroStatsUI**:
  - **m_vecDisplayStats**:
    | m_eStatType | m_eStatCategory |
    | --- | --- |
    | EMaxHealth | ECitadelStat_Vitality |
    | EBaseHealthRegen | ECitadelStat_Vitality |
    | EBulletArmorDamageReduction | ECitadelStat_Vitality |
    | ETechArmorDamageReduction | ECitadelStat_Vitality |
    | ETechPower | ECitadelStat_Spirit |
    | EWeaponDPS | ECitadelStat_Weapon |
    | EBulletDamage | ECitadelStat_Weapon |
    | EClipSize | ECitadelStat_Weapon |
    | ERoundsPerSecond | ECitadelStat_Weapon |
    | ELightMeleeDamage | ECitadelStat_Weapon |
    | EHeavyMeleeDamage | ECitadelStat_Weapon |
    | EMaxMoveSpeed | ECitadelStat_Vitality |
    | ESprintSpeed | ECitadelStat_Vitality |
    | EStamina | ECitadelStat_Vitality |
  - **m_eWeaponStatDisplay**: EMeleeDamage_DEPRECATED
- **m_mapScalingStats**:
- **m_heroStatsDisplay**:
  - **m_vecHealthHeaderStats**:
    - EMaxHealth
    - EBaseHealthRegen
  - **m_vecHealthStats**:
    - EBulletArmorDamageReduction
    - ETechArmorDamageReduction
    - EBulletShieldHealth
    - ETechShieldHealth
    - EBulletLifesteal
    - ETechLifesteal
    - EMaxMoveSpeed
    - ESprintSpeed
    - EStamina
    - EHealingOutput
  - **m_vecWeaponHeaderStats**:
    - EWeaponDPS
    - EBulletDamage
  - **m_vecWeaponStats**:
    - ELightMeleeDamage
    - EHeavyMeleeDamage
    - EFireRate
    - EClipSize
  - **m_vecMagicHeaderStats**:
    - ETechPower
  - **m_vecMagicStats**:
    - ETechCooldown
    - ETechRange
    - ETechDuration
- **m_mapStandardLevelUpUpgrades**:
  - **MODIFIER_VALUE_BASE_BULLET_DAMAGE_FROM_LEVEL**: 0.44
  - **MODIFIER_VALUE_BASE_MELEE_DAMAGE_FROM_LEVEL**: 3.4
  - **MODIFIER_VALUE_BASE_HEALTH_FROM_LEVEL**: 41.0
  - **MODIFIER_VALUE_TECH_DAMAGE_PERCENT**: 0.0
  - **MODIFIER_VALUE_BULLET_ARMOR_DAMAGE_RESIST**: 0.0
- **m_eAbilityResourceType**: EResourceType_None
- **m_ShopStatDisplay**:
  - **m_eWeaponStatsDisplay**:
    - **m_vecDisplayStats**:
      - EBulletDamage
      - EBaseWeaponDamageIncrease
      - ERoundsPerSecond
      - EFireRate
      - EClipSize
      - EClipSizeIncrease
      - EReloadTime
      - EReloadSpeed
      - EBulletSpeed
      - EBulletSpeedIncrease
      - EBulletLifesteal
    - **m_vecOtherDisplayStats**:
      - ELightMeleeDamage
      - EHeavyMeleeDamage
    - **m_strWeaponImage**: panorama:"file://{images}/heroes/guns/engineer_gun.psd"
    - **m_eWeaponAttributes**: EWeaponAttribute_RapidFire | EWeaponAttribute_MediumRange
    - **m_strWeaponDescLocString**: #citadel_weapon_hero_forge_set_desc
  - **m_eVitalityStatsDisplay**:
    - **m_vecDisplayStats**:
      - EMaxHealth
      - EBaseHealthRegen
      - EBulletArmorDamageReduction
      - ETechArmorDamageReduction
      - EBulletShieldHealth
      - ETechShieldHealth
      - ECritDamageReceivedScale
    - **m_vecOtherDisplayStats**:
      - EMaxMoveSpeed
      - ESprintSpeed
      - EStaminaCooldown
      - EStaminaRegenIncrease
      - EStamina
  - **m_eSpiritStatsDisplay**:
    - **m_vecDisplayStats**:
      - ETechCooldown
      - ETechDuration
      - ETechRange
      - ETechLifesteal
      - EMaxChargesIncrease
      - ETechCooldownBetweenChargeUses
- **_base**: hero_base
- **m_bNewPlayerRecommended**: True
- **m_bLaneTestingRecommended**: True
- **m_strSelectionImage**: panorama:"file://{images}/heroes/engineer.psd"
- **m_strIconImageSmall**: panorama:"file://{images}/heroes/engineer_sm.psd"
- **m_strMinimapImage**: panorama:"file://{images}/heroes/engineer_mm.psd"
- **m_strWIPModelName**: resource_name:"models/heroes_staging/engineer_v3/engineer.vmdl"
- **m_strUIAnimGraph**: resource_name:"models/heroes_staging/engineer/ui_engineer.vanmgrph"
- **m_strDeathSound**: soundevent:"Forge.Death"
- **m_hGameSoundEventScript**: resource_name:"soundevents/hero/forge.vsndevts"
- **m_hVOEventScript**: resource_name:"soundevents/vo/vo_hero_forge.vsndevts"
- **m_strRosterSelectedSound**: soundevent:"McGinnis.VO.HeroPick"
- **m_strIconHeroCard**: panorama:"file://{images}/heroes/engineer_card.psd"
- **m_strRosterRemovedSound**: soundevent:"McGinnis.VO.HeroRemove"
- **m_hGeneratedVOEventScript**: resource_name:"soundevents/vo/generated_vo_hero_forge.vsndevts"
- **m_strTopBarImage**: panorama:"file://{images}/hud/hero_portraits/engineer_hud.psd"
- **m_RecommendedUpgrades**:
  - upgrade_extra_charge
  - upgrade_rapid_rounds
  - upgrade_resilience
  - upgrade_improved_stamina
  - upgrade_sprint_booster
  - upgrade_magic_reach
  - upgrade_fleetfoot_boots
  - upgrade_magic_tempo
  - upgrade_bullet_armor
  - upgrade_magic_shield
  - upgrade_magic_vulnerability
  - upgrade_chain_lightning
  - upgrade_rapid_recharge
  - upgrade_dps_aura
  - upgrade_magic_slow
  - upgrade_cooldown_reduction
  - upgrade_ability_power_shard
  - upgrade_escalating_exposure
- **m_strUIPortraitMap**: maps/ui/hero_prefabs/forge.vmap
- **m_strTopBarVertical**: panorama:"file://{images}/heroes/engineer_vertical.psd"
- **m_strUIShopAnimGraph**: resource_name:"models/heroes_staging/engineer/ui_shop_engineer.vanmgrph"
- **m_strUIShoppingMap**: maps/ui/hero_shop/engineer_shop.vmap

---

# Hero: hero_chrono

- **_class**: CitadelHeroData_t
- **m_bPlayerSelectable**: True
- **m_bDisabled**: False
- **m_bInDevelopment**: False
- **m_bNeedsTesting**: False
- **m_bAssignedPlayersOnly**: False
- **m_bBotSelectable**: False
- **m_bLimitedTesting**: False
- **m_nComplexity**: 3
- **m_nReadability**: 1
- **m_HeroID**: 10
- **m_strModelName**: resource_name:"models/heroes_staging/chrono/chrono.vmdl"
- **m_hDamageTakenParticle**: resource_name:"particles/generic/player_damage_screen.vpcf"
- **m_hGroundDamageTakenParticle**: resource_name:"particles/generic/player_ground_damage_screen.vpcf"
- **m_hDeathParticle**: resource_name:"particles/generic/player_death_screen.vpcf"
- **m_hLowHealthParticle**: resource_name:"particles/generic/player_low_health_screen.vpcf"
- **m_hRespawnParticle**: resource_name:"particles/generic/player_respawn_deploy.vpcf"
- **m_nModelSkin**: 0
- **m_mapStartingStats**:
  - **EMaxMoveSpeed**: 6.5
  - **ESprintSpeed**: 0
  - **ECrouchSpeed**: 4.75
  - **EMoveAcceleration**: 4
  - **ELightMeleeDamage**: 63
  - **EHeavyMeleeDamage**: 116
  - **EMaxHealth**: 550
  - **EWeaponPower**: 0
  - **EReloadSpeed**: 1
  - **EWeaponPowerScale**: 1
  - **EProcBuildUpRateScale**: 1
  - **EStamina**: 3
  - **EBaseHealthRegen**: 2.0
  - **EStaminaRegenPerSecond**: 0.2
  - **EAbilityResourceMax**: 0
  - **EAbilityResourceRegenPerSecond**: 0
  - **ECritDamageReceivedScale**: 1.0
  - **ETechDuration**: 1
  - **ETechRange**: 1
- **m_flCollisionRadius**: 20
- **m_flCollisionHeight**: 80
- **m_flStepHeight**: 32
- **m_mapBoundAbilities**:
  - **ESlot_Weapon_Primary**: citadel_weapon_chrono_set
  - **ESlot_Weapon_Melee**: citadel_ability_melee_chrono
  - **ESlot_Ability_Mantle**: citadel_ability_mantle
  - **ESlot_Ability_Jump**: citadel_ability_jump
  - **ESlot_Ability_Slide**: citadel_ability_slide
  - **ESlot_Ability_ZipLine**: citadel_ability_zip_line
  - **ESlot_Ability_ZipLineBoost**: citadel_ability_zipline_boost
  - **ESlot_Ability_Innate_1**: citadel_ability_dash
  - **ESlot_Ability_Innate_2**: citadel_ability_sprint
  - **ESlot_Ability_Innate_3**: citadel_ability_melee_parry
  - **ESlot_Signature_1**: citadel_ability_chrono_pulse_grenade
  - **ESlot_Signature_2**: citadel_ability_chrono_time_wall
  - **ESlot_Signature_3**: citadel_ability_chrono_kinetic_carbine
  - **ESlot_Signature_4**: citadel_ability_chrono_swap
- **m_mapItemSlotInfo**:
  - **EItemSlotType_WeaponMod**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
  - **EItemSlotType_Armor**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
  - **EItemSlotType_Tech**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
- **m_mapPurchaseBonuses**:
  - **EItemSlotType_WeaponMod**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 6 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 2 | 10 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 3 | 14 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 4 | 18 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
  - **EItemSlotType_Armor**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 11 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 2 | 14 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 3 | 17 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 4 | 20 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
  - **EItemSlotType_Tech**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 4 | MODIFIER_VALUE_TECH_POWER |
    | 2 | 8 | MODIFIER_VALUE_TECH_POWER |
    | 3 | 12 | MODIFIER_VALUE_TECH_POWER |
    | 4 | 16 | MODIFIER_VALUE_TECH_POWER |
- **m_mapLevelInfo**:
  - **1**:
    - **m_unRequiredGold**: 0
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **2**:
    - **m_unRequiredGold**: 400
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
      - **EAbilityPoints**: 1
  - **3**:
    - **m_unRequiredGold**: 800
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **4**:
    - **m_unRequiredGold**: 1200
    - **m_bUseStandardUpgrade**: True
  - **5**:
    - **m_unRequiredGold**: 1500
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **6**:
    - **m_unRequiredGold**: 2200
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **7**:
    - **m_unRequiredGold**: 3000
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **8**:
    - **m_unRequiredGold**: 4500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **9**:
    - **m_unRequiredGold**: 6000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **10**:
    - **m_unRequiredGold**: 7500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **11**:
    - **m_unRequiredGold**: 9000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **12**:
    - **m_unRequiredGold**: 10500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **13**:
    - **m_unRequiredGold**: 12000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **14**:
    - **m_unRequiredGold**: 13000
    - **m_bUseStandardUpgrade**: True
  - **15**:
    - **m_unRequiredGold**: 14000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **16**:
    - **m_unRequiredGold**: 15000
    - **m_bUseStandardUpgrade**: True
  - **17**:
    - **m_unRequiredGold**: 16000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **18**:
    - **m_unRequiredGold**: 18000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **19**:
    - **m_unRequiredGold**: 20000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **20**:
    - **m_unRequiredGold**: 22000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **21**:
    - **m_unRequiredGold**: 24000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **22**:
    - **m_unRequiredGold**: 27000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **23**:
    - **m_unRequiredGold**: 30000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **24**:
    - **m_unRequiredGold**: 33000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **25**:
    - **m_unRequiredGold**: 36000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **26**:
    - **m_unRequiredGold**: 39000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **27**:
    - **m_unRequiredGold**: 42000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **28**:
    - **m_unRequiredGold**: 45000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **29**:
    - **m_unRequiredGold**: 48000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
- **m_hFootstepSounds**: sweetener_default
- **m_strFootstepSoundEventDefault**: soundevent:"Chrono.Footstep.Multi"
- **m_flStealthSpeedMetersPerSecond**: 4
- **m_flFootstepSoundTravelDistanceMeters**: 20
- **m_flStepSoundTime**: 0.325
- **m_vecAnimGraphDefaultValueOverrides**:
  | m_strParamName | m_strParamValue |
  | --- | --- |
  | e_SWITCH_4wayRoll_ON/OFF | 0 |
  | e_SWITCH_Recoil_ON/OFF | 1 |
  | e_SWITCH_ZiplinePhysicsSway_ON/OFF | 0 |
  | e_SWITCH_ShootStyle | 0 |
- **m_strLastHitSound**: soundevent:"LastHit.Default"
- **m_strLowHealthSound**: soundevent:"PlayerAlert.LowHealth"
- **m_colorUI**:
  - 152
  - 57
  - 82
- **m_colorGlowFriendly**:
  - 255
  - 239
  - 215
- **m_colorGlowEnemy**:
  - 255
  - 0
  - 0
- **m_colorGlowTeam1**:
  - 231
  - 182
  - 89
- **m_colorGlowTeam2**:
  - 91
  - 121
  - 230
- **m_vecAmbientParticleSettings**:
  | m_eAttachmentType | m_nCP |
  | --- | --- |
  | PATTACH_ABSORIGIN_FOLLOW | 0 |
  | PATTACH_POINT_FOLLOW | 1 |
- **m_heroStatsUI**:
  - **m_vecDisplayStats**:
    | m_eStatType | m_eStatCategory |
    | --- | --- |
    | EMaxHealth | ECitadelStat_Vitality |
    | EBaseHealthRegen | ECitadelStat_Vitality |
    | EBulletArmorDamageReduction | ECitadelStat_Vitality |
    | ETechArmorDamageReduction | ECitadelStat_Vitality |
    | ETechPower | ECitadelStat_Spirit |
    | EWeaponDPS | ECitadelStat_Weapon |
    | EBulletDamage | ECitadelStat_Weapon |
    | EClipSize | ECitadelStat_Weapon |
    | ERoundsPerSecond | ECitadelStat_Weapon |
    | ELightMeleeDamage | ECitadelStat_Weapon |
    | EHeavyMeleeDamage | ECitadelStat_Weapon |
    | EMaxMoveSpeed | ECitadelStat_Vitality |
    | ESprintSpeed | ECitadelStat_Vitality |
    | EStamina | ECitadelStat_Vitality |
  - **m_eWeaponStatDisplay**: EMeleeDamage_DEPRECATED
- **m_mapScalingStats**:
- **m_heroStatsDisplay**:
  - **m_vecHealthHeaderStats**:
    - EMaxHealth
    - EBaseHealthRegen
  - **m_vecHealthStats**:
    - EBulletArmorDamageReduction
    - ETechArmorDamageReduction
    - EBulletShieldHealth
    - ETechShieldHealth
    - EBulletLifesteal
    - ETechLifesteal
    - EMaxMoveSpeed
    - ESprintSpeed
    - EStamina
    - EHealingOutput
  - **m_vecWeaponHeaderStats**:
    - EWeaponDPS
    - EBulletDamage
  - **m_vecWeaponStats**:
    - ELightMeleeDamage
    - EHeavyMeleeDamage
    - EFireRate
    - EClipSize
  - **m_vecMagicHeaderStats**:
    - ETechPower
  - **m_vecMagicStats**:
    - ETechCooldown
    - ETechRange
    - ETechDuration
- **m_mapStandardLevelUpUpgrades**:
  - **MODIFIER_VALUE_BASE_BULLET_DAMAGE_FROM_LEVEL**: 0.42
  - **MODIFIER_VALUE_BASE_MELEE_DAMAGE_FROM_LEVEL**: 3.4
  - **MODIFIER_VALUE_BASE_HEALTH_FROM_LEVEL**: 40.0
  - **MODIFIER_VALUE_TECH_DAMAGE_PERCENT**: 0.0
  - **MODIFIER_VALUE_BULLET_ARMOR_DAMAGE_RESIST**: 0.0
- **m_eAbilityResourceType**: EResourceType_None
- **m_ShopStatDisplay**:
  - **m_eWeaponStatsDisplay**:
    - **m_vecDisplayStats**:
      - EBulletDamage
      - EBaseWeaponDamageIncrease
      - ERoundsPerSecond
      - EFireRate
      - EClipSize
      - EClipSizeIncrease
      - EReloadTime
      - EReloadSpeed
      - EBulletSpeed
      - EBulletSpeedIncrease
      - EBulletLifesteal
    - **m_vecOtherDisplayStats**:
      - ELightMeleeDamage
      - EHeavyMeleeDamage
    - **m_eWeaponAttributes**: EWeaponAttribute_BurstFire | EWeaponAttribute_MediumRange
    - **m_strWeaponImage**: panorama:"file://{images}/heroes/guns/chrono_gun.psd"
  - **m_eVitalityStatsDisplay**:
    - **m_vecDisplayStats**:
      - EMaxHealth
      - EBaseHealthRegen
      - EBulletArmorDamageReduction
      - ETechArmorDamageReduction
      - EBulletShieldHealth
      - ETechShieldHealth
      - ECritDamageReceivedScale
    - **m_vecOtherDisplayStats**:
      - EMaxMoveSpeed
      - ESprintSpeed
      - EStaminaCooldown
      - EStaminaRegenIncrease
      - EStamina
  - **m_eSpiritStatsDisplay**:
    - **m_vecDisplayStats**:
      - ETechCooldown
      - ETechDuration
      - ETechRange
      - ETechLifesteal
      - EMaxChargesIncrease
      - ETechCooldownBetweenChargeUses
- **_base**: hero_base
- **m_strSelectionImage**: panorama:"file://{images}/heroes/chrono.psd"
- **m_strIconImageSmall**: panorama:"file://{images}/heroes/chrono_sm.psd"
- **m_strMinimapImage**: panorama:"file://{images}/heroes/chrono_mm.psd"
- **m_strUIAnimGraph**: resource_name:"models/heroes_staging/chrono/ui_chrono.vanmgrph"
- **m_hGameSoundEventScript**: resource_name:"soundevents/hero/chrono.vsndevts"
- **m_hVOEventScript**: resource_name:"soundevents/vo/vo_hero_chrono.vsndevts"
- **m_strRosterSelectedSound**: soundevent:"Paradox.VO.HeroPick"
- **m_strDeathSound**: soundevent:"Chrono.Death"
- **m_strIconHeroCard**: panorama:"file://{images}/heroes/chrono_card.psd"
- **m_strRosterRemovedSound**: soundevent:"Paradox.VO.HeroRemove"
- **m_strTopBarImage**: panorama:"file://{images}/hud/hero_portraits/chrono_hud.psd"
- **m_hGeneratedVOEventScript**: resource_name:"soundevents/vo/generated_vo_hero_chrono.vsndevts"
- **m_strUIPortraitMap**: maps/ui/hero_prefabs/chrono.vmap
- **m_RecommendedUpgrades**:
  - upgrade_hollow_point_rounds
  - upgrade_medic_bullets
  - upgrade_magic_burst
  - upgrade_sprint_booster
  - upgrade_crackshot
  - upgrade_magic_shield
  - upgrade_regenerating_bullet_shield
  - upgrade_magic_shock
  - upgrade_chain_lightning
  - upgrade_chonky
- **m_strTopBarVertical**: panorama:"file://{images}/heroes/chrono_vertical.psd"
- **m_strUIShoppingMap**: maps/ui/hero_shop/chrono_shop.vmap
- **m_strUIShopAnimGraph**: resource_name:"models/heroes_staging/chrono/ui_shop_chrono.vanmgrph"

---

# Hero: hero_dynamo

- **_class**: CitadelHeroData_t
- **m_bPlayerSelectable**: True
- **m_bDisabled**: False
- **m_bInDevelopment**: False
- **m_bNeedsTesting**: False
- **m_bAssignedPlayersOnly**: False
- **m_bBotSelectable**: True
- **m_bLimitedTesting**: False
- **m_nComplexity**: 2
- **m_nReadability**: 4
- **m_HeroID**: 11
- **m_strModelName**: resource_name:"models/heroes_staging/prof_dynamo/prof_dynamo.vmdl"
- **m_hDamageTakenParticle**: resource_name:"particles/generic/player_damage_screen.vpcf"
- **m_hGroundDamageTakenParticle**: resource_name:"particles/generic/player_ground_damage_screen.vpcf"
- **m_hDeathParticle**: resource_name:"particles/generic/player_death_screen.vpcf"
- **m_hLowHealthParticle**: resource_name:"particles/generic/player_low_health_screen.vpcf"
- **m_hRespawnParticle**: resource_name:"particles/generic/player_respawn_deploy.vpcf"
- **m_nModelSkin**: 0
- **m_mapStartingStats**:
  - **EMaxMoveSpeed**: 6.5
  - **ESprintSpeed**: 0
  - **ECrouchSpeed**: 4.75
  - **EMoveAcceleration**: 4
  - **ELightMeleeDamage**: 63
  - **EHeavyMeleeDamage**: 116
  - **EMaxHealth**: 650
  - **EWeaponPower**: 0
  - **EReloadSpeed**: 1
  - **EWeaponPowerScale**: 1
  - **EProcBuildUpRateScale**: 1
  - **EStamina**: 3
  - **EBaseHealthRegen**: 2.0
  - **EStaminaRegenPerSecond**: 0.2
  - **EAbilityResourceMax**: 0
  - **EAbilityResourceRegenPerSecond**: 0
  - **ECritDamageReceivedScale**: 1.0
  - **ETechDuration**: 1
  - **ETechRange**: 1
- **m_flCollisionRadius**: 20
- **m_flCollisionHeight**: 80
- **m_flStepHeight**: 32
- **m_mapBoundAbilities**:
  - **ESlot_Weapon_Primary**: citadel_weapon_sumo_set
  - **ESlot_Weapon_Melee**: citadel_ability_melee_sumo
  - **ESlot_Ability_Mantle**: citadel_ability_mantle
  - **ESlot_Ability_Jump**: citadel_ability_jump
  - **ESlot_Ability_Slide**: citadel_ability_slide
  - **ESlot_Ability_ZipLine**: citadel_ability_zip_line
  - **ESlot_Ability_ZipLineBoost**: citadel_ability_zipline_boost
  - **ESlot_Ability_Innate_1**: citadel_ability_dash
  - **ESlot_Ability_Innate_2**: citadel_ability_sprint
  - **ESlot_Ability_Innate_3**: citadel_ability_melee_parry
  - **ESlot_Signature_1**: citadel_ability_stomp
  - **ESlot_Signature_2**: citadel_ability_void_sphere
  - **ESlot_Signature_3**: citadel_ability_nikuman
  - **ESlot_Signature_4**: citadel_ability_self_vacuum
- **m_mapItemSlotInfo**:
  - **EItemSlotType_WeaponMod**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
  - **EItemSlotType_Armor**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
  - **EItemSlotType_Tech**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
- **m_mapPurchaseBonuses**:
  - **EItemSlotType_WeaponMod**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 6 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 2 | 10 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 3 | 14 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 4 | 18 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
  - **EItemSlotType_Armor**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 11 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 2 | 14 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 3 | 17 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 4 | 20 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
  - **EItemSlotType_Tech**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 4 | MODIFIER_VALUE_TECH_POWER |
    | 2 | 8 | MODIFIER_VALUE_TECH_POWER |
    | 3 | 12 | MODIFIER_VALUE_TECH_POWER |
    | 4 | 16 | MODIFIER_VALUE_TECH_POWER |
- **m_mapLevelInfo**:
  - **1**:
    - **m_unRequiredGold**: 0
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **2**:
    - **m_unRequiredGold**: 400
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
      - **EAbilityPoints**: 1
  - **3**:
    - **m_unRequiredGold**: 800
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **4**:
    - **m_unRequiredGold**: 1200
    - **m_bUseStandardUpgrade**: True
  - **5**:
    - **m_unRequiredGold**: 1500
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **6**:
    - **m_unRequiredGold**: 2200
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **7**:
    - **m_unRequiredGold**: 3000
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **8**:
    - **m_unRequiredGold**: 4500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **9**:
    - **m_unRequiredGold**: 6000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **10**:
    - **m_unRequiredGold**: 7500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **11**:
    - **m_unRequiredGold**: 9000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **12**:
    - **m_unRequiredGold**: 10500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **13**:
    - **m_unRequiredGold**: 12000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **14**:
    - **m_unRequiredGold**: 13000
    - **m_bUseStandardUpgrade**: True
  - **15**:
    - **m_unRequiredGold**: 14000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **16**:
    - **m_unRequiredGold**: 15000
    - **m_bUseStandardUpgrade**: True
  - **17**:
    - **m_unRequiredGold**: 16000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **18**:
    - **m_unRequiredGold**: 18000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **19**:
    - **m_unRequiredGold**: 20000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **20**:
    - **m_unRequiredGold**: 22000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **21**:
    - **m_unRequiredGold**: 24000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **22**:
    - **m_unRequiredGold**: 27000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **23**:
    - **m_unRequiredGold**: 30000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **24**:
    - **m_unRequiredGold**: 33000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **25**:
    - **m_unRequiredGold**: 36000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **26**:
    - **m_unRequiredGold**: 39000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **27**:
    - **m_unRequiredGold**: 42000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **28**:
    - **m_unRequiredGold**: 45000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **29**:
    - **m_unRequiredGold**: 48000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
- **m_hFootstepSounds**: sweetener_default
- **m_strFootstepSoundEventDefault**: soundevent:"Dynamo.Footstep"
- **m_flStealthSpeedMetersPerSecond**: 4
- **m_flFootstepSoundTravelDistanceMeters**: 20
- **m_flStepSoundTime**: 0.29
- **m_vecAnimGraphDefaultValueOverrides**:
  | m_strParamName | m_strParamValue |
  | --- | --- |
  | e_SWITCH_4wayRoll_ON/OFF | 0 |
  | e_SWITCH_Recoil_ON/OFF | 0 |
  | e_SWITCH_ZiplinePhysicsSway_ON/OFF | 0 |
  | e_SWITCH_ShootStyle | 0 |
  | b_UseNewZipLineSetup | False |
- **m_strLastHitSound**: soundevent:"LastHit.Default"
- **m_strLowHealthSound**: soundevent:"PlayerAlert.LowHealth"
- **m_colorUI**:
  - 207
  - 185
  - 69
- **m_colorGlowFriendly**:
  - 255
  - 239
  - 215
- **m_colorGlowEnemy**:
  - 255
  - 0
  - 0
- **m_colorGlowTeam1**:
  - 231
  - 182
  - 89
- **m_colorGlowTeam2**:
  - 91
  - 121
  - 230
- **m_vecAmbientParticleSettings**:
  | m_eAttachmentType | m_nCP |
  | --- | --- |
  | PATTACH_ABSORIGIN_FOLLOW | 0 |
  | PATTACH_POINT_FOLLOW | 1 |
- **m_heroStatsUI**:
  - **m_vecDisplayStats**:
    | m_eStatType | m_eStatCategory |
    | --- | --- |
    | EMaxHealth | ECitadelStat_Vitality |
    | EBaseHealthRegen | ECitadelStat_Vitality |
    | EBulletArmorDamageReduction | ECitadelStat_Vitality |
    | ETechArmorDamageReduction | ECitadelStat_Vitality |
    | ETechPower | ECitadelStat_Spirit |
    | EWeaponDPS | ECitadelStat_Weapon |
    | EBulletDamage | ECitadelStat_Weapon |
    | EClipSize | ECitadelStat_Weapon |
    | ERoundsPerSecond | ECitadelStat_Weapon |
    | ELightMeleeDamage | ECitadelStat_Weapon |
    | EHeavyMeleeDamage | ECitadelStat_Weapon |
    | EMaxMoveSpeed | ECitadelStat_Vitality |
    | ESprintSpeed | ECitadelStat_Vitality |
    | EStamina | ECitadelStat_Vitality |
  - **m_eWeaponStatDisplay**: EMeleeDamage_DEPRECATED
- **m_mapScalingStats**:
- **m_heroStatsDisplay**:
  - **m_vecHealthHeaderStats**:
    - EMaxHealth
    - EBaseHealthRegen
  - **m_vecHealthStats**:
    - EBulletArmorDamageReduction
    - ETechArmorDamageReduction
    - EBulletShieldHealth
    - ETechShieldHealth
    - EBulletLifesteal
    - ETechLifesteal
    - EMaxMoveSpeed
    - ESprintSpeed
    - EStamina
    - EHealingOutput
  - **m_vecWeaponHeaderStats**:
    - EWeaponDPS
    - EBulletDamage
  - **m_vecWeaponStats**:
    - ELightMeleeDamage
    - EHeavyMeleeDamage
    - EFireRate
    - EClipSize
  - **m_vecMagicHeaderStats**:
    - ETechPower
  - **m_vecMagicStats**:
    - ETechCooldown
    - ETechRange
    - ETechDuration
- **m_mapStandardLevelUpUpgrades**:
  - **MODIFIER_VALUE_BASE_BULLET_DAMAGE_FROM_LEVEL**: 0.9
  - **MODIFIER_VALUE_BASE_MELEE_DAMAGE_FROM_LEVEL**: 3.4
  - **MODIFIER_VALUE_BASE_HEALTH_FROM_LEVEL**: 44.0
  - **MODIFIER_VALUE_TECH_DAMAGE_PERCENT**: 0.0
  - **MODIFIER_VALUE_BULLET_ARMOR_DAMAGE_RESIST**: 0.0
- **m_eAbilityResourceType**: EResourceType_None
- **m_ShopStatDisplay**:
  - **m_eWeaponStatsDisplay**:
    - **m_vecDisplayStats**:
      - EBulletDamage
      - EBaseWeaponDamageIncrease
      - ERoundsPerSecond
      - EFireRate
      - EClipSize
      - EClipSizeIncrease
      - EReloadTime
      - EReloadSpeed
      - EBulletSpeed
      - EBulletSpeedIncrease
      - EBulletLifesteal
    - **m_vecOtherDisplayStats**:
      - ELightMeleeDamage
      - EHeavyMeleeDamage
    - **m_eWeaponAttributes**: EWeaponAttribute_MediumRange | EWeaponAttribute_HeavyHitter | EWeaponAttribute_Projectile
    - **m_strWeaponImage**: panorama:"file://{images}/heroes/guns/dynamo_gun.psd"
  - **m_eVitalityStatsDisplay**:
    - **m_vecDisplayStats**:
      - EMaxHealth
      - EBaseHealthRegen
      - EBulletArmorDamageReduction
      - ETechArmorDamageReduction
      - EBulletShieldHealth
      - ETechShieldHealth
      - ECritDamageReceivedScale
    - **m_vecOtherDisplayStats**:
      - EMaxMoveSpeed
      - ESprintSpeed
      - EStaminaCooldown
      - EStaminaRegenIncrease
      - EStamina
  - **m_eSpiritStatsDisplay**:
    - **m_vecDisplayStats**:
      - ETechCooldown
      - ETechDuration
      - ETechRange
      - ETechLifesteal
      - EMaxChargesIncrease
      - ETechCooldownBetweenChargeUses
- **_base**: hero_base
- **m_bNewPlayerRecommended**: True
- **m_bLaneTestingRecommended**: True
- **m_strSelectionImage**: panorama:"file://{images}/heroes/sumo.psd"
- **m_strIconImageSmall**: panorama:"file://{images}/heroes/sumo_sm.psd"
- **m_strMinimapImage**: panorama:"file://{images}/heroes/sumo_mm.psd"
- **m_strUIAnimGraph**: resource_name:"models/heroes_staging/prof_dynamo/ui_prof_dynamo.vanmgrph"
- **m_strWIPModelName**: resource_name:"models/heroes_staging/prof_dynamo/prof_dynamo.vmdl"
- **m_strDeathSound**: soundevent:"Dynamo.Death"
- **m_hGameSoundEventScript**: resource_name:"soundevents/hero/dynamo.vsndevts"
- **m_hVOEventScript**: resource_name:"soundevents/vo/vo_hero_dynamo.vsndevts"
- **m_strRosterSelectedSound**: soundevent:"Professor.VO.HeroPick"
- **m_strIconHeroCard**: panorama:"file://{images}/heroes/sumo_card.psd"
- **m_strRosterRemovedSound**: soundevent:"Professor.VO.HeroRemove"
- **m_hGeneratedVOEventScript**: resource_name:"soundevents/vo/generated_vo_hero_dynamo.vsndevts"
- **m_strTopBarImage**: panorama:"file://{images}/hud/hero_portraits/sumo_hud.psd"
- **m_RecommendedUpgrades**:
  - upgrade_hollow_point_rounds
  - upgrade_clip_size
  - upgrade_magic_reach
  - upgrade_healing_booster
  - upgrade_arcane_extension
  - upgrade_magic_tempo
  - upgrade_bullet_armor
  - upgrade_tech_armor
  - upgrade_cooldown_reduction
  - upgrade_rocket_booster
  - upgrade_ability_refresher
- **m_strUIPortraitMap**: maps/ui/hero_prefabs/prof_dynamo.vmap
- **m_strTopBarVertical**: panorama:"file://{images}/heroes/sumo_vertical.psd"
- **m_flStepSoundTimeSprinting**: 0.28
- **m_strUIShopAnimGraph**: resource_name:"models/heroes_staging/prof_dynamo/ui_shop_prof_dynamo.vanmgrph"
- **m_strUIShoppingMap**: maps/ui/hero_shop/prof_dynamo_shop.vmap

---

# Hero: hero_kelvin

- **_class**: CitadelHeroData_t
- **m_bPlayerSelectable**: True
- **m_bDisabled**: False
- **m_bInDevelopment**: False
- **m_bNeedsTesting**: False
- **m_bAssignedPlayersOnly**: False
- **m_bBotSelectable**: True
- **m_bLimitedTesting**: False
- **m_nComplexity**: 2
- **m_nReadability**: 3
- **m_HeroID**: 12
- **m_strModelName**: resource_name:"models/heroes_staging/kelvin_v2/kelvin.vmdl"
- **m_hDamageTakenParticle**: resource_name:"particles/generic/player_damage_screen.vpcf"
- **m_hGroundDamageTakenParticle**: resource_name:"particles/generic/player_ground_damage_screen.vpcf"
- **m_hDeathParticle**: resource_name:"particles/generic/player_death_screen.vpcf"
- **m_hLowHealthParticle**: resource_name:"particles/generic/player_low_health_screen.vpcf"
- **m_hRespawnParticle**: resource_name:"particles/generic/player_respawn_deploy.vpcf"
- **m_nModelSkin**: 0
- **m_mapStartingStats**:
  - **EMaxMoveSpeed**: 6.5
  - **ESprintSpeed**: 0
  - **ECrouchSpeed**: 4.75
  - **EMoveAcceleration**: 4
  - **ELightMeleeDamage**: 63
  - **EHeavyMeleeDamage**: 116
  - **EMaxHealth**: 600.0
  - **EWeaponPower**: 0
  - **EReloadSpeed**: 1
  - **EWeaponPowerScale**: 1
  - **EProcBuildUpRateScale**: 1
  - **EStamina**: 3
  - **EBaseHealthRegen**: 2.0
  - **EStaminaRegenPerSecond**: 0.2
  - **EAbilityResourceMax**: 0
  - **EAbilityResourceRegenPerSecond**: 0
  - **ECritDamageReceivedScale**: 1.0
  - **ETechDuration**: 1
  - **ETechRange**: 1
  - **ETechArmorDamageReduction**: 10.0
- **m_flCollisionRadius**: 20
- **m_flCollisionHeight**: 80
- **m_flStepHeight**: 32
- **m_mapBoundAbilities**:
  - **ESlot_Weapon_Primary**: citadel_weapon_kelvin_set
  - **ESlot_Weapon_Melee**: ability_melee_kelvin
  - **ESlot_Ability_Mantle**: citadel_ability_mantle
  - **ESlot_Ability_Jump**: citadel_ability_jump
  - **ESlot_Ability_Slide**: citadel_ability_slide
  - **ESlot_Ability_ZipLine**: citadel_ability_zip_line
  - **ESlot_Ability_ZipLineBoost**: citadel_ability_zipline_boost
  - **ESlot_Ability_Innate_1**: citadel_ability_dash
  - **ESlot_Ability_Innate_2**: citadel_ability_sprint
  - **ESlot_Ability_Innate_3**: citadel_ability_melee_parry
  - **ESlot_Signature_1**: ability_ice_grenade
  - **ESlot_Signature_2**: ability_icepath
  - **ESlot_Signature_3**: ability_icebeam
  - **ESlot_Signature_4**: ability_ice_dome
- **m_mapItemSlotInfo**:
  - **EItemSlotType_WeaponMod**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
  - **EItemSlotType_Armor**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
  - **EItemSlotType_Tech**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
- **m_mapPurchaseBonuses**:
  - **EItemSlotType_WeaponMod**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 6 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 2 | 10 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 3 | 14 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 4 | 18 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
  - **EItemSlotType_Armor**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 11 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 2 | 14 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 3 | 17 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 4 | 20 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
  - **EItemSlotType_Tech**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 4 | MODIFIER_VALUE_TECH_POWER |
    | 2 | 8 | MODIFIER_VALUE_TECH_POWER |
    | 3 | 12 | MODIFIER_VALUE_TECH_POWER |
    | 4 | 16 | MODIFIER_VALUE_TECH_POWER |
- **m_mapLevelInfo**:
  - **1**:
    - **m_unRequiredGold**: 0
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **2**:
    - **m_unRequiredGold**: 400
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
      - **EAbilityPoints**: 1
  - **3**:
    - **m_unRequiredGold**: 800
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **4**:
    - **m_unRequiredGold**: 1200
    - **m_bUseStandardUpgrade**: True
  - **5**:
    - **m_unRequiredGold**: 1500
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **6**:
    - **m_unRequiredGold**: 2200
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **7**:
    - **m_unRequiredGold**: 3000
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **8**:
    - **m_unRequiredGold**: 4500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **9**:
    - **m_unRequiredGold**: 6000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **10**:
    - **m_unRequiredGold**: 7500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **11**:
    - **m_unRequiredGold**: 9000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **12**:
    - **m_unRequiredGold**: 10500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **13**:
    - **m_unRequiredGold**: 12000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **14**:
    - **m_unRequiredGold**: 13000
    - **m_bUseStandardUpgrade**: True
  - **15**:
    - **m_unRequiredGold**: 14000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **16**:
    - **m_unRequiredGold**: 15000
    - **m_bUseStandardUpgrade**: True
  - **17**:
    - **m_unRequiredGold**: 16000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **18**:
    - **m_unRequiredGold**: 18000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **19**:
    - **m_unRequiredGold**: 20000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **20**:
    - **m_unRequiredGold**: 22000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **21**:
    - **m_unRequiredGold**: 24000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **22**:
    - **m_unRequiredGold**: 27000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **23**:
    - **m_unRequiredGold**: 30000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **24**:
    - **m_unRequiredGold**: 33000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **25**:
    - **m_unRequiredGold**: 36000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **26**:
    - **m_unRequiredGold**: 39000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **27**:
    - **m_unRequiredGold**: 42000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **28**:
    - **m_unRequiredGold**: 45000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **29**:
    - **m_unRequiredGold**: 48000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
- **m_hFootstepSounds**: sweetener_default
- **m_strFootstepSoundEventDefault**: soundevent:"Kelvin.Footstep"
- **m_flStealthSpeedMetersPerSecond**: 4
- **m_flFootstepSoundTravelDistanceMeters**: 20
- **m_flStepSoundTime**: 0.32
- **m_vecAnimGraphDefaultValueOverrides**:
  | m_strParamName | m_strParamValue |
  | --- | --- |
  | e_SWITCH_4wayRoll_ON/OFF | 0 |
  | e_SWITCH_Recoil_ON/OFF | 0 |
  | e_SWITCH_ZiplinePhysicsSway_ON/OFF | 0 |
  | e_SWITCH_ShootStyle | 0 |
- **m_strLastHitSound**: soundevent:"LastHit.Default"
- **m_strLowHealthSound**: soundevent:"PlayerAlert.LowHealth"
- **m_colorUI**:
  - 116
  - 171
  - 188
- **m_colorGlowFriendly**:
  - 255
  - 239
  - 215
- **m_colorGlowEnemy**:
  - 255
  - 0
  - 0
- **m_colorGlowTeam1**:
  - 231
  - 182
  - 89
- **m_colorGlowTeam2**:
  - 91
  - 121
  - 230
- **m_vecAmbientParticleSettings**:
  | m_eAttachmentType | m_nCP |
  | --- | --- |
  | PATTACH_ABSORIGIN_FOLLOW | 0 |
  | PATTACH_POINT_FOLLOW | 1 |
- **m_heroStatsUI**:
  - **m_vecDisplayStats**:
    | m_eStatType | m_eStatCategory |
    | --- | --- |
    | EMaxHealth | ECitadelStat_Vitality |
    | EBaseHealthRegen | ECitadelStat_Vitality |
    | EBulletArmorDamageReduction | ECitadelStat_Vitality |
    | ETechArmorDamageReduction | ECitadelStat_Vitality |
    | ETechPower | ECitadelStat_Spirit |
    | EWeaponDPS | ECitadelStat_Weapon |
    | EBulletDamage | ECitadelStat_Weapon |
    | EClipSize | ECitadelStat_Weapon |
    | ERoundsPerSecond | ECitadelStat_Weapon |
    | ELightMeleeDamage | ECitadelStat_Weapon |
    | EHeavyMeleeDamage | ECitadelStat_Weapon |
    | EMaxMoveSpeed | ECitadelStat_Vitality |
    | ESprintSpeed | ECitadelStat_Vitality |
    | EStamina | ECitadelStat_Vitality |
  - **m_eWeaponStatDisplay**: EMeleeDamage_DEPRECATED
- **m_mapScalingStats**:
- **m_heroStatsDisplay**:
  - **m_vecHealthHeaderStats**:
    - EMaxHealth
    - EBaseHealthRegen
  - **m_vecHealthStats**:
    - EBulletArmorDamageReduction
    - ETechArmorDamageReduction
    - EBulletShieldHealth
    - ETechShieldHealth
    - EBulletLifesteal
    - ETechLifesteal
    - EMaxMoveSpeed
    - ESprintSpeed
    - EStamina
    - EHealingOutput
  - **m_vecWeaponHeaderStats**:
    - EWeaponDPS
    - EBulletDamage
  - **m_vecWeaponStats**:
    - ELightMeleeDamage
    - EHeavyMeleeDamage
    - EFireRate
    - EClipSize
  - **m_vecMagicHeaderStats**:
    - ETechPower
  - **m_vecMagicStats**:
    - ETechCooldown
    - ETechRange
    - ETechDuration
- **m_mapStandardLevelUpUpgrades**:
  - **MODIFIER_VALUE_BASE_BULLET_DAMAGE_FROM_LEVEL**: 1.2
  - **MODIFIER_VALUE_BASE_MELEE_DAMAGE_FROM_LEVEL**: 3.4
  - **MODIFIER_VALUE_BASE_HEALTH_FROM_LEVEL**: 45.0
  - **MODIFIER_VALUE_TECH_DAMAGE_PERCENT**: 0.0
  - **MODIFIER_VALUE_BULLET_ARMOR_DAMAGE_RESIST**: 0.0
- **m_eAbilityResourceType**: EResourceType_None
- **m_ShopStatDisplay**:
  - **m_eWeaponStatsDisplay**:
    - **m_vecDisplayStats**:
      - EBulletDamage
      - EBaseWeaponDamageIncrease
      - ERoundsPerSecond
      - EFireRate
      - EClipSize
      - EClipSizeIncrease
      - EReloadTime
      - EReloadSpeed
      - EBulletSpeed
      - EBulletSpeedIncrease
      - EBulletLifesteal
    - **m_vecOtherDisplayStats**:
      - ELightMeleeDamage
      - EHeavyMeleeDamage
    - **m_eWeaponAttributes**: EWeaponAttribute_MediumRange | EWeaponAttribute_HeavyHitter | EWeaponAttribute_Projectile
    - **m_strWeaponImage**: panorama:"file://{images}/heroes/guns/kelvin_gun.psd"
  - **m_eVitalityStatsDisplay**:
    - **m_vecDisplayStats**:
      - EMaxHealth
      - EBaseHealthRegen
      - EBulletArmorDamageReduction
      - ETechArmorDamageReduction
      - EBulletShieldHealth
      - ETechShieldHealth
      - ECritDamageReceivedScale
    - **m_vecOtherDisplayStats**:
      - EMaxMoveSpeed
      - ESprintSpeed
      - EStaminaCooldown
      - EStaminaRegenIncrease
      - EStamina
  - **m_eSpiritStatsDisplay**:
    - **m_vecDisplayStats**:
      - ETechCooldown
      - ETechDuration
      - ETechRange
      - ETechLifesteal
      - EMaxChargesIncrease
      - ETechCooldownBetweenChargeUses
- **_base**: hero_base
- **m_bNewPlayerRecommended**: True
- **m_bLaneTestingRecommended**: True
- **m_strSelectionImage**: panorama:"file://{images}/heroes/kelvin.psd"
- **m_strIconImageSmall**: panorama:"file://{images}/heroes/kelvin_sm.psd"
- **m_strMinimapImage**: panorama:"file://{images}/heroes/kelvin_mm.psd"
- **m_strUIAnimGraph**: resource_name:"models/heroes_staging/kelvin_v2/ui_kelvin.vanmgrph"
- **m_strDeathSound**: soundevent:"Kelvin.Death"
- **m_hGameSoundEventScript**: resource_name:"soundevents/hero/kelvin.vsndevts"
- **m_hVOEventScript**: resource_name:"soundevents/vo/vo_hero_kelvin.vsndevts"
- **m_strRosterSelectedSound**: soundevent:"Kelvin.VO.HeroPick"
- **m_strIconHeroCard**: panorama:"file://{images}/heroes/kelvin_card.psd"
- **m_hGeneratedVOEventScript**: resource_name:"soundevents/vo/generated_vo_hero_kelvin.vsndevts"
- **m_strRosterRemovedSound**: soundevent:"Kelvin.VO.HeroRemove"
- **m_strTopBarImage**: panorama:"file://{images}/hud/hero_portraits/kelvin_hud.psd"
- **m_strUIPortraitMap**: maps/ui/hero_prefabs/kelvin.vmap
- **m_RecommendedUpgrades**:
  - upgrade_medic_bullets
  - upgrade_close_range
  - upgrade_magic_burst
  - upgrade_extra_charge
  - upgrade_resilience
  - upgrade_berserker
  - upgrade_crackshot
  - upgrade_healing_booster
  - upgrade_bullet_armor
  - upgrade_tech_armor
  - upgrade_magic_shock
  - upgrade_close_quarter_combat
  - upgrade_tech_purge
  - upgrade_rapid_recharge
  - upgrade_critshot
- **m_strTopBarVertical**: panorama:"file://{images}/heroes/kelvin_vertical.psd"
- **m_strUIShopAnimGraph**: resource_name:"models/heroes_staging/kelvin_v2/ui_shop_kelvin.vanmgrph"
- **m_strUIShoppingMap**: maps/ui/hero_shop/kelvin_shop.vmap

---

# Hero: hero_haze

- **_class**: CitadelHeroData_t
- **m_bPlayerSelectable**: True
- **m_bDisabled**: False
- **m_bInDevelopment**: False
- **m_bNeedsTesting**: False
- **m_bAssignedPlayersOnly**: False
- **m_bBotSelectable**: True
- **m_bLimitedTesting**: False
- **m_nComplexity**: 1
- **m_nReadability**: 5
- **m_HeroID**: 13
- **m_strModelName**: resource_name:"models/heroes_staging/haze/haze.vmdl"
- **m_hDamageTakenParticle**: resource_name:"particles/generic/player_damage_screen.vpcf"
- **m_hGroundDamageTakenParticle**: resource_name:"particles/generic/player_ground_damage_screen.vpcf"
- **m_hDeathParticle**: resource_name:"particles/generic/player_death_screen.vpcf"
- **m_hLowHealthParticle**: resource_name:"particles/generic/player_low_health_screen.vpcf"
- **m_hRespawnParticle**: resource_name:"particles/generic/player_respawn_deploy.vpcf"
- **m_nModelSkin**: 0
- **m_mapStartingStats**:
  - **EMaxMoveSpeed**: 8.0
  - **ESprintSpeed**: 0
  - **ECrouchSpeed**: 4.75
  - **EMoveAcceleration**: 4
  - **ELightMeleeDamage**: 63
  - **EHeavyMeleeDamage**: 116
  - **EMaxHealth**: 500.0
  - **EWeaponPower**: 0
  - **EReloadSpeed**: 1
  - **EWeaponPowerScale**: 1
  - **EProcBuildUpRateScale**: 1
  - **EStamina**: 3
  - **EBaseHealthRegen**: 2.0
  - **EStaminaRegenPerSecond**: 0.2
  - **EAbilityResourceMax**: 0
  - **EAbilityResourceRegenPerSecond**: 0
  - **ECritDamageReceivedScale**: 1.0
  - **ETechDuration**: 1
  - **ETechRange**: 1
- **m_flCollisionRadius**: 20
- **m_flCollisionHeight**: 80
- **m_flStepHeight**: 32
- **m_mapBoundAbilities**:
  - **ESlot_Weapon_Primary**: citadel_weapon_haze_set
  - **ESlot_Weapon_Melee**: ability_melee_haze
  - **ESlot_Ability_Mantle**: citadel_ability_mantle
  - **ESlot_Ability_Jump**: citadel_ability_jump
  - **ESlot_Ability_Slide**: citadel_ability_slide
  - **ESlot_Ability_ZipLine**: citadel_ability_zip_line
  - **ESlot_Ability_ZipLineBoost**: citadel_ability_zipline_boost
  - **ESlot_Ability_Innate_1**: citadel_ability_dash
  - **ESlot_Ability_Innate_2**: citadel_ability_sprint
  - **ESlot_Ability_Innate_3**: citadel_ability_melee_parry
  - **ESlot_Signature_1**: ability_sleep_dagger
  - **ESlot_Signature_2**: ability_smoke_bomb
  - **ESlot_Signature_3**: ability_stacking_damage
  - **ESlot_Signature_4**: ability_bullet_flurry
- **m_mapItemSlotInfo**:
  - **EItemSlotType_WeaponMod**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
  - **EItemSlotType_Armor**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
  - **EItemSlotType_Tech**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
- **m_mapPurchaseBonuses**:
  - **EItemSlotType_WeaponMod**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 6 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 2 | 10 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 3 | 14 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 4 | 18 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
  - **EItemSlotType_Armor**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 11 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 2 | 14 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 3 | 17 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 4 | 20 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
  - **EItemSlotType_Tech**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 4 | MODIFIER_VALUE_TECH_POWER |
    | 2 | 8 | MODIFIER_VALUE_TECH_POWER |
    | 3 | 12 | MODIFIER_VALUE_TECH_POWER |
    | 4 | 16 | MODIFIER_VALUE_TECH_POWER |
- **m_mapLevelInfo**:
  - **1**:
    - **m_unRequiredGold**: 0
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **2**:
    - **m_unRequiredGold**: 400
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
      - **EAbilityPoints**: 1
  - **3**:
    - **m_unRequiredGold**: 800
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **4**:
    - **m_unRequiredGold**: 1200
    - **m_bUseStandardUpgrade**: True
  - **5**:
    - **m_unRequiredGold**: 1500
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **6**:
    - **m_unRequiredGold**: 2200
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **7**:
    - **m_unRequiredGold**: 3000
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **8**:
    - **m_unRequiredGold**: 4500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **9**:
    - **m_unRequiredGold**: 6000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **10**:
    - **m_unRequiredGold**: 7500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **11**:
    - **m_unRequiredGold**: 9000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **12**:
    - **m_unRequiredGold**: 10500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **13**:
    - **m_unRequiredGold**: 12000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **14**:
    - **m_unRequiredGold**: 13000
    - **m_bUseStandardUpgrade**: True
  - **15**:
    - **m_unRequiredGold**: 14000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **16**:
    - **m_unRequiredGold**: 15000
    - **m_bUseStandardUpgrade**: True
  - **17**:
    - **m_unRequiredGold**: 16000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **18**:
    - **m_unRequiredGold**: 18000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **19**:
    - **m_unRequiredGold**: 20000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **20**:
    - **m_unRequiredGold**: 22000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **21**:
    - **m_unRequiredGold**: 24000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **22**:
    - **m_unRequiredGold**: 27000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **23**:
    - **m_unRequiredGold**: 30000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **24**:
    - **m_unRequiredGold**: 33000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **25**:
    - **m_unRequiredGold**: 36000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **26**:
    - **m_unRequiredGold**: 39000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **27**:
    - **m_unRequiredGold**: 42000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **28**:
    - **m_unRequiredGold**: 45000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **29**:
    - **m_unRequiredGold**: 48000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
- **m_hFootstepSounds**: sweetener_default
- **m_strFootstepSoundEventDefault**: soundevent:"Haze.Footstep"
- **m_flStealthSpeedMetersPerSecond**: 4
- **m_flFootstepSoundTravelDistanceMeters**: 20
- **m_flStepSoundTime**: 0.27
- **m_vecAnimGraphDefaultValueOverrides**:
  | m_strParamName | m_strParamValue |
  | --- | --- |
  | e_SWITCH_4wayRoll_ON/OFF | 0 |
  | e_SWITCH_Recoil_ON/OFF | 1 |
  | e_SWITCH_ZiplinePhysicsSway_ON/OFF | 0 |
  | e_SWITCH_ShootStyle | 2 |
- **m_strLastHitSound**: soundevent:"LastHit.Default"
- **m_strLowHealthSound**: soundevent:"PlayerAlert.LowHealth"
- **m_colorUI**:
  - 172
  - 97
  - 51
- **m_colorGlowFriendly**:
  - 255
  - 239
  - 215
- **m_colorGlowEnemy**:
  - 255
  - 0
  - 0
- **m_colorGlowTeam1**:
  - 231
  - 182
  - 89
- **m_colorGlowTeam2**:
  - 91
  - 121
  - 230
- **m_vecAmbientParticleSettings**:
  | m_eAttachmentType | m_nCP |
  | --- | --- |
  | PATTACH_ABSORIGIN_FOLLOW | 0 |
  | PATTACH_POINT_FOLLOW | 1 |
- **m_heroStatsUI**:
  - **m_vecDisplayStats**:
    | m_eStatType | m_eStatCategory |
    | --- | --- |
    | EMaxHealth | ECitadelStat_Vitality |
    | EBaseHealthRegen | ECitadelStat_Vitality |
    | EBulletArmorDamageReduction | ECitadelStat_Vitality |
    | ETechArmorDamageReduction | ECitadelStat_Vitality |
    | ETechPower | ECitadelStat_Spirit |
    | EWeaponDPS | ECitadelStat_Weapon |
    | EBulletDamage | ECitadelStat_Weapon |
    | EClipSize | ECitadelStat_Weapon |
    | ERoundsPerSecond | ECitadelStat_Weapon |
    | ELightMeleeDamage | ECitadelStat_Weapon |
    | EHeavyMeleeDamage | ECitadelStat_Weapon |
    | EMaxMoveSpeed | ECitadelStat_Vitality |
    | ESprintSpeed | ECitadelStat_Vitality |
    | EStamina | ECitadelStat_Vitality |
  - **m_eWeaponStatDisplay**: EMeleeDamage_DEPRECATED
- **m_mapScalingStats**:
  - **EClipSize**:
    - **eScalingStat**: ETechPower
    - **flScale**: 0.5
- **m_heroStatsDisplay**:
  - **m_vecHealthHeaderStats**:
    - EMaxHealth
    - EBaseHealthRegen
  - **m_vecHealthStats**:
    - EBulletArmorDamageReduction
    - ETechArmorDamageReduction
    - EBulletShieldHealth
    - ETechShieldHealth
    - EBulletLifesteal
    - ETechLifesteal
    - EMaxMoveSpeed
    - ESprintSpeed
    - EStamina
    - EHealingOutput
  - **m_vecWeaponHeaderStats**:
    - EWeaponDPS
    - EBulletDamage
  - **m_vecWeaponStats**:
    - ELightMeleeDamage
    - EHeavyMeleeDamage
    - EFireRate
    - EClipSize
  - **m_vecMagicHeaderStats**:
    - ETechPower
  - **m_vecMagicStats**:
    - ETechCooldown
    - ETechRange
    - ETechDuration
- **m_mapStandardLevelUpUpgrades**:
  - **MODIFIER_VALUE_BASE_BULLET_DAMAGE_FROM_LEVEL**: 0.285
  - **MODIFIER_VALUE_BASE_MELEE_DAMAGE_FROM_LEVEL**: 3.4
  - **MODIFIER_VALUE_BASE_HEALTH_FROM_LEVEL**: 27.0
  - **MODIFIER_VALUE_TECH_DAMAGE_PERCENT**: 0.0
  - **MODIFIER_VALUE_BULLET_ARMOR_DAMAGE_RESIST**: 0.0
- **m_eAbilityResourceType**: EResourceType_None
- **m_ShopStatDisplay**:
  - **m_eWeaponStatsDisplay**:
    - **m_vecDisplayStats**:
      - EBulletDamage
      - EBaseWeaponDamageIncrease
      - ERoundsPerSecond
      - EFireRate
      - EClipSize
      - EClipSizeIncrease
      - EReloadTime
      - EReloadSpeed
      - EBulletSpeed
      - EBulletSpeedIncrease
      - EBulletLifesteal
    - **m_vecOtherDisplayStats**:
      - ELightMeleeDamage
      - EHeavyMeleeDamage
    - **m_eWeaponAttributes**: EWeaponAttribute_RapidFire | EWeaponAttribute_CloseRange
    - **m_strWeaponImage**: panorama:"file://{images}/heroes/guns/haze_gun.psd"
  - **m_eVitalityStatsDisplay**:
    - **m_vecDisplayStats**:
      - EMaxHealth
      - EBaseHealthRegen
      - EBulletArmorDamageReduction
      - ETechArmorDamageReduction
      - EBulletShieldHealth
      - ETechShieldHealth
      - ECritDamageReceivedScale
    - **m_vecOtherDisplayStats**:
      - EMaxMoveSpeed
      - ESprintSpeed
      - EStaminaCooldown
      - EStaminaRegenIncrease
      - EStamina
  - **m_eSpiritStatsDisplay**:
    - **m_vecDisplayStats**:
      - ETechCooldown
      - ETechDuration
      - ETechRange
      - ETechLifesteal
      - EMaxChargesIncrease
      - ETechCooldownBetweenChargeUses
- **_base**: hero_base
- **m_bNewPlayerRecommended**: True
- **m_bLaneTestingRecommended**: True
- **m_strSelectionImage**: panorama:"file://{images}/heroes/haze.psd"
- **m_strIconImageSmall**: panorama:"file://{images}/heroes/haze_sm.psd"
- **m_strMinimapImage**: panorama:"file://{images}/heroes/haze_mm.psd"
- **m_strUIAnimGraph**: resource_name:"models/heroes_staging/haze/ui_haze.vanmgrph"
- **m_strWIPModelName**: resource_name:"models/heroes_staging/haze_v2/haze.vmdl"
- **m_strDeathSound**: soundevent:"Haze.Death"
- **m_hGameSoundEventScript**: resource_name:"soundevents/hero/haze.vsndevts"
- **m_hVOEventScript**: resource_name:"soundevents/vo/vo_hero_haze.vsndevts"
- **m_strRosterSelectedSound**: soundevent:"Haze.VO.HeroPick"
- **m_strIconHeroCard**: panorama:"file://{images}/heroes/haze_card.psd"
- **m_hGeneratedVOEventScript**: resource_name:"soundevents/vo/generated_vo_hero_haze.vsndevts"
- **m_strRosterRemovedSound**: soundevent:"Haze.VO.HeroRemove"
- **m_strTopBarImage**: panorama:"file://{images}/hud/hero_portraits/haze_hud.psd"
- **m_RecommendedUpgrades**:
  - upgrade_endurance
  - upgrade_clip_size
  - upgrade_improved_spirit
  - upgrade_vampire
  - upgrade_slowing_bullets
  - upgrade_blitz_bullets
  - upgrade_regenerating_bullet_shield
  - upgrade_magic_shield
  - upgrade_burst_fire
  - upgrade_bullet_armor_reduction_aura
  - upgrade_chonky
  - upgrade_inhibitor
  - upgrade_silencer
  - upgrade_critshot
- **m_strUIPortraitMap**: maps/ui/hero_prefabs/haze.vmap
- **m_strTopBarVertical**: panorama:"file://{images}/heroes/haze_vertical.psd"
- **m_flStepSoundTimeSprinting**: 0.266
- **m_strUIShoppingMap**: maps/ui/hero_shop/haze_shop.vmap
- **m_strUIShopAnimGraph**: resource_name:"models/heroes_staging/haze/ui_shop_haze.vanmgrph"

---

# Hero: hero_astro

- **_class**: CitadelHeroData_t
- **m_bPlayerSelectable**: True
- **m_bDisabled**: False
- **m_bInDevelopment**: True
- **m_bNeedsTesting**: False
- **m_bAssignedPlayersOnly**: False
- **m_bBotSelectable**: False
- **m_bLimitedTesting**: False
- **m_nComplexity**: 3
- **m_nReadability**: 2
- **m_HeroID**: 14
- **m_strModelName**: resource_name:"models/heroes_staging/astro/astro.vmdl"
- **m_hDamageTakenParticle**: resource_name:"particles/generic/player_damage_screen.vpcf"
- **m_hGroundDamageTakenParticle**: resource_name:"particles/generic/player_ground_damage_screen.vpcf"
- **m_hDeathParticle**: resource_name:"particles/generic/player_death_screen.vpcf"
- **m_hLowHealthParticle**: resource_name:"particles/generic/player_low_health_screen.vpcf"
- **m_hRespawnParticle**: resource_name:"particles/generic/player_respawn_deploy.vpcf"
- **m_nModelSkin**: 0
- **m_mapStartingStats**:
  - **EMaxMoveSpeed**: 8
  - **ESprintSpeed**: 0
  - **ECrouchSpeed**: 4.75
  - **EMoveAcceleration**: 4
  - **ELightMeleeDamage**: 63
  - **EHeavyMeleeDamage**: 116
  - **EMaxHealth**: 625
  - **EWeaponPower**: 0
  - **EReloadSpeed**: 1
  - **EWeaponPowerScale**: 1
  - **EProcBuildUpRateScale**: 1
  - **EStamina**: 2
  - **EBaseHealthRegen**: 2.0
  - **EStaminaRegenPerSecond**: 0.2
  - **EAbilityResourceMax**: 0
  - **EAbilityResourceRegenPerSecond**: 0
  - **ECritDamageReceivedScale**: 1.0
  - **ETechDuration**: 1
  - **ETechRange**: 1
- **m_flCollisionRadius**: 20
- **m_flCollisionHeight**: 80
- **m_flStepHeight**: 32
- **m_mapBoundAbilities**:
  - **ESlot_Weapon_Primary**: citadel_weapon_astro_set
  - **ESlot_Weapon_Melee**: ability_melee_astro
  - **ESlot_Ability_Mantle**: citadel_ability_mantle
  - **ESlot_Ability_Jump**: citadel_ability_jump
  - **ESlot_Ability_Slide**: citadel_ability_slide
  - **ESlot_Ability_ZipLine**: citadel_ability_zip_line
  - **ESlot_Ability_ZipLineBoost**: citadel_ability_zipline_boost
  - **ESlot_Ability_Innate_1**: citadel_ability_dash
  - **ESlot_Ability_Innate_2**: citadel_ability_sprint
  - **ESlot_Ability_Innate_3**: citadel_ability_melee_parry
  - **ESlot_Signature_1**: ability_explosive_barrel
  - **ESlot_Signature_2**: ability_bounce_pad
  - **ESlot_Signature_3**: ability_hat_trick
  - **ESlot_Signature_4**: ability_gravity_lasso
- **m_mapItemSlotInfo**:
  - **EItemSlotType_WeaponMod**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
  - **EItemSlotType_Armor**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
  - **EItemSlotType_Tech**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
- **m_mapPurchaseBonuses**:
  - **EItemSlotType_WeaponMod**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 6 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 2 | 10 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 3 | 14 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 4 | 18 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
  - **EItemSlotType_Armor**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 11 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 2 | 14 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 3 | 17 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 4 | 20 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
  - **EItemSlotType_Tech**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 4 | MODIFIER_VALUE_TECH_POWER |
    | 2 | 8 | MODIFIER_VALUE_TECH_POWER |
    | 3 | 12 | MODIFIER_VALUE_TECH_POWER |
    | 4 | 16 | MODIFIER_VALUE_TECH_POWER |
- **m_mapLevelInfo**:
  - **1**:
    - **m_unRequiredGold**: 0
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **2**:
    - **m_unRequiredGold**: 400
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
      - **EAbilityPoints**: 1
  - **3**:
    - **m_unRequiredGold**: 800
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **4**:
    - **m_unRequiredGold**: 1200
    - **m_bUseStandardUpgrade**: True
  - **5**:
    - **m_unRequiredGold**: 1500
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **6**:
    - **m_unRequiredGold**: 2200
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **7**:
    - **m_unRequiredGold**: 3000
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **8**:
    - **m_unRequiredGold**: 4500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **9**:
    - **m_unRequiredGold**: 6000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **10**:
    - **m_unRequiredGold**: 7500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **11**:
    - **m_unRequiredGold**: 9000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **12**:
    - **m_unRequiredGold**: 10500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **13**:
    - **m_unRequiredGold**: 12000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **14**:
    - **m_unRequiredGold**: 13000
    - **m_bUseStandardUpgrade**: True
  - **15**:
    - **m_unRequiredGold**: 14000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **16**:
    - **m_unRequiredGold**: 15000
    - **m_bUseStandardUpgrade**: True
  - **17**:
    - **m_unRequiredGold**: 16000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **18**:
    - **m_unRequiredGold**: 18000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **19**:
    - **m_unRequiredGold**: 20000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **20**:
    - **m_unRequiredGold**: 22000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **21**:
    - **m_unRequiredGold**: 24000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **22**:
    - **m_unRequiredGold**: 27000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **23**:
    - **m_unRequiredGold**: 30000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **24**:
    - **m_unRequiredGold**: 33000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **25**:
    - **m_unRequiredGold**: 36000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **26**:
    - **m_unRequiredGold**: 39000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **27**:
    - **m_unRequiredGold**: 42000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **28**:
    - **m_unRequiredGold**: 45000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **29**:
    - **m_unRequiredGold**: 48000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
- **m_hFootstepSounds**: sweetener_default
- **m_strFootstepSoundEventDefault**: soundevent:"Astro.Footstep"
- **m_flStealthSpeedMetersPerSecond**: 4
- **m_flFootstepSoundTravelDistanceMeters**: 20
- **m_flStepSoundTime**: 0.3
- **m_vecAnimGraphDefaultValueOverrides**:
  | m_strParamName | m_strParamValue |
  | --- | --- |
  | e_SWITCH_4wayRoll_ON/OFF | 0 |
  | e_SWITCH_Recoil_ON/OFF | 0 |
  | e_SWITCH_ZiplinePhysicsSway_ON/OFF | 0 |
  | e_SWITCH_ShootStyle | 0 |
- **m_strLastHitSound**: soundevent:"LastHit.Default"
- **m_strLowHealthSound**: soundevent:"PlayerAlert.LowHealth"
- **m_colorUI**:
  - 142
  - 76
  - 49
- **m_colorGlowFriendly**:
  - 255
  - 239
  - 215
- **m_colorGlowEnemy**:
  - 255
  - 0
  - 0
- **m_colorGlowTeam1**:
  - 231
  - 182
  - 89
- **m_colorGlowTeam2**:
  - 91
  - 121
  - 230
- **m_vecAmbientParticleSettings**:
  | m_eAttachmentType | m_nCP |
  | --- | --- |
  | PATTACH_ABSORIGIN_FOLLOW | 0 |
  | PATTACH_POINT_FOLLOW | 1 |
- **m_heroStatsUI**:
  - **m_vecDisplayStats**:
    | m_eStatType | m_eStatCategory |
    | --- | --- |
    | EMaxHealth | ECitadelStat_Vitality |
    | EBaseHealthRegen | ECitadelStat_Vitality |
    | EBulletArmorDamageReduction | ECitadelStat_Vitality |
    | ETechArmorDamageReduction | ECitadelStat_Vitality |
    | ETechPower | ECitadelStat_Spirit |
    | EWeaponDPS | ECitadelStat_Weapon |
    | EBulletDamage | ECitadelStat_Weapon |
    | EClipSize | ECitadelStat_Weapon |
    | ERoundsPerSecond | ECitadelStat_Weapon |
    | ELightMeleeDamage | ECitadelStat_Weapon |
    | EHeavyMeleeDamage | ECitadelStat_Weapon |
    | EMaxMoveSpeed | ECitadelStat_Vitality |
    | ESprintSpeed | ECitadelStat_Vitality |
    | EStamina | ECitadelStat_Vitality |
  - **m_eWeaponStatDisplay**: EMeleeDamage_DEPRECATED
- **m_mapScalingStats**:
- **m_heroStatsDisplay**:
  - **m_vecHealthHeaderStats**:
    - EMaxHealth
    - EBaseHealthRegen
  - **m_vecHealthStats**:
    - EBulletArmorDamageReduction
    - ETechArmorDamageReduction
    - EBulletShieldHealth
    - ETechShieldHealth
    - EBulletLifesteal
    - ETechLifesteal
    - EMaxMoveSpeed
    - ESprintSpeed
    - EStamina
    - EHealingOutput
  - **m_vecWeaponHeaderStats**:
    - EWeaponDPS
    - EBulletDamage
  - **m_vecWeaponStats**:
    - ELightMeleeDamage
    - EHeavyMeleeDamage
    - EFireRate
    - EClipSize
  - **m_vecMagicHeaderStats**:
    - ETechPower
  - **m_vecMagicStats**:
    - ETechCooldown
    - ETechRange
    - ETechDuration
- **m_mapStandardLevelUpUpgrades**:
  - **MODIFIER_VALUE_BASE_BULLET_DAMAGE_FROM_LEVEL**: 1.9
  - **MODIFIER_VALUE_BASE_MELEE_DAMAGE_FROM_LEVEL**: 3.4
  - **MODIFIER_VALUE_BASE_HEALTH_FROM_LEVEL**: 33.0
  - **MODIFIER_VALUE_TECH_DAMAGE_PERCENT**: 0.0
  - **MODIFIER_VALUE_BULLET_ARMOR_DAMAGE_RESIST**: 0.0
- **m_eAbilityResourceType**: EResourceType_None
- **m_ShopStatDisplay**:
  - **m_eWeaponStatsDisplay**:
    - **m_vecDisplayStats**:
      - EBulletDamage
      - EBaseWeaponDamageIncrease
      - ERoundsPerSecond
      - EFireRate
      - EClipSize
      - EClipSizeIncrease
      - EReloadTime
      - EReloadSpeed
      - EBulletSpeed
      - EBulletSpeedIncrease
      - EBulletLifesteal
    - **m_vecOtherDisplayStats**:
      - ELightMeleeDamage
      - EHeavyMeleeDamage
    - **m_eWeaponAttributes**: EWeaponAttribute_MediumRange | EWeaponAttribute_HeavyHitter
  - **m_eVitalityStatsDisplay**:
    - **m_vecDisplayStats**:
      - EMaxHealth
      - EBaseHealthRegen
      - EBulletArmorDamageReduction
      - ETechArmorDamageReduction
      - EBulletShieldHealth
      - ETechShieldHealth
      - ECritDamageReceivedScale
    - **m_vecOtherDisplayStats**:
      - EMaxMoveSpeed
      - ESprintSpeed
      - EStaminaCooldown
      - EStaminaRegenIncrease
      - EStamina
  - **m_eSpiritStatsDisplay**:
    - **m_vecDisplayStats**:
      - ETechCooldown
      - ETechDuration
      - ETechRange
      - ETechLifesteal
      - EMaxChargesIncrease
      - ETechCooldownBetweenChargeUses
- **_base**: hero_base
- **m_strSelectionImage**: panorama:"file://{images}/heroes/astro.psd"
- **m_strIconImageSmall**: panorama:"file://{images}/heroes/astro_sm.psd"
- **m_strMinimapImage**: panorama:"file://{images}/heroes/astro_mm.psd"
- **m_strUIAnimGraph**: resource_name:"models/heroes_staging/astro/ui_astro.vanmgrph"
- **m_strDeathSound**: soundevent:"Astro.Death"
- **m_hGameSoundEventScript**: resource_name:"soundevents/hero/astro.vsndevts"
- **m_hVOEventScript**: resource_name:"soundevents/vo/vo_hero_astro.vsndevts"
- **m_strRosterSelectedSound**: soundevent:"Holliday.VO.HeroPick"
- **m_strIconHeroCard**: panorama:"file://{images}/heroes/astro_card.psd"
- **m_hGeneratedVOEventScript**: resource_name:"soundevents/vo/generated_vo_hero_astro.vsndevts"
- **m_strRosterRemovedSound**: soundevent:"Holliday.VO.HeroRemove"
- **m_strTopBarImage**: panorama:"file://{images}/hud/hero_portraits/astro_hud.psd"
- **m_strUIPortraitMap**: maps/ui/hero_prefabs/astro.vmap
- **m_strTopBarVertical**: panorama:"file://{images}/heroes/astro_vertical.psd"
- **m_flStepSoundTimeSprinting**: 0.27
- **m_strUIShopAnimGraph**: resource_name:"models/heroes_staging/astro/ui_shop_astro.vanmgrph"
- **m_strUIShoppingMap**: maps/ui/hero_shop/astro_shop.vmap

---

# Hero: hero_bebop

- **_class**: CitadelHeroData_t
- **m_bPlayerSelectable**: True
- **m_bDisabled**: False
- **m_bInDevelopment**: False
- **m_bNeedsTesting**: False
- **m_bAssignedPlayersOnly**: False
- **m_bBotSelectable**: True
- **m_bLimitedTesting**: False
- **m_nComplexity**: 2
- **m_nReadability**: 2
- **m_HeroID**: 15
- **m_strModelName**: resource_name:"models/heroes_staging/bebop/bebop.vmdl"
- **m_hDamageTakenParticle**: resource_name:"particles/generic/player_damage_screen.vpcf"
- **m_hGroundDamageTakenParticle**: resource_name:"particles/generic/player_ground_damage_screen.vpcf"
- **m_hDeathParticle**: resource_name:"particles/generic/player_death_screen.vpcf"
- **m_hLowHealthParticle**: resource_name:"particles/generic/player_low_health_screen.vpcf"
- **m_hRespawnParticle**: resource_name:"particles/generic/player_respawn_deploy.vpcf"
- **m_nModelSkin**: 0
- **m_mapStartingStats**:
  - **EMaxMoveSpeed**: 6.25
  - **ESprintSpeed**: 3
  - **ECrouchSpeed**: 4.75
  - **EMoveAcceleration**: 4
  - **ELightMeleeDamage**: 63
  - **EHeavyMeleeDamage**: 116
  - **EMaxHealth**: 650.0
  - **EWeaponPower**: 0
  - **EReloadSpeed**: 1
  - **EWeaponPowerScale**: 1
  - **EProcBuildUpRateScale**: 1
  - **EStamina**: 3
  - **EBaseHealthRegen**: 3.0
  - **EStaminaRegenPerSecond**: 0.2
  - **EAbilityResourceMax**: 0
  - **EAbilityResourceRegenPerSecond**: 0
  - **ECritDamageReceivedScale**: 1.0
  - **ETechDuration**: 1
  - **ETechRange**: 1
  - **EBulletArmorDamageReduction**: 10.0
- **m_flCollisionRadius**: 20
- **m_flCollisionHeight**: 80
- **m_flStepHeight**: 32
- **m_mapBoundAbilities**:
  - **ESlot_Weapon_Primary**: citadel_weapon_bebop_set
  - **ESlot_Weapon_Melee**: citadel_ability_melee_bebop
  - **ESlot_Ability_Mantle**: citadel_ability_mantle
  - **ESlot_Ability_Jump**: citadel_ability_jump
  - **ESlot_Ability_Slide**: citadel_ability_slide
  - **ESlot_Ability_ZipLine**: citadel_ability_zip_line
  - **ESlot_Ability_ZipLineBoost**: citadel_ability_zipline_boost
  - **ESlot_Ability_Innate_1**: citadel_ability_dash
  - **ESlot_Ability_Innate_2**: citadel_ability_sprint
  - **ESlot_Ability_Innate_3**: citadel_ability_melee_parry
  - **ESlot_Signature_1**: citadel_ability_uppercut
  - **ESlot_Signature_2**: citadel_ability_sticky_bomb
  - **ESlot_Signature_3**: citadel_ability_hook
  - **ESlot_Signature_4**: citadel_ability_bebop_laser_beam
- **m_mapItemSlotInfo**:
  - **EItemSlotType_WeaponMod**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
  - **EItemSlotType_Armor**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
  - **EItemSlotType_Tech**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
- **m_mapPurchaseBonuses**:
  - **EItemSlotType_WeaponMod**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 6 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 2 | 10 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 3 | 14 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 4 | 18 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
  - **EItemSlotType_Armor**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 11 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 2 | 14 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 3 | 17 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 4 | 20 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
  - **EItemSlotType_Tech**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 4 | MODIFIER_VALUE_TECH_POWER |
    | 2 | 8 | MODIFIER_VALUE_TECH_POWER |
    | 3 | 12 | MODIFIER_VALUE_TECH_POWER |
    | 4 | 16 | MODIFIER_VALUE_TECH_POWER |
- **m_mapLevelInfo**:
  - **1**:
    - **m_unRequiredGold**: 0
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **2**:
    - **m_unRequiredGold**: 400
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
      - **EAbilityPoints**: 1
  - **3**:
    - **m_unRequiredGold**: 800
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **4**:
    - **m_unRequiredGold**: 1200
    - **m_bUseStandardUpgrade**: True
  - **5**:
    - **m_unRequiredGold**: 1500
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **6**:
    - **m_unRequiredGold**: 2200
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **7**:
    - **m_unRequiredGold**: 3000
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **8**:
    - **m_unRequiredGold**: 4500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **9**:
    - **m_unRequiredGold**: 6000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **10**:
    - **m_unRequiredGold**: 7500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **11**:
    - **m_unRequiredGold**: 9000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **12**:
    - **m_unRequiredGold**: 10500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **13**:
    - **m_unRequiredGold**: 12000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **14**:
    - **m_unRequiredGold**: 13000
    - **m_bUseStandardUpgrade**: True
  - **15**:
    - **m_unRequiredGold**: 14000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **16**:
    - **m_unRequiredGold**: 15000
    - **m_bUseStandardUpgrade**: True
  - **17**:
    - **m_unRequiredGold**: 16000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **18**:
    - **m_unRequiredGold**: 18000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **19**:
    - **m_unRequiredGold**: 20000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **20**:
    - **m_unRequiredGold**: 22000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **21**:
    - **m_unRequiredGold**: 24000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **22**:
    - **m_unRequiredGold**: 27000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **23**:
    - **m_unRequiredGold**: 30000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **24**:
    - **m_unRequiredGold**: 33000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **25**:
    - **m_unRequiredGold**: 36000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **26**:
    - **m_unRequiredGold**: 39000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **27**:
    - **m_unRequiredGold**: 42000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **28**:
    - **m_unRequiredGold**: 45000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **29**:
    - **m_unRequiredGold**: 48000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
- **m_hFootstepSounds**: sweetener_default
- **m_strFootstepSoundEventDefault**: soundevent:"Bebop.Footstep.Multi"
- **m_flStealthSpeedMetersPerSecond**: 4
- **m_flFootstepSoundTravelDistanceMeters**: 20
- **m_flStepSoundTime**: 0.372
- **m_vecAnimGraphDefaultValueOverrides**:
  | m_strParamName | m_strParamValue |
  | --- | --- |
  | e_SWITCH_4wayRoll_ON/OFF | 0 |
  | e_SWITCH_Recoil_ON/OFF | 1 |
  | e_SWITCH_ZiplinePhysicsSway_ON/OFF | 0 |
  | e_SWITCH_ShootStyle | 0 |
- **m_strLastHitSound**: soundevent:"LastHit.Default"
- **m_strLowHealthSound**: soundevent:"PlayerAlert.LowHealth"
- **m_colorUI**:
  - 159
  - 71
  - 52
- **m_colorGlowFriendly**:
  - 255
  - 239
  - 215
- **m_colorGlowEnemy**:
  - 255
  - 0
  - 0
- **m_colorGlowTeam1**:
  - 231
  - 182
  - 89
- **m_colorGlowTeam2**:
  - 91
  - 121
  - 230
- **m_vecAmbientParticleSettings**:
  | m_eAttachmentType | m_nCP |
  | --- | --- |
  | PATTACH_ABSORIGIN_FOLLOW | 0 |
  | PATTACH_POINT_FOLLOW | 1 |
- **m_heroStatsUI**:
  - **m_vecDisplayStats**:
    | m_eStatType | m_eStatCategory |
    | --- | --- |
    | EMaxHealth | ECitadelStat_Vitality |
    | EBaseHealthRegen | ECitadelStat_Vitality |
    | EBulletArmorDamageReduction | ECitadelStat_Vitality |
    | ETechArmorDamageReduction | ECitadelStat_Vitality |
    | ETechPower | ECitadelStat_Spirit |
    | EWeaponDPS | ECitadelStat_Weapon |
    | EBulletDamage | ECitadelStat_Weapon |
    | EClipSize | ECitadelStat_Weapon |
    | ERoundsPerSecond | ECitadelStat_Weapon |
    | ELightMeleeDamage | ECitadelStat_Weapon |
    | EHeavyMeleeDamage | ECitadelStat_Weapon |
    | EMaxMoveSpeed | ECitadelStat_Vitality |
    | ESprintSpeed | ECitadelStat_Vitality |
    | EStamina | ECitadelStat_Vitality |
  - **m_eWeaponStatDisplay**: EMeleeDamage_DEPRECATED
- **m_mapScalingStats**:
- **m_heroStatsDisplay**:
  - **m_vecHealthHeaderStats**:
    - EMaxHealth
    - EBaseHealthRegen
  - **m_vecHealthStats**:
    - EBulletArmorDamageReduction
    - ETechArmorDamageReduction
    - EBulletShieldHealth
    - ETechShieldHealth
    - EBulletLifesteal
    - ETechLifesteal
    - EMaxMoveSpeed
    - ESprintSpeed
    - EStamina
    - EHealingOutput
  - **m_vecWeaponHeaderStats**:
    - EWeaponDPS
    - EBulletDamage
  - **m_vecWeaponStats**:
    - ELightMeleeDamage
    - EHeavyMeleeDamage
    - EFireRate
    - EClipSize
  - **m_vecMagicHeaderStats**:
    - ETechPower
  - **m_vecMagicStats**:
    - ETechCooldown
    - ETechRange
    - ETechDuration
- **m_mapStandardLevelUpUpgrades**:
  - **MODIFIER_VALUE_BASE_BULLET_DAMAGE_FROM_LEVEL**: 0.373
  - **MODIFIER_VALUE_BASE_MELEE_DAMAGE_FROM_LEVEL**: 3.4
  - **MODIFIER_VALUE_BASE_HEALTH_FROM_LEVEL**: 41.0
  - **MODIFIER_VALUE_TECH_DAMAGE_PERCENT**: 0.0
  - **MODIFIER_VALUE_BULLET_ARMOR_DAMAGE_RESIST**: 1.6
  - **MODIFIER_VALUE_BONUS_ATTACK_RANGE**: 98.4252
- **m_eAbilityResourceType**: EResourceType_None
- **m_ShopStatDisplay**:
  - **m_eWeaponStatsDisplay**:
    - **m_vecDisplayStats**:
      - EBulletDamage
      - EBaseWeaponDamageIncrease
      - ERoundsPerSecond
      - EFireRate
      - EClipSize
      - EClipSizeIncrease
      - EReloadTime
      - EReloadSpeed
      - EBulletSpeed
      - EBulletSpeedIncrease
      - EBulletLifesteal
    - **m_vecOtherDisplayStats**:
      - ELightMeleeDamage
      - EHeavyMeleeDamage
    - **m_eWeaponAttributes**: EWeaponAttribute_BeamWeapon | EWeaponAttribute_MediumRange
    - **m_strWeaponImage**: panorama:"file://{images}/heroes/guns/bebop_gun.psd"
    - **m_strWeaponDescLocString**: #citadel_weapon_hero_bebop_set_desc
  - **m_eVitalityStatsDisplay**:
    - **m_vecDisplayStats**:
      - EMaxHealth
      - EBaseHealthRegen
      - EBulletArmorDamageReduction
      - ETechArmorDamageReduction
      - EBulletShieldHealth
      - ETechShieldHealth
      - ECritDamageReceivedScale
    - **m_vecOtherDisplayStats**:
      - EMaxMoveSpeed
      - ESprintSpeed
      - EStaminaCooldown
      - EStaminaRegenIncrease
      - EStamina
  - **m_eSpiritStatsDisplay**:
    - **m_vecDisplayStats**:
      - ETechCooldown
      - ETechDuration
      - ETechRange
      - ETechLifesteal
      - EMaxChargesIncrease
      - ETechCooldownBetweenChargeUses
- **_base**: hero_base
- **m_bNewPlayerRecommended**: True
- **m_bLaneTestingRecommended**: True
- **m_strSelectionImage**: panorama:"file://{images}/heroes/bebop.psd"
- **m_strIconImageSmall**: panorama:"file://{images}/heroes/bebop_sm.psd"
- **m_strMinimapImage**: panorama:"file://{images}/heroes/bebop_mm.psd"
- **m_strUIAnimGraph**: resource_name:"models/heroes_staging/bebop/ui_bebop.vanmgrph"
- **m_strMovementLoop**: soundevent:""
- **m_strDeathSound**: soundevent:"Bebop.Death"
- **m_hGameSoundEventScript**: resource_name:"soundevents/hero/bebop.vsndevts"
- **m_hVOEventScript**: resource_name:"soundevents/vo/vo_hero_bebop.vsndevts"
- **m_strRosterSelectedSound**: soundevent:"Bebop.VO.HeroPick"
- **m_strIconHeroCard**: panorama:"file://{images}/heroes/bebop_card.psd"
- **m_hGeneratedVOEventScript**: resource_name:"soundevents/vo/generated_vo_hero_bebop.vsndevts"
- **m_strRosterRemovedSound**: soundevent:"Bebop.VO.HeroRemove"
- **m_strTopBarImage**: panorama:"file://{images}/hud/hero_portraits/bebop_hud.psd"
- **m_RecommendedUpgrades**:
  - upgrade_clip_size
  - upgrade_endurance
  - upgrade_magic_burst
  - upgrade_non_player_bonus
  - upgrade_acolytes_glove
  - upgrade_improved_spirit
  - upgrade_sprint_booster
  - upgrade_soaring_spirit
  - upgrade_tech_defense_shredders
  - upgrade_blitz_bullets
  - upgrade_tech_armor
  - upgrade_magic_shock
  - upgrade_intensifying_clip
  - upgrade_chonky
  - upgrade_mega_spirit
- **m_strUIPortraitMap**: maps/ui/hero_prefabs/bebop.vmap
- **m_strTopBarVertical**: panorama:"file://{images}/heroes/bebop_vertical.psd"
- **m_flStepSoundTimeSprinting**: 0.345
- **m_strUIShoppingMap**: maps/ui/hero_shop/bebop_shop.vmap
- **m_strUIShopAnimGraph**: resource_name:"models/heroes_staging/bebop/ui_shop_bebop.vanmgrph"

---

# Hero: hero_nano

- **_class**: CitadelHeroData_t
- **m_bPlayerSelectable**: True
- **m_bDisabled**: True
- **m_bInDevelopment**: True
- **m_bNeedsTesting**: False
- **m_bAssignedPlayersOnly**: False
- **m_bBotSelectable**: True
- **m_bLimitedTesting**: False
- **m_nComplexity**: 1
- **m_nReadability**: 4
- **m_HeroID**: 16
- **m_strModelName**: resource_name:"models/heroes_staging/nano/nano_v2/nano.vmdl"
- **m_hDamageTakenParticle**: resource_name:"particles/generic/player_damage_screen.vpcf"
- **m_hGroundDamageTakenParticle**: resource_name:"particles/generic/player_ground_damage_screen.vpcf"
- **m_hDeathParticle**: resource_name:"particles/generic/player_death_screen.vpcf"
- **m_hLowHealthParticle**: resource_name:"particles/generic/player_low_health_screen.vpcf"
- **m_hRespawnParticle**: resource_name:"particles/generic/player_respawn_deploy.vpcf"
- **m_nModelSkin**: 0
- **m_mapStartingStats**:
  - **EMaxMoveSpeed**: 7
  - **ESprintSpeed**: 0
  - **ECrouchSpeed**: 4.75
  - **EMoveAcceleration**: 4
  - **ELightMeleeDamage**: 63
  - **EHeavyMeleeDamage**: 116
  - **EMaxHealth**: 550
  - **EWeaponPower**: 0
  - **EReloadSpeed**: 1
  - **EWeaponPowerScale**: 1
  - **EProcBuildUpRateScale**: 1
  - **EStamina**: 3
  - **EBaseHealthRegen**: 2.0
  - **EStaminaRegenPerSecond**: 0.2
  - **EAbilityResourceMax**: 0
  - **EAbilityResourceRegenPerSecond**: 0
  - **ECritDamageReceivedScale**: 1.0
  - **ETechDuration**: 1
  - **ETechRange**: 1
- **m_flCollisionRadius**: 20
- **m_flCollisionHeight**: 80
- **m_flStepHeight**: 32
- **m_mapBoundAbilities**:
  - **ESlot_Weapon_Primary**: citadel_weapon_nano_set
  - **ESlot_Weapon_Melee**: ability_melee_nano
  - **ESlot_Ability_Mantle**: citadel_ability_mantle
  - **ESlot_Ability_Jump**: citadel_ability_jump
  - **ESlot_Ability_Slide**: citadel_ability_slide
  - **ESlot_Ability_ZipLine**: citadel_ability_zip_line
  - **ESlot_Ability_ZipLineBoost**: citadel_ability_zipline_boost
  - **ESlot_Ability_Innate_1**: citadel_ability_dash
  - **ESlot_Ability_Innate_2**: citadel_ability_sprint
  - **ESlot_Ability_Innate_3**: citadel_ability_melee_parry
  - **ESlot_Signature_1**: ability_perched_predator
  - **ESlot_Signature_2**: ability_nano_pounce
  - **ESlot_Signature_3**: ability_nano_proximity_ritual
  - **ESlot_Signature_4**: ability_nano_ult_shadow
- **m_mapItemSlotInfo**:
  - **EItemSlotType_WeaponMod**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
  - **EItemSlotType_Armor**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
  - **EItemSlotType_Tech**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
- **m_mapPurchaseBonuses**:
  - **EItemSlotType_WeaponMod**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 6 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 2 | 10 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 3 | 14 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 4 | 18 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
  - **EItemSlotType_Armor**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 11 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 2 | 14 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 3 | 17 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 4 | 20 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
  - **EItemSlotType_Tech**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 4 | MODIFIER_VALUE_TECH_POWER |
    | 2 | 8 | MODIFIER_VALUE_TECH_POWER |
    | 3 | 12 | MODIFIER_VALUE_TECH_POWER |
    | 4 | 16 | MODIFIER_VALUE_TECH_POWER |
- **m_mapLevelInfo**:
  - **1**:
    - **m_unRequiredGold**: 0
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **2**:
    - **m_unRequiredGold**: 400
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
      - **EAbilityPoints**: 1
  - **3**:
    - **m_unRequiredGold**: 800
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **4**:
    - **m_unRequiredGold**: 1200
    - **m_bUseStandardUpgrade**: True
  - **5**:
    - **m_unRequiredGold**: 1500
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **6**:
    - **m_unRequiredGold**: 2200
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **7**:
    - **m_unRequiredGold**: 3000
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **8**:
    - **m_unRequiredGold**: 4500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **9**:
    - **m_unRequiredGold**: 6000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **10**:
    - **m_unRequiredGold**: 7500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **11**:
    - **m_unRequiredGold**: 9000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **12**:
    - **m_unRequiredGold**: 10500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **13**:
    - **m_unRequiredGold**: 12000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **14**:
    - **m_unRequiredGold**: 13000
    - **m_bUseStandardUpgrade**: True
  - **15**:
    - **m_unRequiredGold**: 14000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **16**:
    - **m_unRequiredGold**: 15000
    - **m_bUseStandardUpgrade**: True
  - **17**:
    - **m_unRequiredGold**: 16000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **18**:
    - **m_unRequiredGold**: 18000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **19**:
    - **m_unRequiredGold**: 20000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **20**:
    - **m_unRequiredGold**: 22000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **21**:
    - **m_unRequiredGold**: 24000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **22**:
    - **m_unRequiredGold**: 27000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **23**:
    - **m_unRequiredGold**: 30000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **24**:
    - **m_unRequiredGold**: 33000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **25**:
    - **m_unRequiredGold**: 36000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **26**:
    - **m_unRequiredGold**: 39000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **27**:
    - **m_unRequiredGold**: 42000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **28**:
    - **m_unRequiredGold**: 45000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **29**:
    - **m_unRequiredGold**: 48000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
- **m_hFootstepSounds**: sweetener_default
- **m_strFootstepSoundEventDefault**: soundevent:"Nano.Footstep"
- **m_flStealthSpeedMetersPerSecond**: 4
- **m_flFootstepSoundTravelDistanceMeters**: 20
- **m_flStepSoundTime**: 0.325
- **m_vecAnimGraphDefaultValueOverrides**:
  | m_strParamName | m_strParamValue |
  | --- | --- |
  | e_SWITCH_4wayRoll_ON/OFF | 0 |
  | e_SWITCH_Recoil_ON/OFF | 0 |
  | e_SWITCH_ZiplinePhysicsSway_ON/OFF | 0 |
  | e_SWITCH_ShootStyle | 0 |
- **m_strLastHitSound**: soundevent:"LastHit.Default"
- **m_strLowHealthSound**: soundevent:"PlayerAlert.LowHealth"
- **m_colorUI**:
  - 98
  - 15
  - 214
- **m_colorGlowFriendly**:
  - 255
  - 239
  - 215
- **m_colorGlowEnemy**:
  - 255
  - 0
  - 0
- **m_colorGlowTeam1**:
  - 231
  - 182
  - 89
- **m_colorGlowTeam2**:
  - 91
  - 121
  - 230
- **m_vecAmbientParticleSettings**:
  | m_eAttachmentType | m_nCP |
  | --- | --- |
  | PATTACH_ABSORIGIN_FOLLOW | 0 |
  | PATTACH_POINT_FOLLOW | 1 |
- **m_heroStatsUI**:
  - **m_vecDisplayStats**:
    | m_eStatType | m_eStatCategory |
    | --- | --- |
    | EMaxHealth | ECitadelStat_Vitality |
    | EBaseHealthRegen | ECitadelStat_Vitality |
    | EBulletArmorDamageReduction | ECitadelStat_Vitality |
    | ETechArmorDamageReduction | ECitadelStat_Vitality |
    | ETechPower | ECitadelStat_Spirit |
    | EWeaponDPS | ECitadelStat_Weapon |
    | EBulletDamage | ECitadelStat_Weapon |
    | EClipSize | ECitadelStat_Weapon |
    | ERoundsPerSecond | ECitadelStat_Weapon |
    | ELightMeleeDamage | ECitadelStat_Weapon |
    | EHeavyMeleeDamage | ECitadelStat_Weapon |
    | EMaxMoveSpeed | ECitadelStat_Vitality |
    | ESprintSpeed | ECitadelStat_Vitality |
    | EStamina | ECitadelStat_Vitality |
  - **m_eWeaponStatDisplay**: EMeleeDamage_DEPRECATED
- **m_mapScalingStats**:
- **m_heroStatsDisplay**:
  - **m_vecHealthHeaderStats**:
    - EMaxHealth
    - EBaseHealthRegen
  - **m_vecHealthStats**:
    - EBulletArmorDamageReduction
    - ETechArmorDamageReduction
    - EBulletShieldHealth
    - ETechShieldHealth
    - EBulletLifesteal
    - ETechLifesteal
    - EMaxMoveSpeed
    - ESprintSpeed
    - EStamina
    - EHealingOutput
  - **m_vecWeaponHeaderStats**:
    - EWeaponDPS
    - EBulletDamage
  - **m_vecWeaponStats**:
    - ELightMeleeDamage
    - EHeavyMeleeDamage
    - EFireRate
    - EClipSize
  - **m_vecMagicHeaderStats**:
    - ETechPower
  - **m_vecMagicStats**:
    - ETechCooldown
    - ETechRange
    - ETechDuration
- **m_mapStandardLevelUpUpgrades**:
  - **MODIFIER_VALUE_BASE_BULLET_DAMAGE_FROM_LEVEL**: 0.159
  - **MODIFIER_VALUE_BASE_MELEE_DAMAGE_FROM_LEVEL**: 3.4
  - **MODIFIER_VALUE_BASE_HEALTH_FROM_LEVEL**: 41.0
  - **MODIFIER_VALUE_TECH_DAMAGE_PERCENT**: 0.0
  - **MODIFIER_VALUE_BULLET_ARMOR_DAMAGE_RESIST**: 0.0
- **m_eAbilityResourceType**: EResourceType_None
- **m_ShopStatDisplay**:
  - **m_eWeaponStatsDisplay**:
    - **m_vecDisplayStats**:
      - EBulletDamage
      - EBaseWeaponDamageIncrease
      - ERoundsPerSecond
      - EFireRate
      - EClipSize
      - EClipSizeIncrease
      - EReloadTime
      - EReloadSpeed
      - EBulletSpeed
      - EBulletSpeedIncrease
      - EBulletLifesteal
    - **m_vecOtherDisplayStats**:
      - ELightMeleeDamage
      - EHeavyMeleeDamage
  - **m_eVitalityStatsDisplay**:
    - **m_vecDisplayStats**:
      - EMaxHealth
      - EBaseHealthRegen
      - EBulletArmorDamageReduction
      - ETechArmorDamageReduction
      - EBulletShieldHealth
      - ETechShieldHealth
      - ECritDamageReceivedScale
    - **m_vecOtherDisplayStats**:
      - EMaxMoveSpeed
      - ESprintSpeed
      - EStaminaCooldown
      - EStaminaRegenIncrease
      - EStamina
  - **m_eSpiritStatsDisplay**:
    - **m_vecDisplayStats**:
      - ETechCooldown
      - ETechDuration
      - ETechRange
      - ETechLifesteal
      - EMaxChargesIncrease
      - ETechCooldownBetweenChargeUses
- **_base**: hero_base
- **m_strSelectionImage**: panorama:"file://{images}/heroes/nano.psd"
- **m_strIconImageSmall**: panorama:"file://{images}/heroes/nano_sm.psd"
- **m_strMinimapImage**: panorama:"file://{images}/heroes/nano_mm.psd"
- **m_strUIAnimGraph**: resource_name:"models/heroes_staging/nano/nano_v2/ui_nano.vanmgrph"
- **m_strDeathSound**: soundevent:"Nano.Death"
- **m_hGameSoundEventScript**: resource_name:"soundevents/hero/nano.vsndevts"
- **m_hVOEventScript**: resource_name:"soundevents/vo/vo_hero_nano.vsndevts"
- **m_strRosterSelectedSound**: soundevent:"Calico.VO.HeroPick"
- **m_strIconHeroCard**: panorama:"file://{images}/heroes/nano_card.psd"
- **m_strRosterRemovedSound**: soundevent:"Calico.VO.HeroRemove"
- **m_strTopBarImage**: panorama:"file://{images}/hud/hero_portraits/nano_hud.psd"
- **m_strUIPortraitMap**: maps/ui/hero_prefabs/nano.vmap
- **m_RecommendedUpgrades**:
  - upgrade_lifestrike_gauntlets
  - upgrade_acolytes_glove
  - upgrade_rapid_recharge
  - upgrade_close_range
  - upgrade_slowing_bullets
  - upgrade_kinetic_sash
  - upgrade_cardio_calibrator
  - upgrade_vampire
  - upgrade_regenerating_bullet_shield
  - upgrade_magic_shield
  - upgrade_boxing_glove
  - upgrade_close_quarter_combat
  - upgrade_toxic_bullets
  - upgrade_magic_burst
  - upgrade_tech_damage_pulse
  - upgrade_belt_fed_magazine
  - upgrade_superior_stamina
  - upgrade_damage_recycler
  - upgrade_tech_range
  - upgrade_mega_spirit
- **m_strTopBarVertical**: panorama:"file://{images}/heroes/nano_vertical.psd"
- **m_strUIShopAnimGraph**: resource_name:"models/heroes_staging/nano/nano_v2/ui_shop_nano.vanmgrph"
- **m_strUIShoppingMap**: maps/ui/hero_shop/nano_shop.vmap

---

# Hero: hero_orion

- **_class**: CitadelHeroData_t
- **m_bPlayerSelectable**: True
- **m_bDisabled**: False
- **m_bInDevelopment**: False
- **m_bNeedsTesting**: False
- **m_bAssignedPlayersOnly**: False
- **m_bBotSelectable**: True
- **m_bLimitedTesting**: False
- **m_nComplexity**: 2
- **m_nReadability**: 5
- **m_HeroID**: 17
- **m_strModelName**: resource_name:"models/heroes_staging/archer/archer.vmdl"
- **m_hDamageTakenParticle**: resource_name:"particles/generic/player_damage_screen.vpcf"
- **m_hGroundDamageTakenParticle**: resource_name:"particles/generic/player_ground_damage_screen.vpcf"
- **m_hDeathParticle**: resource_name:"particles/generic/player_death_screen.vpcf"
- **m_hLowHealthParticle**: resource_name:"particles/generic/player_low_health_screen.vpcf"
- **m_hRespawnParticle**: resource_name:"particles/generic/player_respawn_deploy.vpcf"
- **m_nModelSkin**: 0
- **m_mapStartingStats**:
  - **EMaxMoveSpeed**: 6
  - **ESprintSpeed**: 0
  - **ECrouchSpeed**: 4.75
  - **EMoveAcceleration**: 4
  - **ELightMeleeDamage**: 63
  - **EHeavyMeleeDamage**: 116
  - **EMaxHealth**: 550
  - **EWeaponPower**: 0
  - **EReloadSpeed**: 1
  - **EWeaponPowerScale**: 1
  - **EProcBuildUpRateScale**: 1
  - **EStamina**: 3
  - **EBaseHealthRegen**: 2.0
  - **EStaminaRegenPerSecond**: 0.2
  - **EAbilityResourceMax**: 0
  - **EAbilityResourceRegenPerSecond**: 0
  - **ECritDamageReceivedScale**: 1.0
  - **ETechDuration**: 1
  - **ETechRange**: 1
- **m_flCollisionRadius**: 20
- **m_flCollisionHeight**: 80
- **m_flStepHeight**: 32
- **m_mapBoundAbilities**:
  - **ESlot_Weapon_Primary**: citadel_weapon_archer_set
  - **ESlot_Weapon_Melee**: ability_melee_archer
  - **ESlot_Ability_Mantle**: citadel_ability_mantle
  - **ESlot_Ability_Jump**: citadel_ability_jump
  - **ESlot_Ability_Slide**: citadel_ability_slide
  - **ESlot_Ability_ZipLine**: citadel_ability_zip_line
  - **ESlot_Ability_ZipLineBoost**: citadel_ability_zipline_boost
  - **ESlot_Ability_Innate_1**: citadel_ability_dash
  - **ESlot_Ability_Innate_2**: citadel_ability_sprint
  - **ESlot_Ability_Innate_3**: citadel_ability_melee_parry
  - **ESlot_Signature_1**: ability_charged_shot
  - **ESlot_Signature_2**: ability_power_jump
  - **ESlot_Signature_3**: ability_immobilize_trap
  - **ESlot_Signature_4**: ability_guided_arrow
- **m_mapItemSlotInfo**:
  - **EItemSlotType_WeaponMod**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
  - **EItemSlotType_Armor**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
  - **EItemSlotType_Tech**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
- **m_mapPurchaseBonuses**:
  - **EItemSlotType_WeaponMod**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 6 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 2 | 10 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 3 | 14 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 4 | 18 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
  - **EItemSlotType_Armor**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 11 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 2 | 14 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 3 | 17 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 4 | 20 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
  - **EItemSlotType_Tech**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 4 | MODIFIER_VALUE_TECH_POWER |
    | 2 | 8 | MODIFIER_VALUE_TECH_POWER |
    | 3 | 12 | MODIFIER_VALUE_TECH_POWER |
    | 4 | 16 | MODIFIER_VALUE_TECH_POWER |
- **m_mapLevelInfo**:
  - **1**:
    - **m_unRequiredGold**: 0
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **2**:
    - **m_unRequiredGold**: 400
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
      - **EAbilityPoints**: 1
  - **3**:
    - **m_unRequiredGold**: 800
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **4**:
    - **m_unRequiredGold**: 1200
    - **m_bUseStandardUpgrade**: True
  - **5**:
    - **m_unRequiredGold**: 1500
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **6**:
    - **m_unRequiredGold**: 2200
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **7**:
    - **m_unRequiredGold**: 3000
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **8**:
    - **m_unRequiredGold**: 4500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **9**:
    - **m_unRequiredGold**: 6000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **10**:
    - **m_unRequiredGold**: 7500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **11**:
    - **m_unRequiredGold**: 9000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **12**:
    - **m_unRequiredGold**: 10500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **13**:
    - **m_unRequiredGold**: 12000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **14**:
    - **m_unRequiredGold**: 13000
    - **m_bUseStandardUpgrade**: True
  - **15**:
    - **m_unRequiredGold**: 14000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **16**:
    - **m_unRequiredGold**: 15000
    - **m_bUseStandardUpgrade**: True
  - **17**:
    - **m_unRequiredGold**: 16000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **18**:
    - **m_unRequiredGold**: 18000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **19**:
    - **m_unRequiredGold**: 20000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **20**:
    - **m_unRequiredGold**: 22000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **21**:
    - **m_unRequiredGold**: 24000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **22**:
    - **m_unRequiredGold**: 27000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **23**:
    - **m_unRequiredGold**: 30000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **24**:
    - **m_unRequiredGold**: 33000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **25**:
    - **m_unRequiredGold**: 36000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **26**:
    - **m_unRequiredGold**: 39000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **27**:
    - **m_unRequiredGold**: 42000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **28**:
    - **m_unRequiredGold**: 45000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **29**:
    - **m_unRequiredGold**: 48000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
- **m_hFootstepSounds**: sweetener_default
- **m_strFootstepSoundEventDefault**: soundevent:"Orion.Footstep"
- **m_flStealthSpeedMetersPerSecond**: 4
- **m_flFootstepSoundTravelDistanceMeters**: 20
- **m_flStepSoundTime**: 0.36
- **m_vecAnimGraphDefaultValueOverrides**:
  | m_strParamName | m_strParamValue |
  | --- | --- |
  | e_SWITCH_4wayRoll_ON/OFF | 0 |
  | e_SWITCH_Recoil_ON/OFF | 0 |
  | e_SWITCH_ZiplinePhysicsSway_ON/OFF | 0 |
  | e_SWITCH_ShootStyle | 0 |
- **m_strLastHitSound**: soundevent:"LastHit.Default"
- **m_strLowHealthSound**: soundevent:"PlayerAlert.LowHealth"
- **m_colorUI**:
  - 94
  - 176
  - 131
- **m_colorGlowFriendly**:
  - 255
  - 239
  - 215
- **m_colorGlowEnemy**:
  - 255
  - 0
  - 0
- **m_colorGlowTeam1**:
  - 231
  - 182
  - 89
- **m_colorGlowTeam2**:
  - 91
  - 121
  - 230
- **m_vecAmbientParticleSettings**:
  | m_eAttachmentType | m_nCP |
  | --- | --- |
  | PATTACH_ABSORIGIN_FOLLOW | 0 |
  | PATTACH_POINT_FOLLOW | 1 |
- **m_heroStatsUI**:
  - **m_vecDisplayStats**:
    | m_eStatType | m_eStatCategory |
    | --- | --- |
    | EMaxHealth | ECitadelStat_Vitality |
    | EBaseHealthRegen | ECitadelStat_Vitality |
    | EBulletArmorDamageReduction | ECitadelStat_Vitality |
    | ETechArmorDamageReduction | ECitadelStat_Vitality |
    | ETechPower | ECitadelStat_Spirit |
    | EWeaponDPS | ECitadelStat_Weapon |
    | EBulletDamage | ECitadelStat_Weapon |
    | EClipSize | ECitadelStat_Weapon |
    | ERoundsPerSecond | ECitadelStat_Weapon |
    | ELightMeleeDamage | ECitadelStat_Weapon |
    | EHeavyMeleeDamage | ECitadelStat_Weapon |
    | EMaxMoveSpeed | ECitadelStat_Vitality |
    | ESprintSpeed | ECitadelStat_Vitality |
    | EStamina | ECitadelStat_Vitality |
  - **m_eWeaponStatDisplay**: EMeleeDamage_DEPRECATED
- **m_mapScalingStats**:
  - **EMaxMoveSpeed**:
    - **eScalingStat**: ETechPower
    - **flScale**: 0.04
- **m_heroStatsDisplay**:
  - **m_vecHealthHeaderStats**:
    - EMaxHealth
    - EBaseHealthRegen
  - **m_vecHealthStats**:
    - EBulletArmorDamageReduction
    - ETechArmorDamageReduction
    - EBulletShieldHealth
    - ETechShieldHealth
    - EBulletLifesteal
    - ETechLifesteal
    - EMaxMoveSpeed
    - ESprintSpeed
    - EStamina
    - EHealingOutput
  - **m_vecWeaponHeaderStats**:
    - EWeaponDPS
    - EBulletDamage
  - **m_vecWeaponStats**:
    - ELightMeleeDamage
    - EHeavyMeleeDamage
    - EFireRate
    - EClipSize
  - **m_vecMagicHeaderStats**:
    - ETechPower
  - **m_vecMagicStats**:
    - ETechCooldown
    - ETechRange
    - ETechDuration
- **m_mapStandardLevelUpUpgrades**:
  - **MODIFIER_VALUE_BASE_BULLET_DAMAGE_FROM_LEVEL**: 1.46
  - **MODIFIER_VALUE_BASE_MELEE_DAMAGE_FROM_LEVEL**: 3.4
  - **MODIFIER_VALUE_BASE_HEALTH_FROM_LEVEL**: 27.0
  - **MODIFIER_VALUE_TECH_DAMAGE_PERCENT**: 0.0
  - **MODIFIER_VALUE_BULLET_ARMOR_DAMAGE_RESIST**: 0.0
- **m_eAbilityResourceType**: EResourceType_None
- **m_ShopStatDisplay**:
  - **m_eWeaponStatsDisplay**:
    - **m_vecDisplayStats**:
      - EBulletDamage
      - EBaseWeaponDamageIncrease
      - ERoundsPerSecond
      - EFireRate
      - EClipSize
      - EClipSizeIncrease
      - EReloadTime
      - EReloadSpeed
      - EBulletSpeed
      - EBulletSpeedIncrease
      - EBulletLifesteal
    - **m_vecOtherDisplayStats**:
      - ELightMeleeDamage
      - EHeavyMeleeDamage
    - **m_eWeaponAttributes**: EWeaponAttribute_MediumRange | EWeaponAttribute_HeavyHitter | EWeaponAttribute_Projectile
    - **m_strWeaponImage**: panorama:"file://{images}/heroes/guns/archer_gun.psd"
  - **m_eVitalityStatsDisplay**:
    - **m_vecDisplayStats**:
      - EMaxHealth
      - EBaseHealthRegen
      - EBulletArmorDamageReduction
      - ETechArmorDamageReduction
      - EBulletShieldHealth
      - ETechShieldHealth
      - ECritDamageReceivedScale
    - **m_vecOtherDisplayStats**:
      - EMaxMoveSpeed
      - ESprintSpeed
      - EStaminaCooldown
      - EStaminaRegenIncrease
      - EStamina
  - **m_eSpiritStatsDisplay**:
    - **m_vecDisplayStats**:
      - ETechCooldown
      - ETechDuration
      - ETechRange
      - ETechLifesteal
      - EMaxChargesIncrease
      - ETechCooldownBetweenChargeUses
- **_base**: hero_base
- **m_bNewPlayerRecommended**: True
- **m_bLaneTestingRecommended**: True
- **m_strSelectionImage**: panorama:"file://{images}/heroes/archer.psd"
- **m_strIconImageSmall**: panorama:"file://{images}/heroes/archer_sm.psd"
- **m_strMinimapImage**: panorama:"file://{images}/heroes/archer_mm.psd"
- **m_strUIAnimGraph**: resource_name:"models/heroes_staging/archer/ui_archer.vanmgrph"
- **m_strDeathSound**: soundevent:"Orion.Death"
- **m_hGameSoundEventScript**: resource_name:"soundevents/hero/orion.vsndevts"
- **m_hVOEventScript**: resource_name:"soundevents/vo/vo_hero_orion.vsndevts"
- **m_strRosterSelectedSound**: soundevent:"Orion.VO.HeroPick"
- **m_strIconHeroCard**: panorama:"file://{images}/heroes/archer_card.psd"
- **m_strRosterRemovedSound**: soundevent:"Orion.VO.HeroRemove"
- **m_hGeneratedVOEventScript**: resource_name:"soundevents/vo/generated_vo_hero_orion.vsndevts"
- **m_strTopBarImage**: panorama:"file://{images}/hud/hero_portraits/archer_hud.psd"
- **m_strUIPortraitMap**: maps/ui/hero_prefabs/archer.vmap
- **m_RecommendedUpgrades**:
  - upgrade_hollow_point_rounds
  - upgrade_endurance
  - upgrade_magic_burst
  - upgrade_extra_charge
  - upgrade_improved_spirit
  - upgrade_sprint_booster
  - upgrade_crackshot
  - upgrade_long_range
  - upgrade_regenerating_bullet_shield
  - upgrade_magic_shield
  - upgrade_tech_defense_shredders
  - upgrade_magic_shock
  - upgrade_rapid_recharge
  - upgrade_soaring_spirit
  - upgrade_magic_storm
  - upgrade_sharpshooter
  - upgrade_mega_spirit
- **m_strTopBarVertical**: panorama:"file://{images}/heroes/archer_vertical.psd"
- **m_flStepSoundTimeSprinting**: 0.355
- **m_strUIShopAnimGraph**: resource_name:"models/heroes_staging/archer/ui_shop_archer.vanmgrph"
- **m_strUIShoppingMap**: maps/ui/hero_shop/gray_talon_shop.vmap

---

# Hero: hero_krill

- **_class**: CitadelHeroData_t
- **m_bPlayerSelectable**: True
- **m_bDisabled**: False
- **m_bInDevelopment**: False
- **m_bNeedsTesting**: False
- **m_bAssignedPlayersOnly**: False
- **m_bBotSelectable**: False
- **m_bLimitedTesting**: False
- **m_nComplexity**: 3
- **m_nReadability**: 3
- **m_HeroID**: 18
- **m_strModelName**: resource_name:"models/heroes_staging/digger/digger.vmdl"
- **m_hDamageTakenParticle**: resource_name:"particles/generic/player_damage_screen.vpcf"
- **m_hGroundDamageTakenParticle**: resource_name:"particles/generic/player_ground_damage_screen.vpcf"
- **m_hDeathParticle**: resource_name:"particles/generic/player_death_screen.vpcf"
- **m_hLowHealthParticle**: resource_name:"particles/generic/player_low_health_screen.vpcf"
- **m_hRespawnParticle**: resource_name:"particles/generic/player_respawn_deploy.vpcf"
- **m_nModelSkin**: 0
- **m_mapStartingStats**:
  - **EMaxMoveSpeed**: 7.8
  - **ESprintSpeed**: 0
  - **ECrouchSpeed**: 4.75
  - **EMoveAcceleration**: 4
  - **ELightMeleeDamage**: 63
  - **EHeavyMeleeDamage**: 116
  - **EMaxHealth**: 700
  - **EWeaponPower**: 0
  - **EReloadSpeed**: 1
  - **EWeaponPowerScale**: 1
  - **EProcBuildUpRateScale**: 1
  - **EStamina**: 3
  - **EBaseHealthRegen**: 3
  - **EStaminaRegenPerSecond**: 0.2
  - **EAbilityResourceMax**: 0
  - **EAbilityResourceRegenPerSecond**: 0
  - **ECritDamageReceivedScale**: 1.0
  - **ETechDuration**: 1
  - **ETechRange**: 1
- **m_flCollisionRadius**: 28
- **m_flCollisionHeight**: 80
- **m_flStepHeight**: 24
- **m_mapBoundAbilities**:
  - **ESlot_Weapon_Primary**: citadel_weapon_digger_set
  - **ESlot_Weapon_Melee**: ability_melee_digger
  - **ESlot_Ability_Mantle**: citadel_ability_mantle
  - **ESlot_Ability_Jump**: citadel_ability_jump
  - **ESlot_Ability_Slide**: citadel_ability_slide
  - **ESlot_Ability_ZipLine**: citadel_ability_zip_line
  - **ESlot_Ability_ZipLineBoost**: citadel_ability_zipline_boost
  - **ESlot_Ability_Innate_1**: citadel_ability_dash
  - **ESlot_Ability_Innate_2**: citadel_ability_sprint
  - **ESlot_Ability_Innate_3**: citadel_ability_melee_parry
  - **ESlot_Signature_1**: ability_intimidate
  - **ESlot_Signature_2**: ability_burrow
  - **ESlot_Signature_3**: ability_throw_sand
  - **ESlot_Signature_4**: ability_ult_combo
- **m_mapItemSlotInfo**:
  - **EItemSlotType_WeaponMod**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
  - **EItemSlotType_Armor**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
  - **EItemSlotType_Tech**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
- **m_mapPurchaseBonuses**:
  - **EItemSlotType_WeaponMod**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 6 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 2 | 10 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 3 | 14 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 4 | 18 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
  - **EItemSlotType_Armor**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 11 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 2 | 14 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 3 | 17 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 4 | 20 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
  - **EItemSlotType_Tech**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 4 | MODIFIER_VALUE_TECH_POWER |
    | 2 | 8 | MODIFIER_VALUE_TECH_POWER |
    | 3 | 12 | MODIFIER_VALUE_TECH_POWER |
    | 4 | 16 | MODIFIER_VALUE_TECH_POWER |
- **m_mapLevelInfo**:
  - **1**:
    - **m_unRequiredGold**: 0
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **2**:
    - **m_unRequiredGold**: 400
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
      - **EAbilityPoints**: 1
  - **3**:
    - **m_unRequiredGold**: 800
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **4**:
    - **m_unRequiredGold**: 1200
    - **m_bUseStandardUpgrade**: True
  - **5**:
    - **m_unRequiredGold**: 1500
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **6**:
    - **m_unRequiredGold**: 2200
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **7**:
    - **m_unRequiredGold**: 3000
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **8**:
    - **m_unRequiredGold**: 4500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **9**:
    - **m_unRequiredGold**: 6000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **10**:
    - **m_unRequiredGold**: 7500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **11**:
    - **m_unRequiredGold**: 9000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **12**:
    - **m_unRequiredGold**: 10500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **13**:
    - **m_unRequiredGold**: 12000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **14**:
    - **m_unRequiredGold**: 13000
    - **m_bUseStandardUpgrade**: True
  - **15**:
    - **m_unRequiredGold**: 14000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **16**:
    - **m_unRequiredGold**: 15000
    - **m_bUseStandardUpgrade**: True
  - **17**:
    - **m_unRequiredGold**: 16000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **18**:
    - **m_unRequiredGold**: 18000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **19**:
    - **m_unRequiredGold**: 20000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **20**:
    - **m_unRequiredGold**: 22000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **21**:
    - **m_unRequiredGold**: 24000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **22**:
    - **m_unRequiredGold**: 27000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **23**:
    - **m_unRequiredGold**: 30000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **24**:
    - **m_unRequiredGold**: 33000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **25**:
    - **m_unRequiredGold**: 36000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **26**:
    - **m_unRequiredGold**: 39000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **27**:
    - **m_unRequiredGold**: 42000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **28**:
    - **m_unRequiredGold**: 45000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **29**:
    - **m_unRequiredGold**: 48000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
- **m_hFootstepSounds**: sweetener_default
- **m_strFootstepSoundEventDefault**: soundevent:"Digger.Footstep"
- **m_flStealthSpeedMetersPerSecond**: 4
- **m_flFootstepSoundTravelDistanceMeters**: 20
- **m_flStepSoundTime**: 0.3
- **m_vecAnimGraphDefaultValueOverrides**:
  | m_strParamName | m_strParamValue |
  | --- | --- |
  | e_SWITCH_4wayRoll_ON/OFF | 0 |
  | e_SWITCH_Recoil_ON/OFF | 0 |
  | e_SWITCH_ZiplinePhysicsSway_ON/OFF | 0 |
  | e_SWITCH_ShootStyle | 0 |
- **m_strLastHitSound**: soundevent:"LastHit.Default"
- **m_strLowHealthSound**: soundevent:"PlayerAlert.LowHealth"
- **m_colorUI**:
  - 104
  - 75
  - 133
- **m_colorGlowFriendly**:
  - 255
  - 239
  - 215
- **m_colorGlowEnemy**:
  - 255
  - 0
  - 0
- **m_colorGlowTeam1**:
  - 231
  - 182
  - 89
- **m_colorGlowTeam2**:
  - 91
  - 121
  - 230
- **m_vecAmbientParticleSettings**:
  | m_eAttachmentType | m_nCP |
  | --- | --- |
  | PATTACH_ABSORIGIN_FOLLOW | 0 |
  | PATTACH_POINT_FOLLOW | 1 |
- **m_heroStatsUI**:
  - **m_vecDisplayStats**:
    | m_eStatType | m_eStatCategory |
    | --- | --- |
    | EMaxHealth | ECitadelStat_Vitality |
    | EBaseHealthRegen | ECitadelStat_Vitality |
    | EBulletArmorDamageReduction | ECitadelStat_Vitality |
    | ETechArmorDamageReduction | ECitadelStat_Vitality |
    | ETechPower | ECitadelStat_Spirit |
    | EWeaponDPS | ECitadelStat_Weapon |
    | EBulletDamage | ECitadelStat_Weapon |
    | EClipSize | ECitadelStat_Weapon |
    | ERoundsPerSecond | ECitadelStat_Weapon |
    | ELightMeleeDamage | ECitadelStat_Weapon |
    | EHeavyMeleeDamage | ECitadelStat_Weapon |
    | EMaxMoveSpeed | ECitadelStat_Vitality |
    | ESprintSpeed | ECitadelStat_Vitality |
    | EStamina | ECitadelStat_Vitality |
  - **m_eWeaponStatDisplay**: EMeleeDamage_DEPRECATED
- **m_mapScalingStats**:
- **m_heroStatsDisplay**:
  - **m_vecHealthHeaderStats**:
    - EMaxHealth
    - EBaseHealthRegen
  - **m_vecHealthStats**:
    - EBulletArmorDamageReduction
    - ETechArmorDamageReduction
    - EBulletShieldHealth
    - ETechShieldHealth
    - EBulletLifesteal
    - ETechLifesteal
    - EMaxMoveSpeed
    - ESprintSpeed
    - EStamina
    - EHealingOutput
  - **m_vecWeaponHeaderStats**:
    - EWeaponDPS
    - EBulletDamage
  - **m_vecWeaponStats**:
    - ELightMeleeDamage
    - EHeavyMeleeDamage
    - EFireRate
    - EClipSize
  - **m_vecMagicHeaderStats**:
    - ETechPower
  - **m_vecMagicStats**:
    - ETechCooldown
    - ETechRange
    - ETechDuration
- **m_mapStandardLevelUpUpgrades**:
  - **MODIFIER_VALUE_BASE_BULLET_DAMAGE_FROM_LEVEL**: 0.25
  - **MODIFIER_VALUE_BASE_MELEE_DAMAGE_FROM_LEVEL**: 3.4
  - **MODIFIER_VALUE_BASE_HEALTH_FROM_LEVEL**: 44.0
  - **MODIFIER_VALUE_TECH_DAMAGE_PERCENT**: 0.0
  - **MODIFIER_VALUE_BULLET_ARMOR_DAMAGE_RESIST**: 0.0
- **m_eAbilityResourceType**: EResourceType_None
- **m_ShopStatDisplay**:
  - **m_eWeaponStatsDisplay**:
    - **m_vecDisplayStats**:
      - EBulletDamage
      - EBaseWeaponDamageIncrease
      - ERoundsPerSecond
      - EFireRate
      - EClipSize
      - EClipSizeIncrease
      - EReloadTime
      - EReloadSpeed
      - EBulletSpeed
      - EBulletSpeedIncrease
      - EBulletLifesteal
    - **m_vecOtherDisplayStats**:
      - ELightMeleeDamage
      - EHeavyMeleeDamage
    - **m_eWeaponAttributes**: EWeaponAttribute_RapidFire | EWeaponAttribute_Spreadshot
    - **m_strWeaponImage**: panorama:"file://{images}/heroes/guns/digger_gun.psd"
  - **m_eVitalityStatsDisplay**:
    - **m_vecDisplayStats**:
      - EMaxHealth
      - EBaseHealthRegen
      - EBulletArmorDamageReduction
      - ETechArmorDamageReduction
      - EBulletShieldHealth
      - ETechShieldHealth
      - ECritDamageReceivedScale
    - **m_vecOtherDisplayStats**:
      - EMaxMoveSpeed
      - ESprintSpeed
      - EStaminaCooldown
      - EStaminaRegenIncrease
      - EStamina
  - **m_eSpiritStatsDisplay**:
    - **m_vecDisplayStats**:
      - ETechCooldown
      - ETechDuration
      - ETechRange
      - ETechLifesteal
      - EMaxChargesIncrease
      - ETechCooldownBetweenChargeUses
- **_base**: hero_base
- **m_bNewPlayerRecommended**: False
- **m_bLaneTestingRecommended**: False
- **m_strSelectionImage**: panorama:"file://{images}/heroes/digger.psd"
- **m_strIconImageSmall**: panorama:"file://{images}/heroes/digger_sm.psd"
- **m_strMinimapImage**: panorama:"file://{images}/heroes/digger_mm.psd"
- **m_strUIAnimGraph**: resource_name:"models/heroes_staging/digger/ui_digger.vanmgrph"
- **m_strDeathSound**: soundevent:"MoKrill.Death"
- **m_hGameSoundEventScript**: resource_name:"soundevents/hero/krill.vsndevts"
- **m_hVOEventScript**: resource_name:"soundevents/vo/vo_hero_krill.vsndevts"
- **m_strRosterSelectedSound**: soundevent:"MoKrill.VO.HeroPick"
- **m_strIconHeroCard**: panorama:"file://{images}/heroes/digger_card.psd"
- **m_strRosterRemovedSound**: soundevent:"MoKrill.VO.HeroRemove"
- **m_hGeneratedVOEventScript**: resource_name:"soundevents/vo/generated_vo_hero_krill.vsndevts"
- **m_strTopBarImage**: panorama:"file://{images}/hud/hero_portraits/digger_hud.psd"
- **m_RecommendedUpgrades**:
  - upgrade_medic_bullets
  - upgrade_magic_burst
  - upgrade_close_range
  - upgrade_sprint_booster
  - upgrade_fleetfoot_boots
  - upgrade_berserker
  - upgrade_cardio_calibrator
  - upgrade_healing_booster
  - upgrade_tech_armor
  - upgrade_bullet_armor
  - upgrade_magic_vulnerability
  - upgrade_tech_damage_pulse
  - upgrade_improved_bullet_armor
  - upgrade_tech_purge
  - upgrade_phantom_strike
- **m_strUIPortraitMap**: maps/ui/hero_prefabs/digger.vmap
- **m_strTopBarVertical**: panorama:"file://{images}/heroes/digger_vertical.psd"
- **m_strUIShopAnimGraph**: resource_name:"models/heroes_staging/digger/ui_shop_digger.vanmgrph"
- **m_strUIShoppingMap**: maps/ui/hero_shop/digger_shop.vmap

---

# Hero: hero_shiv

- **_class**: CitadelHeroData_t
- **m_bPlayerSelectable**: True
- **m_bDisabled**: False
- **m_bInDevelopment**: False
- **m_bNeedsTesting**: False
- **m_bAssignedPlayersOnly**: False
- **m_bBotSelectable**: True
- **m_bLimitedTesting**: False
- **m_nComplexity**: 3
- **m_nReadability**: 1
- **m_HeroID**: 19
- **m_strModelName**: resource_name:"models/heroes_staging/shiv/shiv.vmdl"
- **m_hDamageTakenParticle**: resource_name:"particles/generic/player_damage_screen.vpcf"
- **m_hGroundDamageTakenParticle**: resource_name:"particles/generic/player_ground_damage_screen.vpcf"
- **m_hDeathParticle**: resource_name:"particles/generic/player_death_screen.vpcf"
- **m_hLowHealthParticle**: resource_name:"particles/generic/player_low_health_screen.vpcf"
- **m_hRespawnParticle**: resource_name:"particles/generic/player_respawn_deploy.vpcf"
- **m_nModelSkin**: 0
- **m_mapStartingStats**:
  - **EMaxMoveSpeed**: 7
  - **ESprintSpeed**: 0
  - **ECrouchSpeed**: 4.75
  - **EMoveAcceleration**: 4
  - **ELightMeleeDamage**: 63
  - **EHeavyMeleeDamage**: 116
  - **EMaxHealth**: 600.0
  - **EWeaponPower**: 0
  - **EReloadSpeed**: 1
  - **EWeaponPowerScale**: 1
  - **EProcBuildUpRateScale**: 1
  - **EStamina**: 3
  - **EBaseHealthRegen**: 2.0
  - **EStaminaRegenPerSecond**: 0.2
  - **EAbilityResourceMax**: 0
  - **EAbilityResourceRegenPerSecond**: 0
  - **ECritDamageReceivedScale**: 1.0
  - **ETechDuration**: 1
  - **ETechRange**: 1
- **m_flCollisionRadius**: 20
- **m_flCollisionHeight**: 80
- **m_flStepHeight**: 32
- **m_mapBoundAbilities**:
  - **ESlot_Weapon_Primary**: citadel_weapon_shiv_set
  - **ESlot_Weapon_Melee**: citadel_ability_melee_shiv
  - **ESlot_Ability_Mantle**: citadel_ability_mantle
  - **ESlot_Ability_Jump**: citadel_ability_jump
  - **ESlot_Ability_Slide**: citadel_ability_slide
  - **ESlot_Ability_ZipLine**: citadel_ability_zip_line
  - **ESlot_Ability_ZipLineBoost**: citadel_ability_zipline_boost
  - **ESlot_Ability_Innate_1**: citadel_ability_dash
  - **ESlot_Ability_Innate_2**: citadel_ability_sprint
  - **ESlot_Ability_Innate_3**: citadel_ability_melee_parry
  - **ESlot_Weapon_Secondary**: citadel_weapon_shiv_alt
  - **ESlot_Signature_1**: citadel_ability_shiv_dagger
  - **ESlot_Signature_2**: citadel_ability_shiv_dash
  - **ESlot_Signature_3**: citadel_ability_shiv_defer_damage
  - **ESlot_Signature_4**: citadel_ability_shiv_killing_blow
- **m_mapItemSlotInfo**:
  - **EItemSlotType_WeaponMod**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
  - **EItemSlotType_Armor**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
  - **EItemSlotType_Tech**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
- **m_mapPurchaseBonuses**:
  - **EItemSlotType_WeaponMod**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 6 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 2 | 10 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 3 | 14 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 4 | 18 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
  - **EItemSlotType_Armor**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 11 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 2 | 14 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 3 | 17 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 4 | 20 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
  - **EItemSlotType_Tech**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 4 | MODIFIER_VALUE_TECH_POWER |
    | 2 | 8 | MODIFIER_VALUE_TECH_POWER |
    | 3 | 12 | MODIFIER_VALUE_TECH_POWER |
    | 4 | 16 | MODIFIER_VALUE_TECH_POWER |
- **m_mapLevelInfo**:
  - **1**:
    - **m_unRequiredGold**: 0
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **2**:
    - **m_unRequiredGold**: 400
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
      - **EAbilityPoints**: 1
  - **3**:
    - **m_unRequiredGold**: 800
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **4**:
    - **m_unRequiredGold**: 1200
    - **m_bUseStandardUpgrade**: True
  - **5**:
    - **m_unRequiredGold**: 1500
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **6**:
    - **m_unRequiredGold**: 2200
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **7**:
    - **m_unRequiredGold**: 3000
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **8**:
    - **m_unRequiredGold**: 4500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **9**:
    - **m_unRequiredGold**: 6000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **10**:
    - **m_unRequiredGold**: 7500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **11**:
    - **m_unRequiredGold**: 9000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **12**:
    - **m_unRequiredGold**: 10500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **13**:
    - **m_unRequiredGold**: 12000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **14**:
    - **m_unRequiredGold**: 13000
    - **m_bUseStandardUpgrade**: True
  - **15**:
    - **m_unRequiredGold**: 14000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **16**:
    - **m_unRequiredGold**: 15000
    - **m_bUseStandardUpgrade**: True
  - **17**:
    - **m_unRequiredGold**: 16000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **18**:
    - **m_unRequiredGold**: 18000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **19**:
    - **m_unRequiredGold**: 20000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **20**:
    - **m_unRequiredGold**: 22000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **21**:
    - **m_unRequiredGold**: 24000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **22**:
    - **m_unRequiredGold**: 27000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **23**:
    - **m_unRequiredGold**: 30000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **24**:
    - **m_unRequiredGold**: 33000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **25**:
    - **m_unRequiredGold**: 36000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **26**:
    - **m_unRequiredGold**: 39000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **27**:
    - **m_unRequiredGold**: 42000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **28**:
    - **m_unRequiredGold**: 45000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **29**:
    - **m_unRequiredGold**: 48000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
- **m_hFootstepSounds**: sweetener_default
- **m_strFootstepSoundEventDefault**: soundevent:"Shiv.Footstep"
- **m_flStealthSpeedMetersPerSecond**: 4
- **m_flFootstepSoundTravelDistanceMeters**: 20
- **m_flStepSoundTime**: 0.315
- **m_vecAnimGraphDefaultValueOverrides**:
  | m_strParamName | m_strParamValue |
  | --- | --- |
  | e_SWITCH_4wayRoll_ON/OFF | 0 |
  | e_SWITCH_Recoil_ON/OFF | 0 |
  | e_SWITCH_ZiplinePhysicsSway_ON/OFF | 0 |
  | e_SWITCH_ShootStyle | 0 |
- **m_strLastHitSound**: soundevent:"LastHit.Default"
- **m_strLowHealthSound**: soundevent:"PlayerAlert.LowHealth"
- **m_colorUI**:
  - 164
  - 60
  - 135
- **m_colorGlowFriendly**:
  - 255
  - 239
  - 215
- **m_colorGlowEnemy**:
  - 255
  - 0
  - 0
- **m_colorGlowTeam1**:
  - 231
  - 182
  - 89
- **m_colorGlowTeam2**:
  - 91
  - 121
  - 230
- **m_vecAmbientParticleSettings**:
  | m_eAttachmentType | m_nCP |
  | --- | --- |
  | PATTACH_ABSORIGIN_FOLLOW | 0 |
  | PATTACH_POINT_FOLLOW | 1 |
- **m_heroStatsUI**:
  - **m_vecDisplayStats**:
    | m_eStatType | m_eStatCategory |
    | --- | --- |
    | EMaxHealth | ECitadelStat_Vitality |
    | EBaseHealthRegen | ECitadelStat_Vitality |
    | EBulletArmorDamageReduction | ECitadelStat_Vitality |
    | ETechArmorDamageReduction | ECitadelStat_Vitality |
    | ETechPower | ECitadelStat_Spirit |
    | EWeaponDPS | ECitadelStat_Weapon |
    | EBulletDamage | ECitadelStat_Weapon |
    | EClipSize | ECitadelStat_Weapon |
    | ERoundsPerSecond | ECitadelStat_Weapon |
    | ELightMeleeDamage | ECitadelStat_Weapon |
    | EHeavyMeleeDamage | ECitadelStat_Weapon |
    | EMaxMoveSpeed | ECitadelStat_Vitality |
    | ESprintSpeed | ECitadelStat_Vitality |
    | EStamina | ECitadelStat_Vitality |
  - **m_eWeaponStatDisplay**: EMeleeDamage_DEPRECATED
- **m_mapScalingStats**:
- **m_heroStatsDisplay**:
  - **m_vecHealthHeaderStats**:
    - EMaxHealth
    - EBaseHealthRegen
  - **m_vecHealthStats**:
    - EBulletArmorDamageReduction
    - ETechArmorDamageReduction
    - EBulletShieldHealth
    - ETechShieldHealth
    - EBulletLifesteal
    - ETechLifesteal
    - EMaxMoveSpeed
    - ESprintSpeed
    - EStamina
    - EHealingOutput
  - **m_vecWeaponHeaderStats**:
    - EWeaponDPS
    - EBulletDamage
  - **m_vecWeaponStats**:
    - ELightMeleeDamage
    - EHeavyMeleeDamage
    - EFireRate
    - EClipSize
  - **m_vecMagicHeaderStats**:
    - ETechPower
  - **m_vecMagicStats**:
    - ETechCooldown
    - ETechRange
    - ETechDuration
- **m_mapStandardLevelUpUpgrades**:
  - **MODIFIER_VALUE_BASE_BULLET_DAMAGE_FROM_LEVEL**: 0.5
  - **MODIFIER_VALUE_BASE_MELEE_DAMAGE_FROM_LEVEL**: 3.4
  - **MODIFIER_VALUE_BASE_HEALTH_FROM_LEVEL**: 41.0
  - **MODIFIER_VALUE_TECH_DAMAGE_PERCENT**: 0.0
  - **MODIFIER_VALUE_BULLET_ARMOR_DAMAGE_RESIST**: 0.0
- **m_eAbilityResourceType**: EResourceType_Rage
- **m_ShopStatDisplay**:
  - **m_eWeaponStatsDisplay**:
    - **m_vecDisplayStats**:
      - EBulletDamage
      - EBaseWeaponDamageIncrease
      - ERoundsPerSecond
      - EFireRate
      - EClipSize
      - EClipSizeIncrease
      - EReloadTime
      - EReloadSpeed
      - EBulletSpeed
      - EBulletSpeedIncrease
      - EBulletLifesteal
    - **m_vecOtherDisplayStats**:
      - ELightMeleeDamage
      - EHeavyMeleeDamage
    - **m_eWeaponAttributes**: EWeaponAttribute_Spreadshot | EWeaponAttribute_CloseRange
    - **m_strWeaponImage**: panorama:"file://{images}/heroes/guns/shiv_gun.psd"
  - **m_eVitalityStatsDisplay**:
    - **m_vecDisplayStats**:
      - EMaxHealth
      - EBaseHealthRegen
      - EBulletArmorDamageReduction
      - ETechArmorDamageReduction
      - EBulletShieldHealth
      - ETechShieldHealth
      - ECritDamageReceivedScale
    - **m_vecOtherDisplayStats**:
      - EMaxMoveSpeed
      - ESprintSpeed
      - EStaminaCooldown
      - EStaminaRegenIncrease
      - EStamina
  - **m_eSpiritStatsDisplay**:
    - **m_vecDisplayStats**:
      - ETechCooldown
      - ETechDuration
      - ETechRange
      - ETechLifesteal
      - EMaxChargesIncrease
      - ETechCooldownBetweenChargeUses
- **_base**: hero_base
- **m_strSelectionImage**: panorama:"file://{images}/heroes/shiv.psd"
- **m_strIconImageSmall**: panorama:"file://{images}/heroes/shiv_sm.psd"
- **m_strMinimapImage**: panorama:"file://{images}/heroes/shiv_mm.psd"
- **m_strUIAnimGraph**: resource_name:"models/heroes_staging/shiv/ui_shiv.vanmgrph"
- **m_strDeathSound**: soundevent:"Shiv.Death"
- **m_hGameSoundEventScript**: resource_name:"soundevents/hero/shiv.vsndevts"
- **m_hVOEventScript**: resource_name:"soundevents/vo/vo_hero_shiv.vsndevts"
- **m_strRosterSelectedSound**: soundevent:"Shiv.VO.HeroPick"
- **m_strIconHeroCard**: panorama:"file://{images}/heroes/shiv_card.psd"
- **m_hGeneratedVOEventScript**: resource_name:"soundevents/vo/generated_vo_hero_shiv.vsndevts"
- **m_strRosterRemovedSound**: soundevent:"Shiv.VO.HeroRemove"
- **m_strTopBarImage**: panorama:"file://{images}/hud/hero_portraits/shiv_hud.psd"
- **m_strUIPortraitMap**: maps/ui/hero_prefabs/shiv.vmap
- **m_strTopBarVertical**: panorama:"file://{images}/heroes/shiv_vertical.psd"
- **m_RecommendedUpgrades**:
  - upgrade_endurance
  - upgrade_health
  - upgrade_close_range
  - upgrade_clip_size
  - upgrade_improved_spirit
  - upgrade_crackshot
  - upgrade_tech_defense_shredders
  - upgrade_slowing_bullets
  - upgrade_cardio_calibrator
  - upgrade_tech_armor
  - upgrade_bullet_armor
  - upgrade_bullet_resist_shredder
  - upgrade_health_stealing_magic
  - upgrade_magic_storm
  - upgrade_magic_vulnerability
  - upgrade_reduce_debuff_duration
  - upgrade_magic_slow
  - upgrade_close_quarter_combat
  - upgrade_tech_purge
  - upgrade_soaring_spirit
  - upgrade_cooldown_reduction
  - upgrade_mega_spirit
  - upgrade_escalating_exposure
  - upgrade_damage_recycler
  - upgrade_siphon_bullets
- **m_strUIShopAnimGraph**: resource_name:"models/heroes_staging/shiv/ui_shop_shiv.vanmgrph"
- **m_strUIShoppingMap**: maps/ui/hero_shop/shiv_shop.vmap

---

# Hero: hero_tengu

- **_class**: CitadelHeroData_t
- **m_bPlayerSelectable**: True
- **m_bDisabled**: False
- **m_bInDevelopment**: False
- **m_bNeedsTesting**: False
- **m_bAssignedPlayersOnly**: False
- **m_bBotSelectable**: False
- **m_bLimitedTesting**: False
- **m_nComplexity**: 3
- **m_nReadability**: 0
- **m_HeroID**: 20
- **m_strModelName**: resource_name:"models/heroes_staging/tengu/tengu_v2/tengu.vmdl"
- **m_hDamageTakenParticle**: resource_name:"particles/generic/player_damage_screen.vpcf"
- **m_hGroundDamageTakenParticle**: resource_name:"particles/generic/player_ground_damage_screen.vpcf"
- **m_hDeathParticle**: resource_name:"particles/generic/player_death_screen.vpcf"
- **m_hLowHealthParticle**: resource_name:"particles/generic/player_low_health_screen.vpcf"
- **m_hRespawnParticle**: resource_name:"particles/generic/player_respawn_deploy.vpcf"
- **m_nModelSkin**: 0
- **m_mapStartingStats**:
  - **EMaxMoveSpeed**: 7
  - **ESprintSpeed**: 0
  - **ECrouchSpeed**: 4.75
  - **EMoveAcceleration**: 4
  - **ELightMeleeDamage**: 63
  - **EHeavyMeleeDamage**: 116
  - **EMaxHealth**: 550
  - **EWeaponPower**: 0
  - **EReloadSpeed**: 1
  - **EWeaponPowerScale**: 1
  - **EProcBuildUpRateScale**: 1
  - **EStamina**: 4
  - **EBaseHealthRegen**: 2.0
  - **EStaminaRegenPerSecond**: 0.2
  - **EAbilityResourceMax**: 0
  - **EAbilityResourceRegenPerSecond**: 0
  - **ECritDamageReceivedScale**: 1.0
  - **ETechDuration**: 1
  - **ETechRange**: 1
- **m_flCollisionRadius**: 20
- **m_flCollisionHeight**: 80
- **m_flStepHeight**: 32
- **m_mapBoundAbilities**:
  - **ESlot_Weapon_Primary**: citadel_weapon_tengu_set
  - **ESlot_Weapon_Melee**: citadel_ability_melee_tengu
  - **ESlot_Ability_Mantle**: citadel_ability_mantle
  - **ESlot_Ability_Jump**: citadel_ability_jump
  - **ESlot_Ability_Slide**: citadel_ability_slide
  - **ESlot_Ability_ZipLine**: citadel_ability_zip_line
  - **ESlot_Ability_ZipLineBoost**: citadel_ability_zipline_boost
  - **ESlot_Ability_Innate_1**: citadel_ability_dash
  - **ESlot_Ability_Innate_2**: citadel_ability_sprint
  - **ESlot_Ability_Innate_3**: citadel_ability_melee_parry
  - **ESlot_Signature_1**: citadel_ability_tengu_urn
  - **ESlot_Signature_2**: citadel_ability_tangotether
  - **ESlot_Signature_3**: citadel_ability_tengu_stone_form
  - **ESlot_Signature_4**: citadel_ability_tengu_airlift
- **m_mapItemSlotInfo**:
  - **EItemSlotType_WeaponMod**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
  - **EItemSlotType_Armor**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
  - **EItemSlotType_Tech**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
- **m_mapPurchaseBonuses**:
  - **EItemSlotType_WeaponMod**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 6 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 2 | 10 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 3 | 14 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 4 | 18 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
  - **EItemSlotType_Armor**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 11 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 2 | 14 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 3 | 17 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 4 | 20 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
  - **EItemSlotType_Tech**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 4 | MODIFIER_VALUE_TECH_POWER |
    | 2 | 8 | MODIFIER_VALUE_TECH_POWER |
    | 3 | 12 | MODIFIER_VALUE_TECH_POWER |
    | 4 | 16 | MODIFIER_VALUE_TECH_POWER |
- **m_mapLevelInfo**:
  - **1**:
    - **m_unRequiredGold**: 0
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **2**:
    - **m_unRequiredGold**: 400
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
      - **EAbilityPoints**: 1
  - **3**:
    - **m_unRequiredGold**: 800
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **4**:
    - **m_unRequiredGold**: 1200
    - **m_bUseStandardUpgrade**: True
  - **5**:
    - **m_unRequiredGold**: 1500
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **6**:
    - **m_unRequiredGold**: 2200
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **7**:
    - **m_unRequiredGold**: 3000
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **8**:
    - **m_unRequiredGold**: 4500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **9**:
    - **m_unRequiredGold**: 6000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **10**:
    - **m_unRequiredGold**: 7500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **11**:
    - **m_unRequiredGold**: 9000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **12**:
    - **m_unRequiredGold**: 10500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **13**:
    - **m_unRequiredGold**: 12000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **14**:
    - **m_unRequiredGold**: 13000
    - **m_bUseStandardUpgrade**: True
  - **15**:
    - **m_unRequiredGold**: 14000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **16**:
    - **m_unRequiredGold**: 15000
    - **m_bUseStandardUpgrade**: True
  - **17**:
    - **m_unRequiredGold**: 16000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **18**:
    - **m_unRequiredGold**: 18000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **19**:
    - **m_unRequiredGold**: 20000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **20**:
    - **m_unRequiredGold**: 22000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **21**:
    - **m_unRequiredGold**: 24000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **22**:
    - **m_unRequiredGold**: 27000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **23**:
    - **m_unRequiredGold**: 30000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **24**:
    - **m_unRequiredGold**: 33000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **25**:
    - **m_unRequiredGold**: 36000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **26**:
    - **m_unRequiredGold**: 39000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **27**:
    - **m_unRequiredGold**: 42000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **28**:
    - **m_unRequiredGold**: 45000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **29**:
    - **m_unRequiredGold**: 48000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
- **m_hFootstepSounds**: sweetener_default
- **m_strFootstepSoundEventDefault**: soundevent:"Tengu.Footstep"
- **m_flStealthSpeedMetersPerSecond**: 4
- **m_flFootstepSoundTravelDistanceMeters**: 20
- **m_flStepSoundTime**: 0.383
- **m_vecAnimGraphDefaultValueOverrides**:
  | m_strParamName | m_strParamValue |
  | --- | --- |
  | e_SWITCH_4wayRoll_ON/OFF | 0 |
  | e_SWITCH_Recoil_ON/OFF | 0 |
  | e_SWITCH_ZiplinePhysicsSway_ON/OFF | 0 |
  | e_SWITCH_ShootStyle | 0 |
- **m_strLastHitSound**: soundevent:"LastHit.Default"
- **m_strLowHealthSound**: soundevent:"PlayerAlert.LowHealth"
- **m_colorUI**:
  - 179
  - 115
  - 217
- **m_colorGlowFriendly**:
  - 255
  - 239
  - 215
- **m_colorGlowEnemy**:
  - 255
  - 0
  - 0
- **m_colorGlowTeam1**:
  - 231
  - 182
  - 89
- **m_colorGlowTeam2**:
  - 91
  - 121
  - 230
- **m_vecAmbientParticleSettings**:
  | m_eAttachmentType | m_nCP |
  | --- | --- |
  | PATTACH_ABSORIGIN_FOLLOW | 0 |
  | PATTACH_POINT_FOLLOW | 1 |
- **m_heroStatsUI**:
  - **m_vecDisplayStats**:
    | m_eStatType | m_eStatCategory |
    | --- | --- |
    | EMaxHealth | ECitadelStat_Vitality |
    | EBaseHealthRegen | ECitadelStat_Vitality |
    | EBulletArmorDamageReduction | ECitadelStat_Vitality |
    | ETechArmorDamageReduction | ECitadelStat_Vitality |
    | ETechPower | ECitadelStat_Spirit |
    | EWeaponDPS | ECitadelStat_Weapon |
    | EBulletDamage | ECitadelStat_Weapon |
    | EClipSize | ECitadelStat_Weapon |
    | ERoundsPerSecond | ECitadelStat_Weapon |
    | ELightMeleeDamage | ECitadelStat_Weapon |
    | EHeavyMeleeDamage | ECitadelStat_Weapon |
    | EMaxMoveSpeed | ECitadelStat_Vitality |
    | ESprintSpeed | ECitadelStat_Vitality |
    | EStamina | ECitadelStat_Vitality |
  - **m_eWeaponStatDisplay**: EMeleeDamage_DEPRECATED
- **m_mapScalingStats**:
- **m_heroStatsDisplay**:
  - **m_vecHealthHeaderStats**:
    - EMaxHealth
    - EBaseHealthRegen
  - **m_vecHealthStats**:
    - EBulletArmorDamageReduction
    - ETechArmorDamageReduction
    - EBulletShieldHealth
    - ETechShieldHealth
    - EBulletLifesteal
    - ETechLifesteal
    - EMaxMoveSpeed
    - ESprintSpeed
    - EStamina
    - EHealingOutput
  - **m_vecWeaponHeaderStats**:
    - EWeaponDPS
    - EBulletDamage
  - **m_vecWeaponStats**:
    - ELightMeleeDamage
    - EHeavyMeleeDamage
    - EFireRate
    - EClipSize
  - **m_vecMagicHeaderStats**:
    - ETechPower
  - **m_vecMagicStats**:
    - ETechCooldown
    - ETechRange
    - ETechDuration
- **m_mapStandardLevelUpUpgrades**:
  - **MODIFIER_VALUE_BASE_BULLET_DAMAGE_FROM_LEVEL**: 0.55
  - **MODIFIER_VALUE_BASE_MELEE_DAMAGE_FROM_LEVEL**: 3.4
  - **MODIFIER_VALUE_BASE_HEALTH_FROM_LEVEL**: 41.0
  - **MODIFIER_VALUE_TECH_DAMAGE_PERCENT**: 0.0
  - **MODIFIER_VALUE_BULLET_ARMOR_DAMAGE_RESIST**: 0.0
- **m_eAbilityResourceType**: EResourceType_None
- **m_ShopStatDisplay**:
  - **m_eWeaponStatsDisplay**:
    - **m_vecDisplayStats**:
      - EBulletDamage
      - EBaseWeaponDamageIncrease
      - ERoundsPerSecond
      - EFireRate
      - EClipSize
      - EClipSizeIncrease
      - EReloadTime
      - EReloadSpeed
      - EBulletSpeed
      - EBulletSpeedIncrease
      - EBulletLifesteal
    - **m_vecOtherDisplayStats**:
      - ELightMeleeDamage
      - EHeavyMeleeDamage
    - **m_eWeaponAttributes**: EWeaponAttribute_RapidFire | EWeaponAttribute_MediumRange
    - **m_strWeaponImage**: panorama:"file://{images}/heroes/guns/ivy_gun.psd"
  - **m_eVitalityStatsDisplay**:
    - **m_vecDisplayStats**:
      - EMaxHealth
      - EBaseHealthRegen
      - EBulletArmorDamageReduction
      - ETechArmorDamageReduction
      - EBulletShieldHealth
      - ETechShieldHealth
      - ECritDamageReceivedScale
    - **m_vecOtherDisplayStats**:
      - EMaxMoveSpeed
      - ESprintSpeed
      - EStaminaCooldown
      - EStaminaRegenIncrease
      - EStamina
  - **m_eSpiritStatsDisplay**:
    - **m_vecDisplayStats**:
      - ETechCooldown
      - ETechDuration
      - ETechRange
      - ETechLifesteal
      - EMaxChargesIncrease
      - ETechCooldownBetweenChargeUses
- **_base**: hero_base
- **m_strSelectionImage**: panorama:"file://{images}/heroes/tengu.psd"
- **m_strIconImageSmall**: panorama:"file://{images}/heroes/tengu_sm.psd"
- **m_strMinimapImage**: panorama:"file://{images}/heroes/tengu_mm.psd"
- **m_strUIAnimGraph**: resource_name:"models/heroes_staging/tengu/tengu_v2/ui_tengu.vanmgrph"
- **m_strDeathSound**: soundevent:"Ivy.Death"
- **m_hGameSoundEventScript**: resource_name:"soundevents/hero/tengu.vsndevts"
- **m_hVOEventScript**: resource_name:"soundevents/vo/vo_hero_tengu.vsndevts"
- **m_strIconHeroCard**: panorama:"file://{images}/heroes/tengu_card.psd"
- **m_strTopBarImage**: panorama:"file://{images}/hud/hero_portraits/tengu_hud.psd"
- **m_strRosterRemovedSound**: soundevent:"Ivy.VO.HeroRemove"
- **m_strRosterSelectedSound**: soundevent:"Ivy.VO.HeroPick"
- **m_hGeneratedVOEventScript**: resource_name:"soundevents/vo/generated_vo_hero_tengu.vsndevts"
- **m_strWIPModelName**: resource_name:"models/heroes_staging/tengu/tengu_v2/tengu.vmdl"
- **m_strUIPortraitMap**: maps/ui/hero_prefabs/tengu.vmap
- **m_RecommendedUpgrades**:
  - upgrade_health_stimpak
  - upgrade_clip_size
  - upgrade_non_player_bonus
  - upgrade_health_nova
  - upgrade_healing_booster
  - upgrade_bullet_armor
  - upgrade_tech_armor
  - upgrade_magic_tempo
  - upgrade_chain_lightning
  - upgrade_titan_round
  - upgrade_chonky
  - upgrade_banshee_slugs
  - upgrade_inhibitor
- **m_strTopBarVertical**: panorama:"file://{images}/heroes/tengu_vertical.psd"
- **m_mapWIPAbilities**:
- **m_flStepSoundTimeSprinting**: 0.383
- **m_strUIShopAnimGraph**: resource_name:"models/heroes_staging/tengu/tengu_v2/ui_shop_tengu.vanmgrph"
- **m_strUIShoppingMap**: maps/ui/hero_shop/tengu_shop.vmap

---

# Hero: hero_kali

- **_class**: CitadelHeroData_t
- **m_bPlayerSelectable**: True
- **m_bDisabled**: True
- **m_bInDevelopment**: False
- **m_bNeedsTesting**: False
- **m_bAssignedPlayersOnly**: False
- **m_bBotSelectable**: False
- **m_bLimitedTesting**: False
- **m_nComplexity**: 2
- **m_nReadability**: 1
- **m_HeroID**: 21
- **m_strModelName**: resource_name:"models/heroes_staging/kali/kali.vmdl"
- **m_hDamageTakenParticle**: resource_name:"particles/generic/player_damage_screen.vpcf"
- **m_hGroundDamageTakenParticle**: resource_name:"particles/generic/player_ground_damage_screen.vpcf"
- **m_hDeathParticle**: resource_name:"particles/generic/player_death_screen.vpcf"
- **m_hLowHealthParticle**: resource_name:"particles/generic/player_low_health_screen.vpcf"
- **m_hRespawnParticle**: resource_name:"particles/generic/player_respawn_deploy.vpcf"
- **m_nModelSkin**: 0
- **m_mapStartingStats**:
  - **EMaxMoveSpeed**: 7
  - **ESprintSpeed**: 0
  - **ECrouchSpeed**: 4.75
  - **EMoveAcceleration**: 4
  - **ELightMeleeDamage**: 63
  - **EHeavyMeleeDamage**: 116
  - **EMaxHealth**: 550
  - **EWeaponPower**: 0
  - **EReloadSpeed**: 1
  - **EWeaponPowerScale**: 1
  - **EProcBuildUpRateScale**: 1
  - **EStamina**: 3
  - **EBaseHealthRegen**: 2.0
  - **EStaminaRegenPerSecond**: 0.2
  - **EAbilityResourceMax**: 0
  - **EAbilityResourceRegenPerSecond**: 0
  - **ECritDamageReceivedScale**: 1.0
  - **ETechDuration**: 1
  - **ETechRange**: 1
- **m_flCollisionRadius**: 20
- **m_flCollisionHeight**: 80
- **m_flStepHeight**: 32
- **m_mapBoundAbilities**:
  - **ESlot_Weapon_Primary**: citadel_weapon_kali_set
  - **ESlot_Weapon_Melee**: citadel_ability_melee_kali
  - **ESlot_Ability_Mantle**: citadel_ability_mantle
  - **ESlot_Ability_Jump**: citadel_ability_jump
  - **ESlot_Ability_Slide**: citadel_ability_slide
  - **ESlot_Ability_ZipLine**: citadel_ability_zip_line
  - **ESlot_Ability_ZipLineBoost**: citadel_ability_zipline_boost
  - **ESlot_Ability_Innate_1**: citadel_ability_dash
  - **ESlot_Ability_Innate_2**: citadel_ability_sprint
  - **ESlot_Ability_Innate_3**: citadel_ability_melee_parry
  - **ESlot_Signature_1**: citadel_ability_kali_spinning_blade
  - **ESlot_Signature_2**: citadel_ability_kali_disruptive_charge
  - **ESlot_Signature_3**: ability_kali_dust_storm
  - **ESlot_Signature_4**: ability_kali_trappers_bolo
- **m_mapItemSlotInfo**:
  - **EItemSlotType_WeaponMod**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
  - **EItemSlotType_Armor**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
  - **EItemSlotType_Tech**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
- **m_mapPurchaseBonuses**:
  - **EItemSlotType_WeaponMod**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 6 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 2 | 10 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 3 | 14 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 4 | 18 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
  - **EItemSlotType_Armor**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 11 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 2 | 14 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 3 | 17 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 4 | 20 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
  - **EItemSlotType_Tech**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 4 | MODIFIER_VALUE_TECH_POWER |
    | 2 | 8 | MODIFIER_VALUE_TECH_POWER |
    | 3 | 12 | MODIFIER_VALUE_TECH_POWER |
    | 4 | 16 | MODIFIER_VALUE_TECH_POWER |
- **m_mapLevelInfo**:
  - **1**:
    - **m_unRequiredGold**: 0
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **2**:
    - **m_unRequiredGold**: 400
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
      - **EAbilityPoints**: 1
  - **3**:
    - **m_unRequiredGold**: 800
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **4**:
    - **m_unRequiredGold**: 1200
    - **m_bUseStandardUpgrade**: True
  - **5**:
    - **m_unRequiredGold**: 1500
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **6**:
    - **m_unRequiredGold**: 2200
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **7**:
    - **m_unRequiredGold**: 3000
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **8**:
    - **m_unRequiredGold**: 4500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **9**:
    - **m_unRequiredGold**: 6000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **10**:
    - **m_unRequiredGold**: 7500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **11**:
    - **m_unRequiredGold**: 9000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **12**:
    - **m_unRequiredGold**: 10500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **13**:
    - **m_unRequiredGold**: 12000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **14**:
    - **m_unRequiredGold**: 13000
    - **m_bUseStandardUpgrade**: True
  - **15**:
    - **m_unRequiredGold**: 14000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **16**:
    - **m_unRequiredGold**: 15000
    - **m_bUseStandardUpgrade**: True
  - **17**:
    - **m_unRequiredGold**: 16000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **18**:
    - **m_unRequiredGold**: 18000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **19**:
    - **m_unRequiredGold**: 20000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **20**:
    - **m_unRequiredGold**: 22000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **21**:
    - **m_unRequiredGold**: 24000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **22**:
    - **m_unRequiredGold**: 27000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **23**:
    - **m_unRequiredGold**: 30000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **24**:
    - **m_unRequiredGold**: 33000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **25**:
    - **m_unRequiredGold**: 36000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **26**:
    - **m_unRequiredGold**: 39000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **27**:
    - **m_unRequiredGold**: 42000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **28**:
    - **m_unRequiredGold**: 45000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **29**:
    - **m_unRequiredGold**: 48000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
- **m_hFootstepSounds**: sweetener_default
- **m_strFootstepSoundEventDefault**: soundevent:"Hero.Default.Footstep"
- **m_flStealthSpeedMetersPerSecond**: 4
- **m_flFootstepSoundTravelDistanceMeters**: 20
- **m_flStepSoundTime**: 0.3
- **m_vecAnimGraphDefaultValueOverrides**:
  | m_strParamName | m_strParamValue |
  | --- | --- |
  | e_SWITCH_4wayRoll_ON/OFF | 0 |
  | e_SWITCH_Recoil_ON/OFF | 0 |
  | e_SWITCH_ZiplinePhysicsSway_ON/OFF | 0 |
  | e_SWITCH_ShootStyle | 0 |
- **m_strLastHitSound**: soundevent:"LastHit.Default"
- **m_strLowHealthSound**: soundevent:"PlayerAlert.LowHealth"
- **m_colorUI**:
  - 246
  - 218
  - 79
- **m_colorGlowFriendly**:
  - 255
  - 239
  - 215
- **m_colorGlowEnemy**:
  - 255
  - 0
  - 0
- **m_colorGlowTeam1**:
  - 231
  - 182
  - 89
- **m_colorGlowTeam2**:
  - 91
  - 121
  - 230
- **m_vecAmbientParticleSettings**:
  | m_eAttachmentType | m_nCP |
  | --- | --- |
  | PATTACH_ABSORIGIN_FOLLOW | 0 |
  | PATTACH_POINT_FOLLOW | 1 |
- **m_heroStatsUI**:
  - **m_vecDisplayStats**:
    | m_eStatType | m_eStatCategory |
    | --- | --- |
    | EMaxHealth | ECitadelStat_Vitality |
    | EBaseHealthRegen | ECitadelStat_Vitality |
    | EBulletArmorDamageReduction | ECitadelStat_Vitality |
    | ETechArmorDamageReduction | ECitadelStat_Vitality |
    | ETechPower | ECitadelStat_Spirit |
    | EWeaponDPS | ECitadelStat_Weapon |
    | EBulletDamage | ECitadelStat_Weapon |
    | EClipSize | ECitadelStat_Weapon |
    | ERoundsPerSecond | ECitadelStat_Weapon |
    | ELightMeleeDamage | ECitadelStat_Weapon |
    | EHeavyMeleeDamage | ECitadelStat_Weapon |
    | EMaxMoveSpeed | ECitadelStat_Vitality |
    | ESprintSpeed | ECitadelStat_Vitality |
    | EStamina | ECitadelStat_Vitality |
  - **m_eWeaponStatDisplay**: EMeleeDamage_DEPRECATED
- **m_mapScalingStats**:
- **m_heroStatsDisplay**:
  - **m_vecHealthHeaderStats**:
    - EMaxHealth
    - EBaseHealthRegen
  - **m_vecHealthStats**:
    - EBulletArmorDamageReduction
    - ETechArmorDamageReduction
    - EBulletShieldHealth
    - ETechShieldHealth
    - EBulletLifesteal
    - ETechLifesteal
    - EMaxMoveSpeed
    - ESprintSpeed
    - EStamina
    - EHealingOutput
  - **m_vecWeaponHeaderStats**:
    - EWeaponDPS
    - EBulletDamage
  - **m_vecWeaponStats**:
    - ELightMeleeDamage
    - EHeavyMeleeDamage
    - EFireRate
    - EClipSize
  - **m_vecMagicHeaderStats**:
    - ETechPower
  - **m_vecMagicStats**:
    - ETechCooldown
    - ETechRange
    - ETechDuration
- **m_mapStandardLevelUpUpgrades**:
  - **MODIFIER_VALUE_BASE_BULLET_DAMAGE_FROM_LEVEL**: 0.0
  - **MODIFIER_VALUE_BASE_MELEE_DAMAGE_FROM_LEVEL**: 3.4
  - **MODIFIER_VALUE_BASE_HEALTH_FROM_LEVEL**: 41.0
  - **MODIFIER_VALUE_TECH_DAMAGE_PERCENT**: 0.0
  - **MODIFIER_VALUE_BULLET_ARMOR_DAMAGE_RESIST**: 0.0
- **m_eAbilityResourceType**: EResourceType_None
- **m_ShopStatDisplay**:
  - **m_eWeaponStatsDisplay**:
    - **m_vecDisplayStats**:
      - EBulletDamage
      - EBaseWeaponDamageIncrease
      - ERoundsPerSecond
      - EFireRate
      - EClipSize
      - EClipSizeIncrease
      - EReloadTime
      - EReloadSpeed
      - EBulletSpeed
      - EBulletSpeedIncrease
      - EBulletLifesteal
    - **m_vecOtherDisplayStats**:
      - ELightMeleeDamage
      - EHeavyMeleeDamage
  - **m_eVitalityStatsDisplay**:
    - **m_vecDisplayStats**:
      - EMaxHealth
      - EBaseHealthRegen
      - EBulletArmorDamageReduction
      - ETechArmorDamageReduction
      - EBulletShieldHealth
      - ETechShieldHealth
      - ECritDamageReceivedScale
    - **m_vecOtherDisplayStats**:
      - EMaxMoveSpeed
      - ESprintSpeed
      - EStaminaCooldown
      - EStaminaRegenIncrease
      - EStamina
  - **m_eSpiritStatsDisplay**:
    - **m_vecDisplayStats**:
      - ETechCooldown
      - ETechDuration
      - ETechRange
      - ETechLifesteal
      - EMaxChargesIncrease
      - ETechCooldownBetweenChargeUses
- **_base**: hero_base
- **m_strSelectionImage**: panorama:"file://{images}/heroes/kali.psd"
- **m_strIconImageSmall**: panorama:"file://{images}/heroes/kali_sm.psd"
- **m_strMinimapImage**: panorama:"file://{images}/heroes/kali_mm.psd"
- **m_strUIAnimGraph**: resource_name:"models/heroes_staging/kali/ui_kali.vanmgrph"
- **m_strDeathSound**: soundevent:"Kali.Death"
- **m_hGameSoundEventScript**: resource_name:"soundevents/hero/kali.vsndevts"
- **m_hVOEventScript**: resource_name:"soundevents/vo/vo_hero_kali.vsndevts"
- **m_strRosterSelectedSound**: soundevent:"Kali.VO.HeroPick"
- **m_strIconHeroCard**: panorama:"file://{images}/heroes/kali_card.psd"
- **m_strRosterRemovedSound**: soundevent:"Kali.VO.HeroRemove"
- **m_strTopBarImage**: panorama:"file://{images}/hud/hero_portraits/kali_hud.psd"
- **m_strUIShopAnimGraph**: resource_name:"models/heroes_staging/kali/ui_shop_kali.vanmgrph"
- **m_strUIShoppingMap**: maps/ui/hero_shop/kali_shop.vmap

---

# Hero: hero_warden

- **_class**: CitadelHeroData_t
- **m_bPlayerSelectable**: True
- **m_bDisabled**: False
- **m_bInDevelopment**: False
- **m_bNeedsTesting**: False
- **m_bAssignedPlayersOnly**: False
- **m_bBotSelectable**: True
- **m_bLimitedTesting**: False
- **m_nComplexity**: 2
- **m_nReadability**: 1
- **m_HeroID**: 25
- **m_strModelName**: resource_name:"models/heroes_staging/warden/warden.vmdl"
- **m_hDamageTakenParticle**: resource_name:"particles/generic/player_damage_screen.vpcf"
- **m_hGroundDamageTakenParticle**: resource_name:"particles/generic/player_ground_damage_screen.vpcf"
- **m_hDeathParticle**: resource_name:"particles/generic/player_death_screen.vpcf"
- **m_hLowHealthParticle**: resource_name:"particles/generic/player_low_health_screen.vpcf"
- **m_hRespawnParticle**: resource_name:"particles/generic/player_respawn_deploy.vpcf"
- **m_nModelSkin**: 0
- **m_mapStartingStats**:
  - **EMaxMoveSpeed**: 6.5
  - **ESprintSpeed**: 0
  - **ECrouchSpeed**: 4.75
  - **EMoveAcceleration**: 4
  - **ELightMeleeDamage**: 63
  - **EHeavyMeleeDamage**: 116
  - **EMaxHealth**: 550
  - **EWeaponPower**: 0
  - **EReloadSpeed**: 1
  - **EWeaponPowerScale**: 1
  - **EProcBuildUpRateScale**: 1
  - **EStamina**: 3
  - **EBaseHealthRegen**: 2.0
  - **EStaminaRegenPerSecond**: 0.2
  - **EAbilityResourceMax**: 0
  - **EAbilityResourceRegenPerSecond**: 0
  - **ECritDamageReceivedScale**: 1.0
  - **ETechDuration**: 1
  - **ETechRange**: 1
- **m_flCollisionRadius**: 20
- **m_flCollisionHeight**: 80
- **m_flStepHeight**: 32
- **m_mapBoundAbilities**:
  - **ESlot_Weapon_Primary**: citadel_weapon_warden_set
  - **ESlot_Weapon_Melee**: citadel_ability_melee_warden
  - **ESlot_Ability_Mantle**: citadel_ability_mantle
  - **ESlot_Ability_Jump**: citadel_ability_jump
  - **ESlot_Ability_Slide**: citadel_ability_slide
  - **ESlot_Ability_ZipLine**: citadel_ability_zip_line
  - **ESlot_Ability_ZipLineBoost**: citadel_ability_zipline_boost
  - **ESlot_Ability_Innate_1**: citadel_ability_dash
  - **ESlot_Ability_Innate_2**: citadel_ability_sprint
  - **ESlot_Ability_Innate_3**: citadel_ability_melee_parry
  - **ESlot_Signature_1**: ability_warden_crowd_control
  - **ESlot_Signature_2**: ability_warden_high_alert
  - **ESlot_Signature_3**: ability_warden_lock_down
  - **ESlot_Signature_4**: ability_warden_riot_protocol
- **m_mapItemSlotInfo**:
  - **EItemSlotType_WeaponMod**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
  - **EItemSlotType_Armor**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
  - **EItemSlotType_Tech**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
- **m_mapPurchaseBonuses**:
  - **EItemSlotType_WeaponMod**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 6 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 2 | 10 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 3 | 14 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 4 | 18 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
  - **EItemSlotType_Armor**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 11 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 2 | 14 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 3 | 17 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 4 | 20 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
  - **EItemSlotType_Tech**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 4 | MODIFIER_VALUE_TECH_POWER |
    | 2 | 8 | MODIFIER_VALUE_TECH_POWER |
    | 3 | 12 | MODIFIER_VALUE_TECH_POWER |
    | 4 | 16 | MODIFIER_VALUE_TECH_POWER |
- **m_mapLevelInfo**:
  - **1**:
    - **m_unRequiredGold**: 0
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **2**:
    - **m_unRequiredGold**: 400
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
      - **EAbilityPoints**: 1
  - **3**:
    - **m_unRequiredGold**: 800
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **4**:
    - **m_unRequiredGold**: 1200
    - **m_bUseStandardUpgrade**: True
  - **5**:
    - **m_unRequiredGold**: 1500
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **6**:
    - **m_unRequiredGold**: 2200
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **7**:
    - **m_unRequiredGold**: 3000
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **8**:
    - **m_unRequiredGold**: 4500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **9**:
    - **m_unRequiredGold**: 6000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **10**:
    - **m_unRequiredGold**: 7500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **11**:
    - **m_unRequiredGold**: 9000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **12**:
    - **m_unRequiredGold**: 10500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **13**:
    - **m_unRequiredGold**: 12000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **14**:
    - **m_unRequiredGold**: 13000
    - **m_bUseStandardUpgrade**: True
  - **15**:
    - **m_unRequiredGold**: 14000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **16**:
    - **m_unRequiredGold**: 15000
    - **m_bUseStandardUpgrade**: True
  - **17**:
    - **m_unRequiredGold**: 16000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **18**:
    - **m_unRequiredGold**: 18000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **19**:
    - **m_unRequiredGold**: 20000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **20**:
    - **m_unRequiredGold**: 22000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **21**:
    - **m_unRequiredGold**: 24000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **22**:
    - **m_unRequiredGold**: 27000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **23**:
    - **m_unRequiredGold**: 30000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **24**:
    - **m_unRequiredGold**: 33000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **25**:
    - **m_unRequiredGold**: 36000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **26**:
    - **m_unRequiredGold**: 39000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **27**:
    - **m_unRequiredGold**: 42000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **28**:
    - **m_unRequiredGold**: 45000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **29**:
    - **m_unRequiredGold**: 48000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
- **m_hFootstepSounds**: sweetener_default
- **m_strFootstepSoundEventDefault**: soundevent:"Warden.Footstep"
- **m_flStealthSpeedMetersPerSecond**: 4
- **m_flFootstepSoundTravelDistanceMeters**: 20
- **m_flStepSoundTime**: 0.33
- **m_vecAnimGraphDefaultValueOverrides**:
  | m_strParamName | m_strParamValue |
  | --- | --- |
  | e_SWITCH_4wayRoll_ON/OFF | 0 |
  | e_SWITCH_Recoil_ON/OFF | 0 |
  | e_SWITCH_ZiplinePhysicsSway_ON/OFF | 0 |
  | e_SWITCH_ShootStyle | 0 |
- **m_strLastHitSound**: soundevent:"LastHit.Default"
- **m_strLowHealthSound**: soundevent:"PlayerAlert.LowHealth"
- **m_colorUI**:
  - 85
  - 97
  - 120
- **m_colorGlowFriendly**:
  - 255
  - 239
  - 215
- **m_colorGlowEnemy**:
  - 255
  - 0
  - 0
- **m_colorGlowTeam1**:
  - 231
  - 182
  - 89
- **m_colorGlowTeam2**:
  - 91
  - 121
  - 230
- **m_vecAmbientParticleSettings**:
  | m_eAttachmentType | m_nCP |
  | --- | --- |
  | PATTACH_ABSORIGIN_FOLLOW | 0 |
  | PATTACH_POINT_FOLLOW | 1 |
- **m_heroStatsUI**:
  - **m_vecDisplayStats**:
    | m_eStatType | m_eStatCategory |
    | --- | --- |
    | EMaxHealth | ECitadelStat_Vitality |
    | EBaseHealthRegen | ECitadelStat_Vitality |
    | EBulletArmorDamageReduction | ECitadelStat_Vitality |
    | ETechArmorDamageReduction | ECitadelStat_Vitality |
    | ETechPower | ECitadelStat_Spirit |
    | EWeaponDPS | ECitadelStat_Weapon |
    | EBulletDamage | ECitadelStat_Weapon |
    | EClipSize | ECitadelStat_Weapon |
    | ERoundsPerSecond | ECitadelStat_Weapon |
    | ELightMeleeDamage | ECitadelStat_Weapon |
    | EHeavyMeleeDamage | ECitadelStat_Weapon |
    | EMaxMoveSpeed | ECitadelStat_Vitality |
    | ESprintSpeed | ECitadelStat_Vitality |
    | EStamina | ECitadelStat_Vitality |
  - **m_eWeaponStatDisplay**: EMeleeDamage_DEPRECATED
- **m_mapScalingStats**:
  - **ERoundsPerSecond**:
    - **eScalingStat**: ETechPower
    - **flScale**: 0.015
  - **EFireRate**:
    - **eScalingStat**: ETechPower
    - **flScale**: 0.375
- **m_heroStatsDisplay**:
  - **m_vecHealthHeaderStats**:
    - EMaxHealth
    - EBaseHealthRegen
  - **m_vecHealthStats**:
    - EBulletArmorDamageReduction
    - ETechArmorDamageReduction
    - EBulletShieldHealth
    - ETechShieldHealth
    - EBulletLifesteal
    - ETechLifesteal
    - EMaxMoveSpeed
    - ESprintSpeed
    - EStamina
    - EHealingOutput
  - **m_vecWeaponHeaderStats**:
    - EWeaponDPS
    - EBulletDamage
  - **m_vecWeaponStats**:
    - ELightMeleeDamage
    - EHeavyMeleeDamage
    - EFireRate
    - EClipSize
  - **m_vecMagicHeaderStats**:
    - ETechPower
  - **m_vecMagicStats**:
    - ETechCooldown
    - ETechRange
    - ETechDuration
- **m_mapStandardLevelUpUpgrades**:
  - **MODIFIER_VALUE_BASE_BULLET_DAMAGE_FROM_LEVEL**: 1.31
  - **MODIFIER_VALUE_BASE_MELEE_DAMAGE_FROM_LEVEL**: 3.4
  - **MODIFIER_VALUE_BASE_HEALTH_FROM_LEVEL**: 45.0
  - **MODIFIER_VALUE_TECH_DAMAGE_PERCENT**: 0.0
  - **MODIFIER_VALUE_BULLET_ARMOR_DAMAGE_RESIST**: 0.0
- **m_eAbilityResourceType**: EResourceType_None
- **m_ShopStatDisplay**:
  - **m_eWeaponStatsDisplay**:
    - **m_vecDisplayStats**:
      - EBulletDamage
      - EBaseWeaponDamageIncrease
      - ERoundsPerSecond
      - EFireRate
      - EClipSize
      - EClipSizeIncrease
      - EReloadTime
      - EReloadSpeed
      - EBulletSpeed
      - EBulletSpeedIncrease
      - EBulletLifesteal
    - **m_vecOtherDisplayStats**:
      - ELightMeleeDamage
      - EHeavyMeleeDamage
    - **m_eWeaponAttributes**: EWeaponAttribute_MediumRange | EWeaponAttribute_Projectile
    - **m_strWeaponImage**: panorama:"file://{images}/heroes/guns/warden_gun.psd"
  - **m_eVitalityStatsDisplay**:
    - **m_vecDisplayStats**:
      - EMaxHealth
      - EBaseHealthRegen
      - EBulletArmorDamageReduction
      - ETechArmorDamageReduction
      - EBulletShieldHealth
      - ETechShieldHealth
      - ECritDamageReceivedScale
    - **m_vecOtherDisplayStats**:
      - EMaxMoveSpeed
      - ESprintSpeed
      - EStaminaCooldown
      - EStaminaRegenIncrease
      - EStamina
  - **m_eSpiritStatsDisplay**:
    - **m_vecDisplayStats**:
      - ETechCooldown
      - ETechDuration
      - ETechRange
      - ETechLifesteal
      - EMaxChargesIncrease
      - ETechCooldownBetweenChargeUses
- **_base**: hero_base
- **m_strSelectionImage**: panorama:"file://{images}/heroes/warden.psd"
- **m_strIconImageSmall**: panorama:"file://{images}/heroes/warden_sm.psd"
- **m_strMinimapImage**: panorama:"file://{images}/heroes/warden_mm.psd"
- **m_strUIAnimGraph**: resource_name:"models/heroes_staging/warden/ui_warden.vanmgrph"
- **m_strPublicModelName**: resource_name:"models/heroes_staging/warden/warden.vmdl"
- **m_strDeathSound**: soundevent:"Warden.Death"
- **m_hGameSoundEventScript**: resource_name:"soundevents/hero/warden.vsndevts"
- **m_hVOEventScript**: resource_name:"soundevents/vo/vo_hero_warden.vsndevts"
- **m_strRosterSelectedSound**: soundevent:"Warden.VO.HeroPick"
- **m_strIconHeroCard**: panorama:"file://{images}/heroes/warden_card.psd"
- **m_hGeneratedVOEventScript**: resource_name:"soundevents/vo/generated_vo_hero_warden.vsndevts"
- **m_strRosterRemovedSound**: soundevent:"Warden.VO.HeroRemove"
- **m_strTopBarImage**: panorama:"file://{images}/hud/hero_portraits/warden_hud.psd"
- **m_RecommendedUpgrades**:
  - upgrade_endurance
  - upgrade_close_range
  - upgrade_non_player_bonus
  - upgrade_magic_reach
  - upgrade_fleetfoot_boots
  - upgrade_berserker
  - upgrade_cardio_calibrator
  - upgrade_bullet_armor
  - upgrade_tech_armor
  - upgrade_suppressor
  - upgrade_magic_slow
  - upgrade_close_quarter_combat
  - upgrade_improved_bullet_armor
  - upgrade_tech_purge
  - upgrade_unstoppable
  - upgrade_inhibitor
- **m_strUIPortraitMap**: maps/ui/hero_prefabs/warden.vmap
- **m_strTopBarVertical**: panorama:"file://{images}/heroes/warden_vertical.psd"
- **m_strUIShopAnimGraph**: resource_name:"models/heroes_staging/warden/ui_shop_warden.vanmgrph"
- **m_strUIShoppingMap**: maps/ui/hero_shop/warden_shop.vmap

---

# Hero: hero_yamato

- **_class**: CitadelHeroData_t
- **m_bPlayerSelectable**: True
- **m_bDisabled**: False
- **m_bInDevelopment**: False
- **m_bNeedsTesting**: False
- **m_bAssignedPlayersOnly**: False
- **m_bBotSelectable**: False
- **m_bLimitedTesting**: False
- **m_nComplexity**: 3
- **m_nReadability**: 0
- **m_HeroID**: 27
- **m_strModelName**: resource_name:"models/heroes_staging/yamato_v2/yamato.vmdl"
- **m_hDamageTakenParticle**: resource_name:"particles/generic/player_damage_screen.vpcf"
- **m_hGroundDamageTakenParticle**: resource_name:"particles/generic/player_ground_damage_screen.vpcf"
- **m_hDeathParticle**: resource_name:"particles/generic/player_death_screen.vpcf"
- **m_hLowHealthParticle**: resource_name:"particles/generic/player_low_health_screen.vpcf"
- **m_hRespawnParticle**: resource_name:"particles/generic/player_respawn_deploy.vpcf"
- **m_nModelSkin**: 0
- **m_mapStartingStats**:
  - **EMaxMoveSpeed**: 8.0
  - **ESprintSpeed**: 0
  - **ECrouchSpeed**: 4.75
  - **EMoveAcceleration**: 4
  - **ELightMeleeDamage**: 69
  - **EHeavyMeleeDamage**: 128
  - **EMaxHealth**: 500.0
  - **EWeaponPower**: 0
  - **EReloadSpeed**: 1
  - **EWeaponPowerScale**: 1
  - **EProcBuildUpRateScale**: 1
  - **EStamina**: 3
  - **EBaseHealthRegen**: 2.0
  - **EStaminaRegenPerSecond**: 0.2
  - **EAbilityResourceMax**: 0
  - **EAbilityResourceRegenPerSecond**: 0
  - **ECritDamageReceivedScale**: 1.0
  - **ETechDuration**: 1
  - **ETechRange**: 1
- **m_flCollisionRadius**: 20
- **m_flCollisionHeight**: 80
- **m_flStepHeight**: 32
- **m_mapBoundAbilities**:
  - **ESlot_Weapon_Primary**: citadel_weapon_yamato_set
  - **ESlot_Weapon_Melee**: ability_melee_yamato
  - **ESlot_Ability_Mantle**: citadel_ability_mantle
  - **ESlot_Ability_Jump**: citadel_ability_jump
  - **ESlot_Ability_Slide**: citadel_ability_slide
  - **ESlot_Ability_ZipLine**: citadel_ability_zip_line
  - **ESlot_Ability_ZipLineBoost**: citadel_ability_zipline_boost
  - **ESlot_Ability_Innate_1**: citadel_ability_dash
  - **ESlot_Ability_Innate_2**: citadel_ability_sprint
  - **ESlot_Ability_Innate_3**: citadel_ability_melee_parry
  - **ESlot_Weapon_Secondary**: citadel_weapon_yamato_alt
  - **ESlot_Signature_1**: citadel_ability_power_slash
  - **ESlot_Signature_2**: citadel_ability_flying_strike
  - **ESlot_Signature_3**: citadel_ability_healing_slash
  - **ESlot_Signature_4**: citadel_ability_infinity_slash
- **m_mapItemSlotInfo**:
  - **EItemSlotType_WeaponMod**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
  - **EItemSlotType_Armor**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
  - **EItemSlotType_Tech**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
- **m_mapPurchaseBonuses**:
  - **EItemSlotType_WeaponMod**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 6 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 2 | 10 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 3 | 14 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 4 | 18 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
  - **EItemSlotType_Armor**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 11 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 2 | 14 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 3 | 17 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 4 | 20 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
  - **EItemSlotType_Tech**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 4 | MODIFIER_VALUE_TECH_POWER |
    | 2 | 8 | MODIFIER_VALUE_TECH_POWER |
    | 3 | 12 | MODIFIER_VALUE_TECH_POWER |
    | 4 | 16 | MODIFIER_VALUE_TECH_POWER |
- **m_mapLevelInfo**:
  - **1**:
    - **m_unRequiredGold**: 0
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **2**:
    - **m_unRequiredGold**: 400
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
      - **EAbilityPoints**: 1
  - **3**:
    - **m_unRequiredGold**: 800
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **4**:
    - **m_unRequiredGold**: 1200
    - **m_bUseStandardUpgrade**: True
  - **5**:
    - **m_unRequiredGold**: 1500
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **6**:
    - **m_unRequiredGold**: 2200
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **7**:
    - **m_unRequiredGold**: 3000
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **8**:
    - **m_unRequiredGold**: 4500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **9**:
    - **m_unRequiredGold**: 6000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **10**:
    - **m_unRequiredGold**: 7500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **11**:
    - **m_unRequiredGold**: 9000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **12**:
    - **m_unRequiredGold**: 10500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **13**:
    - **m_unRequiredGold**: 12000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **14**:
    - **m_unRequiredGold**: 13000
    - **m_bUseStandardUpgrade**: True
  - **15**:
    - **m_unRequiredGold**: 14000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **16**:
    - **m_unRequiredGold**: 15000
    - **m_bUseStandardUpgrade**: True
  - **17**:
    - **m_unRequiredGold**: 16000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **18**:
    - **m_unRequiredGold**: 18000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **19**:
    - **m_unRequiredGold**: 20000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **20**:
    - **m_unRequiredGold**: 22000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **21**:
    - **m_unRequiredGold**: 24000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **22**:
    - **m_unRequiredGold**: 27000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **23**:
    - **m_unRequiredGold**: 30000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **24**:
    - **m_unRequiredGold**: 33000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **25**:
    - **m_unRequiredGold**: 36000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **26**:
    - **m_unRequiredGold**: 39000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **27**:
    - **m_unRequiredGold**: 42000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **28**:
    - **m_unRequiredGold**: 45000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **29**:
    - **m_unRequiredGold**: 48000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
- **m_hFootstepSounds**: sweetener_default
- **m_strFootstepSoundEventDefault**: soundevent:"Yamato.Footstep"
- **m_flStealthSpeedMetersPerSecond**: 4
- **m_flFootstepSoundTravelDistanceMeters**: 20
- **m_flStepSoundTime**: 0.325
- **m_vecAnimGraphDefaultValueOverrides**:
  | m_strParamName | m_strParamValue |
  | --- | --- |
  | e_SWITCH_4wayRoll_ON/OFF | 0 |
  | e_SWITCH_Recoil_ON/OFF | 0 |
  | e_SWITCH_ZiplinePhysicsSway_ON/OFF | 0 |
  | e_SWITCH_ShootStyle | 1 |
- **m_strLastHitSound**: soundevent:"LastHit.Default"
- **m_strLowHealthSound**: soundevent:"PlayerAlert.LowHealth"
- **m_colorUI**:
  - 110
  - 144
  - 128
- **m_colorGlowFriendly**:
  - 255
  - 239
  - 215
- **m_colorGlowEnemy**:
  - 255
  - 0
  - 0
- **m_colorGlowTeam1**:
  - 231
  - 182
  - 89
- **m_colorGlowTeam2**:
  - 91
  - 121
  - 230
- **m_vecAmbientParticleSettings**:
  | m_eAttachmentType | m_nCP |
  | --- | --- |
  | PATTACH_ABSORIGIN_FOLLOW | 0 |
  | PATTACH_POINT_FOLLOW | 1 |
- **m_heroStatsUI**:
  - **m_vecDisplayStats**:
    | m_eStatType | m_eStatCategory |
    | --- | --- |
    | EMaxHealth | ECitadelStat_Vitality |
    | EBaseHealthRegen | ECitadelStat_Vitality |
    | EBulletArmorDamageReduction | ECitadelStat_Vitality |
    | ETechArmorDamageReduction | ECitadelStat_Vitality |
    | ETechPower | ECitadelStat_Spirit |
    | EWeaponDPS | ECitadelStat_Weapon |
    | EBulletDamage | ECitadelStat_Weapon |
    | EClipSize | ECitadelStat_Weapon |
    | ERoundsPerSecond | ECitadelStat_Weapon |
    | ELightMeleeDamage | ECitadelStat_Weapon |
    | EHeavyMeleeDamage | ECitadelStat_Weapon |
    | EMaxMoveSpeed | ECitadelStat_Vitality |
    | ESprintSpeed | ECitadelStat_Vitality |
    | EStamina | ECitadelStat_Vitality |
  - **m_eWeaponStatDisplay**: EMeleeDamage_DEPRECATED
- **m_mapScalingStats**:
- **m_heroStatsDisplay**:
  - **m_vecHealthHeaderStats**:
    - EMaxHealth
    - EBaseHealthRegen
  - **m_vecHealthStats**:
    - EBulletArmorDamageReduction
    - ETechArmorDamageReduction
    - EBulletShieldHealth
    - ETechShieldHealth
    - EBulletLifesteal
    - ETechLifesteal
    - EMaxMoveSpeed
    - ESprintSpeed
    - EStamina
    - EHealingOutput
  - **m_vecWeaponHeaderStats**:
    - EWeaponDPS
    - EBulletDamage
  - **m_vecWeaponStats**:
    - ELightMeleeDamage
    - EHeavyMeleeDamage
    - EFireRate
    - EClipSize
  - **m_vecMagicHeaderStats**:
    - ETechPower
  - **m_vecMagicStats**:
    - ETechCooldown
    - ETechRange
    - ETechDuration
- **m_mapStandardLevelUpUpgrades**:
  - **MODIFIER_VALUE_BASE_BULLET_DAMAGE_FROM_LEVEL**: 0.5
  - **MODIFIER_VALUE_BASE_MELEE_DAMAGE_FROM_LEVEL**: 3.4
  - **MODIFIER_VALUE_BASE_HEALTH_FROM_LEVEL**: 31.0
  - **MODIFIER_VALUE_TECH_DAMAGE_PERCENT**: 0.0
  - **MODIFIER_VALUE_BULLET_ARMOR_DAMAGE_RESIST**: 0.0
- **m_eAbilityResourceType**: EResourceType_None
- **m_ShopStatDisplay**:
  - **m_eWeaponStatsDisplay**:
    - **m_vecDisplayStats**:
      - EBulletDamage
      - EBaseWeaponDamageIncrease
      - ERoundsPerSecond
      - EFireRate
      - EClipSize
      - EClipSizeIncrease
      - EReloadTime
      - EReloadSpeed
      - EBulletSpeed
      - EBulletSpeedIncrease
      - EBulletLifesteal
    - **m_vecOtherDisplayStats**:
      - ELightMeleeDamage
      - EHeavyMeleeDamage
    - **m_eWeaponAttributes**: EWeaponAttribute_Spreadshot | EWeaponAttribute_CloseRange
    - **m_strWeaponImage**: panorama:"file://{images}/heroes/guns/yamato_gun.psd"
  - **m_eVitalityStatsDisplay**:
    - **m_vecDisplayStats**:
      - EMaxHealth
      - EBaseHealthRegen
      - EBulletArmorDamageReduction
      - ETechArmorDamageReduction
      - EBulletShieldHealth
      - ETechShieldHealth
      - ECritDamageReceivedScale
    - **m_vecOtherDisplayStats**:
      - EMaxMoveSpeed
      - ESprintSpeed
      - EStaminaCooldown
      - EStaminaRegenIncrease
      - EStamina
  - **m_eSpiritStatsDisplay**:
    - **m_vecDisplayStats**:
      - ETechCooldown
      - ETechDuration
      - ETechRange
      - ETechLifesteal
      - EMaxChargesIncrease
      - ETechCooldownBetweenChargeUses
- **_base**: hero_base
- **m_strSelectionImage**: panorama:"file://{images}/heroes/yamato.psd"
- **m_strIconImageSmall**: panorama:"file://{images}/heroes/yamato_sm.psd"
- **m_strMinimapImage**: panorama:"file://{images}/heroes/yamato_mm.psd"
- **m_strUIAnimGraph**: resource_name:"models/heroes_staging/yamato_v2/ui_yamato.vanmgrph"
- **m_strDeathSound**: soundevent:"Yamato.Death"
- **m_hGameSoundEventScript**: resource_name:"soundevents/hero/yamato.vsndevts"
- **m_hVOEventScript**: resource_name:"soundevents/vo/vo_hero_yamato.vsndevts"
- **m_strRosterSelectedSound**: soundevent:"Yamato.VO.HeroPick"
- **m_strIconHeroCard**: panorama:"file://{images}/heroes/yamato_card.psd"
- **m_hGeneratedVOEventScript**: resource_name:"soundevents/vo/generated_vo_hero_yamato.vsndevts"
- **m_strRosterRemovedSound**: soundevent:"Yamato.VO.HeroRemove"
- **m_strTopBarImage**: panorama:"file://{images}/hud/hero_portraits/yamato_hud.psd"
- **m_strUIPortraitMap**: maps/ui/hero_prefabs/yamato.vmap
- **m_RecommendedUpgrades**:
  - upgrade_endurance
  - upgrade_close_range
  - upgrade_headshot_booster
  - upgrade_magic_burst
  - upgrade_improved_spirit
  - upgrade_resilience
  - upgrade_cold_front
  - upgrade_crackshot
  - upgrade_tech_defense_shredders
  - upgrade_bullet_armor
  - upgrade_tech_armor
  - upgrade_healbane
  - upgrade_magic_shock
  - upgrade_tech_damage_pulse
  - upgrade_soaring_spirit
  - upgrade_close_quarter_combat
  - upgrade_fervor
  - upgrade_mega_spirit
  - upgrade_ability_refresher
- **m_strTopBarVertical**: panorama:"file://{images}/heroes/yamato_vertical.psd"
- **m_strUIShopAnimGraph**: resource_name:"models/heroes_staging/yamato_v2/ui_shop_yamato.vanmgrph"
- **m_strUIShoppingMap**: maps/ui/hero_shop/yamato_shop.vmap

---

# Hero: hero_lash

- **_class**: CitadelHeroData_t
- **m_bPlayerSelectable**: True
- **m_bDisabled**: False
- **m_bInDevelopment**: False
- **m_bNeedsTesting**: False
- **m_bAssignedPlayersOnly**: False
- **m_bBotSelectable**: True
- **m_bLimitedTesting**: False
- **m_nComplexity**: 3
- **m_nReadability**: 2
- **m_HeroID**: 31
- **m_strModelName**: resource_name:"models/heroes_staging/lash_v2/lash.vmdl"
- **m_hDamageTakenParticle**: resource_name:"particles/generic/player_damage_screen.vpcf"
- **m_hGroundDamageTakenParticle**: resource_name:"particles/generic/player_ground_damage_screen.vpcf"
- **m_hDeathParticle**: resource_name:"particles/generic/player_death_screen.vpcf"
- **m_hLowHealthParticle**: resource_name:"particles/generic/player_low_health_screen.vpcf"
- **m_hRespawnParticle**: resource_name:"particles/generic/player_respawn_deploy.vpcf"
- **m_nModelSkin**: 0
- **m_mapStartingStats**:
  - **EMaxMoveSpeed**: 7
  - **ESprintSpeed**: 1
  - **ECrouchSpeed**: 4.75
  - **EMoveAcceleration**: 4
  - **ELightMeleeDamage**: 63
  - **EHeavyMeleeDamage**: 116
  - **EMaxHealth**: 550
  - **EWeaponPower**: 0
  - **EReloadSpeed**: 1
  - **EWeaponPowerScale**: 1
  - **EProcBuildUpRateScale**: 1
  - **EStamina**: 3
  - **EBaseHealthRegen**: 2.0
  - **EStaminaRegenPerSecond**: 0.2
  - **EAbilityResourceMax**: 0
  - **EAbilityResourceRegenPerSecond**: 0
  - **ECritDamageReceivedScale**: 1.0
  - **ETechDuration**: 1
  - **ETechRange**: 1
  - **ETechArmorDamageReduction**: 15.0
- **m_flCollisionRadius**: 20
- **m_flCollisionHeight**: 80
- **m_flStepHeight**: 32
- **m_mapBoundAbilities**:
  - **ESlot_Weapon_Primary**: citadel_weapon_lash_set
  - **ESlot_Weapon_Melee**: ability_melee_lash
  - **ESlot_Ability_Mantle**: citadel_ability_mantle
  - **ESlot_Ability_Jump**: citadel_ability_jump
  - **ESlot_Ability_Slide**: citadel_ability_slide
  - **ESlot_Ability_ZipLine**: citadel_ability_zip_line
  - **ESlot_Ability_ZipLineBoost**: citadel_ability_zipline_boost
  - **ESlot_Ability_Innate_1**: citadel_ability_dash
  - **ESlot_Ability_Innate_2**: citadel_ability_sprint
  - **ESlot_Ability_Innate_3**: citadel_ability_melee_parry
  - **ESlot_Signature_1**: citadel_ability_lash_down_strike
  - **ESlot_Signature_2**: citadel_ability_lash
  - **ESlot_Signature_3**: ability_lash_flog
  - **ESlot_Signature_4**: citadel_ability_lash_ultimate
- **m_mapItemSlotInfo**:
  - **EItemSlotType_WeaponMod**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
  - **EItemSlotType_Armor**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
  - **EItemSlotType_Tech**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
- **m_mapPurchaseBonuses**:
  - **EItemSlotType_WeaponMod**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 6 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 2 | 10 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 3 | 14 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 4 | 18 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
  - **EItemSlotType_Armor**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 11 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 2 | 14 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 3 | 17 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 4 | 20 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
  - **EItemSlotType_Tech**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 4 | MODIFIER_VALUE_TECH_POWER |
    | 2 | 8 | MODIFIER_VALUE_TECH_POWER |
    | 3 | 12 | MODIFIER_VALUE_TECH_POWER |
    | 4 | 16 | MODIFIER_VALUE_TECH_POWER |
- **m_mapLevelInfo**:
  - **1**:
    - **m_unRequiredGold**: 0
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **2**:
    - **m_unRequiredGold**: 400
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
      - **EAbilityPoints**: 1
  - **3**:
    - **m_unRequiredGold**: 800
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **4**:
    - **m_unRequiredGold**: 1200
    - **m_bUseStandardUpgrade**: True
  - **5**:
    - **m_unRequiredGold**: 1500
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **6**:
    - **m_unRequiredGold**: 2200
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **7**:
    - **m_unRequiredGold**: 3000
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **8**:
    - **m_unRequiredGold**: 4500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **9**:
    - **m_unRequiredGold**: 6000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **10**:
    - **m_unRequiredGold**: 7500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **11**:
    - **m_unRequiredGold**: 9000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **12**:
    - **m_unRequiredGold**: 10500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **13**:
    - **m_unRequiredGold**: 12000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **14**:
    - **m_unRequiredGold**: 13000
    - **m_bUseStandardUpgrade**: True
  - **15**:
    - **m_unRequiredGold**: 14000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **16**:
    - **m_unRequiredGold**: 15000
    - **m_bUseStandardUpgrade**: True
  - **17**:
    - **m_unRequiredGold**: 16000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **18**:
    - **m_unRequiredGold**: 18000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **19**:
    - **m_unRequiredGold**: 20000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **20**:
    - **m_unRequiredGold**: 22000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **21**:
    - **m_unRequiredGold**: 24000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **22**:
    - **m_unRequiredGold**: 27000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **23**:
    - **m_unRequiredGold**: 30000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **24**:
    - **m_unRequiredGold**: 33000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **25**:
    - **m_unRequiredGold**: 36000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **26**:
    - **m_unRequiredGold**: 39000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **27**:
    - **m_unRequiredGold**: 42000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **28**:
    - **m_unRequiredGold**: 45000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **29**:
    - **m_unRequiredGold**: 48000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
- **m_hFootstepSounds**: sweetener_default
- **m_strFootstepSoundEventDefault**: soundevent:"Lash.Footstep"
- **m_flStealthSpeedMetersPerSecond**: 4
- **m_flFootstepSoundTravelDistanceMeters**: 20
- **m_flStepSoundTime**: 0.24
- **m_vecAnimGraphDefaultValueOverrides**:
  | m_strParamName | m_strParamValue |
  | --- | --- |
  | e_SWITCH_4wayRoll_ON/OFF | 0 |
  | e_SWITCH_Recoil_ON/OFF | 0 |
  | e_SWITCH_ZiplinePhysicsSway_ON/OFF | 0 |
  | e_SWITCH_ShootStyle | 2 |
- **m_strLastHitSound**: soundevent:"LastHit.Default"
- **m_strLowHealthSound**: soundevent:"PlayerAlert.LowHealth"
- **m_colorUI**:
  - 66
  - 75
  - 86
- **m_colorGlowFriendly**:
  - 255
  - 239
  - 215
- **m_colorGlowEnemy**:
  - 255
  - 0
  - 0
- **m_colorGlowTeam1**:
  - 231
  - 182
  - 89
- **m_colorGlowTeam2**:
  - 91
  - 121
  - 230
- **m_vecAmbientParticleSettings**:
  | m_eAttachmentType | m_nCP |
  | --- | --- |
  | PATTACH_ABSORIGIN_FOLLOW | 0 |
  | PATTACH_POINT_FOLLOW | 1 |
- **m_heroStatsUI**:
  - **m_vecDisplayStats**:
    | m_eStatType | m_eStatCategory |
    | --- | --- |
    | EMaxHealth | ECitadelStat_Vitality |
    | EBaseHealthRegen | ECitadelStat_Vitality |
    | EBulletArmorDamageReduction | ECitadelStat_Vitality |
    | ETechArmorDamageReduction | ECitadelStat_Vitality |
    | ETechPower | ECitadelStat_Spirit |
    | EWeaponDPS | ECitadelStat_Weapon |
    | EBulletDamage | ECitadelStat_Weapon |
    | EClipSize | ECitadelStat_Weapon |
    | ERoundsPerSecond | ECitadelStat_Weapon |
    | ELightMeleeDamage | ECitadelStat_Weapon |
    | EHeavyMeleeDamage | ECitadelStat_Weapon |
    | EMaxMoveSpeed | ECitadelStat_Vitality |
    | ESprintSpeed | ECitadelStat_Vitality |
    | EStamina | ECitadelStat_Vitality |
  - **m_eWeaponStatDisplay**: EMeleeDamage_DEPRECATED
- **m_mapScalingStats**:
- **m_heroStatsDisplay**:
  - **m_vecHealthHeaderStats**:
    - EMaxHealth
    - EBaseHealthRegen
  - **m_vecHealthStats**:
    - EBulletArmorDamageReduction
    - ETechArmorDamageReduction
    - EBulletShieldHealth
    - ETechShieldHealth
    - EBulletLifesteal
    - ETechLifesteal
    - EMaxMoveSpeed
    - ESprintSpeed
    - EStamina
    - EHealingOutput
  - **m_vecWeaponHeaderStats**:
    - EWeaponDPS
    - EBulletDamage
  - **m_vecWeaponStats**:
    - ELightMeleeDamage
    - EHeavyMeleeDamage
    - EFireRate
    - EClipSize
  - **m_vecMagicHeaderStats**:
    - ETechPower
  - **m_vecMagicStats**:
    - ETechCooldown
    - ETechRange
    - ETechDuration
- **m_mapStandardLevelUpUpgrades**:
  - **MODIFIER_VALUE_BASE_BULLET_DAMAGE_FROM_LEVEL**: 1.15
  - **MODIFIER_VALUE_BASE_MELEE_DAMAGE_FROM_LEVEL**: 3.4
  - **MODIFIER_VALUE_BASE_HEALTH_FROM_LEVEL**: 42.0
  - **MODIFIER_VALUE_TECH_DAMAGE_PERCENT**: 0.0
  - **MODIFIER_VALUE_BULLET_ARMOR_DAMAGE_RESIST**: 0.0
- **m_eAbilityResourceType**: EResourceType_None
- **m_ShopStatDisplay**:
  - **m_eWeaponStatsDisplay**:
    - **m_vecDisplayStats**:
      - EBulletDamage
      - EBaseWeaponDamageIncrease
      - ERoundsPerSecond
      - EFireRate
      - EClipSize
      - EClipSizeIncrease
      - EReloadTime
      - EReloadSpeed
      - EBulletSpeed
      - EBulletSpeedIncrease
      - EBulletLifesteal
    - **m_vecOtherDisplayStats**:
      - ELightMeleeDamage
      - EHeavyMeleeDamage
    - **m_eWeaponAttributes**: EWeaponAttribute_BurstFire | EWeaponAttribute_MediumRange
    - **m_strWeaponImage**: panorama:"file://{images}/heroes/guns/lash_gun.psd"
  - **m_eVitalityStatsDisplay**:
    - **m_vecDisplayStats**:
      - EMaxHealth
      - EBaseHealthRegen
      - EBulletArmorDamageReduction
      - ETechArmorDamageReduction
      - EBulletShieldHealth
      - ETechShieldHealth
      - ECritDamageReceivedScale
    - **m_vecOtherDisplayStats**:
      - EMaxMoveSpeed
      - ESprintSpeed
      - EStaminaCooldown
      - EStaminaRegenIncrease
      - EStamina
  - **m_eSpiritStatsDisplay**:
    - **m_vecDisplayStats**:
      - ETechCooldown
      - ETechDuration
      - ETechRange
      - ETechLifesteal
      - EMaxChargesIncrease
      - ETechCooldownBetweenChargeUses
- **_base**: hero_base
- **m_strIconImageSmall**: panorama:"file://{images}/heroes/lash_sm.psd"
- **m_strMinimapImage**: panorama:"file://{images}/heroes/lash_mm.psd"
- **m_strUIAnimGraph**: resource_name:"models/heroes_staging/lash_v2/ui_lash.vanmgrph"
- **m_strDeathSound**: soundevent:"Lash.Death"
- **m_hVOEventScript**: resource_name:"soundevents/vo/vo_hero_lash.vsndevts"
- **m_strRosterSelectedSound**: soundevent:"Lash.VO.HeroPick"
- **m_strIconHeroCard**: panorama:"file://{images}/heroes/lash_card.psd"
- **m_strRosterRemovedSound**: soundevent:"Lash.VO.HeroRemove"
- **m_strTopBarImage**: panorama:"file://{images}/hud/hero_portraits/lash_hud.psd"
- **m_hGeneratedVOEventScript**: resource_name:"soundevents/vo/generated_vo_hero_lash.vsndevts"
- **m_strUIPortraitMap**: maps/ui/hero_prefabs/lash.vmap
- **m_RecommendedUpgrades**:
  - upgrade_magic_burst
  - upgrade_non_player_bonus
  - upgrade_close_range
  - upgrade_extra_charge
  - upgrade_sprint_booster
  - upgrade_magic_reach
  - upgrade_cold_front
  - upgrade_bullet_armor
  - upgrade_tech_armor
  - upgrade_superior_stamina
  - upgrade_rapid_recharge
  - upgrade_tech_range
  - upgrade_magic_shock
  - upgrade_chonky
- **m_hGameSoundEventScript**: resource_name:"soundevents/hero/lash.vsndevts"
- **m_strTopBarVertical**: panorama:"file://{images}/heroes/lash_vertical.psd"
- **m_strUIShopAnimGraph**: resource_name:"models/heroes_staging/lash_v2/ui_shop_lash.vanmgrph"
- **m_strUIShoppingMap**: maps/ui/hero_shop/lash_shop.vmap

---

# Hero: hero_viscous

- **_class**: CitadelHeroData_t
- **m_bPlayerSelectable**: True
- **m_bDisabled**: False
- **m_bInDevelopment**: False
- **m_bNeedsTesting**: False
- **m_bAssignedPlayersOnly**: False
- **m_bBotSelectable**: False
- **m_bLimitedTesting**: False
- **m_nComplexity**: 2
- **m_nReadability**: 3
- **m_HeroID**: 35
- **m_strModelName**: resource_name:"models/heroes_staging/viscous/viscous.vmdl"
- **m_hDamageTakenParticle**: resource_name:"particles/generic/player_damage_screen.vpcf"
- **m_hGroundDamageTakenParticle**: resource_name:"particles/generic/player_ground_damage_screen.vpcf"
- **m_hDeathParticle**: resource_name:"particles/generic/player_death_screen.vpcf"
- **m_hLowHealthParticle**: resource_name:"particles/generic/player_low_health_screen.vpcf"
- **m_hRespawnParticle**: resource_name:"particles/generic/player_respawn_deploy.vpcf"
- **m_nModelSkin**: 0
- **m_mapStartingStats**:
  - **EMaxMoveSpeed**: 7
  - **ESprintSpeed**: 0
  - **ECrouchSpeed**: 4.75
  - **EMoveAcceleration**: 4
  - **ELightMeleeDamage**: 63
  - **EHeavyMeleeDamage**: 116
  - **EMaxHealth**: 550
  - **EWeaponPower**: 0
  - **EReloadSpeed**: 1
  - **EWeaponPowerScale**: 1
  - **EProcBuildUpRateScale**: 1
  - **EStamina**: 3
  - **EBaseHealthRegen**: 2.0
  - **EStaminaRegenPerSecond**: 0.2
  - **EAbilityResourceMax**: 0
  - **EAbilityResourceRegenPerSecond**: 0
  - **ECritDamageReceivedScale**: 1.0
  - **ETechDuration**: 1
  - **ETechRange**: 1
- **m_flCollisionRadius**: 20
- **m_flCollisionHeight**: 80
- **m_flStepHeight**: 32
- **m_mapBoundAbilities**:
  - **ESlot_Weapon_Primary**: citadel_weapon_viscous_set
  - **ESlot_Weapon_Melee**: ability_melee_viscous
  - **ESlot_Ability_Mantle**: citadel_ability_mantle
  - **ESlot_Ability_Jump**: citadel_ability_jump
  - **ESlot_Ability_Slide**: citadel_ability_slide
  - **ESlot_Ability_ZipLine**: citadel_ability_zip_line
  - **ESlot_Ability_ZipLineBoost**: citadel_ability_zipline_boost
  - **ESlot_Ability_Innate_1**: citadel_ability_dash
  - **ESlot_Ability_Innate_2**: citadel_ability_sprint
  - **ESlot_Ability_Innate_3**: citadel_ability_melee_parry
  - **ESlot_Signature_1**: viscous_goo_grenade
  - **ESlot_Signature_2**: viscous_restorative_goo
  - **ESlot_Signature_3**: viscous_telepunch
  - **ESlot_Signature_4**: viscous_goo_bowling_ball
- **m_mapItemSlotInfo**:
  - **EItemSlotType_WeaponMod**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
  - **EItemSlotType_Armor**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
  - **EItemSlotType_Tech**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
- **m_mapPurchaseBonuses**:
  - **EItemSlotType_WeaponMod**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 6 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 2 | 10 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 3 | 14 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 4 | 18 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
  - **EItemSlotType_Armor**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 11 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 2 | 14 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 3 | 17 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 4 | 20 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
  - **EItemSlotType_Tech**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 4 | MODIFIER_VALUE_TECH_POWER |
    | 2 | 8 | MODIFIER_VALUE_TECH_POWER |
    | 3 | 12 | MODIFIER_VALUE_TECH_POWER |
    | 4 | 16 | MODIFIER_VALUE_TECH_POWER |
- **m_mapLevelInfo**:
  - **1**:
    - **m_unRequiredGold**: 0
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **2**:
    - **m_unRequiredGold**: 400
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
      - **EAbilityPoints**: 1
  - **3**:
    - **m_unRequiredGold**: 800
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **4**:
    - **m_unRequiredGold**: 1200
    - **m_bUseStandardUpgrade**: True
  - **5**:
    - **m_unRequiredGold**: 1500
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **6**:
    - **m_unRequiredGold**: 2200
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **7**:
    - **m_unRequiredGold**: 3000
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **8**:
    - **m_unRequiredGold**: 4500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **9**:
    - **m_unRequiredGold**: 6000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **10**:
    - **m_unRequiredGold**: 7500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **11**:
    - **m_unRequiredGold**: 9000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **12**:
    - **m_unRequiredGold**: 10500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **13**:
    - **m_unRequiredGold**: 12000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **14**:
    - **m_unRequiredGold**: 13000
    - **m_bUseStandardUpgrade**: True
  - **15**:
    - **m_unRequiredGold**: 14000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **16**:
    - **m_unRequiredGold**: 15000
    - **m_bUseStandardUpgrade**: True
  - **17**:
    - **m_unRequiredGold**: 16000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **18**:
    - **m_unRequiredGold**: 18000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **19**:
    - **m_unRequiredGold**: 20000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **20**:
    - **m_unRequiredGold**: 22000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **21**:
    - **m_unRequiredGold**: 24000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **22**:
    - **m_unRequiredGold**: 27000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **23**:
    - **m_unRequiredGold**: 30000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **24**:
    - **m_unRequiredGold**: 33000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **25**:
    - **m_unRequiredGold**: 36000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **26**:
    - **m_unRequiredGold**: 39000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **27**:
    - **m_unRequiredGold**: 42000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **28**:
    - **m_unRequiredGold**: 45000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **29**:
    - **m_unRequiredGold**: 48000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
- **m_hFootstepSounds**: sweetener_default
- **m_strFootstepSoundEventDefault**: soundevent:"Viscous.Footstep"
- **m_flStealthSpeedMetersPerSecond**: 4
- **m_flFootstepSoundTravelDistanceMeters**: 20
- **m_flStepSoundTime**: 0.3
- **m_vecAnimGraphDefaultValueOverrides**:
  | m_strParamName | m_strParamValue |
  | --- | --- |
  | e_SWITCH_4wayRoll_ON/OFF | 0 |
  | e_SWITCH_Recoil_ON/OFF | 0 |
  | e_SWITCH_ZiplinePhysicsSway_ON/OFF | 0 |
  | e_SWITCH_ShootStyle | 0 |
- **m_strLastHitSound**: soundevent:"LastHit.Default"
- **m_strLowHealthSound**: soundevent:"PlayerAlert.LowHealth"
- **m_colorUI**:
  - 136
  - 195
  - 99
- **m_colorGlowFriendly**:
  - 255
  - 239
  - 215
- **m_colorGlowEnemy**:
  - 255
  - 0
  - 0
- **m_colorGlowTeam1**:
  - 231
  - 182
  - 89
- **m_colorGlowTeam2**:
  - 91
  - 121
  - 230
- **m_vecAmbientParticleSettings**:
  | m_eAttachmentType | m_nCP |
  | --- | --- |
  | PATTACH_ABSORIGIN_FOLLOW | 0 |
  | PATTACH_POINT_FOLLOW | 1 |
- **m_heroStatsUI**:
  - **m_vecDisplayStats**:
    | m_eStatType | m_eStatCategory |
    | --- | --- |
    | EMaxHealth | ECitadelStat_Vitality |
    | EBaseHealthRegen | ECitadelStat_Vitality |
    | EBulletArmorDamageReduction | ECitadelStat_Vitality |
    | ETechArmorDamageReduction | ECitadelStat_Vitality |
    | ETechPower | ECitadelStat_Spirit |
    | EWeaponDPS | ECitadelStat_Weapon |
    | EBulletDamage | ECitadelStat_Weapon |
    | EClipSize | ECitadelStat_Weapon |
    | ERoundsPerSecond | ECitadelStat_Weapon |
    | ELightMeleeDamage | ECitadelStat_Weapon |
    | EHeavyMeleeDamage | ECitadelStat_Weapon |
    | EMaxMoveSpeed | ECitadelStat_Vitality |
    | ESprintSpeed | ECitadelStat_Vitality |
    | EStamina | ECitadelStat_Vitality |
  - **m_eWeaponStatDisplay**: EMeleeDamage_DEPRECATED
- **m_mapScalingStats**:
- **m_heroStatsDisplay**:
  - **m_vecHealthHeaderStats**:
    - EMaxHealth
    - EBaseHealthRegen
  - **m_vecHealthStats**:
    - EBulletArmorDamageReduction
    - ETechArmorDamageReduction
    - EBulletShieldHealth
    - ETechShieldHealth
    - EBulletLifesteal
    - ETechLifesteal
    - EMaxMoveSpeed
    - ESprintSpeed
    - EStamina
    - EHealingOutput
  - **m_vecWeaponHeaderStats**:
    - EWeaponDPS
    - EBulletDamage
  - **m_vecWeaponStats**:
    - ELightMeleeDamage
    - EHeavyMeleeDamage
    - EFireRate
    - EClipSize
  - **m_vecMagicHeaderStats**:
    - ETechPower
  - **m_vecMagicStats**:
    - ETechCooldown
    - ETechRange
    - ETechDuration
- **m_mapStandardLevelUpUpgrades**:
  - **MODIFIER_VALUE_BASE_BULLET_DAMAGE_FROM_LEVEL**: 0.9
  - **MODIFIER_VALUE_BASE_MELEE_DAMAGE_FROM_LEVEL**: 3.4
  - **MODIFIER_VALUE_BASE_HEALTH_FROM_LEVEL**: 38.0
  - **MODIFIER_VALUE_TECH_DAMAGE_PERCENT**: 0.0
  - **MODIFIER_VALUE_BULLET_ARMOR_DAMAGE_RESIST**: 0.0
- **m_eAbilityResourceType**: EResourceType_None
- **m_ShopStatDisplay**:
  - **m_eWeaponStatsDisplay**:
    - **m_vecDisplayStats**:
      - EBulletDamage
      - EBaseWeaponDamageIncrease
      - ERoundsPerSecond
      - EFireRate
      - EClipSize
      - EClipSizeIncrease
      - EReloadTime
      - EReloadSpeed
      - EBulletSpeed
      - EBulletSpeedIncrease
      - EBulletLifesteal
    - **m_vecOtherDisplayStats**:
      - ELightMeleeDamage
      - EHeavyMeleeDamage
    - **m_eWeaponAttributes**: EWeaponAttribute_MediumRange | EWeaponAttribute_Projectile
    - **m_strWeaponImage**: panorama:"file://{images}/heroes/guns/viscous_gun.psd"
  - **m_eVitalityStatsDisplay**:
    - **m_vecDisplayStats**:
      - EMaxHealth
      - EBaseHealthRegen
      - EBulletArmorDamageReduction
      - ETechArmorDamageReduction
      - EBulletShieldHealth
      - ETechShieldHealth
      - ECritDamageReceivedScale
    - **m_vecOtherDisplayStats**:
      - EMaxMoveSpeed
      - ESprintSpeed
      - EStaminaCooldown
      - EStaminaRegenIncrease
      - EStamina
  - **m_eSpiritStatsDisplay**:
    - **m_vecDisplayStats**:
      - ETechCooldown
      - ETechDuration
      - ETechRange
      - ETechLifesteal
      - EMaxChargesIncrease
      - ETechCooldownBetweenChargeUses
- **_base**: hero_base
- **m_strSelectionImage**: panorama:"file://{images}/heroes/viscous.psd"
- **m_strIconImageSmall**: panorama:"file://{images}/heroes/viscous_sm.psd"
- **m_strMinimapImage**: panorama:"file://{images}/heroes/viscous_mm.psd"
- **m_strUIAnimGraph**: resource_name:"models/heroes_staging/viscous/ui_viscous.vanmgrph"
- **m_strDeathSound**: soundevent:"Viscous.Death"
- **m_strWIPModelName**: resource_name:"models/heroes_staging/viscous_v2/viscous.vmdl"
- **m_mapWIPAbilities**:
- **m_hGameSoundEventScript**: resource_name:"soundevents/hero/viscous.vsndevts"
- **m_hVOEventScript**: resource_name:"soundevents/vo/vo_hero_viscous.vsndevts"
- **m_strRosterSelectedSound**: soundevent:"Viscous.VO.HeroPick"
- **m_strIconHeroCard**: panorama:"file://{images}/heroes/viscous_card.psd"
- **m_strRosterRemovedSound**: soundevent:"Viscous.VO.HeroRemove"
- **m_strTopBarImage**: panorama:"file://{images}/hud/hero_portraits/viscous_hud.psd"
- **m_strTopBarVertical**: panorama:"file://{images}/heroes/viscous_vertical.psd"
- **m_strUIPortraitMap**: maps/ui/hero_prefabs/viscous.vmap
- **m_hGeneratedVOEventScript**: resource_name:"soundevents/vo/generated_vo_hero_viscous.vsndevts"
- **m_RecommendedUpgrades**:
  - upgrade_non_player_bonus
  - upgrade_magic_burst
  - upgrade_resilience
  - upgrade_extra_charge
  - upgrade_improved_spirit
  - upgrade_berserker
  - upgrade_healing_booster
  - upgrade_bullet_armor
  - upgrade_tech_armor
  - upgrade_magic_shock
  - upgrade_rapid_recharge
  - upgrade_tech_damage_pulse
  - upgrade_magic_reach
  - upgrade_soaring_spirit
  - upgrade_tech_purge
  - upgrade_critshot
- **m_strUIShopAnimGraph**: resource_name:"models/heroes_staging/viscous/ui_shop_viscous.vanmgrph"
- **m_strUIShoppingMap**: maps/ui/hero_shop/viscous_shop.vmap

---

# Hero: hero_gunslinger

- **_class**: CitadelHeroData_t
- **m_bPlayerSelectable**: True
- **m_bDisabled**: True
- **m_bInDevelopment**: True
- **m_bNeedsTesting**: True
- **m_bAssignedPlayersOnly**: False
- **m_bBotSelectable**: False
- **m_bLimitedTesting**: False
- **m_nComplexity**: 2
- **m_nReadability**: 1
- **m_HeroID**: 38
- **m_strModelName**: resource_name:"models/heroes_staging/gunslinger/gunslinger.vmdl"
- **m_hDamageTakenParticle**: resource_name:"particles/generic/player_damage_screen.vpcf"
- **m_hGroundDamageTakenParticle**: resource_name:"particles/generic/player_ground_damage_screen.vpcf"
- **m_hDeathParticle**: resource_name:"particles/generic/player_death_screen.vpcf"
- **m_hLowHealthParticle**: resource_name:"particles/generic/player_low_health_screen.vpcf"
- **m_hRespawnParticle**: resource_name:"particles/generic/player_respawn_deploy.vpcf"
- **m_nModelSkin**: 0
- **m_mapStartingStats**:
  - **EMaxMoveSpeed**: 7
  - **ESprintSpeed**: 0
  - **ECrouchSpeed**: 4.75
  - **EMoveAcceleration**: 4
  - **ELightMeleeDamage**: 63
  - **EHeavyMeleeDamage**: 116
  - **EMaxHealth**: 550
  - **EWeaponPower**: 0
  - **EReloadSpeed**: 1
  - **EWeaponPowerScale**: 1
  - **EProcBuildUpRateScale**: 1
  - **EStamina**: 3
  - **EBaseHealthRegen**: 2.0
  - **EStaminaRegenPerSecond**: 0.2
  - **EAbilityResourceMax**: 0
  - **EAbilityResourceRegenPerSecond**: 0
  - **ECritDamageReceivedScale**: 1.0
  - **ETechDuration**: 1
  - **ETechRange**: 1
- **m_flCollisionRadius**: 20
- **m_flCollisionHeight**: 80
- **m_flStepHeight**: 32
- **m_mapBoundAbilities**:
  - **ESlot_Weapon_Primary**: citadel_weapon_gunslinger_set
  - **ESlot_Weapon_Melee**: citadel_ability_melee_gunslinger
  - **ESlot_Ability_Mantle**: citadel_ability_mantle
  - **ESlot_Ability_Jump**: citadel_ability_jump
  - **ESlot_Ability_Slide**: citadel_ability_slide
  - **ESlot_Ability_ZipLine**: citadel_ability_zip_line
  - **ESlot_Ability_ZipLineBoost**: citadel_ability_zipline_boost
  - **ESlot_Ability_Innate_1**: citadel_ability_dash
  - **ESlot_Ability_Innate_2**: citadel_ability_sprint
  - **ESlot_Ability_Innate_3**: citadel_ability_melee_parry
  - **ESlot_Signature_1**: gunslinger_rapid_fire
  - **ESlot_Signature_2**: gunslinger_rocket_launcher
  - **ESlot_Signature_3**: gunslinger_tenacity
  - **ESlot_Signature_4**: gunslinger_sleep_bomb
- **m_mapItemSlotInfo**:
  - **EItemSlotType_WeaponMod**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
  - **EItemSlotType_Armor**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
  - **EItemSlotType_Tech**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
- **m_mapPurchaseBonuses**:
  - **EItemSlotType_WeaponMod**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 6 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 2 | 10 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 3 | 14 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 4 | 18 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
  - **EItemSlotType_Armor**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 11 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 2 | 14 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 3 | 17 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 4 | 20 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
  - **EItemSlotType_Tech**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 4 | MODIFIER_VALUE_TECH_POWER |
    | 2 | 8 | MODIFIER_VALUE_TECH_POWER |
    | 3 | 12 | MODIFIER_VALUE_TECH_POWER |
    | 4 | 16 | MODIFIER_VALUE_TECH_POWER |
- **m_mapLevelInfo**:
  - **1**:
    - **m_unRequiredGold**: 0
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **2**:
    - **m_unRequiredGold**: 400
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
      - **EAbilityPoints**: 1
  - **3**:
    - **m_unRequiredGold**: 800
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **4**:
    - **m_unRequiredGold**: 1200
    - **m_bUseStandardUpgrade**: True
  - **5**:
    - **m_unRequiredGold**: 1500
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **6**:
    - **m_unRequiredGold**: 2200
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **7**:
    - **m_unRequiredGold**: 3000
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **8**:
    - **m_unRequiredGold**: 4500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **9**:
    - **m_unRequiredGold**: 6000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **10**:
    - **m_unRequiredGold**: 7500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **11**:
    - **m_unRequiredGold**: 9000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **12**:
    - **m_unRequiredGold**: 10500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **13**:
    - **m_unRequiredGold**: 12000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **14**:
    - **m_unRequiredGold**: 13000
    - **m_bUseStandardUpgrade**: True
  - **15**:
    - **m_unRequiredGold**: 14000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **16**:
    - **m_unRequiredGold**: 15000
    - **m_bUseStandardUpgrade**: True
  - **17**:
    - **m_unRequiredGold**: 16000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **18**:
    - **m_unRequiredGold**: 18000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **19**:
    - **m_unRequiredGold**: 20000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **20**:
    - **m_unRequiredGold**: 22000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **21**:
    - **m_unRequiredGold**: 24000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **22**:
    - **m_unRequiredGold**: 27000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **23**:
    - **m_unRequiredGold**: 30000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **24**:
    - **m_unRequiredGold**: 33000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **25**:
    - **m_unRequiredGold**: 36000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **26**:
    - **m_unRequiredGold**: 39000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **27**:
    - **m_unRequiredGold**: 42000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **28**:
    - **m_unRequiredGold**: 45000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **29**:
    - **m_unRequiredGold**: 48000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
- **m_hFootstepSounds**: sweetener_default
- **m_strFootstepSoundEventDefault**: soundevent:"Hero.Default.Footstep"
- **m_flStealthSpeedMetersPerSecond**: 4
- **m_flFootstepSoundTravelDistanceMeters**: 20
- **m_flStepSoundTime**: 0.3
- **m_vecAnimGraphDefaultValueOverrides**:
  | m_strParamName | m_strParamValue |
  | --- | --- |
  | e_SWITCH_4wayRoll_ON/OFF | 0 |
  | e_SWITCH_Recoil_ON/OFF | 1 |
  | e_SWITCH_ZiplinePhysicsSway_ON/OFF | 0 |
  | e_SWITCH_ShootStyle | 2 |
- **m_strLastHitSound**: soundevent:"LastHit.Default"
- **m_strLowHealthSound**: soundevent:"PlayerAlert.LowHealth"
- **m_colorUI**:
  - 255
  - 255
  - 255
- **m_colorGlowFriendly**:
  - 255
  - 239
  - 215
- **m_colorGlowEnemy**:
  - 255
  - 0
  - 0
- **m_colorGlowTeam1**:
  - 231
  - 182
  - 89
- **m_colorGlowTeam2**:
  - 91
  - 121
  - 230
- **m_vecAmbientParticleSettings**:
  | m_eAttachmentType | m_nCP |
  | --- | --- |
  | PATTACH_ABSORIGIN_FOLLOW | 0 |
  | PATTACH_POINT_FOLLOW | 1 |
- **m_heroStatsUI**:
  - **m_vecDisplayStats**:
    | m_eStatType | m_eStatCategory |
    | --- | --- |
    | EMaxHealth | ECitadelStat_Vitality |
    | EBaseHealthRegen | ECitadelStat_Vitality |
    | EBulletArmorDamageReduction | ECitadelStat_Vitality |
    | ETechArmorDamageReduction | ECitadelStat_Vitality |
    | ETechPower | ECitadelStat_Spirit |
    | EWeaponDPS | ECitadelStat_Weapon |
    | EBulletDamage | ECitadelStat_Weapon |
    | EClipSize | ECitadelStat_Weapon |
    | ERoundsPerSecond | ECitadelStat_Weapon |
    | ELightMeleeDamage | ECitadelStat_Weapon |
    | EHeavyMeleeDamage | ECitadelStat_Weapon |
    | EMaxMoveSpeed | ECitadelStat_Vitality |
    | ESprintSpeed | ECitadelStat_Vitality |
    | EStamina | ECitadelStat_Vitality |
  - **m_eWeaponStatDisplay**: EMeleeDamage_DEPRECATED
- **m_mapScalingStats**:
- **m_heroStatsDisplay**:
  - **m_vecHealthHeaderStats**:
    - EMaxHealth
    - EBaseHealthRegen
  - **m_vecHealthStats**:
    - EBulletArmorDamageReduction
    - ETechArmorDamageReduction
    - EBulletShieldHealth
    - ETechShieldHealth
    - EBulletLifesteal
    - ETechLifesteal
    - EMaxMoveSpeed
    - ESprintSpeed
    - EStamina
    - EHealingOutput
  - **m_vecWeaponHeaderStats**:
    - EWeaponDPS
    - EBulletDamage
  - **m_vecWeaponStats**:
    - ELightMeleeDamage
    - EHeavyMeleeDamage
    - EFireRate
    - EClipSize
  - **m_vecMagicHeaderStats**:
    - ETechPower
  - **m_vecMagicStats**:
    - ETechCooldown
    - ETechRange
    - ETechDuration
- **m_mapStandardLevelUpUpgrades**:
  - **MODIFIER_VALUE_BASE_BULLET_DAMAGE_FROM_LEVEL**: 0.0
  - **MODIFIER_VALUE_BASE_MELEE_DAMAGE_FROM_LEVEL**: 3.4
  - **MODIFIER_VALUE_BASE_HEALTH_FROM_LEVEL**: 41.0
  - **MODIFIER_VALUE_TECH_DAMAGE_PERCENT**: 0.0
  - **MODIFIER_VALUE_BULLET_ARMOR_DAMAGE_RESIST**: 0.0
- **m_eAbilityResourceType**: EResourceType_None
- **m_ShopStatDisplay**:
  - **m_eWeaponStatsDisplay**:
    - **m_vecDisplayStats**:
      - EBulletDamage
      - EBaseWeaponDamageIncrease
      - ERoundsPerSecond
      - EFireRate
      - EClipSize
      - EClipSizeIncrease
      - EReloadTime
      - EReloadSpeed
      - EBulletSpeed
      - EBulletSpeedIncrease
      - EBulletLifesteal
    - **m_vecOtherDisplayStats**:
      - ELightMeleeDamage
      - EHeavyMeleeDamage
  - **m_eVitalityStatsDisplay**:
    - **m_vecDisplayStats**:
      - EMaxHealth
      - EBaseHealthRegen
      - EBulletArmorDamageReduction
      - ETechArmorDamageReduction
      - EBulletShieldHealth
      - ETechShieldHealth
      - ECritDamageReceivedScale
    - **m_vecOtherDisplayStats**:
      - EMaxMoveSpeed
      - ESprintSpeed
      - EStaminaCooldown
      - EStaminaRegenIncrease
      - EStamina
  - **m_eSpiritStatsDisplay**:
    - **m_vecDisplayStats**:
      - ETechCooldown
      - ETechDuration
      - ETechRange
      - ETechLifesteal
      - EMaxChargesIncrease
      - ETechCooldownBetweenChargeUses
- **_base**: hero_base
- **m_strSelectionImage**: panorama:"file://{images}/heroes/gunslinger.psd"
- **m_strIconImageSmall**: panorama:"file://{images}/heroes/gunslinger_sm.psd"
- **m_strMinimapImage**: panorama:"file://{images}/heroes/gunslinger_mm.psd"
- **m_strUIAnimGraph**: resource_name:"models/heroes_staging/gunslinger/ui_gunslinger.vanmgrph"
- **m_strDeathSound**: soundevent:"Player.DeathFemale"
- **m_hGameSoundEventScript**: resource_name:"soundevents/game_sounds_heroes/game_sounds_hero_gunslinger.vsndevts"
- **m_hVOEventScript**: resource_name:"soundevents/vo/vo_hero_gunslinger.vsndevts"
- **m_strIconHeroCard**: panorama:"file://{images}/heroes/gunslinger_sm.psd"

---

# Hero: hero_yakuza

- **_class**: CitadelHeroData_t
- **m_bPlayerSelectable**: True
- **m_bDisabled**: True
- **m_bInDevelopment**: True
- **m_bNeedsTesting**: False
- **m_bAssignedPlayersOnly**: False
- **m_bBotSelectable**: False
- **m_bLimitedTesting**: False
- **m_nComplexity**: 2
- **m_nReadability**: 1
- **m_HeroID**: 39
- **m_strModelName**: resource_name:"models/heroes_staging/yakuza/yakuza.vmdl"
- **m_hDamageTakenParticle**: resource_name:"particles/generic/player_damage_screen.vpcf"
- **m_hGroundDamageTakenParticle**: resource_name:"particles/generic/player_ground_damage_screen.vpcf"
- **m_hDeathParticle**: resource_name:"particles/generic/player_death_screen.vpcf"
- **m_hLowHealthParticle**: resource_name:"particles/generic/player_low_health_screen.vpcf"
- **m_hRespawnParticle**: resource_name:"particles/generic/player_respawn_deploy.vpcf"
- **m_nModelSkin**: 0
- **m_mapStartingStats**:
  - **EMaxMoveSpeed**: 7
  - **ESprintSpeed**: 0
  - **ECrouchSpeed**: 4.75
  - **EMoveAcceleration**: 4
  - **ELightMeleeDamage**: 63
  - **EHeavyMeleeDamage**: 116
  - **EMaxHealth**: 550
  - **EWeaponPower**: 0
  - **EReloadSpeed**: 1
  - **EWeaponPowerScale**: 1
  - **EProcBuildUpRateScale**: 1
  - **EStamina**: 3
  - **EBaseHealthRegen**: 2.0
  - **EStaminaRegenPerSecond**: 0.2
  - **EAbilityResourceMax**: 0
  - **EAbilityResourceRegenPerSecond**: 0
  - **ECritDamageReceivedScale**: 1.0
  - **ETechDuration**: 1
  - **ETechRange**: 1
- **m_flCollisionRadius**: 20
- **m_flCollisionHeight**: 80
- **m_flStepHeight**: 32
- **m_mapBoundAbilities**:
  - **ESlot_Weapon_Primary**: citadel_weapon_yakuza_set
  - **ESlot_Weapon_Melee**: citadel_ability_melee_yakuza
  - **ESlot_Ability_Mantle**: citadel_ability_mantle
  - **ESlot_Ability_Jump**: citadel_ability_jump
  - **ESlot_Ability_Slide**: citadel_ability_slide
  - **ESlot_Ability_ZipLine**: citadel_ability_zip_line
  - **ESlot_Ability_ZipLineBoost**: citadel_ability_zipline_boost
  - **ESlot_Ability_Innate_1**: citadel_ability_dash
  - **ESlot_Ability_Innate_2**: citadel_ability_sprint
  - **ESlot_Ability_Innate_3**: citadel_ability_melee_parry
  - **ESlot_Signature_1**: yakuza_shakedown_target
  - **ESlot_Signature_2**: yakuza_kobun
  - **ESlot_Signature_3**: yakuza_protection_racket
  - **ESlot_Signature_4**: yakuza_setting_sun
- **m_mapItemSlotInfo**:
  - **EItemSlotType_WeaponMod**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
  - **EItemSlotType_Armor**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
  - **EItemSlotType_Tech**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
- **m_mapPurchaseBonuses**:
  - **EItemSlotType_WeaponMod**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 6 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 2 | 10 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 3 | 14 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 4 | 18 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
  - **EItemSlotType_Armor**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 11 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 2 | 14 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 3 | 17 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 4 | 20 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
  - **EItemSlotType_Tech**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 4 | MODIFIER_VALUE_TECH_POWER |
    | 2 | 8 | MODIFIER_VALUE_TECH_POWER |
    | 3 | 12 | MODIFIER_VALUE_TECH_POWER |
    | 4 | 16 | MODIFIER_VALUE_TECH_POWER |
- **m_mapLevelInfo**:
  - **1**:
    - **m_unRequiredGold**: 0
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **2**:
    - **m_unRequiredGold**: 400
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
      - **EAbilityPoints**: 1
  - **3**:
    - **m_unRequiredGold**: 800
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **4**:
    - **m_unRequiredGold**: 1200
    - **m_bUseStandardUpgrade**: True
  - **5**:
    - **m_unRequiredGold**: 1500
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **6**:
    - **m_unRequiredGold**: 2200
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **7**:
    - **m_unRequiredGold**: 3000
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **8**:
    - **m_unRequiredGold**: 4500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **9**:
    - **m_unRequiredGold**: 6000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **10**:
    - **m_unRequiredGold**: 7500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **11**:
    - **m_unRequiredGold**: 9000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **12**:
    - **m_unRequiredGold**: 10500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **13**:
    - **m_unRequiredGold**: 12000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **14**:
    - **m_unRequiredGold**: 13000
    - **m_bUseStandardUpgrade**: True
  - **15**:
    - **m_unRequiredGold**: 14000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **16**:
    - **m_unRequiredGold**: 15000
    - **m_bUseStandardUpgrade**: True
  - **17**:
    - **m_unRequiredGold**: 16000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **18**:
    - **m_unRequiredGold**: 18000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **19**:
    - **m_unRequiredGold**: 20000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **20**:
    - **m_unRequiredGold**: 22000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **21**:
    - **m_unRequiredGold**: 24000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **22**:
    - **m_unRequiredGold**: 27000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **23**:
    - **m_unRequiredGold**: 30000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **24**:
    - **m_unRequiredGold**: 33000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **25**:
    - **m_unRequiredGold**: 36000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **26**:
    - **m_unRequiredGold**: 39000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **27**:
    - **m_unRequiredGold**: 42000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **28**:
    - **m_unRequiredGold**: 45000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **29**:
    - **m_unRequiredGold**: 48000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
- **m_hFootstepSounds**: sweetener_default
- **m_strFootstepSoundEventDefault**: soundevent:"Hero.Default.Footstep"
- **m_flStealthSpeedMetersPerSecond**: 4
- **m_flFootstepSoundTravelDistanceMeters**: 20
- **m_flStepSoundTime**: 0.3
- **m_vecAnimGraphDefaultValueOverrides**:
  | m_strParamName | m_strParamValue |
  | --- | --- |
  | e_SWITCH_4wayRoll_ON/OFF | 0 |
  | e_SWITCH_Recoil_ON/OFF | 0 |
  | e_SWITCH_ZiplinePhysicsSway_ON/OFF | 0 |
  | e_SWITCH_ShootStyle | 0 |
- **m_strLastHitSound**: soundevent:"LastHit.Default"
- **m_strLowHealthSound**: soundevent:"PlayerAlert.LowHealth"
- **m_colorUI**:
  - 255
  - 255
  - 255
- **m_colorGlowFriendly**:
  - 255
  - 239
  - 215
- **m_colorGlowEnemy**:
  - 255
  - 0
  - 0
- **m_colorGlowTeam1**:
  - 231
  - 182
  - 89
- **m_colorGlowTeam2**:
  - 91
  - 121
  - 230
- **m_vecAmbientParticleSettings**:
  | m_eAttachmentType | m_nCP |
  | --- | --- |
  | PATTACH_ABSORIGIN_FOLLOW | 0 |
  | PATTACH_POINT_FOLLOW | 1 |
- **m_heroStatsUI**:
  - **m_vecDisplayStats**:
    | m_eStatType | m_eStatCategory |
    | --- | --- |
    | EMaxHealth | ECitadelStat_Vitality |
    | EBaseHealthRegen | ECitadelStat_Vitality |
    | EBulletArmorDamageReduction | ECitadelStat_Vitality |
    | ETechArmorDamageReduction | ECitadelStat_Vitality |
    | ETechPower | ECitadelStat_Spirit |
    | EWeaponDPS | ECitadelStat_Weapon |
    | EBulletDamage | ECitadelStat_Weapon |
    | EClipSize | ECitadelStat_Weapon |
    | ERoundsPerSecond | ECitadelStat_Weapon |
    | ELightMeleeDamage | ECitadelStat_Weapon |
    | EHeavyMeleeDamage | ECitadelStat_Weapon |
    | EMaxMoveSpeed | ECitadelStat_Vitality |
    | ESprintSpeed | ECitadelStat_Vitality |
    | EStamina | ECitadelStat_Vitality |
  - **m_eWeaponStatDisplay**: EMeleeDamage_DEPRECATED
- **m_mapScalingStats**:
- **m_heroStatsDisplay**:
  - **m_vecHealthHeaderStats**:
    - EMaxHealth
    - EBaseHealthRegen
  - **m_vecHealthStats**:
    - EBulletArmorDamageReduction
    - ETechArmorDamageReduction
    - EBulletShieldHealth
    - ETechShieldHealth
    - EBulletLifesteal
    - ETechLifesteal
    - EMaxMoveSpeed
    - ESprintSpeed
    - EStamina
    - EHealingOutput
  - **m_vecWeaponHeaderStats**:
    - EWeaponDPS
    - EBulletDamage
  - **m_vecWeaponStats**:
    - ELightMeleeDamage
    - EHeavyMeleeDamage
    - EFireRate
    - EClipSize
  - **m_vecMagicHeaderStats**:
    - ETechPower
  - **m_vecMagicStats**:
    - ETechCooldown
    - ETechRange
    - ETechDuration
- **m_mapStandardLevelUpUpgrades**:
  - **MODIFIER_VALUE_BASE_BULLET_DAMAGE_FROM_LEVEL**: 0.0
  - **MODIFIER_VALUE_BASE_MELEE_DAMAGE_FROM_LEVEL**: 3.4
  - **MODIFIER_VALUE_BASE_HEALTH_FROM_LEVEL**: 41.0
  - **MODIFIER_VALUE_TECH_DAMAGE_PERCENT**: 0.0
  - **MODIFIER_VALUE_BULLET_ARMOR_DAMAGE_RESIST**: 0.0
- **m_eAbilityResourceType**: EResourceType_None
- **m_ShopStatDisplay**:
  - **m_eWeaponStatsDisplay**:
    - **m_vecDisplayStats**:
      - EBulletDamage
      - EBaseWeaponDamageIncrease
      - ERoundsPerSecond
      - EFireRate
      - EClipSize
      - EClipSizeIncrease
      - EReloadTime
      - EReloadSpeed
      - EBulletSpeed
      - EBulletSpeedIncrease
      - EBulletLifesteal
    - **m_vecOtherDisplayStats**:
      - ELightMeleeDamage
      - EHeavyMeleeDamage
  - **m_eVitalityStatsDisplay**:
    - **m_vecDisplayStats**:
      - EMaxHealth
      - EBaseHealthRegen
      - EBulletArmorDamageReduction
      - ETechArmorDamageReduction
      - EBulletShieldHealth
      - ETechShieldHealth
      - ECritDamageReceivedScale
    - **m_vecOtherDisplayStats**:
      - EMaxMoveSpeed
      - ESprintSpeed
      - EStaminaCooldown
      - EStaminaRegenIncrease
      - EStamina
  - **m_eSpiritStatsDisplay**:
    - **m_vecDisplayStats**:
      - ETechCooldown
      - ETechDuration
      - ETechRange
      - ETechLifesteal
      - EMaxChargesIncrease
      - ETechCooldownBetweenChargeUses
- **_base**: hero_base
- **m_strSelectionImage**: panorama:"file://{images}/heroes/yakuza.psd"
- **m_strIconImageSmall**: panorama:"file://{images}/heroes/yakuza_sm.psd"
- **m_strMinimapImage**: panorama:"file://{images}/heroes/yakuza_mm.psd"
- **m_strUIAnimGraph**: resource_name:"models/heroes_staging/yakuza/ui_yakuza.vanmgrph"
- **m_strDeathSound**: soundevent:"Player.DeathFemale"
- **m_hGameSoundEventScript**: resource_name:"soundevents/game_sounds_heroes/game_sounds_hero_yakuza.vsndevts"
- **m_hVOEventScript**: resource_name:"soundevents/vo/vo_hero_yakuza.vsndevts"
- **m_strIconHeroCard**: panorama:"file://{images}/heroes/yakuza_sm.psd"
- **m_strUIShopAnimGraph**: resource_name:"models/heroes_staging/yakuza/ui_shop_yakuza.vanmgrph"
- **m_strUIShoppingMap**: maps/ui/hero_shop/yakuza_shop.vmap

---

# Hero: hero_genericperson

- **_class**: CitadelHeroData_t
- **m_bPlayerSelectable**: False
- **m_bDisabled**: True
- **m_bInDevelopment**: True
- **m_bNeedsTesting**: True
- **m_bAssignedPlayersOnly**: False
- **m_bBotSelectable**: False
- **m_bLimitedTesting**: False
- **m_nComplexity**: 2
- **m_nReadability**: 1
- **m_HeroID**: 46
- **m_strModelName**: resource_name:"models/heroes_staging/gen_man/gen_man.vmdl"
- **m_hDamageTakenParticle**: resource_name:"particles/generic/player_damage_screen.vpcf"
- **m_hGroundDamageTakenParticle**: resource_name:"particles/generic/player_ground_damage_screen.vpcf"
- **m_hDeathParticle**: resource_name:"particles/generic/player_death_screen.vpcf"
- **m_hLowHealthParticle**: resource_name:"particles/generic/player_low_health_screen.vpcf"
- **m_hRespawnParticle**: resource_name:"particles/generic/player_respawn_deploy.vpcf"
- **m_nModelSkin**: 0
- **m_mapStartingStats**:
  - **EMaxMoveSpeed**: 7
  - **ESprintSpeed**: 0
  - **ECrouchSpeed**: 4.75
  - **EMoveAcceleration**: 4
  - **ELightMeleeDamage**: 63
  - **EHeavyMeleeDamage**: 116
  - **EMaxHealth**: 550
  - **EWeaponPower**: 0
  - **EReloadSpeed**: 1
  - **EWeaponPowerScale**: 1
  - **EProcBuildUpRateScale**: 1
  - **EStamina**: 3
  - **EBaseHealthRegen**: 2.0
  - **EStaminaRegenPerSecond**: 0.2
  - **EAbilityResourceMax**: 0
  - **EAbilityResourceRegenPerSecond**: 0
  - **ECritDamageReceivedScale**: 1.0
  - **ETechDuration**: 1
  - **ETechRange**: 1
- **m_flCollisionRadius**: 20
- **m_flCollisionHeight**: 80
- **m_flStepHeight**: 32
- **m_mapBoundAbilities**:
  - **ESlot_Weapon_Primary**: citadel_weapon_genericperson_set
  - **ESlot_Weapon_Melee**: citadel_ability_melee_genericperson
  - **ESlot_Ability_Mantle**: citadel_ability_mantle
  - **ESlot_Ability_Jump**: citadel_ability_jump
  - **ESlot_Ability_Slide**: citadel_ability_slide
  - **ESlot_Ability_ZipLine**: citadel_ability_zip_line
  - **ESlot_Ability_ZipLineBoost**: citadel_ability_zipline_boost
  - **ESlot_Ability_Innate_1**: citadel_ability_dash
  - **ESlot_Ability_Innate_2**: citadel_ability_sprint
  - **ESlot_Ability_Innate_3**: citadel_ability_melee_parry
  - **ESlot_Signature_1**: genericperson_ability_1
  - **ESlot_Signature_2**: genericperson_ability_2
  - **ESlot_Signature_3**: genericperson_ability_3
  - **ESlot_Signature_4**: genericperson_ability_4
- **m_mapItemSlotInfo**:
  - **EItemSlotType_WeaponMod**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
  - **EItemSlotType_Armor**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
  - **EItemSlotType_Tech**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
- **m_mapPurchaseBonuses**:
  - **EItemSlotType_WeaponMod**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 6 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 2 | 10 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 3 | 14 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 4 | 18 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
  - **EItemSlotType_Armor**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 11 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 2 | 14 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 3 | 17 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 4 | 20 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
  - **EItemSlotType_Tech**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 4 | MODIFIER_VALUE_TECH_POWER |
    | 2 | 8 | MODIFIER_VALUE_TECH_POWER |
    | 3 | 12 | MODIFIER_VALUE_TECH_POWER |
    | 4 | 16 | MODIFIER_VALUE_TECH_POWER |
- **m_mapLevelInfo**:
  - **1**:
    - **m_unRequiredGold**: 0
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **2**:
    - **m_unRequiredGold**: 400
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
      - **EAbilityPoints**: 1
  - **3**:
    - **m_unRequiredGold**: 800
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **4**:
    - **m_unRequiredGold**: 1200
    - **m_bUseStandardUpgrade**: True
  - **5**:
    - **m_unRequiredGold**: 1500
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **6**:
    - **m_unRequiredGold**: 2200
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **7**:
    - **m_unRequiredGold**: 3000
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **8**:
    - **m_unRequiredGold**: 4500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **9**:
    - **m_unRequiredGold**: 6000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **10**:
    - **m_unRequiredGold**: 7500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **11**:
    - **m_unRequiredGold**: 9000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **12**:
    - **m_unRequiredGold**: 10500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **13**:
    - **m_unRequiredGold**: 12000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **14**:
    - **m_unRequiredGold**: 13000
    - **m_bUseStandardUpgrade**: True
  - **15**:
    - **m_unRequiredGold**: 14000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **16**:
    - **m_unRequiredGold**: 15000
    - **m_bUseStandardUpgrade**: True
  - **17**:
    - **m_unRequiredGold**: 16000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **18**:
    - **m_unRequiredGold**: 18000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **19**:
    - **m_unRequiredGold**: 20000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **20**:
    - **m_unRequiredGold**: 22000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **21**:
    - **m_unRequiredGold**: 24000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **22**:
    - **m_unRequiredGold**: 27000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **23**:
    - **m_unRequiredGold**: 30000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **24**:
    - **m_unRequiredGold**: 33000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **25**:
    - **m_unRequiredGold**: 36000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **26**:
    - **m_unRequiredGold**: 39000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **27**:
    - **m_unRequiredGold**: 42000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **28**:
    - **m_unRequiredGold**: 45000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **29**:
    - **m_unRequiredGold**: 48000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
- **m_hFootstepSounds**: sweetener_default
- **m_strFootstepSoundEventDefault**: soundevent:"Hero.Default.Footstep"
- **m_flStealthSpeedMetersPerSecond**: 4
- **m_flFootstepSoundTravelDistanceMeters**: 20
- **m_flStepSoundTime**: 0.3
- **m_vecAnimGraphDefaultValueOverrides**:
  | m_strParamName | m_strParamValue |
  | --- | --- |
  | e_SWITCH_4wayRoll_ON/OFF | 0 |
  | e_SWITCH_Recoil_ON/OFF | 0 |
  | e_SWITCH_ZiplinePhysicsSway_ON/OFF | 0 |
  | e_SWITCH_ShootStyle | 0 |
- **m_strLastHitSound**: soundevent:"LastHit.Default"
- **m_strLowHealthSound**: soundevent:"PlayerAlert.LowHealth"
- **m_colorUI**:
  - 255
  - 255
  - 255
- **m_colorGlowFriendly**:
  - 255
  - 239
  - 215
- **m_colorGlowEnemy**:
  - 255
  - 0
  - 0
- **m_colorGlowTeam1**:
  - 231
  - 182
  - 89
- **m_colorGlowTeam2**:
  - 91
  - 121
  - 230
- **m_vecAmbientParticleSettings**:
  | m_eAttachmentType | m_nCP |
  | --- | --- |
  | PATTACH_ABSORIGIN_FOLLOW | 0 |
  | PATTACH_POINT_FOLLOW | 1 |
- **m_heroStatsUI**:
  - **m_vecDisplayStats**:
    | m_eStatType | m_eStatCategory |
    | --- | --- |
    | EMaxHealth | ECitadelStat_Vitality |
    | EBaseHealthRegen | ECitadelStat_Vitality |
    | EBulletArmorDamageReduction | ECitadelStat_Vitality |
    | ETechArmorDamageReduction | ECitadelStat_Vitality |
    | ETechPower | ECitadelStat_Spirit |
    | EWeaponDPS | ECitadelStat_Weapon |
    | EBulletDamage | ECitadelStat_Weapon |
    | EClipSize | ECitadelStat_Weapon |
    | ERoundsPerSecond | ECitadelStat_Weapon |
    | ELightMeleeDamage | ECitadelStat_Weapon |
    | EHeavyMeleeDamage | ECitadelStat_Weapon |
    | EMaxMoveSpeed | ECitadelStat_Vitality |
    | ESprintSpeed | ECitadelStat_Vitality |
    | EStamina | ECitadelStat_Vitality |
  - **m_eWeaponStatDisplay**: EMeleeDamage_DEPRECATED
- **m_mapScalingStats**:
- **m_heroStatsDisplay**:
  - **m_vecHealthHeaderStats**:
    - EMaxHealth
    - EBaseHealthRegen
  - **m_vecHealthStats**:
    - EBulletArmorDamageReduction
    - ETechArmorDamageReduction
    - EBulletShieldHealth
    - ETechShieldHealth
    - EBulletLifesteal
    - ETechLifesteal
    - EMaxMoveSpeed
    - ESprintSpeed
    - EStamina
    - EHealingOutput
  - **m_vecWeaponHeaderStats**:
    - EWeaponDPS
    - EBulletDamage
  - **m_vecWeaponStats**:
    - ELightMeleeDamage
    - EHeavyMeleeDamage
    - EFireRate
    - EClipSize
  - **m_vecMagicHeaderStats**:
    - ETechPower
  - **m_vecMagicStats**:
    - ETechCooldown
    - ETechRange
    - ETechDuration
- **m_mapStandardLevelUpUpgrades**:
  - **MODIFIER_VALUE_BASE_BULLET_DAMAGE_FROM_LEVEL**: 0.0
  - **MODIFIER_VALUE_BASE_MELEE_DAMAGE_FROM_LEVEL**: 3.4
  - **MODIFIER_VALUE_BASE_HEALTH_FROM_LEVEL**: 41.0
  - **MODIFIER_VALUE_TECH_DAMAGE_PERCENT**: 0.0
  - **MODIFIER_VALUE_BULLET_ARMOR_DAMAGE_RESIST**: 0.0
- **m_eAbilityResourceType**: EResourceType_None
- **m_ShopStatDisplay**:
  - **m_eWeaponStatsDisplay**:
    - **m_vecDisplayStats**:
      - EBulletDamage
      - EBaseWeaponDamageIncrease
      - ERoundsPerSecond
      - EFireRate
      - EClipSize
      - EClipSizeIncrease
      - EReloadTime
      - EReloadSpeed
      - EBulletSpeed
      - EBulletSpeedIncrease
      - EBulletLifesteal
    - **m_vecOtherDisplayStats**:
      - ELightMeleeDamage
      - EHeavyMeleeDamage
  - **m_eVitalityStatsDisplay**:
    - **m_vecDisplayStats**:
      - EMaxHealth
      - EBaseHealthRegen
      - EBulletArmorDamageReduction
      - ETechArmorDamageReduction
      - EBulletShieldHealth
      - ETechShieldHealth
      - ECritDamageReceivedScale
    - **m_vecOtherDisplayStats**:
      - EMaxMoveSpeed
      - ESprintSpeed
      - EStaminaCooldown
      - EStaminaRegenIncrease
      - EStamina
  - **m_eSpiritStatsDisplay**:
    - **m_vecDisplayStats**:
      - ETechCooldown
      - ETechDuration
      - ETechRange
      - ETechLifesteal
      - EMaxChargesIncrease
      - ETechCooldownBetweenChargeUses
- **_base**: hero_base
- **m_strSelectionImage**: panorama:"file://{images}/heroes/genericperson.psd"
- **m_strIconImageSmall**: panorama:"file://{images}/heroes/genericperson_sm.psd"
- **m_strMinimapImage**: panorama:"file://{images}/heroes/genericperson_mm.psd"
- **m_strDeathSound**: soundevent:"Player.DeathFemale"
- **m_hGameSoundEventScript**: resource_name:"soundevents/game_sounds_heroes/game_sounds_hero_genericperson.vsndevts"
- **m_hVOEventScript**: resource_name:"soundevents/vo/vo_hero_genericperson.vsndevts"
- **m_strIconHeroCard**: panorama:"file://{images}/heroes/genericperson_sm.psd"

---

# Hero: hero_tokamak

- **_class**: CitadelHeroData_t
- **m_bPlayerSelectable**: True
- **m_bDisabled**: True
- **m_bInDevelopment**: True
- **m_bNeedsTesting**: False
- **m_bAssignedPlayersOnly**: False
- **m_bBotSelectable**: False
- **m_bLimitedTesting**: False
- **m_nComplexity**: 2
- **m_nReadability**: 1
- **m_HeroID**: 47
- **m_strModelName**: resource_name:"models/heroes_staging/tokamak/tokamak.vmdl"
- **m_hDamageTakenParticle**: resource_name:"particles/generic/player_damage_screen.vpcf"
- **m_hGroundDamageTakenParticle**: resource_name:"particles/generic/player_ground_damage_screen.vpcf"
- **m_hDeathParticle**: resource_name:"particles/generic/player_death_screen.vpcf"
- **m_hLowHealthParticle**: resource_name:"particles/generic/player_low_health_screen.vpcf"
- **m_hRespawnParticle**: resource_name:"particles/generic/player_respawn_deploy.vpcf"
- **m_nModelSkin**: 0
- **m_mapStartingStats**:
  - **EMaxMoveSpeed**: 7
  - **ESprintSpeed**: 0
  - **ECrouchSpeed**: 4.75
  - **EMoveAcceleration**: 4
  - **ELightMeleeDamage**: 63
  - **EHeavyMeleeDamage**: 116
  - **EMaxHealth**: 550
  - **EWeaponPower**: 0
  - **EReloadSpeed**: 1
  - **EWeaponPowerScale**: 1
  - **EProcBuildUpRateScale**: 1
  - **EStamina**: 3
  - **EBaseHealthRegen**: 2.0
  - **EStaminaRegenPerSecond**: 0.2
  - **EAbilityResourceMax**: 0
  - **EAbilityResourceRegenPerSecond**: 0
  - **ECritDamageReceivedScale**: 1.0
  - **ETechDuration**: 1
  - **ETechRange**: 1
- **m_flCollisionRadius**: 20
- **m_flCollisionHeight**: 80
- **m_flStepHeight**: 32
- **m_mapBoundAbilities**:
  - **ESlot_Weapon_Primary**: citadel_weapon_tokamak_set
  - **ESlot_Weapon_Melee**: citadel_ability_melee_tokamak
  - **ESlot_Ability_Mantle**: citadel_ability_mantle
  - **ESlot_Ability_Jump**: citadel_ability_jump
  - **ESlot_Ability_Slide**: citadel_ability_slide
  - **ESlot_Ability_ZipLine**: citadel_ability_zip_line
  - **ESlot_Ability_ZipLineBoost**: citadel_ability_zipline_boost
  - **ESlot_Ability_Innate_1**: citadel_ability_dash
  - **ESlot_Ability_Innate_2**: citadel_ability_sprint
  - **ESlot_Ability_Innate_3**: citadel_ability_melee_parry
  - **ESlot_Signature_1**: tokamak_hot_shot
  - **ESlot_Signature_2**: tokamak_dying_star
  - **ESlot_Signature_3**: tokamak_radiance
  - **ESlot_Signature_4**: tokamak_crimson_cannon
- **m_mapItemSlotInfo**:
  - **EItemSlotType_WeaponMod**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
  - **EItemSlotType_Armor**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
  - **EItemSlotType_Tech**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
- **m_mapPurchaseBonuses**:
  - **EItemSlotType_WeaponMod**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 6 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 2 | 10 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 3 | 14 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 4 | 18 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
  - **EItemSlotType_Armor**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 11 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 2 | 14 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 3 | 17 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 4 | 20 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
  - **EItemSlotType_Tech**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 4 | MODIFIER_VALUE_TECH_POWER |
    | 2 | 8 | MODIFIER_VALUE_TECH_POWER |
    | 3 | 12 | MODIFIER_VALUE_TECH_POWER |
    | 4 | 16 | MODIFIER_VALUE_TECH_POWER |
- **m_mapLevelInfo**:
  - **1**:
    - **m_unRequiredGold**: 0
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **2**:
    - **m_unRequiredGold**: 400
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
      - **EAbilityPoints**: 1
  - **3**:
    - **m_unRequiredGold**: 800
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **4**:
    - **m_unRequiredGold**: 1200
    - **m_bUseStandardUpgrade**: True
  - **5**:
    - **m_unRequiredGold**: 1500
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **6**:
    - **m_unRequiredGold**: 2200
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **7**:
    - **m_unRequiredGold**: 3000
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **8**:
    - **m_unRequiredGold**: 4500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **9**:
    - **m_unRequiredGold**: 6000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **10**:
    - **m_unRequiredGold**: 7500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **11**:
    - **m_unRequiredGold**: 9000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **12**:
    - **m_unRequiredGold**: 10500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **13**:
    - **m_unRequiredGold**: 12000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **14**:
    - **m_unRequiredGold**: 13000
    - **m_bUseStandardUpgrade**: True
  - **15**:
    - **m_unRequiredGold**: 14000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **16**:
    - **m_unRequiredGold**: 15000
    - **m_bUseStandardUpgrade**: True
  - **17**:
    - **m_unRequiredGold**: 16000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **18**:
    - **m_unRequiredGold**: 18000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **19**:
    - **m_unRequiredGold**: 20000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **20**:
    - **m_unRequiredGold**: 22000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **21**:
    - **m_unRequiredGold**: 24000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **22**:
    - **m_unRequiredGold**: 27000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **23**:
    - **m_unRequiredGold**: 30000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **24**:
    - **m_unRequiredGold**: 33000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **25**:
    - **m_unRequiredGold**: 36000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **26**:
    - **m_unRequiredGold**: 39000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **27**:
    - **m_unRequiredGold**: 42000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **28**:
    - **m_unRequiredGold**: 45000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **29**:
    - **m_unRequiredGold**: 48000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
- **m_hFootstepSounds**: sweetener_default
- **m_strFootstepSoundEventDefault**: soundevent:""
- **m_flStealthSpeedMetersPerSecond**: 4
- **m_flFootstepSoundTravelDistanceMeters**: 20
- **m_flStepSoundTime**: 0.375
- **m_vecAnimGraphDefaultValueOverrides**:
  | m_strParamName | m_strParamValue |
  | --- | --- |
  | e_SWITCH_4wayRoll_ON/OFF | 0 |
  | e_SWITCH_Recoil_ON/OFF | 0 |
  | e_SWITCH_ZiplinePhysicsSway_ON/OFF | 0 |
  | e_SWITCH_ShootStyle | 0 |
- **m_strLastHitSound**: soundevent:"LastHit.Default"
- **m_strLowHealthSound**: soundevent:"PlayerAlert.LowHealth"
- **m_colorUI**:
  - 38
  - 141
  - 173
- **m_colorGlowFriendly**:
  - 255
  - 239
  - 215
- **m_colorGlowEnemy**:
  - 255
  - 0
  - 0
- **m_colorGlowTeam1**:
  - 231
  - 182
  - 89
- **m_colorGlowTeam2**:
  - 91
  - 121
  - 230
- **m_vecAmbientParticleSettings**:
  | m_eAttachmentType | m_nCP |
  | --- | --- |
  | PATTACH_ABSORIGIN_FOLLOW | 0 |
  | PATTACH_POINT_FOLLOW | 1 |
- **m_heroStatsUI**:
  - **m_vecDisplayStats**:
    | m_eStatType | m_eStatCategory |
    | --- | --- |
    | EMaxHealth | ECitadelStat_Vitality |
    | EBaseHealthRegen | ECitadelStat_Vitality |
    | EBulletArmorDamageReduction | ECitadelStat_Vitality |
    | ETechArmorDamageReduction | ECitadelStat_Vitality |
    | ETechPower | ECitadelStat_Spirit |
    | EWeaponDPS | ECitadelStat_Weapon |
    | EBulletDamage | ECitadelStat_Weapon |
    | EClipSize | ECitadelStat_Weapon |
    | ERoundsPerSecond | ECitadelStat_Weapon |
    | ELightMeleeDamage | ECitadelStat_Weapon |
    | EHeavyMeleeDamage | ECitadelStat_Weapon |
    | EMaxMoveSpeed | ECitadelStat_Vitality |
    | ESprintSpeed | ECitadelStat_Vitality |
    | EStamina | ECitadelStat_Vitality |
  - **m_eWeaponStatDisplay**: EMeleeDamage_DEPRECATED
- **m_mapScalingStats**:
- **m_heroStatsDisplay**:
  - **m_vecHealthHeaderStats**:
    - EMaxHealth
    - EBaseHealthRegen
  - **m_vecHealthStats**:
    - EBulletArmorDamageReduction
    - ETechArmorDamageReduction
    - EBulletShieldHealth
    - ETechShieldHealth
    - EBulletLifesteal
    - ETechLifesteal
    - EMaxMoveSpeed
    - ESprintSpeed
    - EStamina
    - EHealingOutput
  - **m_vecWeaponHeaderStats**:
    - EWeaponDPS
    - EBulletDamage
  - **m_vecWeaponStats**:
    - ELightMeleeDamage
    - EHeavyMeleeDamage
    - EFireRate
    - EClipSize
  - **m_vecMagicHeaderStats**:
    - ETechPower
  - **m_vecMagicStats**:
    - ETechCooldown
    - ETechRange
    - ETechDuration
- **m_mapStandardLevelUpUpgrades**:
  - **MODIFIER_VALUE_BASE_BULLET_DAMAGE_FROM_LEVEL**: 0.8487
  - **MODIFIER_VALUE_BASE_MELEE_DAMAGE_FROM_LEVEL**: 3.4
  - **MODIFIER_VALUE_BASE_HEALTH_FROM_LEVEL**: 41.0
  - **MODIFIER_VALUE_TECH_DAMAGE_PERCENT**: 0.0
  - **MODIFIER_VALUE_BULLET_ARMOR_DAMAGE_RESIST**: 0.0
- **m_eAbilityResourceType**: EResourceType_None
- **m_ShopStatDisplay**:
  - **m_eWeaponStatsDisplay**:
    - **m_vecDisplayStats**:
      - EBulletDamage
      - EBaseWeaponDamageIncrease
      - ERoundsPerSecond
      - EFireRate
      - EClipSize
      - EClipSizeIncrease
      - EReloadTime
      - EReloadSpeed
      - EBulletSpeed
      - EBulletSpeedIncrease
      - EBulletLifesteal
    - **m_vecOtherDisplayStats**:
      - ELightMeleeDamage
      - EHeavyMeleeDamage
  - **m_eVitalityStatsDisplay**:
    - **m_vecDisplayStats**:
      - EMaxHealth
      - EBaseHealthRegen
      - EBulletArmorDamageReduction
      - ETechArmorDamageReduction
      - EBulletShieldHealth
      - ETechShieldHealth
      - ECritDamageReceivedScale
    - **m_vecOtherDisplayStats**:
      - EMaxMoveSpeed
      - ESprintSpeed
      - EStaminaCooldown
      - EStaminaRegenIncrease
      - EStamina
  - **m_eSpiritStatsDisplay**:
    - **m_vecDisplayStats**:
      - ETechCooldown
      - ETechDuration
      - ETechRange
      - ETechLifesteal
      - EMaxChargesIncrease
      - ETechCooldownBetweenChargeUses
- **_base**: hero_base
- **m_strSelectionImage**: panorama:"file://{images}/heroes/tokamak.psd"
- **m_strIconImageSmall**: panorama:"file://{images}/heroes/tokamak_sm.psd"
- **m_strMinimapImage**: panorama:"file://{images}/heroes/tokamak_mm.psd"
- **m_strIconHeroCard**: panorama:"file://{images}/hud/hero_portraits/tokamak_hud.psd"
- **m_strUIAnimGraph**: resource_name:"models/heroes_staging/tokamak/ui_tokamak.vanmgrph"
- **m_strDeathSound**: soundevent:"Player.DeathFemale"
- **m_hGameSoundEventScript**: resource_name:"soundevents/hero/tokamak.vsndevts"
- **m_hVOEventScript**: resource_name:"soundevents/vo/vo_hero_tokamak.vsndevts"
- **m_strTopBarImage**: panorama:"file://{images}/hud/hero_portraits/tokamak_hud.psd"

---

# Hero: hero_wrecker

- **_class**: CitadelHeroData_t
- **m_bPlayerSelectable**: True
- **m_bDisabled**: False
- **m_bInDevelopment**: True
- **m_bNeedsTesting**: False
- **m_bAssignedPlayersOnly**: False
- **m_bBotSelectable**: False
- **m_bLimitedTesting**: False
- **m_nComplexity**: 3
- **m_nReadability**: 0
- **m_HeroID**: 48
- **m_strModelName**: resource_name:"models/heroes_staging/wrecker/wrecker.vmdl"
- **m_hDamageTakenParticle**: resource_name:"particles/generic/player_damage_screen.vpcf"
- **m_hGroundDamageTakenParticle**: resource_name:"particles/generic/player_ground_damage_screen.vpcf"
- **m_hDeathParticle**: resource_name:"particles/generic/player_death_screen.vpcf"
- **m_hLowHealthParticle**: resource_name:"particles/generic/player_low_health_screen.vpcf"
- **m_hRespawnParticle**: resource_name:"particles/generic/player_respawn_deploy.vpcf"
- **m_nModelSkin**: 0
- **m_mapStartingStats**:
  - **EMaxMoveSpeed**: 7
  - **ESprintSpeed**: 0
  - **ECrouchSpeed**: 4.75
  - **EMoveAcceleration**: 4
  - **ELightMeleeDamage**: 63
  - **EHeavyMeleeDamage**: 116
  - **EMaxHealth**: 550
  - **EWeaponPower**: 0
  - **EReloadSpeed**: 1
  - **EWeaponPowerScale**: 1
  - **EProcBuildUpRateScale**: 1
  - **EStamina**: 3
  - **EBaseHealthRegen**: 2.0
  - **EStaminaRegenPerSecond**: 0.2
  - **EAbilityResourceMax**: 0
  - **EAbilityResourceRegenPerSecond**: 0
  - **ECritDamageReceivedScale**: 1.0
  - **ETechDuration**: 1
  - **ETechRange**: 1
- **m_flCollisionRadius**: 20
- **m_flCollisionHeight**: 80
- **m_flStepHeight**: 32
- **m_mapBoundAbilities**:
  - **ESlot_Weapon_Primary**: citadel_weapon_wrecker_set
  - **ESlot_Weapon_Melee**: ability_melee_wrecker
  - **ESlot_Ability_Mantle**: citadel_ability_mantle
  - **ESlot_Ability_Jump**: citadel_ability_jump
  - **ESlot_Ability_Slide**: citadel_ability_slide
  - **ESlot_Ability_ZipLine**: citadel_ability_zip_line
  - **ESlot_Ability_ZipLineBoost**: citadel_ability_zipline_boost
  - **ESlot_Ability_Innate_1**: citadel_ability_dash
  - **ESlot_Ability_Innate_2**: citadel_ability_sprint
  - **ESlot_Ability_Innate_3**: citadel_ability_melee_parry
  - **ESlot_Signature_1**: ability_wrecking_ball
  - **ESlot_Signature_2**: ability_wrecker_salvage
  - **ESlot_Signature_3**: ability_scrap_blast
  - **ESlot_Signature_4**: ability_wrecker_teleport
- **m_mapItemSlotInfo**:
  - **EItemSlotType_WeaponMod**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
  - **EItemSlotType_Armor**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
  - **EItemSlotType_Tech**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
- **m_mapPurchaseBonuses**:
  - **EItemSlotType_WeaponMod**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 6 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 2 | 10 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 3 | 14 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 4 | 18 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
  - **EItemSlotType_Armor**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 11 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 2 | 14 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 3 | 17 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 4 | 20 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
  - **EItemSlotType_Tech**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 4 | MODIFIER_VALUE_TECH_POWER |
    | 2 | 8 | MODIFIER_VALUE_TECH_POWER |
    | 3 | 12 | MODIFIER_VALUE_TECH_POWER |
    | 4 | 16 | MODIFIER_VALUE_TECH_POWER |
- **m_mapLevelInfo**:
  - **1**:
    - **m_unRequiredGold**: 0
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **2**:
    - **m_unRequiredGold**: 400
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
      - **EAbilityPoints**: 1
  - **3**:
    - **m_unRequiredGold**: 800
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **4**:
    - **m_unRequiredGold**: 1200
    - **m_bUseStandardUpgrade**: True
  - **5**:
    - **m_unRequiredGold**: 1500
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **6**:
    - **m_unRequiredGold**: 2200
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **7**:
    - **m_unRequiredGold**: 3000
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **8**:
    - **m_unRequiredGold**: 4500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **9**:
    - **m_unRequiredGold**: 6000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **10**:
    - **m_unRequiredGold**: 7500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **11**:
    - **m_unRequiredGold**: 9000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **12**:
    - **m_unRequiredGold**: 10500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **13**:
    - **m_unRequiredGold**: 12000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **14**:
    - **m_unRequiredGold**: 13000
    - **m_bUseStandardUpgrade**: True
  - **15**:
    - **m_unRequiredGold**: 14000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **16**:
    - **m_unRequiredGold**: 15000
    - **m_bUseStandardUpgrade**: True
  - **17**:
    - **m_unRequiredGold**: 16000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **18**:
    - **m_unRequiredGold**: 18000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **19**:
    - **m_unRequiredGold**: 20000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **20**:
    - **m_unRequiredGold**: 22000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **21**:
    - **m_unRequiredGold**: 24000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **22**:
    - **m_unRequiredGold**: 27000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **23**:
    - **m_unRequiredGold**: 30000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **24**:
    - **m_unRequiredGold**: 33000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **25**:
    - **m_unRequiredGold**: 36000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **26**:
    - **m_unRequiredGold**: 39000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **27**:
    - **m_unRequiredGold**: 42000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **28**:
    - **m_unRequiredGold**: 45000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **29**:
    - **m_unRequiredGold**: 48000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
- **m_hFootstepSounds**: sweetener_default
- **m_strFootstepSoundEventDefault**: soundevent:"Wrecker.Footstep"
- **m_flStealthSpeedMetersPerSecond**: 4
- **m_flFootstepSoundTravelDistanceMeters**: 20
- **m_flStepSoundTime**: 0.33
- **m_vecAnimGraphDefaultValueOverrides**:
  | m_strParamName | m_strParamValue |
  | --- | --- |
  | e_SWITCH_4wayRoll_ON/OFF | 0 |
  | e_SWITCH_Recoil_ON/OFF | 0 |
  | e_SWITCH_ZiplinePhysicsSway_ON/OFF | 0 |
  | e_SWITCH_ShootStyle | 0 |
- **m_strLastHitSound**: soundevent:"LastHit.Default"
- **m_strLowHealthSound**: soundevent:"PlayerAlert.LowHealth"
- **m_colorUI**:
  - 127
  - 45
  - 177
- **m_colorGlowFriendly**:
  - 255
  - 239
  - 215
- **m_colorGlowEnemy**:
  - 255
  - 0
  - 0
- **m_colorGlowTeam1**:
  - 231
  - 182
  - 89
- **m_colorGlowTeam2**:
  - 91
  - 121
  - 230
- **m_vecAmbientParticleSettings**:
  | m_eAttachmentType | m_nCP |
  | --- | --- |
  | PATTACH_ABSORIGIN_FOLLOW | 0 |
  | PATTACH_POINT_FOLLOW | 1 |
- **m_heroStatsUI**:
  - **m_vecDisplayStats**:
    | m_eStatType | m_eStatCategory |
    | --- | --- |
    | EMaxHealth | ECitadelStat_Vitality |
    | EBaseHealthRegen | ECitadelStat_Vitality |
    | EBulletArmorDamageReduction | ECitadelStat_Vitality |
    | ETechArmorDamageReduction | ECitadelStat_Vitality |
    | ETechPower | ECitadelStat_Spirit |
    | EWeaponDPS | ECitadelStat_Weapon |
    | EBulletDamage | ECitadelStat_Weapon |
    | EClipSize | ECitadelStat_Weapon |
    | ERoundsPerSecond | ECitadelStat_Weapon |
    | ELightMeleeDamage | ECitadelStat_Weapon |
    | EHeavyMeleeDamage | ECitadelStat_Weapon |
    | EMaxMoveSpeed | ECitadelStat_Vitality |
    | ESprintSpeed | ECitadelStat_Vitality |
    | EStamina | ECitadelStat_Vitality |
  - **m_eWeaponStatDisplay**: EMeleeDamage_DEPRECATED
- **m_mapScalingStats**:
- **m_heroStatsDisplay**:
  - **m_vecHealthHeaderStats**:
    - EMaxHealth
    - EBaseHealthRegen
  - **m_vecHealthStats**:
    - EBulletArmorDamageReduction
    - ETechArmorDamageReduction
    - EBulletShieldHealth
    - ETechShieldHealth
    - EBulletLifesteal
    - ETechLifesteal
    - EMaxMoveSpeed
    - ESprintSpeed
    - EStamina
    - EHealingOutput
  - **m_vecWeaponHeaderStats**:
    - EWeaponDPS
    - EBulletDamage
  - **m_vecWeaponStats**:
    - ELightMeleeDamage
    - EHeavyMeleeDamage
    - EFireRate
    - EClipSize
  - **m_vecMagicHeaderStats**:
    - ETechPower
  - **m_vecMagicStats**:
    - ETechCooldown
    - ETechRange
    - ETechDuration
- **m_mapStandardLevelUpUpgrades**:
  - **MODIFIER_VALUE_BASE_BULLET_DAMAGE_FROM_LEVEL**: 1.58
  - **MODIFIER_VALUE_BASE_MELEE_DAMAGE_FROM_LEVEL**: 3.4
  - **MODIFIER_VALUE_BASE_HEALTH_FROM_LEVEL**: 41.0
  - **MODIFIER_VALUE_TECH_DAMAGE_PERCENT**: 0.0
  - **MODIFIER_VALUE_BULLET_ARMOR_DAMAGE_RESIST**: 0.0
- **m_eAbilityResourceType**: EResourceType_None
- **m_ShopStatDisplay**:
  - **m_eWeaponStatsDisplay**:
    - **m_vecDisplayStats**:
      - EBulletDamage
      - EBaseWeaponDamageIncrease
      - ERoundsPerSecond
      - EFireRate
      - EClipSize
      - EClipSizeIncrease
      - EReloadTime
      - EReloadSpeed
      - EBulletSpeed
      - EBulletSpeedIncrease
      - EBulletLifesteal
    - **m_vecOtherDisplayStats**:
      - ELightMeleeDamage
      - EHeavyMeleeDamage
    - **m_eWeaponAttributes**: EWeaponAttribute_MediumRange | EWeaponAttribute_HeavyHitter
  - **m_eVitalityStatsDisplay**:
    - **m_vecDisplayStats**:
      - EMaxHealth
      - EBaseHealthRegen
      - EBulletArmorDamageReduction
      - ETechArmorDamageReduction
      - EBulletShieldHealth
      - ETechShieldHealth
      - ECritDamageReceivedScale
    - **m_vecOtherDisplayStats**:
      - EMaxMoveSpeed
      - ESprintSpeed
      - EStaminaCooldown
      - EStaminaRegenIncrease
      - EStamina
  - **m_eSpiritStatsDisplay**:
    - **m_vecDisplayStats**:
      - ETechCooldown
      - ETechDuration
      - ETechRange
      - ETechLifesteal
      - EMaxChargesIncrease
      - ETechCooldownBetweenChargeUses
- **_base**: hero_base
- **m_strSelectionImage**: panorama:"file://{images}/heroes/wrecker.psd"
- **m_strIconImageSmall**: panorama:"file://{images}/heroes/wrecker_sm.psd"
- **m_strIconHeroCard**: panorama:"file://{images}/heroes/wrecker_card.psd"
- **m_strMinimapImage**: panorama:"file://{images}/heroes/wrecker_mm.psd"
- **m_strTopBarImage**: panorama:"file://{images}/hud/hero_portraits/wrecker_hud.psd"
- **m_strUIAnimGraph**: resource_name:"models/heroes_staging/wrecker/ui_wrecker.vanmgrph"
- **m_strDeathSound**: soundevent:"Butcher.Death"
- **m_hGameSoundEventScript**: resource_name:"soundevents/hero/wrecker.vsndevts"
- **m_hVOEventScript**: resource_name:"soundevents/vo/vo_hero_wrecker.vsndevts"
- **m_strRosterSelectedSound**: soundevent:"Wrecker.VO.HeroPick"
- **m_strRosterRemovedSound**: soundevent:"Wrecker.VO.HeroRemove"
- **m_hGeneratedVOEventScript**: resource_name:"soundevents/vo/generated_vo_hero_wrecker.vsndevts"
- **m_strUIPortraitMap**: maps/ui/hero_prefabs/wrecker.vmap
- **m_RecommendedUpgrades**:
  - upgrade_improved_spirit
  - upgrade_clip_size
  - upgrade_extra_charge
  - upgrade_health
  - upgrade_endurance
  - upgrade_quick_silver
  - upgrade_vampire
  - upgrade_crackshot
  - upgrade_magic_tempo
  - upgrade_magic_shield
  - upgrade_regenerating_bullet_shield
  - upgrade_long_range
  - upgrade_quick_silver
  - upgrade_magic_storm
  - upgrade_soaring_spirit
  - upgrade_rapid_recharge
  - upgrade_cooldown_reduction
  - upgrade_chonky
  - upgrade_titan_round
  - upgrade_armor_reduction_debuff
  - upgrade_mega_spirit
  - upgrade_damage_recycler
- **m_strTopBarVertical**: panorama:"file://{images}/heroes/wrecker_vertical.psd"
- **m_strUIShopAnimGraph**: resource_name:"models/heroes_staging/wrecker/ui_shop_wrecker.vanmgrph"
- **m_strUIShoppingMap**: maps/ui/hero_shop/wrecker_shop.vmap

---

# Hero: hero_rutger

- **_class**: CitadelHeroData_t
- **m_bPlayerSelectable**: True
- **m_bDisabled**: True
- **m_bInDevelopment**: True
- **m_bNeedsTesting**: True
- **m_bAssignedPlayersOnly**: False
- **m_bBotSelectable**: False
- **m_bLimitedTesting**: False
- **m_nComplexity**: 2
- **m_nReadability**: 1
- **m_HeroID**: 49
- **m_strModelName**: resource_name:"models/heroes_staging/rutger/rutger.vmdl"
- **m_hDamageTakenParticle**: resource_name:"particles/generic/player_damage_screen.vpcf"
- **m_hGroundDamageTakenParticle**: resource_name:"particles/generic/player_ground_damage_screen.vpcf"
- **m_hDeathParticle**: resource_name:"particles/generic/player_death_screen.vpcf"
- **m_hLowHealthParticle**: resource_name:"particles/generic/player_low_health_screen.vpcf"
- **m_hRespawnParticle**: resource_name:"particles/generic/player_respawn_deploy.vpcf"
- **m_nModelSkin**: 0
- **m_mapStartingStats**:
  - **EMaxMoveSpeed**: 7
  - **ESprintSpeed**: 0
  - **ECrouchSpeed**: 4.75
  - **EMoveAcceleration**: 4
  - **ELightMeleeDamage**: 63
  - **EHeavyMeleeDamage**: 116
  - **EMaxHealth**: 550
  - **EWeaponPower**: 0
  - **EReloadSpeed**: 1
  - **EWeaponPowerScale**: 1
  - **EProcBuildUpRateScale**: 1
  - **EStamina**: 3
  - **EBaseHealthRegen**: 2.0
  - **EStaminaRegenPerSecond**: 0.2
  - **EAbilityResourceMax**: 0
  - **EAbilityResourceRegenPerSecond**: 0
  - **ECritDamageReceivedScale**: 1.0
  - **ETechDuration**: 1
  - **ETechRange**: 1
- **m_flCollisionRadius**: 20
- **m_flCollisionHeight**: 80
- **m_flStepHeight**: 32
- **m_mapBoundAbilities**:
  - **ESlot_Weapon_Primary**: citadel_weapon_rutger_set
  - **ESlot_Weapon_Melee**: citadel_ability_melee_genericperson
  - **ESlot_Ability_Mantle**: citadel_ability_mantle
  - **ESlot_Ability_Jump**: citadel_ability_jump
  - **ESlot_Ability_Slide**: citadel_ability_slide
  - **ESlot_Ability_ZipLine**: citadel_ability_zip_line
  - **ESlot_Ability_ZipLineBoost**: citadel_ability_zipline_boost
  - **ESlot_Ability_Innate_1**: citadel_ability_dash
  - **ESlot_Ability_Innate_2**: citadel_ability_sprint
  - **ESlot_Ability_Innate_3**: citadel_ability_melee_parry
  - **ESlot_Signature_1**: rutger_rocket
  - **ESlot_Signature_2**: rutger_force_field
  - **ESlot_Signature_3**: rutger_cheat_death
  - **ESlot_Signature_4**: rutger_pulse
- **m_mapItemSlotInfo**:
  - **EItemSlotType_WeaponMod**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
  - **EItemSlotType_Armor**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
  - **EItemSlotType_Tech**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
- **m_mapPurchaseBonuses**:
  - **EItemSlotType_WeaponMod**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 6 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 2 | 10 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 3 | 14 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 4 | 18 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
  - **EItemSlotType_Armor**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 11 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 2 | 14 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 3 | 17 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 4 | 20 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
  - **EItemSlotType_Tech**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 4 | MODIFIER_VALUE_TECH_POWER |
    | 2 | 8 | MODIFIER_VALUE_TECH_POWER |
    | 3 | 12 | MODIFIER_VALUE_TECH_POWER |
    | 4 | 16 | MODIFIER_VALUE_TECH_POWER |
- **m_mapLevelInfo**:
  - **1**:
    - **m_unRequiredGold**: 0
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **2**:
    - **m_unRequiredGold**: 400
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
      - **EAbilityPoints**: 1
  - **3**:
    - **m_unRequiredGold**: 800
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **4**:
    - **m_unRequiredGold**: 1200
    - **m_bUseStandardUpgrade**: True
  - **5**:
    - **m_unRequiredGold**: 1500
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **6**:
    - **m_unRequiredGold**: 2200
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **7**:
    - **m_unRequiredGold**: 3000
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **8**:
    - **m_unRequiredGold**: 4500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **9**:
    - **m_unRequiredGold**: 6000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **10**:
    - **m_unRequiredGold**: 7500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **11**:
    - **m_unRequiredGold**: 9000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **12**:
    - **m_unRequiredGold**: 10500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **13**:
    - **m_unRequiredGold**: 12000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **14**:
    - **m_unRequiredGold**: 13000
    - **m_bUseStandardUpgrade**: True
  - **15**:
    - **m_unRequiredGold**: 14000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **16**:
    - **m_unRequiredGold**: 15000
    - **m_bUseStandardUpgrade**: True
  - **17**:
    - **m_unRequiredGold**: 16000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **18**:
    - **m_unRequiredGold**: 18000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **19**:
    - **m_unRequiredGold**: 20000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **20**:
    - **m_unRequiredGold**: 22000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **21**:
    - **m_unRequiredGold**: 24000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **22**:
    - **m_unRequiredGold**: 27000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **23**:
    - **m_unRequiredGold**: 30000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **24**:
    - **m_unRequiredGold**: 33000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **25**:
    - **m_unRequiredGold**: 36000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **26**:
    - **m_unRequiredGold**: 39000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **27**:
    - **m_unRequiredGold**: 42000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **28**:
    - **m_unRequiredGold**: 45000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **29**:
    - **m_unRequiredGold**: 48000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
- **m_hFootstepSounds**: sweetener_default
- **m_strFootstepSoundEventDefault**: soundevent:"Hero.Default.Footstep"
- **m_flStealthSpeedMetersPerSecond**: 4
- **m_flFootstepSoundTravelDistanceMeters**: 20
- **m_flStepSoundTime**: 0.3
- **m_vecAnimGraphDefaultValueOverrides**:
  | m_strParamName | m_strParamValue |
  | --- | --- |
  | e_SWITCH_4wayRoll_ON/OFF | 0 |
  | e_SWITCH_Recoil_ON/OFF | 0 |
  | e_SWITCH_ZiplinePhysicsSway_ON/OFF | 0 |
  | e_SWITCH_ShootStyle | 0 |
- **m_strLastHitSound**: soundevent:"LastHit.Default"
- **m_strLowHealthSound**: soundevent:"PlayerAlert.LowHealth"
- **m_colorUI**:
  - 255
  - 255
  - 255
- **m_colorGlowFriendly**:
  - 255
  - 239
  - 215
- **m_colorGlowEnemy**:
  - 255
  - 0
  - 0
- **m_colorGlowTeam1**:
  - 231
  - 182
  - 89
- **m_colorGlowTeam2**:
  - 91
  - 121
  - 230
- **m_vecAmbientParticleSettings**:
  | m_eAttachmentType | m_nCP |
  | --- | --- |
  | PATTACH_ABSORIGIN_FOLLOW | 0 |
  | PATTACH_POINT_FOLLOW | 1 |
- **m_heroStatsUI**:
  - **m_vecDisplayStats**:
    | m_eStatType | m_eStatCategory |
    | --- | --- |
    | EMaxHealth | ECitadelStat_Vitality |
    | EBaseHealthRegen | ECitadelStat_Vitality |
    | EBulletArmorDamageReduction | ECitadelStat_Vitality |
    | ETechArmorDamageReduction | ECitadelStat_Vitality |
    | ETechPower | ECitadelStat_Spirit |
    | EWeaponDPS | ECitadelStat_Weapon |
    | EBulletDamage | ECitadelStat_Weapon |
    | EClipSize | ECitadelStat_Weapon |
    | ERoundsPerSecond | ECitadelStat_Weapon |
    | ELightMeleeDamage | ECitadelStat_Weapon |
    | EHeavyMeleeDamage | ECitadelStat_Weapon |
    | EMaxMoveSpeed | ECitadelStat_Vitality |
    | ESprintSpeed | ECitadelStat_Vitality |
    | EStamina | ECitadelStat_Vitality |
  - **m_eWeaponStatDisplay**: EMeleeDamage_DEPRECATED
- **m_mapScalingStats**:
- **m_heroStatsDisplay**:
  - **m_vecHealthHeaderStats**:
    - EMaxHealth
    - EBaseHealthRegen
  - **m_vecHealthStats**:
    - EBulletArmorDamageReduction
    - ETechArmorDamageReduction
    - EBulletShieldHealth
    - ETechShieldHealth
    - EBulletLifesteal
    - ETechLifesteal
    - EMaxMoveSpeed
    - ESprintSpeed
    - EStamina
    - EHealingOutput
  - **m_vecWeaponHeaderStats**:
    - EWeaponDPS
    - EBulletDamage
  - **m_vecWeaponStats**:
    - ELightMeleeDamage
    - EHeavyMeleeDamage
    - EFireRate
    - EClipSize
  - **m_vecMagicHeaderStats**:
    - ETechPower
  - **m_vecMagicStats**:
    - ETechCooldown
    - ETechRange
    - ETechDuration
- **m_mapStandardLevelUpUpgrades**:
  - **MODIFIER_VALUE_BASE_BULLET_DAMAGE_FROM_LEVEL**: 0.0
  - **MODIFIER_VALUE_BASE_MELEE_DAMAGE_FROM_LEVEL**: 3.4
  - **MODIFIER_VALUE_BASE_HEALTH_FROM_LEVEL**: 41.0
  - **MODIFIER_VALUE_TECH_DAMAGE_PERCENT**: 0.0
  - **MODIFIER_VALUE_BULLET_ARMOR_DAMAGE_RESIST**: 0.0
- **m_eAbilityResourceType**: EResourceType_None
- **m_ShopStatDisplay**:
  - **m_eWeaponStatsDisplay**:
    - **m_vecDisplayStats**:
      - EBulletDamage
      - EBaseWeaponDamageIncrease
      - ERoundsPerSecond
      - EFireRate
      - EClipSize
      - EClipSizeIncrease
      - EReloadTime
      - EReloadSpeed
      - EBulletSpeed
      - EBulletSpeedIncrease
      - EBulletLifesteal
    - **m_vecOtherDisplayStats**:
      - ELightMeleeDamage
      - EHeavyMeleeDamage
  - **m_eVitalityStatsDisplay**:
    - **m_vecDisplayStats**:
      - EMaxHealth
      - EBaseHealthRegen
      - EBulletArmorDamageReduction
      - ETechArmorDamageReduction
      - EBulletShieldHealth
      - ETechShieldHealth
      - ECritDamageReceivedScale
    - **m_vecOtherDisplayStats**:
      - EMaxMoveSpeed
      - ESprintSpeed
      - EStaminaCooldown
      - EStaminaRegenIncrease
      - EStamina
  - **m_eSpiritStatsDisplay**:
    - **m_vecDisplayStats**:
      - ETechCooldown
      - ETechDuration
      - ETechRange
      - ETechLifesteal
      - EMaxChargesIncrease
      - ETechCooldownBetweenChargeUses
- **_base**: hero_base
- **m_strIconHeroCard**: panorama:"file://{images}/heroes/rutger_card.psd"
- **m_strMinimapImage**: panorama:"file://{images}/heroes/rutger_mm.psd"
- **m_strIconImageSmall**: panorama:"file://{images}/heroes/rutger_sm.psd"
- **m_strSelectionImage**: panorama:"file://{images}/heroes/rutger.psd"
- **m_strTopBarImage**: panorama:"file://{images}/hud/hero_portraits/rutger_hud.psd"
- **m_strUIAnimGraph**: resource_name:"models/heroes_staging/rutger/ui_rutger.vanmgrph"
- **m_strDeathSound**: soundevent:"Player.DeathFemale"
- **m_hGameSoundEventScript**: resource_name:"soundevents/game_sounds_heroes/game_sounds_hero_rutger.vsndevts"
- **m_hVOEventScript**: resource_name:"soundevents/vo/vo_hero_genericperson.vsndevts"

---

# Hero: hero_synth

- **_class**: CitadelHeroData_t
- **m_bPlayerSelectable**: True
- **m_bDisabled**: False
- **m_bInDevelopment**: False
- **m_bNeedsTesting**: False
- **m_bAssignedPlayersOnly**: False
- **m_bBotSelectable**: False
- **m_bLimitedTesting**: False
- **m_nComplexity**: 2
- **m_nReadability**: 1
- **m_HeroID**: 50
- **m_strModelName**: resource_name:"models/heroes_staging/synth/synth.vmdl"
- **m_hDamageTakenParticle**: resource_name:"particles/generic/player_damage_screen.vpcf"
- **m_hGroundDamageTakenParticle**: resource_name:"particles/generic/player_ground_damage_screen.vpcf"
- **m_hDeathParticle**: resource_name:"particles/generic/player_death_screen.vpcf"
- **m_hLowHealthParticle**: resource_name:"particles/generic/player_low_health_screen.vpcf"
- **m_hRespawnParticle**: resource_name:"particles/generic/player_respawn_deploy.vpcf"
- **m_nModelSkin**: 0
- **m_mapStartingStats**:
  - **EMaxMoveSpeed**: 7
  - **ESprintSpeed**: 0
  - **ECrouchSpeed**: 4.75
  - **EMoveAcceleration**: 4
  - **ELightMeleeDamage**: 63
  - **EHeavyMeleeDamage**: 116
  - **EMaxHealth**: 550
  - **EWeaponPower**: 0
  - **EReloadSpeed**: 1
  - **EWeaponPowerScale**: 1
  - **EProcBuildUpRateScale**: 1
  - **EStamina**: 3
  - **EBaseHealthRegen**: 2.0
  - **EStaminaRegenPerSecond**: 0.2
  - **EAbilityResourceMax**: 0
  - **EAbilityResourceRegenPerSecond**: 0
  - **ECritDamageReceivedScale**: 1.0
  - **ETechDuration**: 1
  - **ETechRange**: 1
  - **ETechArmorDamageReduction**: -15.0
- **m_flCollisionRadius**: 20
- **m_flCollisionHeight**: 80
- **m_flStepHeight**: 32
- **m_mapBoundAbilities**:
  - **ESlot_Weapon_Primary**: citadel_weapon_synth_set
  - **ESlot_Weapon_Melee**: citadel_ability_melee_genericperson
  - **ESlot_Ability_Mantle**: citadel_ability_mantle
  - **ESlot_Ability_Jump**: citadel_ability_jump
  - **ESlot_Ability_Slide**: citadel_ability_slide
  - **ESlot_Ability_ZipLine**: citadel_ability_zip_line
  - **ESlot_Ability_ZipLineBoost**: citadel_ability_zipline_boost
  - **ESlot_Ability_Innate_1**: citadel_ability_dash
  - **ESlot_Ability_Innate_2**: citadel_ability_sprint
  - **ESlot_Ability_Innate_3**: citadel_ability_melee_parry
  - **ESlot_Signature_1**: synth_barrage
  - **ESlot_Signature_2**: synth_plasma_flux
  - **ESlot_Signature_3**: synth_pulse
  - **ESlot_Signature_4**: synth_affliction
- **m_mapItemSlotInfo**:
  - **EItemSlotType_WeaponMod**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
  - **EItemSlotType_Armor**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
  - **EItemSlotType_Tech**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
- **m_mapPurchaseBonuses**:
  - **EItemSlotType_WeaponMod**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 6 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 2 | 10 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 3 | 14 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 4 | 18 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
  - **EItemSlotType_Armor**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 11 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 2 | 14 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 3 | 17 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 4 | 20 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
  - **EItemSlotType_Tech**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 4 | MODIFIER_VALUE_TECH_POWER |
    | 2 | 8 | MODIFIER_VALUE_TECH_POWER |
    | 3 | 12 | MODIFIER_VALUE_TECH_POWER |
    | 4 | 16 | MODIFIER_VALUE_TECH_POWER |
- **m_mapLevelInfo**:
  - **1**:
    - **m_unRequiredGold**: 0
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **2**:
    - **m_unRequiredGold**: 400
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
      - **EAbilityPoints**: 1
  - **3**:
    - **m_unRequiredGold**: 800
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **4**:
    - **m_unRequiredGold**: 1200
    - **m_bUseStandardUpgrade**: True
  - **5**:
    - **m_unRequiredGold**: 1500
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **6**:
    - **m_unRequiredGold**: 2200
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **7**:
    - **m_unRequiredGold**: 3000
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **8**:
    - **m_unRequiredGold**: 4500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **9**:
    - **m_unRequiredGold**: 6000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **10**:
    - **m_unRequiredGold**: 7500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **11**:
    - **m_unRequiredGold**: 9000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **12**:
    - **m_unRequiredGold**: 10500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **13**:
    - **m_unRequiredGold**: 12000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **14**:
    - **m_unRequiredGold**: 13000
    - **m_bUseStandardUpgrade**: True
  - **15**:
    - **m_unRequiredGold**: 14000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **16**:
    - **m_unRequiredGold**: 15000
    - **m_bUseStandardUpgrade**: True
  - **17**:
    - **m_unRequiredGold**: 16000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **18**:
    - **m_unRequiredGold**: 18000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **19**:
    - **m_unRequiredGold**: 20000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **20**:
    - **m_unRequiredGold**: 22000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **21**:
    - **m_unRequiredGold**: 24000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **22**:
    - **m_unRequiredGold**: 27000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **23**:
    - **m_unRequiredGold**: 30000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **24**:
    - **m_unRequiredGold**: 33000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **25**:
    - **m_unRequiredGold**: 36000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **26**:
    - **m_unRequiredGold**: 39000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **27**:
    - **m_unRequiredGold**: 42000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **28**:
    - **m_unRequiredGold**: 45000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **29**:
    - **m_unRequiredGold**: 48000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
- **m_hFootstepSounds**: sweetener_default
- **m_strFootstepSoundEventDefault**: soundevent:"Pocket.Footstep.Multi"
- **m_flStealthSpeedMetersPerSecond**: 4
- **m_flFootstepSoundTravelDistanceMeters**: 20
- **m_flStepSoundTime**: 0.3
- **m_vecAnimGraphDefaultValueOverrides**:
  | m_strParamName | m_strParamValue |
  | --- | --- |
  | e_SWITCH_4wayRoll_ON/OFF | 0 |
  | e_SWITCH_Recoil_ON/OFF | 0 |
  | e_SWITCH_ZiplinePhysicsSway_ON/OFF | 0 |
  | e_SWITCH_ShootStyle | 0 |
- **m_strLastHitSound**: soundevent:"LastHit.Default"
- **m_strLowHealthSound**: soundevent:"PlayerAlert.LowHealth"
- **m_colorUI**:
  - 84
  - 95
  - 149
- **m_colorGlowFriendly**:
  - 255
  - 239
  - 215
- **m_colorGlowEnemy**:
  - 255
  - 0
  - 0
- **m_colorGlowTeam1**:
  - 231
  - 182
  - 89
- **m_colorGlowTeam2**:
  - 91
  - 121
  - 230
- **m_vecAmbientParticleSettings**:
  | m_eAttachmentType | m_nCP |
  | --- | --- |
  | PATTACH_ABSORIGIN_FOLLOW | 0 |
  | PATTACH_POINT_FOLLOW | 1 |
- **m_heroStatsUI**:
  - **m_vecDisplayStats**:
    | m_eStatType | m_eStatCategory |
    | --- | --- |
    | EMaxHealth | ECitadelStat_Vitality |
    | EBaseHealthRegen | ECitadelStat_Vitality |
    | EBulletArmorDamageReduction | ECitadelStat_Vitality |
    | ETechArmorDamageReduction | ECitadelStat_Vitality |
    | ETechPower | ECitadelStat_Spirit |
    | EWeaponDPS | ECitadelStat_Weapon |
    | EBulletDamage | ECitadelStat_Weapon |
    | EClipSize | ECitadelStat_Weapon |
    | ERoundsPerSecond | ECitadelStat_Weapon |
    | ELightMeleeDamage | ECitadelStat_Weapon |
    | EHeavyMeleeDamage | ECitadelStat_Weapon |
    | EMaxMoveSpeed | ECitadelStat_Vitality |
    | ESprintSpeed | ECitadelStat_Vitality |
    | EStamina | ECitadelStat_Vitality |
  - **m_eWeaponStatDisplay**: EMeleeDamage_DEPRECATED
- **m_mapScalingStats**:
- **m_heroStatsDisplay**:
  - **m_vecHealthHeaderStats**:
    - EMaxHealth
    - EBaseHealthRegen
  - **m_vecHealthStats**:
    - EBulletArmorDamageReduction
    - ETechArmorDamageReduction
    - EBulletShieldHealth
    - ETechShieldHealth
    - EBulletLifesteal
    - ETechLifesteal
    - EMaxMoveSpeed
    - ESprintSpeed
    - EStamina
    - EHealingOutput
  - **m_vecWeaponHeaderStats**:
    - EWeaponDPS
    - EBulletDamage
  - **m_vecWeaponStats**:
    - ELightMeleeDamage
    - EHeavyMeleeDamage
    - EFireRate
    - EClipSize
  - **m_vecMagicHeaderStats**:
    - ETechPower
  - **m_vecMagicStats**:
    - ETechCooldown
    - ETechRange
    - ETechDuration
- **m_mapStandardLevelUpUpgrades**:
  - **MODIFIER_VALUE_BASE_BULLET_DAMAGE_FROM_LEVEL**: 0.4
  - **MODIFIER_VALUE_BASE_MELEE_DAMAGE_FROM_LEVEL**: 3.4
  - **MODIFIER_VALUE_BASE_HEALTH_FROM_LEVEL**: 31.0
  - **MODIFIER_VALUE_TECH_DAMAGE_PERCENT**: 0.0
  - **MODIFIER_VALUE_BULLET_ARMOR_DAMAGE_RESIST**: 0.0
- **m_eAbilityResourceType**: EResourceType_None
- **m_ShopStatDisplay**:
  - **m_eWeaponStatsDisplay**:
    - **m_vecDisplayStats**:
      - EBulletDamage
      - EBaseWeaponDamageIncrease
      - ERoundsPerSecond
      - EFireRate
      - EClipSize
      - EClipSizeIncrease
      - EReloadTime
      - EReloadSpeed
      - EBulletSpeed
      - EBulletSpeedIncrease
      - EBulletLifesteal
    - **m_vecOtherDisplayStats**:
      - ELightMeleeDamage
      - EHeavyMeleeDamage
    - **m_eWeaponAttributes**: EWeaponAttribute_Spreadshot | EWeaponAttribute_CloseRange
    - **m_strWeaponImage**: panorama:"file://{images}/heroes/guns/synth_gun.psd"
  - **m_eVitalityStatsDisplay**:
    - **m_vecDisplayStats**:
      - EMaxHealth
      - EBaseHealthRegen
      - EBulletArmorDamageReduction
      - ETechArmorDamageReduction
      - EBulletShieldHealth
      - ETechShieldHealth
      - ECritDamageReceivedScale
    - **m_vecOtherDisplayStats**:
      - EMaxMoveSpeed
      - ESprintSpeed
      - EStaminaCooldown
      - EStaminaRegenIncrease
      - EStamina
  - **m_eSpiritStatsDisplay**:
    - **m_vecDisplayStats**:
      - ETechCooldown
      - ETechDuration
      - ETechRange
      - ETechLifesteal
      - EMaxChargesIncrease
      - ETechCooldownBetweenChargeUses
- **_base**: hero_base
- **m_strIconHeroCard**: panorama:"file://{images}/heroes/synth_card.psd"
- **m_strIconImageSmall**: panorama:"file://{images}/heroes/synth_sm.psd"
- **m_strMinimapImage**: panorama:"file://{images}/heroes/synth_mm.psd"
- **m_strSelectionImage**: panorama:"file://{images}/heroes/synth.psd"
- **m_strTopBarImage**: panorama:"file://{images}/hud/hero_portraits/synth_hud.psd"
- **m_strUIAnimGraph**: resource_name:"models/heroes_staging/synth/ui_synth.vanmgrph"
- **m_strDeathSound**: soundevent:"Pocket.Death"
- **m_hGameSoundEventScript**: resource_name:"soundevents/hero/pocket.vsndevts"
- **m_hVOEventScript**: resource_name:"soundevents/vo/vo_hero_synth.vsndevts"
- **m_hGeneratedVOEventScript**: resource_name:"soundevents/vo/generated_vo_hero_synth.vsndevts"
- **m_strTopBarVertical**: panorama:"file://{images}/heroes/synth_vertical.psd"
- **m_strRosterSelectedSound**: soundevent:"Pocket.VO.HeroPick"
- **m_strRosterRemovedSound**: soundevent:"Pocket.VO.HeroRemove"
- **m_strUIPortraitMap**: maps/ui/hero_prefabs/pocket.vmap
- **m_RecommendedUpgrades**:
  - upgrade_health_stimpak
  - upgrade_magic_burst
  - upgrade_close_range
  - upgrade_resilience
  - upgrade_improved_spirit
  - upgrade_crackshot
  - upgrade_tech_defense_shredders
  - upgrade_magic_shield
  - upgrade_regenerating_bullet_shield
  - upgrade_suppressor
  - upgrade_magic_vulnerability
  - upgrade_rocket_booster
  - upgrade_magic_shock
  - upgrade_soaring_spirit
  - upgrade_magic_slow
  - upgrade_mega_spirit
  - upgrade_escalating_exposure
- **m_strUIShopAnimGraph**: resource_name:"models/heroes_staging/synth/ui_shop_synth.vanmgrph"
- **m_strUIShoppingMap**: maps/ui/hero_shop/pocket_shop.vmap

---

# Hero: hero_thumper

- **_class**: CitadelHeroData_t
- **m_bPlayerSelectable**: True
- **m_bDisabled**: True
- **m_bInDevelopment**: True
- **m_bNeedsTesting**: True
- **m_bAssignedPlayersOnly**: False
- **m_bBotSelectable**: False
- **m_bLimitedTesting**: False
- **m_nComplexity**: 2
- **m_nReadability**: 1
- **m_HeroID**: 51
- **m_strModelName**: resource_name:"models/heroes_staging/thumper/thumper.vmdl"
- **m_hDamageTakenParticle**: resource_name:"particles/generic/player_damage_screen.vpcf"
- **m_hGroundDamageTakenParticle**: resource_name:"particles/generic/player_ground_damage_screen.vpcf"
- **m_hDeathParticle**: resource_name:"particles/generic/player_death_screen.vpcf"
- **m_hLowHealthParticle**: resource_name:"particles/generic/player_low_health_screen.vpcf"
- **m_hRespawnParticle**: resource_name:"particles/generic/player_respawn_deploy.vpcf"
- **m_nModelSkin**: 0
- **m_mapStartingStats**:
  - **EMaxMoveSpeed**: 7
  - **ESprintSpeed**: 0
  - **ECrouchSpeed**: 4.75
  - **EMoveAcceleration**: 4
  - **ELightMeleeDamage**: 63
  - **EHeavyMeleeDamage**: 116
  - **EMaxHealth**: 550
  - **EWeaponPower**: 0
  - **EReloadSpeed**: 1
  - **EWeaponPowerScale**: 1
  - **EProcBuildUpRateScale**: 1
  - **EStamina**: 3
  - **EBaseHealthRegen**: 2.0
  - **EStaminaRegenPerSecond**: 0.2
  - **EAbilityResourceMax**: 0
  - **EAbilityResourceRegenPerSecond**: 0
  - **ECritDamageReceivedScale**: 1.0
  - **ETechDuration**: 1
  - **ETechRange**: 1
- **m_flCollisionRadius**: 20
- **m_flCollisionHeight**: 80
- **m_flStepHeight**: 32
- **m_mapBoundAbilities**:
  - **ESlot_Weapon_Primary**: citadel_weapon_thumper_set
  - **ESlot_Weapon_Melee**: citadel_ability_melee_thumper
  - **ESlot_Ability_Mantle**: citadel_ability_mantle
  - **ESlot_Ability_Jump**: citadel_ability_jump
  - **ESlot_Ability_Slide**: citadel_ability_slide
  - **ESlot_Ability_ZipLine**: citadel_ability_zip_line
  - **ESlot_Ability_ZipLineBoost**: citadel_ability_zipline_boost
  - **ESlot_Ability_Innate_1**: citadel_ability_dash
  - **ESlot_Ability_Innate_2**: citadel_ability_sprint
  - **ESlot_Ability_Innate_3**: citadel_ability_melee_parry
  - **ESlot_Signature_1**: thumper_ability_1
  - **ESlot_Signature_2**: thumper_ability_2
  - **ESlot_Signature_3**: thumper_ability_3
  - **ESlot_Signature_4**: thumper_ability_4
- **m_mapItemSlotInfo**:
  - **EItemSlotType_WeaponMod**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
  - **EItemSlotType_Armor**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
  - **EItemSlotType_Tech**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
- **m_mapPurchaseBonuses**:
  - **EItemSlotType_WeaponMod**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 6 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 2 | 10 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 3 | 14 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 4 | 18 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
  - **EItemSlotType_Armor**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 11 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 2 | 14 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 3 | 17 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 4 | 20 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
  - **EItemSlotType_Tech**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 4 | MODIFIER_VALUE_TECH_POWER |
    | 2 | 8 | MODIFIER_VALUE_TECH_POWER |
    | 3 | 12 | MODIFIER_VALUE_TECH_POWER |
    | 4 | 16 | MODIFIER_VALUE_TECH_POWER |
- **m_mapLevelInfo**:
  - **1**:
    - **m_unRequiredGold**: 0
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **2**:
    - **m_unRequiredGold**: 400
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
      - **EAbilityPoints**: 1
  - **3**:
    - **m_unRequiredGold**: 800
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **4**:
    - **m_unRequiredGold**: 1200
    - **m_bUseStandardUpgrade**: True
  - **5**:
    - **m_unRequiredGold**: 1500
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **6**:
    - **m_unRequiredGold**: 2200
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **7**:
    - **m_unRequiredGold**: 3000
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **8**:
    - **m_unRequiredGold**: 4500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **9**:
    - **m_unRequiredGold**: 6000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **10**:
    - **m_unRequiredGold**: 7500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **11**:
    - **m_unRequiredGold**: 9000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **12**:
    - **m_unRequiredGold**: 10500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **13**:
    - **m_unRequiredGold**: 12000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **14**:
    - **m_unRequiredGold**: 13000
    - **m_bUseStandardUpgrade**: True
  - **15**:
    - **m_unRequiredGold**: 14000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **16**:
    - **m_unRequiredGold**: 15000
    - **m_bUseStandardUpgrade**: True
  - **17**:
    - **m_unRequiredGold**: 16000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **18**:
    - **m_unRequiredGold**: 18000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **19**:
    - **m_unRequiredGold**: 20000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **20**:
    - **m_unRequiredGold**: 22000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **21**:
    - **m_unRequiredGold**: 24000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **22**:
    - **m_unRequiredGold**: 27000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **23**:
    - **m_unRequiredGold**: 30000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **24**:
    - **m_unRequiredGold**: 33000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **25**:
    - **m_unRequiredGold**: 36000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **26**:
    - **m_unRequiredGold**: 39000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **27**:
    - **m_unRequiredGold**: 42000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **28**:
    - **m_unRequiredGold**: 45000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **29**:
    - **m_unRequiredGold**: 48000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
- **m_hFootstepSounds**: sweetener_default
- **m_strFootstepSoundEventDefault**: soundevent:"Hero.Default.Footstep"
- **m_flStealthSpeedMetersPerSecond**: 4
- **m_flFootstepSoundTravelDistanceMeters**: 20
- **m_flStepSoundTime**: 0.3
- **m_vecAnimGraphDefaultValueOverrides**:
  | m_strParamName | m_strParamValue |
  | --- | --- |
  | e_SWITCH_4wayRoll_ON/OFF | 0 |
  | e_SWITCH_Recoil_ON/OFF | 0 |
  | e_SWITCH_ZiplinePhysicsSway_ON/OFF | 0 |
  | e_SWITCH_ShootStyle | 0 |
- **m_strLastHitSound**: soundevent:"LastHit.Default"
- **m_strLowHealthSound**: soundevent:"PlayerAlert.LowHealth"
- **m_colorUI**:
  - 255
  - 255
  - 255
- **m_colorGlowFriendly**:
  - 255
  - 239
  - 215
- **m_colorGlowEnemy**:
  - 255
  - 0
  - 0
- **m_colorGlowTeam1**:
  - 231
  - 182
  - 89
- **m_colorGlowTeam2**:
  - 91
  - 121
  - 230
- **m_vecAmbientParticleSettings**:
  | m_eAttachmentType | m_nCP |
  | --- | --- |
  | PATTACH_ABSORIGIN_FOLLOW | 0 |
  | PATTACH_POINT_FOLLOW | 1 |
- **m_heroStatsUI**:
  - **m_vecDisplayStats**:
    | m_eStatType | m_eStatCategory |
    | --- | --- |
    | EMaxHealth | ECitadelStat_Vitality |
    | EBaseHealthRegen | ECitadelStat_Vitality |
    | EBulletArmorDamageReduction | ECitadelStat_Vitality |
    | ETechArmorDamageReduction | ECitadelStat_Vitality |
    | ETechPower | ECitadelStat_Spirit |
    | EWeaponDPS | ECitadelStat_Weapon |
    | EBulletDamage | ECitadelStat_Weapon |
    | EClipSize | ECitadelStat_Weapon |
    | ERoundsPerSecond | ECitadelStat_Weapon |
    | ELightMeleeDamage | ECitadelStat_Weapon |
    | EHeavyMeleeDamage | ECitadelStat_Weapon |
    | EMaxMoveSpeed | ECitadelStat_Vitality |
    | ESprintSpeed | ECitadelStat_Vitality |
    | EStamina | ECitadelStat_Vitality |
  - **m_eWeaponStatDisplay**: EMeleeDamage_DEPRECATED
- **m_mapScalingStats**:
- **m_heroStatsDisplay**:
  - **m_vecHealthHeaderStats**:
    - EMaxHealth
    - EBaseHealthRegen
  - **m_vecHealthStats**:
    - EBulletArmorDamageReduction
    - ETechArmorDamageReduction
    - EBulletShieldHealth
    - ETechShieldHealth
    - EBulletLifesteal
    - ETechLifesteal
    - EMaxMoveSpeed
    - ESprintSpeed
    - EStamina
    - EHealingOutput
  - **m_vecWeaponHeaderStats**:
    - EWeaponDPS
    - EBulletDamage
  - **m_vecWeaponStats**:
    - ELightMeleeDamage
    - EHeavyMeleeDamage
    - EFireRate
    - EClipSize
  - **m_vecMagicHeaderStats**:
    - ETechPower
  - **m_vecMagicStats**:
    - ETechCooldown
    - ETechRange
    - ETechDuration
- **m_mapStandardLevelUpUpgrades**:
  - **MODIFIER_VALUE_BASE_BULLET_DAMAGE_FROM_LEVEL**: 0.0
  - **MODIFIER_VALUE_BASE_MELEE_DAMAGE_FROM_LEVEL**: 3.4
  - **MODIFIER_VALUE_BASE_HEALTH_FROM_LEVEL**: 41.0
  - **MODIFIER_VALUE_TECH_DAMAGE_PERCENT**: 0.0
  - **MODIFIER_VALUE_BULLET_ARMOR_DAMAGE_RESIST**: 0.0
- **m_eAbilityResourceType**: EResourceType_None
- **m_ShopStatDisplay**:
  - **m_eWeaponStatsDisplay**:
    - **m_vecDisplayStats**:
      - EBulletDamage
      - EBaseWeaponDamageIncrease
      - ERoundsPerSecond
      - EFireRate
      - EClipSize
      - EClipSizeIncrease
      - EReloadTime
      - EReloadSpeed
      - EBulletSpeed
      - EBulletSpeedIncrease
      - EBulletLifesteal
    - **m_vecOtherDisplayStats**:
      - ELightMeleeDamage
      - EHeavyMeleeDamage
  - **m_eVitalityStatsDisplay**:
    - **m_vecDisplayStats**:
      - EMaxHealth
      - EBaseHealthRegen
      - EBulletArmorDamageReduction
      - ETechArmorDamageReduction
      - EBulletShieldHealth
      - ETechShieldHealth
      - ECritDamageReceivedScale
    - **m_vecOtherDisplayStats**:
      - EMaxMoveSpeed
      - ESprintSpeed
      - EStaminaCooldown
      - EStaminaRegenIncrease
      - EStamina
  - **m_eSpiritStatsDisplay**:
    - **m_vecDisplayStats**:
      - ETechCooldown
      - ETechDuration
      - ETechRange
      - ETechLifesteal
      - EMaxChargesIncrease
      - ETechCooldownBetweenChargeUses
- **_base**: hero_base
- **m_strSelectionImage**: panorama:"file://{images}/heroes/thumper.psd"
- **m_strIconImageSmall**: panorama:"file://{images}/heroes/thumper_sm.psd"
- **m_strMinimapImage**: panorama:"file://{images}/heroes/thumper_mm.psd"
- **m_strUIAnimGraph**: resource_name:"models/heroes_staging/thumper/ui_thumper.vanmgrph"
- **m_strDeathSound**: soundevent:"Player.DeathFemale"
- **m_hGameSoundEventScript**: resource_name:"soundevents/game_sounds_heroes/game_sounds_hero_thumper.vsndevts"
- **m_hVOEventScript**: resource_name:"soundevents/vo/vo_hero_thumper.vsndevts"
- **m_strIconHeroCard**: panorama:"file://{images}/heroes/thumper_sm.psd"
- **m_strUIShopAnimGraph**: resource_name:"models/heroes_staging/thumper/ui_shop_thumper.vanmgrph"
- **m_strUIShoppingMap**: maps/ui/hero_shop/thumper_shop.vmap

---

# Hero: hero_mirage

- **_class**: CitadelHeroData_t
- **m_bPlayerSelectable**: True
- **m_bDisabled**: False
- **m_bInDevelopment**: True
- **m_bNeedsTesting**: False
- **m_bAssignedPlayersOnly**: False
- **m_bBotSelectable**: False
- **m_bLimitedTesting**: False
- **m_nComplexity**: 2
- **m_nReadability**: 1
- **m_HeroID**: 52
- **m_strModelName**: resource_name:"models/heroes_staging/mirage/mirage.vmdl"
- **m_hDamageTakenParticle**: resource_name:"particles/generic/player_damage_screen.vpcf"
- **m_hGroundDamageTakenParticle**: resource_name:"particles/generic/player_ground_damage_screen.vpcf"
- **m_hDeathParticle**: resource_name:"particles/generic/player_death_screen.vpcf"
- **m_hLowHealthParticle**: resource_name:"particles/generic/player_low_health_screen.vpcf"
- **m_hRespawnParticle**: resource_name:"particles/generic/player_respawn_deploy.vpcf"
- **m_nModelSkin**: 0
- **m_mapStartingStats**:
  - **EMaxMoveSpeed**: 7
  - **ESprintSpeed**: 0
  - **ECrouchSpeed**: 4.75
  - **EMoveAcceleration**: 4
  - **ELightMeleeDamage**: 63
  - **EHeavyMeleeDamage**: 116
  - **EMaxHealth**: 550
  - **EWeaponPower**: 0
  - **EReloadSpeed**: 1
  - **EWeaponPowerScale**: 1
  - **EProcBuildUpRateScale**: 1
  - **EStamina**: 3
  - **EBaseHealthRegen**: 2.0
  - **EStaminaRegenPerSecond**: 0.2
  - **EAbilityResourceMax**: 0
  - **EAbilityResourceRegenPerSecond**: 0
  - **ECritDamageReceivedScale**: 1.0
  - **ETechDuration**: 1
  - **ETechRange**: 1
- **m_flCollisionRadius**: 20
- **m_flCollisionHeight**: 80
- **m_flStepHeight**: 32
- **m_mapBoundAbilities**:
  - **ESlot_Weapon_Primary**: citadel_weapon_mirage_set
  - **ESlot_Weapon_Melee**: citadel_ability_melee_genericperson
  - **ESlot_Ability_Mantle**: citadel_ability_mantle
  - **ESlot_Ability_Jump**: citadel_ability_jump
  - **ESlot_Ability_Slide**: citadel_ability_slide
  - **ESlot_Ability_ZipLine**: citadel_ability_zip_line
  - **ESlot_Ability_ZipLineBoost**: citadel_ability_zipline_boost
  - **ESlot_Ability_Innate_1**: citadel_ability_dash
  - **ESlot_Ability_Innate_2**: citadel_ability_sprint
  - **ESlot_Ability_Innate_3**: citadel_ability_melee_parry
  - **ESlot_Signature_1**: mirage_tornado
  - **ESlot_Signature_2**: mirage_fire_beetles
  - **ESlot_Signature_3**: mirage_sand_phantom
  - **ESlot_Signature_4**: mirage_djinns_reach
- **m_mapItemSlotInfo**:
  - **EItemSlotType_WeaponMod**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
  - **EItemSlotType_Armor**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
  - **EItemSlotType_Tech**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
- **m_mapPurchaseBonuses**:
  - **EItemSlotType_WeaponMod**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 6 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 2 | 10 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 3 | 14 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 4 | 18 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
  - **EItemSlotType_Armor**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 11 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 2 | 14 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 3 | 17 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 4 | 20 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
  - **EItemSlotType_Tech**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 4 | MODIFIER_VALUE_TECH_POWER |
    | 2 | 8 | MODIFIER_VALUE_TECH_POWER |
    | 3 | 12 | MODIFIER_VALUE_TECH_POWER |
    | 4 | 16 | MODIFIER_VALUE_TECH_POWER |
- **m_mapLevelInfo**:
  - **1**:
    - **m_unRequiredGold**: 0
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **2**:
    - **m_unRequiredGold**: 400
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
      - **EAbilityPoints**: 1
  - **3**:
    - **m_unRequiredGold**: 800
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **4**:
    - **m_unRequiredGold**: 1200
    - **m_bUseStandardUpgrade**: True
  - **5**:
    - **m_unRequiredGold**: 1500
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **6**:
    - **m_unRequiredGold**: 2200
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **7**:
    - **m_unRequiredGold**: 3000
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **8**:
    - **m_unRequiredGold**: 4500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **9**:
    - **m_unRequiredGold**: 6000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **10**:
    - **m_unRequiredGold**: 7500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **11**:
    - **m_unRequiredGold**: 9000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **12**:
    - **m_unRequiredGold**: 10500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **13**:
    - **m_unRequiredGold**: 12000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **14**:
    - **m_unRequiredGold**: 13000
    - **m_bUseStandardUpgrade**: True
  - **15**:
    - **m_unRequiredGold**: 14000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **16**:
    - **m_unRequiredGold**: 15000
    - **m_bUseStandardUpgrade**: True
  - **17**:
    - **m_unRequiredGold**: 16000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **18**:
    - **m_unRequiredGold**: 18000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **19**:
    - **m_unRequiredGold**: 20000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **20**:
    - **m_unRequiredGold**: 22000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **21**:
    - **m_unRequiredGold**: 24000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **22**:
    - **m_unRequiredGold**: 27000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **23**:
    - **m_unRequiredGold**: 30000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **24**:
    - **m_unRequiredGold**: 33000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **25**:
    - **m_unRequiredGold**: 36000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **26**:
    - **m_unRequiredGold**: 39000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **27**:
    - **m_unRequiredGold**: 42000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **28**:
    - **m_unRequiredGold**: 45000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **29**:
    - **m_unRequiredGold**: 48000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
- **m_hFootstepSounds**: sweetener_default
- **m_strFootstepSoundEventDefault**: soundevent:"Mirage.Footstep"
- **m_flStealthSpeedMetersPerSecond**: 4
- **m_flFootstepSoundTravelDistanceMeters**: 20
- **m_flStepSoundTime**: 0.35
- **m_vecAnimGraphDefaultValueOverrides**:
  | m_strParamName | m_strParamValue |
  | --- | --- |
  | e_SWITCH_4wayRoll_ON/OFF | 0 |
  | e_SWITCH_Recoil_ON/OFF | 0 |
  | e_SWITCH_ZiplinePhysicsSway_ON/OFF | 0 |
  | e_SWITCH_ShootStyle | 0 |
- **m_strLastHitSound**: soundevent:"LastHit.Default"
- **m_strLowHealthSound**: soundevent:"PlayerAlert.LowHealth"
- **m_colorUI**:
  - 132
  - 103
  - 60
- **m_colorGlowFriendly**:
  - 255
  - 239
  - 215
- **m_colorGlowEnemy**:
  - 255
  - 0
  - 0
- **m_colorGlowTeam1**:
  - 231
  - 182
  - 89
- **m_colorGlowTeam2**:
  - 91
  - 121
  - 230
- **m_vecAmbientParticleSettings**:
  | m_eAttachmentType | m_nCP |
  | --- | --- |
  | PATTACH_ABSORIGIN_FOLLOW | 0 |
  | PATTACH_POINT_FOLLOW | 1 |
- **m_heroStatsUI**:
  - **m_vecDisplayStats**:
    | m_eStatType | m_eStatCategory |
    | --- | --- |
    | EMaxHealth | ECitadelStat_Vitality |
    | EBaseHealthRegen | ECitadelStat_Vitality |
    | EBulletArmorDamageReduction | ECitadelStat_Vitality |
    | ETechArmorDamageReduction | ECitadelStat_Vitality |
    | ETechPower | ECitadelStat_Spirit |
    | EWeaponDPS | ECitadelStat_Weapon |
    | EBulletDamage | ECitadelStat_Weapon |
    | EClipSize | ECitadelStat_Weapon |
    | ERoundsPerSecond | ECitadelStat_Weapon |
    | ELightMeleeDamage | ECitadelStat_Weapon |
    | EHeavyMeleeDamage | ECitadelStat_Weapon |
    | EMaxMoveSpeed | ECitadelStat_Vitality |
    | ESprintSpeed | ECitadelStat_Vitality |
    | EStamina | ECitadelStat_Vitality |
  - **m_eWeaponStatDisplay**: EMeleeDamage_DEPRECATED
- **m_mapScalingStats**:
- **m_heroStatsDisplay**:
  - **m_vecHealthHeaderStats**:
    - EMaxHealth
    - EBaseHealthRegen
  - **m_vecHealthStats**:
    - EBulletArmorDamageReduction
    - ETechArmorDamageReduction
    - EBulletShieldHealth
    - ETechShieldHealth
    - EBulletLifesteal
    - ETechLifesteal
    - EMaxMoveSpeed
    - ESprintSpeed
    - EStamina
    - EHealingOutput
  - **m_vecWeaponHeaderStats**:
    - EWeaponDPS
    - EBulletDamage
  - **m_vecWeaponStats**:
    - ELightMeleeDamage
    - EHeavyMeleeDamage
    - EFireRate
    - EClipSize
  - **m_vecMagicHeaderStats**:
    - ETechPower
  - **m_vecMagicStats**:
    - ETechCooldown
    - ETechRange
    - ETechDuration
- **m_mapStandardLevelUpUpgrades**:
  - **MODIFIER_VALUE_BASE_BULLET_DAMAGE_FROM_LEVEL**: 1.7
  - **MODIFIER_VALUE_BASE_MELEE_DAMAGE_FROM_LEVEL**: 3.4
  - **MODIFIER_VALUE_BASE_HEALTH_FROM_LEVEL**: 41.0
  - **MODIFIER_VALUE_TECH_DAMAGE_PERCENT**: 0.0
  - **MODIFIER_VALUE_BULLET_ARMOR_DAMAGE_RESIST**: 0.0
- **m_eAbilityResourceType**: EResourceType_None
- **m_ShopStatDisplay**:
  - **m_eWeaponStatsDisplay**:
    - **m_vecDisplayStats**:
      - EBulletDamage
      - EBaseWeaponDamageIncrease
      - ERoundsPerSecond
      - EFireRate
      - EClipSize
      - EClipSizeIncrease
      - EReloadTime
      - EReloadSpeed
      - EBulletSpeed
      - EBulletSpeedIncrease
      - EBulletLifesteal
    - **m_vecOtherDisplayStats**:
      - ELightMeleeDamage
      - EHeavyMeleeDamage
    - **m_eWeaponAttributes**: EWeaponAttribute_MediumRange | EWeaponAttribute_HeavyHitter
  - **m_eVitalityStatsDisplay**:
    - **m_vecDisplayStats**:
      - EMaxHealth
      - EBaseHealthRegen
      - EBulletArmorDamageReduction
      - ETechArmorDamageReduction
      - EBulletShieldHealth
      - ETechShieldHealth
      - ECritDamageReceivedScale
    - **m_vecOtherDisplayStats**:
      - EMaxMoveSpeed
      - ESprintSpeed
      - EStaminaCooldown
      - EStaminaRegenIncrease
      - EStamina
  - **m_eSpiritStatsDisplay**:
    - **m_vecDisplayStats**:
      - ETechCooldown
      - ETechDuration
      - ETechRange
      - ETechLifesteal
      - EMaxChargesIncrease
      - ETechCooldownBetweenChargeUses
- **_base**: hero_base
- **m_strSelectionImage**: panorama:"file://{images}/heroes/mirage.psd"
- **m_strIconHeroCard**: panorama:"file://{images}/heroes/mirage_card.psd"
- **m_strIconImageSmall**: panorama:"file://{images}/heroes/mirage_sm.psd"
- **m_strMinimapImage**: panorama:"file://{images}/heroes/mirage_mm.psd"
- **m_strTopBarImage**: panorama:"file://{images}/hud/hero_portraits/mirage_hud.psd"
- **m_strUIAnimGraph**: resource_name:"models/heroes_staging/mirage/ui_mirage.vanmgrph"
- **m_strDeathSound**: soundevent:"Player.DeathFemale"
- **m_hGameSoundEventScript**: resource_name:"soundevents/hero/mirage.vsndevts"
- **m_hVOEventScript**: resource_name:"soundevents/vo/vo_hero_mirage.vsndevts"
- **m_hGeneratedVOEventScript**: resource_name:"soundevents/vo/generated_vo_hero_mirage.vsndevts"
- **m_strRosterSelectedSound**: soundevent:"Mirage.VO.HeroPick"
- **m_strRosterRemovedSound**: soundevent:"Mirage.VO.HeroRemove"
- **m_strUIPortraitMap**: maps/ui/hero_prefabs/mirage.vmap
- **m_strTopBarVertical**: panorama:"file://{images}/heroes/mirage_vertical.psd"
- **m_RecommendedUpgrades**:
  - upgrade_clip_size
  - upgrade_close_range
  - upgrade_magic_reach
  - upgrade_endurance
  - upgrade_improved_spirit
  - upgrade_magic_tempo
  - upgrade_fleetfoot_boots
  - upgrade_vampire
  - upgrade_bullet_armor
  - upgrade_cold_front
  - upgrade_slowing_bullets
  - upgrade_tech_armor
  - upgrade_magic_shield
  - upgrade_cooldown_reduction
  - upgrade_soaring_spirit
  - upgrade_close_quarter_combat
  - upgrade_tech_purge
  - upgrade_damage_recycler
  - upgrade_tech_range
  - upgrade_mega_spirit
  - upgrade_silencer
  - upgrade_siphon_bullets
- **m_strUIShopAnimGraph**: resource_name:"models/heroes_staging/mirage/ui_shop_mirage.vanmgrph"
- **m_strUIShoppingMap**: maps/ui/hero_shop/mirage_shop.vmap

---

# Hero: hero_slork

- **_class**: CitadelHeroData_t
- **m_bPlayerSelectable**: True
- **m_bDisabled**: True
- **m_bInDevelopment**: True
- **m_bNeedsTesting**: False
- **m_bAssignedPlayersOnly**: False
- **m_bBotSelectable**: False
- **m_bLimitedTesting**: False
- **m_nComplexity**: 2
- **m_nReadability**: 1
- **m_HeroID**: 53
- **m_strModelName**: resource_name:"models/heroes_staging/slork/slork.vmdl"
- **m_hDamageTakenParticle**: resource_name:"particles/generic/player_damage_screen.vpcf"
- **m_hGroundDamageTakenParticle**: resource_name:"particles/generic/player_ground_damage_screen.vpcf"
- **m_hDeathParticle**: resource_name:"particles/generic/player_death_screen.vpcf"
- **m_hLowHealthParticle**: resource_name:"particles/generic/player_low_health_screen.vpcf"
- **m_hRespawnParticle**: resource_name:"particles/generic/player_respawn_deploy.vpcf"
- **m_nModelSkin**: 0
- **m_mapStartingStats**:
  - **EMaxMoveSpeed**: 7
  - **ESprintSpeed**: 0
  - **ECrouchSpeed**: 4.75
  - **EMoveAcceleration**: 4
  - **ELightMeleeDamage**: 63
  - **EHeavyMeleeDamage**: 116
  - **EMaxHealth**: 550
  - **EWeaponPower**: 0
  - **EReloadSpeed**: 1
  - **EWeaponPowerScale**: 1
  - **EProcBuildUpRateScale**: 1
  - **EStamina**: 3
  - **EBaseHealthRegen**: 2.0
  - **EStaminaRegenPerSecond**: 0.2
  - **EAbilityResourceMax**: 0
  - **EAbilityResourceRegenPerSecond**: 0
  - **ECritDamageReceivedScale**: 1.0
  - **ETechDuration**: 1
  - **ETechRange**: 1
- **m_flCollisionRadius**: 20
- **m_flCollisionHeight**: 80
- **m_flStepHeight**: 32
- **m_mapBoundAbilities**:
  - **ESlot_Weapon_Primary**: citadel_weapon_slork_set
  - **ESlot_Weapon_Melee**: citadel_ability_melee_genericperson
  - **ESlot_Ability_Mantle**: citadel_ability_mantle
  - **ESlot_Ability_Jump**: citadel_ability_jump
  - **ESlot_Ability_Slide**: citadel_ability_slide
  - **ESlot_Ability_ZipLine**: citadel_ability_zip_line
  - **ESlot_Ability_ZipLineBoost**: citadel_ability_zipline_boost
  - **ESlot_Ability_Innate_1**: citadel_ability_dash
  - **ESlot_Ability_Innate_2**: citadel_ability_sprint
  - **ESlot_Ability_Innate_3**: citadel_ability_melee_parry
  - **ESlot_Weapon_Secondary**: citadel_weapon_slork_alt
  - **ESlot_Signature_1**: slork_riptide
  - **ESlot_Signature_2**: slork_chomp
  - **ESlot_Signature_3**: slork_last_breath
  - **ESlot_Signature_4**: slork_ability_invis
- **m_mapItemSlotInfo**:
  - **EItemSlotType_WeaponMod**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
  - **EItemSlotType_Armor**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
  - **EItemSlotType_Tech**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
- **m_mapPurchaseBonuses**:
  - **EItemSlotType_WeaponMod**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 6 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 2 | 10 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 3 | 14 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 4 | 18 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
  - **EItemSlotType_Armor**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 11 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 2 | 14 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 3 | 17 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 4 | 20 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
  - **EItemSlotType_Tech**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 4 | MODIFIER_VALUE_TECH_POWER |
    | 2 | 8 | MODIFIER_VALUE_TECH_POWER |
    | 3 | 12 | MODIFIER_VALUE_TECH_POWER |
    | 4 | 16 | MODIFIER_VALUE_TECH_POWER |
- **m_mapLevelInfo**:
  - **1**:
    - **m_unRequiredGold**: 0
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **2**:
    - **m_unRequiredGold**: 400
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
      - **EAbilityPoints**: 1
  - **3**:
    - **m_unRequiredGold**: 800
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **4**:
    - **m_unRequiredGold**: 1200
    - **m_bUseStandardUpgrade**: True
  - **5**:
    - **m_unRequiredGold**: 1500
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **6**:
    - **m_unRequiredGold**: 2200
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **7**:
    - **m_unRequiredGold**: 3000
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **8**:
    - **m_unRequiredGold**: 4500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **9**:
    - **m_unRequiredGold**: 6000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **10**:
    - **m_unRequiredGold**: 7500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **11**:
    - **m_unRequiredGold**: 9000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **12**:
    - **m_unRequiredGold**: 10500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **13**:
    - **m_unRequiredGold**: 12000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **14**:
    - **m_unRequiredGold**: 13000
    - **m_bUseStandardUpgrade**: True
  - **15**:
    - **m_unRequiredGold**: 14000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **16**:
    - **m_unRequiredGold**: 15000
    - **m_bUseStandardUpgrade**: True
  - **17**:
    - **m_unRequiredGold**: 16000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **18**:
    - **m_unRequiredGold**: 18000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **19**:
    - **m_unRequiredGold**: 20000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **20**:
    - **m_unRequiredGold**: 22000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **21**:
    - **m_unRequiredGold**: 24000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **22**:
    - **m_unRequiredGold**: 27000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **23**:
    - **m_unRequiredGold**: 30000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **24**:
    - **m_unRequiredGold**: 33000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **25**:
    - **m_unRequiredGold**: 36000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **26**:
    - **m_unRequiredGold**: 39000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **27**:
    - **m_unRequiredGold**: 42000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **28**:
    - **m_unRequiredGold**: 45000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **29**:
    - **m_unRequiredGold**: 48000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
- **m_hFootstepSounds**: sweetener_default
- **m_strFootstepSoundEventDefault**: soundevent:""
- **m_flStealthSpeedMetersPerSecond**: 4
- **m_flFootstepSoundTravelDistanceMeters**: 20
- **m_flStepSoundTime**: 0.385
- **m_vecAnimGraphDefaultValueOverrides**:
  | m_strParamName | m_strParamValue |
  | --- | --- |
  | e_SWITCH_4wayRoll_ON/OFF | 0 |
  | e_SWITCH_Recoil_ON/OFF | 0 |
  | e_SWITCH_ZiplinePhysicsSway_ON/OFF | 0 |
  | e_SWITCH_ShootStyle | 0 |
- **m_strLastHitSound**: soundevent:"LastHit.Default"
- **m_strLowHealthSound**: soundevent:"PlayerAlert.LowHealth"
- **m_colorUI**:
  - 255
  - 255
  - 255
- **m_colorGlowFriendly**:
  - 255
  - 239
  - 215
- **m_colorGlowEnemy**:
  - 255
  - 0
  - 0
- **m_colorGlowTeam1**:
  - 231
  - 182
  - 89
- **m_colorGlowTeam2**:
  - 91
  - 121
  - 230
- **m_vecAmbientParticleSettings**:
  | m_eAttachmentType | m_nCP |
  | --- | --- |
  | PATTACH_ABSORIGIN_FOLLOW | 0 |
  | PATTACH_POINT_FOLLOW | 1 |
- **m_heroStatsUI**:
  - **m_vecDisplayStats**:
    | m_eStatType | m_eStatCategory |
    | --- | --- |
    | EMaxHealth | ECitadelStat_Vitality |
    | EBaseHealthRegen | ECitadelStat_Vitality |
    | EBulletArmorDamageReduction | ECitadelStat_Vitality |
    | ETechArmorDamageReduction | ECitadelStat_Vitality |
    | ETechPower | ECitadelStat_Spirit |
    | EWeaponDPS | ECitadelStat_Weapon |
    | EBulletDamage | ECitadelStat_Weapon |
    | EClipSize | ECitadelStat_Weapon |
    | ERoundsPerSecond | ECitadelStat_Weapon |
    | ELightMeleeDamage | ECitadelStat_Weapon |
    | EHeavyMeleeDamage | ECitadelStat_Weapon |
    | EMaxMoveSpeed | ECitadelStat_Vitality |
    | ESprintSpeed | ECitadelStat_Vitality |
    | EStamina | ECitadelStat_Vitality |
  - **m_eWeaponStatDisplay**: EMeleeDamage_DEPRECATED
- **m_mapScalingStats**:
- **m_heroStatsDisplay**:
  - **m_vecHealthHeaderStats**:
    - EMaxHealth
    - EBaseHealthRegen
  - **m_vecHealthStats**:
    - EBulletArmorDamageReduction
    - ETechArmorDamageReduction
    - EBulletShieldHealth
    - ETechShieldHealth
    - EBulletLifesteal
    - ETechLifesteal
    - EMaxMoveSpeed
    - ESprintSpeed
    - EStamina
    - EHealingOutput
  - **m_vecWeaponHeaderStats**:
    - EWeaponDPS
    - EBulletDamage
  - **m_vecWeaponStats**:
    - ELightMeleeDamage
    - EHeavyMeleeDamage
    - EFireRate
    - EClipSize
  - **m_vecMagicHeaderStats**:
    - ETechPower
  - **m_vecMagicStats**:
    - ETechCooldown
    - ETechRange
    - ETechDuration
- **m_mapStandardLevelUpUpgrades**:
  - **MODIFIER_VALUE_BASE_BULLET_DAMAGE_FROM_LEVEL**: 0.73
  - **MODIFIER_VALUE_BASE_MELEE_DAMAGE_FROM_LEVEL**: 3.4
  - **MODIFIER_VALUE_BASE_HEALTH_FROM_LEVEL**: 41.0
  - **MODIFIER_VALUE_TECH_DAMAGE_PERCENT**: 0.0
  - **MODIFIER_VALUE_BULLET_ARMOR_DAMAGE_RESIST**: 0.0
- **m_eAbilityResourceType**: EResourceType_None
- **m_ShopStatDisplay**:
  - **m_eWeaponStatsDisplay**:
    - **m_vecDisplayStats**:
      - EBulletDamage
      - EBaseWeaponDamageIncrease
      - ERoundsPerSecond
      - EFireRate
      - EClipSize
      - EClipSizeIncrease
      - EReloadTime
      - EReloadSpeed
      - EBulletSpeed
      - EBulletSpeedIncrease
      - EBulletLifesteal
    - **m_vecOtherDisplayStats**:
      - ELightMeleeDamage
      - EHeavyMeleeDamage
  - **m_eVitalityStatsDisplay**:
    - **m_vecDisplayStats**:
      - EMaxHealth
      - EBaseHealthRegen
      - EBulletArmorDamageReduction
      - ETechArmorDamageReduction
      - EBulletShieldHealth
      - ETechShieldHealth
      - ECritDamageReceivedScale
    - **m_vecOtherDisplayStats**:
      - EMaxMoveSpeed
      - ESprintSpeed
      - EStaminaCooldown
      - EStaminaRegenIncrease
      - EStamina
  - **m_eSpiritStatsDisplay**:
    - **m_vecDisplayStats**:
      - ETechCooldown
      - ETechDuration
      - ETechRange
      - ETechLifesteal
      - EMaxChargesIncrease
      - ETechCooldownBetweenChargeUses
- **_base**: hero_base
- **m_strSelectionImage**: panorama:"file://{images}/heroes/slork.psd"
- **m_strIconImageSmall**: panorama:"file://{images}/heroes/slork_sm.psd"
- **m_strMinimapImage**: panorama:"file://{images}/heroes/slork_mm.psd"
- **m_strIconHeroCard**: panorama:"file://{images}/heroes/slork_sm.psd"
- **m_strTopBarImage**: panorama:"file://{images}/hud/hero_portraits/slork_hud.psd"
- **m_strUIAnimGraph**: resource_name:"models/heroes_staging/slork/ui_slork.vanmgrph"
- **m_strDeathSound**: soundevent:"Player.DeathFemale"
- **m_hGameSoundEventScript**: resource_name:"soundevents/hero/slork.vsndevts"
- **m_hVOEventScript**: resource_name:"soundevents/vo/vo_hero_genericperson.vsndevts"
- **m_strRosterSelectedSound**: soundevent:"Slork.VO.HeroPick"
- **m_strRosterRemovedSound**: soundevent:"Slork.VO.HeroRemove"
- **m_strUIShopAnimGraph**: resource_name:"models/heroes_staging/slork/ui_shop_slork.vanmgrph"
- **m_strUIShoppingMap**: maps/ui/hero_shop/slork_shop.vmap

---

# Hero: hero_cadence

- **_class**: CitadelHeroData_t
- **m_bPlayerSelectable**: True
- **m_bDisabled**: True
- **m_bInDevelopment**: True
- **m_bNeedsTesting**: True
- **m_bAssignedPlayersOnly**: False
- **m_bBotSelectable**: False
- **m_bLimitedTesting**: False
- **m_nComplexity**: 2
- **m_nReadability**: 1
- **m_HeroID**: 54
- **m_strModelName**: resource_name:"models/heroes_staging/cadence/cadence.vmdl"
- **m_hDamageTakenParticle**: resource_name:"particles/generic/player_damage_screen.vpcf"
- **m_hGroundDamageTakenParticle**: resource_name:"particles/generic/player_ground_damage_screen.vpcf"
- **m_hDeathParticle**: resource_name:"particles/generic/player_death_screen.vpcf"
- **m_hLowHealthParticle**: resource_name:"particles/generic/player_low_health_screen.vpcf"
- **m_hRespawnParticle**: resource_name:"particles/generic/player_respawn_deploy.vpcf"
- **m_nModelSkin**: 0
- **m_mapStartingStats**:
  - **EMaxMoveSpeed**: 7
  - **ESprintSpeed**: 0
  - **ECrouchSpeed**: 4.75
  - **EMoveAcceleration**: 4
  - **ELightMeleeDamage**: 63
  - **EHeavyMeleeDamage**: 116
  - **EMaxHealth**: 650
  - **EWeaponPower**: 0
  - **EReloadSpeed**: 1
  - **EWeaponPowerScale**: 1
  - **EProcBuildUpRateScale**: 1
  - **EStamina**: 3
  - **EBaseHealthRegen**: 2.0
  - **EStaminaRegenPerSecond**: 0.2
  - **EAbilityResourceMax**: 0
  - **EAbilityResourceRegenPerSecond**: 0
  - **ECritDamageReceivedScale**: 1.0
  - **ETechDuration**: 1
  - **ETechRange**: 1
- **m_flCollisionRadius**: 20
- **m_flCollisionHeight**: 80
- **m_flStepHeight**: 32
- **m_mapBoundAbilities**:
  - **ESlot_Weapon_Primary**: citadel_weapon_cadence_set
  - **ESlot_Weapon_Melee**: citadel_ability_melee_cadence
  - **ESlot_Ability_Mantle**: citadel_ability_mantle
  - **ESlot_Ability_Jump**: citadel_ability_jump
  - **ESlot_Ability_Slide**: citadel_ability_slide
  - **ESlot_Ability_ZipLine**: citadel_ability_zip_line
  - **ESlot_Ability_ZipLineBoost**: citadel_ability_zipline_boost
  - **ESlot_Ability_Innate_1**: citadel_ability_dash
  - **ESlot_Ability_Innate_2**: citadel_ability_sprint
  - **ESlot_Ability_Innate_3**: citadel_ability_melee_parry
  - **ESlot_Signature_1**: cadence_ability_anthem
  - **ESlot_Signature_2**: cadence_ability_silencecontraptions
  - **ESlot_Signature_3**: cadence_ability_lullaby
  - **ESlot_Signature_4**: cadence_ability_crescendo
- **m_mapItemSlotInfo**:
  - **EItemSlotType_WeaponMod**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
  - **EItemSlotType_Armor**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
  - **EItemSlotType_Tech**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
- **m_mapPurchaseBonuses**:
  - **EItemSlotType_WeaponMod**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 6 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 2 | 10 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 3 | 14 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 4 | 18 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
  - **EItemSlotType_Armor**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 11 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 2 | 14 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 3 | 17 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 4 | 20 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
  - **EItemSlotType_Tech**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 4 | MODIFIER_VALUE_TECH_POWER |
    | 2 | 8 | MODIFIER_VALUE_TECH_POWER |
    | 3 | 12 | MODIFIER_VALUE_TECH_POWER |
    | 4 | 16 | MODIFIER_VALUE_TECH_POWER |
- **m_mapLevelInfo**:
  - **1**:
    - **m_unRequiredGold**: 0
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **2**:
    - **m_unRequiredGold**: 400
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
      - **EAbilityPoints**: 1
  - **3**:
    - **m_unRequiredGold**: 800
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **4**:
    - **m_unRequiredGold**: 1200
    - **m_bUseStandardUpgrade**: True
  - **5**:
    - **m_unRequiredGold**: 1500
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **6**:
    - **m_unRequiredGold**: 2200
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **7**:
    - **m_unRequiredGold**: 3000
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **8**:
    - **m_unRequiredGold**: 4500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **9**:
    - **m_unRequiredGold**: 6000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **10**:
    - **m_unRequiredGold**: 7500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **11**:
    - **m_unRequiredGold**: 9000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **12**:
    - **m_unRequiredGold**: 10500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **13**:
    - **m_unRequiredGold**: 12000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **14**:
    - **m_unRequiredGold**: 13000
    - **m_bUseStandardUpgrade**: True
  - **15**:
    - **m_unRequiredGold**: 14000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **16**:
    - **m_unRequiredGold**: 15000
    - **m_bUseStandardUpgrade**: True
  - **17**:
    - **m_unRequiredGold**: 16000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **18**:
    - **m_unRequiredGold**: 18000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **19**:
    - **m_unRequiredGold**: 20000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **20**:
    - **m_unRequiredGold**: 22000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **21**:
    - **m_unRequiredGold**: 24000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **22**:
    - **m_unRequiredGold**: 27000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **23**:
    - **m_unRequiredGold**: 30000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **24**:
    - **m_unRequiredGold**: 33000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **25**:
    - **m_unRequiredGold**: 36000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **26**:
    - **m_unRequiredGold**: 39000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **27**:
    - **m_unRequiredGold**: 42000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **28**:
    - **m_unRequiredGold**: 45000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **29**:
    - **m_unRequiredGold**: 48000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
- **m_hFootstepSounds**: sweetener_default
- **m_strFootstepSoundEventDefault**: soundevent:""
- **m_flStealthSpeedMetersPerSecond**: 4
- **m_flFootstepSoundTravelDistanceMeters**: 20
- **m_flStepSoundTime**: 0.3
- **m_vecAnimGraphDefaultValueOverrides**:
  | m_strParamName | m_strParamValue |
  | --- | --- |
  | e_SWITCH_4wayRoll_ON/OFF | 0 |
  | e_SWITCH_Recoil_ON/OFF | 0 |
  | e_SWITCH_ZiplinePhysicsSway_ON/OFF | 0 |
  | e_SWITCH_ShootStyle | 0 |
- **m_strLastHitSound**: soundevent:"LastHit.Default"
- **m_strLowHealthSound**: soundevent:"PlayerAlert.LowHealth"
- **m_colorUI**:
  - 255
  - 255
  - 255
- **m_colorGlowFriendly**:
  - 255
  - 239
  - 215
- **m_colorGlowEnemy**:
  - 255
  - 0
  - 0
- **m_colorGlowTeam1**:
  - 231
  - 182
  - 89
- **m_colorGlowTeam2**:
  - 91
  - 121
  - 230
- **m_vecAmbientParticleSettings**:
  | m_eAttachmentType | m_nCP |
  | --- | --- |
  | PATTACH_ABSORIGIN_FOLLOW | 0 |
  | PATTACH_POINT_FOLLOW | 1 |
- **m_heroStatsUI**:
  - **m_vecDisplayStats**:
    | m_eStatType | m_eStatCategory |
    | --- | --- |
    | EMaxHealth | ECitadelStat_Vitality |
    | EBaseHealthRegen | ECitadelStat_Vitality |
    | EBulletArmorDamageReduction | ECitadelStat_Vitality |
    | ETechArmorDamageReduction | ECitadelStat_Vitality |
    | ETechPower | ECitadelStat_Spirit |
    | EWeaponDPS | ECitadelStat_Weapon |
    | EBulletDamage | ECitadelStat_Weapon |
    | EClipSize | ECitadelStat_Weapon |
    | ERoundsPerSecond | ECitadelStat_Weapon |
    | ELightMeleeDamage | ECitadelStat_Weapon |
    | EHeavyMeleeDamage | ECitadelStat_Weapon |
    | EMaxMoveSpeed | ECitadelStat_Vitality |
    | ESprintSpeed | ECitadelStat_Vitality |
    | EStamina | ECitadelStat_Vitality |
  - **m_eWeaponStatDisplay**: EMeleeDamage_DEPRECATED
- **m_mapScalingStats**:
- **m_heroStatsDisplay**:
  - **m_vecHealthHeaderStats**:
    - EMaxHealth
    - EBaseHealthRegen
  - **m_vecHealthStats**:
    - EBulletArmorDamageReduction
    - ETechArmorDamageReduction
    - EBulletShieldHealth
    - ETechShieldHealth
    - EBulletLifesteal
    - ETechLifesteal
    - EMaxMoveSpeed
    - ESprintSpeed
    - EStamina
    - EHealingOutput
  - **m_vecWeaponHeaderStats**:
    - EWeaponDPS
    - EBulletDamage
  - **m_vecWeaponStats**:
    - ELightMeleeDamage
    - EHeavyMeleeDamage
    - EFireRate
    - EClipSize
  - **m_vecMagicHeaderStats**:
    - ETechPower
  - **m_vecMagicStats**:
    - ETechCooldown
    - ETechRange
    - ETechDuration
- **m_mapStandardLevelUpUpgrades**:
  - **MODIFIER_VALUE_BASE_BULLET_DAMAGE_FROM_LEVEL**: 0.0
  - **MODIFIER_VALUE_BASE_MELEE_DAMAGE_FROM_LEVEL**: 3.4
  - **MODIFIER_VALUE_BASE_HEALTH_FROM_LEVEL**: 41.0
  - **MODIFIER_VALUE_TECH_DAMAGE_PERCENT**: 0.0
  - **MODIFIER_VALUE_BULLET_ARMOR_DAMAGE_RESIST**: 0.0
- **m_eAbilityResourceType**: EResourceType_None
- **m_ShopStatDisplay**:
  - **m_eWeaponStatsDisplay**:
    - **m_vecDisplayStats**:
      - EBulletDamage
      - EBaseWeaponDamageIncrease
      - ERoundsPerSecond
      - EFireRate
      - EClipSize
      - EClipSizeIncrease
      - EReloadTime
      - EReloadSpeed
      - EBulletSpeed
      - EBulletSpeedIncrease
      - EBulletLifesteal
    - **m_vecOtherDisplayStats**:
      - ELightMeleeDamage
      - EHeavyMeleeDamage
  - **m_eVitalityStatsDisplay**:
    - **m_vecDisplayStats**:
      - EMaxHealth
      - EBaseHealthRegen
      - EBulletArmorDamageReduction
      - ETechArmorDamageReduction
      - EBulletShieldHealth
      - ETechShieldHealth
      - ECritDamageReceivedScale
    - **m_vecOtherDisplayStats**:
      - EMaxMoveSpeed
      - ESprintSpeed
      - EStaminaCooldown
      - EStaminaRegenIncrease
      - EStamina
  - **m_eSpiritStatsDisplay**:
    - **m_vecDisplayStats**:
      - ETechCooldown
      - ETechDuration
      - ETechRange
      - ETechLifesteal
      - EMaxChargesIncrease
      - ETechCooldownBetweenChargeUses
- **_base**: hero_base
- **m_strSelectionImage**: panorama:"file://{images}/heroes/cadence.psd"
- **m_strIconImageSmall**: panorama:"file://{images}/heroes/cadence_sm.psd"
- **m_strMinimapImage**: panorama:"file://{images}/heroes/cadence_mm.psd"
- **m_strUIAnimGraph**: resource_name:"models/heroes_staging/cadence/ui_cadence.vanmgrph"
- **m_strDeathSound**: soundevent:"Player.DeathFemale"
- **m_strTopBarImage**: panorama:"file://{images}/hud/hero_portraits/cadence_hud.psd"
- **m_hGameSoundEventScript**: resource_name:"soundevents/game_sounds_heroes/game_sounds_hero_cadence.vsndevts"
- **m_hVOEventScript**: resource_name:"soundevents/vo/vo_hero_cadence.vsndevts"
- **m_strIconHeroCard**: panorama:"file://{images}/heroes/cadence_sm.psd"
- **m_strUIShopAnimGraph**: resource_name:"models/heroes_staging/cadence/ui_shop_cadence.vanmgrph"

---

# Hero: hero_targetdummy

- **_class**: CitadelHeroData_t
- **m_bPlayerSelectable**: False
- **m_bDisabled**: True
- **m_bInDevelopment**: True
- **m_bNeedsTesting**: True
- **m_bAssignedPlayersOnly**: False
- **m_bBotSelectable**: False
- **m_bLimitedTesting**: False
- **m_nComplexity**: 2
- **m_nReadability**: 1
- **m_HeroID**: 55
- **m_strModelName**: resource_name:"models/heroes_staging/gen_man/gen_man.vmdl"
- **m_hDamageTakenParticle**: resource_name:"particles/generic/player_damage_screen.vpcf"
- **m_hGroundDamageTakenParticle**: resource_name:"particles/generic/player_ground_damage_screen.vpcf"
- **m_hDeathParticle**: resource_name:"particles/generic/player_death_screen.vpcf"
- **m_hLowHealthParticle**: resource_name:"particles/generic/player_low_health_screen.vpcf"
- **m_hRespawnParticle**: resource_name:"particles/generic/player_respawn_deploy.vpcf"
- **m_nModelSkin**: 0
- **m_mapStartingStats**:
  - **EMaxMoveSpeed**: 7
  - **ESprintSpeed**: 0
  - **ECrouchSpeed**: 4.75
  - **EMoveAcceleration**: 4
  - **ELightMeleeDamage**: 63
  - **EHeavyMeleeDamage**: 116
  - **EMaxHealth**: 3000
  - **EWeaponPower**: 0
  - **EReloadSpeed**: 1
  - **EWeaponPowerScale**: 1
  - **EProcBuildUpRateScale**: 1
  - **EStamina**: 3
  - **EBaseHealthRegen**: 2.0
  - **EStaminaRegenPerSecond**: 0.2
  - **EAbilityResourceMax**: 0
  - **EAbilityResourceRegenPerSecond**: 0
  - **ECritDamageReceivedScale**: 1.0
  - **ETechDuration**: 1
  - **ETechRange**: 1
- **m_flCollisionRadius**: 20
- **m_flCollisionHeight**: 80
- **m_flStepHeight**: 32
- **m_mapBoundAbilities**:
  - **ESlot_Weapon_Primary**: citadel_weapon_targetdummy_set
  - **ESlot_Weapon_Melee**: citadel_ability_melee_targetdummy
  - **ESlot_Ability_Mantle**: citadel_ability_mantle
  - **ESlot_Ability_Jump**: citadel_ability_jump
  - **ESlot_Ability_Slide**: citadel_ability_slide
  - **ESlot_Ability_ZipLine**: citadel_ability_zip_line
  - **ESlot_Ability_ZipLineBoost**: citadel_ability_zipline_boost
  - **ESlot_Ability_Innate_1**: citadel_ability_dash
  - **ESlot_Ability_Innate_2**: citadel_ability_sprint
  - **ESlot_Ability_Innate_3**: citadel_ability_melee_parry
  - **ESlot_Signature_1**: targetdummy_ability_1
  - **ESlot_Signature_2**: targetdummy_ability_2
  - **ESlot_Signature_3**: targetdummy_ability_3
  - **ESlot_Signature_4**: targetdummy_ability_4
- **m_mapItemSlotInfo**:
  - **EItemSlotType_WeaponMod**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
  - **EItemSlotType_Armor**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
  - **EItemSlotType_Tech**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
- **m_mapPurchaseBonuses**:
  - **EItemSlotType_WeaponMod**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 6 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 2 | 10 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 3 | 14 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 4 | 18 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
  - **EItemSlotType_Armor**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 11 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 2 | 14 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 3 | 17 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 4 | 20 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
  - **EItemSlotType_Tech**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 4 | MODIFIER_VALUE_TECH_POWER |
    | 2 | 8 | MODIFIER_VALUE_TECH_POWER |
    | 3 | 12 | MODIFIER_VALUE_TECH_POWER |
    | 4 | 16 | MODIFIER_VALUE_TECH_POWER |
- **m_mapLevelInfo**:
  - **1**:
    - **m_unRequiredGold**: 0
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **2**:
    - **m_unRequiredGold**: 400
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
      - **EAbilityPoints**: 1
  - **3**:
    - **m_unRequiredGold**: 800
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **4**:
    - **m_unRequiredGold**: 1200
    - **m_bUseStandardUpgrade**: True
  - **5**:
    - **m_unRequiredGold**: 1500
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **6**:
    - **m_unRequiredGold**: 2200
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **7**:
    - **m_unRequiredGold**: 3000
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **8**:
    - **m_unRequiredGold**: 4500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **9**:
    - **m_unRequiredGold**: 6000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **10**:
    - **m_unRequiredGold**: 7500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **11**:
    - **m_unRequiredGold**: 9000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **12**:
    - **m_unRequiredGold**: 10500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **13**:
    - **m_unRequiredGold**: 12000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **14**:
    - **m_unRequiredGold**: 13000
    - **m_bUseStandardUpgrade**: True
  - **15**:
    - **m_unRequiredGold**: 14000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **16**:
    - **m_unRequiredGold**: 15000
    - **m_bUseStandardUpgrade**: True
  - **17**:
    - **m_unRequiredGold**: 16000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **18**:
    - **m_unRequiredGold**: 18000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **19**:
    - **m_unRequiredGold**: 20000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **20**:
    - **m_unRequiredGold**: 22000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **21**:
    - **m_unRequiredGold**: 24000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **22**:
    - **m_unRequiredGold**: 27000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **23**:
    - **m_unRequiredGold**: 30000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **24**:
    - **m_unRequiredGold**: 33000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **25**:
    - **m_unRequiredGold**: 36000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **26**:
    - **m_unRequiredGold**: 39000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **27**:
    - **m_unRequiredGold**: 42000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **28**:
    - **m_unRequiredGold**: 45000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **29**:
    - **m_unRequiredGold**: 48000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
- **m_hFootstepSounds**: sweetener_default
- **m_strFootstepSoundEventDefault**: soundevent:"Hero.Default.Footstep"
- **m_flStealthSpeedMetersPerSecond**: 4
- **m_flFootstepSoundTravelDistanceMeters**: 20
- **m_flStepSoundTime**: 0.3
- **m_vecAnimGraphDefaultValueOverrides**:
  | m_strParamName | m_strParamValue |
  | --- | --- |
  | e_SWITCH_4wayRoll_ON/OFF | 0 |
  | e_SWITCH_Recoil_ON/OFF | 0 |
  | e_SWITCH_ZiplinePhysicsSway_ON/OFF | 0 |
  | e_SWITCH_ShootStyle | 0 |
- **m_strLastHitSound**: soundevent:"LastHit.Default"
- **m_strLowHealthSound**: soundevent:"PlayerAlert.LowHealth"
- **m_colorUI**:
  - 255
  - 255
  - 255
- **m_colorGlowFriendly**:
  - 255
  - 239
  - 215
- **m_colorGlowEnemy**:
  - 255
  - 0
  - 0
- **m_colorGlowTeam1**:
  - 231
  - 182
  - 89
- **m_colorGlowTeam2**:
  - 91
  - 121
  - 230
- **m_vecAmbientParticleSettings**:
  | m_eAttachmentType | m_nCP |
  | --- | --- |
  | PATTACH_ABSORIGIN_FOLLOW | 0 |
  | PATTACH_POINT_FOLLOW | 1 |
- **m_heroStatsUI**:
  - **m_vecDisplayStats**:
    | m_eStatType | m_eStatCategory |
    | --- | --- |
    | EMaxHealth | ECitadelStat_Vitality |
    | EBaseHealthRegen | ECitadelStat_Vitality |
    | EBulletArmorDamageReduction | ECitadelStat_Vitality |
    | ETechArmorDamageReduction | ECitadelStat_Vitality |
    | ETechPower | ECitadelStat_Spirit |
    | EWeaponDPS | ECitadelStat_Weapon |
    | EBulletDamage | ECitadelStat_Weapon |
    | EClipSize | ECitadelStat_Weapon |
    | ERoundsPerSecond | ECitadelStat_Weapon |
    | ELightMeleeDamage | ECitadelStat_Weapon |
    | EHeavyMeleeDamage | ECitadelStat_Weapon |
    | EMaxMoveSpeed | ECitadelStat_Vitality |
    | ESprintSpeed | ECitadelStat_Vitality |
    | EStamina | ECitadelStat_Vitality |
  - **m_eWeaponStatDisplay**: EMeleeDamage_DEPRECATED
- **m_mapScalingStats**:
- **m_heroStatsDisplay**:
  - **m_vecHealthHeaderStats**:
    - EMaxHealth
    - EBaseHealthRegen
  - **m_vecHealthStats**:
    - EBulletArmorDamageReduction
    - ETechArmorDamageReduction
    - EBulletShieldHealth
    - ETechShieldHealth
    - EBulletLifesteal
    - ETechLifesteal
    - EMaxMoveSpeed
    - ESprintSpeed
    - EStamina
    - EHealingOutput
  - **m_vecWeaponHeaderStats**:
    - EWeaponDPS
    - EBulletDamage
  - **m_vecWeaponStats**:
    - ELightMeleeDamage
    - EHeavyMeleeDamage
    - EFireRate
    - EClipSize
  - **m_vecMagicHeaderStats**:
    - ETechPower
  - **m_vecMagicStats**:
    - ETechCooldown
    - ETechRange
    - ETechDuration
- **m_mapStandardLevelUpUpgrades**:
  - **MODIFIER_VALUE_BASE_BULLET_DAMAGE_FROM_LEVEL**: 0.0
  - **MODIFIER_VALUE_BASE_MELEE_DAMAGE_FROM_LEVEL**: 3.4
  - **MODIFIER_VALUE_BASE_HEALTH_FROM_LEVEL**: 41.0
  - **MODIFIER_VALUE_TECH_DAMAGE_PERCENT**: 0.0
  - **MODIFIER_VALUE_BULLET_ARMOR_DAMAGE_RESIST**: 0.0
- **m_eAbilityResourceType**: EResourceType_None
- **m_ShopStatDisplay**:
  - **m_eWeaponStatsDisplay**:
    - **m_vecDisplayStats**:
      - EBulletDamage
      - EBaseWeaponDamageIncrease
      - ERoundsPerSecond
      - EFireRate
      - EClipSize
      - EClipSizeIncrease
      - EReloadTime
      - EReloadSpeed
      - EBulletSpeed
      - EBulletSpeedIncrease
      - EBulletLifesteal
    - **m_vecOtherDisplayStats**:
      - ELightMeleeDamage
      - EHeavyMeleeDamage
  - **m_eVitalityStatsDisplay**:
    - **m_vecDisplayStats**:
      - EMaxHealth
      - EBaseHealthRegen
      - EBulletArmorDamageReduction
      - ETechArmorDamageReduction
      - EBulletShieldHealth
      - ETechShieldHealth
      - ECritDamageReceivedScale
    - **m_vecOtherDisplayStats**:
      - EMaxMoveSpeed
      - ESprintSpeed
      - EStaminaCooldown
      - EStaminaRegenIncrease
      - EStamina
  - **m_eSpiritStatsDisplay**:
    - **m_vecDisplayStats**:
      - ETechCooldown
      - ETechDuration
      - ETechRange
      - ETechLifesteal
      - EMaxChargesIncrease
      - ETechCooldownBetweenChargeUses
- **_base**: hero_base
- **m_strSelectionImage**: panorama:"file://{images}/heroes/targetdummy.psd"
- **m_strIconImageSmall**: panorama:"file://{images}/heroes/targetdummy_sm.psd"
- **m_strMinimapImage**: panorama:"file://{images}/heroes/targetdummy_mm.psd"
- **m_strDeathSound**: soundevent:"Player.DeathFemale"
- **m_hGameSoundEventScript**: resource_name:"soundevents/game_sounds_heroes/game_sounds_hero_targetdummy.vsndevts"
- **m_hVOEventScript**: resource_name:"soundevents/vo/vo_hero_targetdummy.vsndevts"
- **m_strIconHeroCard**: panorama:"file://{images}/heroes/targetdummy_sm.psd"
- **m_strTopBarVertical**: panorama:"file://{images}/heroes/generic_vertical.psd"

---

# Hero: hero_bomber

- **_class**: CitadelHeroData_t
- **m_bPlayerSelectable**: True
- **m_bDisabled**: True
- **m_bInDevelopment**: True
- **m_bNeedsTesting**: False
- **m_bAssignedPlayersOnly**: False
- **m_bBotSelectable**: False
- **m_bLimitedTesting**: False
- **m_nComplexity**: 1
- **m_nReadability**: 4
- **m_HeroID**: 56
- **m_strModelName**: resource_name:"models/heroes_staging/gen_man/gen_man.vmdl"
- **m_hDamageTakenParticle**: resource_name:"particles/generic/player_damage_screen.vpcf"
- **m_hGroundDamageTakenParticle**: resource_name:"particles/generic/player_ground_damage_screen.vpcf"
- **m_hDeathParticle**: resource_name:"particles/generic/player_death_screen.vpcf"
- **m_hLowHealthParticle**: resource_name:"particles/generic/player_low_health_screen.vpcf"
- **m_hRespawnParticle**: resource_name:"particles/generic/player_respawn_deploy.vpcf"
- **m_nModelSkin**: 0
- **m_mapStartingStats**:
  - **EMaxMoveSpeed**: 7
  - **ESprintSpeed**: 0
  - **ECrouchSpeed**: 4.75
  - **EMoveAcceleration**: 4
  - **ELightMeleeDamage**: 63
  - **EHeavyMeleeDamage**: 116
  - **EMaxHealth**: 550
  - **EWeaponPower**: 0
  - **EReloadSpeed**: 1
  - **EWeaponPowerScale**: 1
  - **EProcBuildUpRateScale**: 1
  - **EStamina**: 3
  - **EBaseHealthRegen**: 2.0
  - **EStaminaRegenPerSecond**: 0.2
  - **EAbilityResourceMax**: 0
  - **EAbilityResourceRegenPerSecond**: 0
  - **ECritDamageReceivedScale**: 1.0
  - **ETechDuration**: 1
  - **ETechRange**: 1
- **m_flCollisionRadius**: 20
- **m_flCollisionHeight**: 80
- **m_flStepHeight**: 32
- **m_mapBoundAbilities**:
  - **ESlot_Weapon_Primary**: citadel_weapon_bomber_set
  - **ESlot_Weapon_Melee**: ability_melee_bomber
  - **ESlot_Ability_Mantle**: citadel_ability_mantle
  - **ESlot_Ability_Jump**: citadel_ability_jump
  - **ESlot_Ability_Slide**: citadel_ability_slide
  - **ESlot_Ability_ZipLine**: citadel_ability_zip_line
  - **ESlot_Ability_ZipLineBoost**: citadel_ability_zipline_boost
  - **ESlot_Ability_Innate_1**: citadel_ability_dash
  - **ESlot_Ability_Innate_2**: citadel_ability_sprint
  - **ESlot_Ability_Innate_3**: citadel_ability_melee_parry
  - **ESlot_Signature_1**: ability_charged_bomb
  - **ESlot_Signature_2**: ability_bomber_ability02
  - **ESlot_Signature_3**: ability_bomber_ability03
  - **ESlot_Signature_4**: ability_bomber_ult
- **m_mapItemSlotInfo**:
  - **EItemSlotType_WeaponMod**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
  - **EItemSlotType_Armor**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
  - **EItemSlotType_Tech**:
    - **m_arMaxPurchasesForTier**:
      - 6
      - 6
      - 6
- **m_mapPurchaseBonuses**:
  - **EItemSlotType_WeaponMod**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 6 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 2 | 10 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 3 | 14 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
    | 4 | 18 | MODIFIER_VALUE_BASEATTACK_DAMAGE_PERCENT |
  - **EItemSlotType_Armor**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 11 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 2 | 14 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 3 | 17 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
    | 4 | 20 | MODIFIER_VALUE_BASE_HEALTH_PERCENT |
  - **EItemSlotType_Tech**:
    | m_nTier | m_strValue | m_ValueType |
    | --- | --- | --- |
    | 1 | 4 | MODIFIER_VALUE_TECH_POWER |
    | 2 | 8 | MODIFIER_VALUE_TECH_POWER |
    | 3 | 12 | MODIFIER_VALUE_TECH_POWER |
    | 4 | 16 | MODIFIER_VALUE_TECH_POWER |
- **m_mapLevelInfo**:
  - **1**:
    - **m_unRequiredGold**: 0
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **2**:
    - **m_unRequiredGold**: 400
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
      - **EAbilityPoints**: 1
  - **3**:
    - **m_unRequiredGold**: 800
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **4**:
    - **m_unRequiredGold**: 1200
    - **m_bUseStandardUpgrade**: True
  - **5**:
    - **m_unRequiredGold**: 1500
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **6**:
    - **m_unRequiredGold**: 2200
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **7**:
    - **m_unRequiredGold**: 3000
    - **m_mapBonusCurrencies**:
      - **EAbilityUnlocks**: 1
  - **8**:
    - **m_unRequiredGold**: 4500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **9**:
    - **m_unRequiredGold**: 6000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **10**:
    - **m_unRequiredGold**: 7500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **11**:
    - **m_unRequiredGold**: 9000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **12**:
    - **m_unRequiredGold**: 10500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **13**:
    - **m_unRequiredGold**: 12000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **14**:
    - **m_unRequiredGold**: 13000
    - **m_bUseStandardUpgrade**: True
  - **15**:
    - **m_unRequiredGold**: 14000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **16**:
    - **m_unRequiredGold**: 15000
    - **m_bUseStandardUpgrade**: True
  - **17**:
    - **m_unRequiredGold**: 16000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **18**:
    - **m_unRequiredGold**: 18000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **19**:
    - **m_unRequiredGold**: 20000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **20**:
    - **m_unRequiredGold**: 22000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **21**:
    - **m_unRequiredGold**: 24000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **22**:
    - **m_unRequiredGold**: 27000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **23**:
    - **m_unRequiredGold**: 30000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **24**:
    - **m_unRequiredGold**: 33000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **25**:
    - **m_unRequiredGold**: 36000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **26**:
    - **m_unRequiredGold**: 39000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **27**:
    - **m_unRequiredGold**: 42000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **28**:
    - **m_unRequiredGold**: 45000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **29**:
    - **m_unRequiredGold**: 48000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
- **m_hFootstepSounds**: sweetener_default
- **m_strFootstepSoundEventDefault**: soundevent:"Hero.Default.Footstep"
- **m_flStealthSpeedMetersPerSecond**: 4
- **m_flFootstepSoundTravelDistanceMeters**: 20
- **m_flStepSoundTime**: 0.325
- **m_vecAnimGraphDefaultValueOverrides**:
  | m_strParamName | m_strParamValue |
  | --- | --- |
  | e_SWITCH_4wayRoll_ON/OFF | 0 |
  | e_SWITCH_Recoil_ON/OFF | 0 |
  | e_SWITCH_ZiplinePhysicsSway_ON/OFF | 0 |
  | e_SWITCH_ShootStyle | 0 |
- **m_strLastHitSound**: soundevent:"LastHit.Default"
- **m_strLowHealthSound**: soundevent:"PlayerAlert.LowHealth"
- **m_colorUI**:
  - 98
  - 15
  - 214
- **m_colorGlowFriendly**:
  - 255
  - 239
  - 215
- **m_colorGlowEnemy**:
  - 255
  - 0
  - 0
- **m_colorGlowTeam1**:
  - 231
  - 182
  - 89
- **m_colorGlowTeam2**:
  - 91
  - 121
  - 230
- **m_vecAmbientParticleSettings**:
  | m_eAttachmentType | m_nCP |
  | --- | --- |
  | PATTACH_ABSORIGIN_FOLLOW | 0 |
  | PATTACH_POINT_FOLLOW | 1 |
- **m_heroStatsUI**:
  - **m_vecDisplayStats**:
    | m_eStatType | m_eStatCategory |
    | --- | --- |
    | EMaxHealth | ECitadelStat_Vitality |
    | EBaseHealthRegen | ECitadelStat_Vitality |
    | EBulletArmorDamageReduction | ECitadelStat_Vitality |
    | ETechArmorDamageReduction | ECitadelStat_Vitality |
    | ETechPower | ECitadelStat_Spirit |
    | EWeaponDPS | ECitadelStat_Weapon |
    | EBulletDamage | ECitadelStat_Weapon |
    | EClipSize | ECitadelStat_Weapon |
    | ERoundsPerSecond | ECitadelStat_Weapon |
    | ELightMeleeDamage | ECitadelStat_Weapon |
    | EHeavyMeleeDamage | ECitadelStat_Weapon |
    | EMaxMoveSpeed | ECitadelStat_Vitality |
    | ESprintSpeed | ECitadelStat_Vitality |
    | EStamina | ECitadelStat_Vitality |
  - **m_eWeaponStatDisplay**: EMeleeDamage_DEPRECATED
- **m_mapScalingStats**:
- **m_heroStatsDisplay**:
  - **m_vecHealthHeaderStats**:
    - EMaxHealth
    - EBaseHealthRegen
  - **m_vecHealthStats**:
    - EBulletArmorDamageReduction
    - ETechArmorDamageReduction
    - EBulletShieldHealth
    - ETechShieldHealth
    - EBulletLifesteal
    - ETechLifesteal
    - EMaxMoveSpeed
    - ESprintSpeed
    - EStamina
    - EHealingOutput
  - **m_vecWeaponHeaderStats**:
    - EWeaponDPS
    - EBulletDamage
  - **m_vecWeaponStats**:
    - ELightMeleeDamage
    - EHeavyMeleeDamage
    - EFireRate
    - EClipSize
  - **m_vecMagicHeaderStats**:
    - ETechPower
  - **m_vecMagicStats**:
    - ETechCooldown
    - ETechRange
    - ETechDuration
- **m_mapStandardLevelUpUpgrades**:
  - **MODIFIER_VALUE_BASE_BULLET_DAMAGE_FROM_LEVEL**: 0.159
  - **MODIFIER_VALUE_BASE_MELEE_DAMAGE_FROM_LEVEL**: 3.4
  - **MODIFIER_VALUE_BASE_HEALTH_FROM_LEVEL**: 41.0
  - **MODIFIER_VALUE_TECH_DAMAGE_PERCENT**: 0.0
  - **MODIFIER_VALUE_BULLET_ARMOR_DAMAGE_RESIST**: 0.0
- **m_eAbilityResourceType**: EResourceType_None
- **m_ShopStatDisplay**:
  - **m_eWeaponStatsDisplay**:
    - **m_vecDisplayStats**:
      - EBulletDamage
      - EBaseWeaponDamageIncrease
      - ERoundsPerSecond
      - EFireRate
      - EClipSize
      - EClipSizeIncrease
      - EReloadTime
      - EReloadSpeed
      - EBulletSpeed
      - EBulletSpeedIncrease
      - EBulletLifesteal
    - **m_vecOtherDisplayStats**:
      - ELightMeleeDamage
      - EHeavyMeleeDamage
  - **m_eVitalityStatsDisplay**:
    - **m_vecDisplayStats**:
      - EMaxHealth
      - EBaseHealthRegen
      - EBulletArmorDamageReduction
      - ETechArmorDamageReduction
      - EBulletShieldHealth
      - ETechShieldHealth
      - ECritDamageReceivedScale
    - **m_vecOtherDisplayStats**:
      - EMaxMoveSpeed
      - ESprintSpeed
      - EStaminaCooldown
      - EStaminaRegenIncrease
      - EStamina
  - **m_eSpiritStatsDisplay**:
    - **m_vecDisplayStats**:
      - ETechCooldown
      - ETechDuration
      - ETechRange
      - ETechLifesteal
      - EMaxChargesIncrease
      - ETechCooldownBetweenChargeUses
- **_base**: hero_base
- **m_strDeathSound**: soundevent:"Nano.Death"

---

## NPCs

# NPC: weapon_base

- **_not_pickable**: 2
- **m_WeaponInfo**:
  - **m_Spread**: 0.5
  - **m_StandingSpread**: 1.5
  - **m_flScatterYawScale**: 1
  - **m_flShootingUpSpreadPenalty**: 0
  - **m_flZoomMoveSpeedPercent**: 0.7
  - **m_flShootMoveSpeedPercent**: 0.7
  - **m_flHorizontalPunch**: 0
  - **m_flVerticalPunch**: 0
  - **m_flRecoilRecoverySpeed**: 10.0
  - **m_VerticallRecoil**:
    - **m_Range**:
      - -0.2
      - 0.2
    - **m_flBurstSlope**: 0.0
    - **m_flBurstExponent**: 0.0
    - **m_flBurstConstant**: 0.0
  - **m_HorizontalRecoil**:
    - **m_Range**:
      - -0.1
      - 0.1
    - **m_flBurstExponent**: 0.0
  - **m_flRecoilSpeed**: 1
  - **m_flZoomFOV**: 40.0
  - **m_flDamageFalloffStartRange**: 2000.0
  - **m_flDamageFalloffEndRange**: 3000.0
  - **m_flRange**: 3500.0
  - **m_flBulletLifetime**: 2
  - **m_flDamageFalloffEndScale**: 0.3
  - **m_flDamageFalloffBias**: 0.5
  - **m_iBullets**: 1
  - **m_flCycleTime**: 0.3
  - **m_reloadDuration**: 1.5
  - **m_iClipSize**: 10
  - **m_iBurstShotCount**: 1
  - **m_flBurstShotCooldown**: 0
  - **m_flBulletGravityScale**: 0.8
  - **m_flBulletRadius**: 3
  - **m_flBulletDrag**: 1
  - **m_flBulletDragBias**: 0.5
  - **m_flBulletReflectScale**: 0
  - **m_flBulletReflectAmount**: 1
  - **m_flBulletInheritShooterVelocityScale**: 0
  - **m_szBulletTravelTracerParticle**: resource_name:"particles/weapon_fx/default_tracer.vpcf"
  - **m_szMuzzleFlashEffectName**: resource_name:"particles/dev/bullet_debug_muzzle_flash.vpcf"
  - **m_strShootSound**: soundevent:"Pistol.Fire"
  - **m_strBulletWhizSound**: soundevent:"Base.Bullet.Whizby"
  - **m_BulletSpeedCurve**:
    - **m_spline**:
      | x | y | m_flSlopeIncoming | m_flSlopeOutgoing |
      | --- | --- | --- | --- |
      | 0.0 | 18000.0 | 0.0 | 0.0 |
      | 100.0 | 18000.0 | 0.0 | 0.0 |
    - **m_tangents**:
      | m_nIncomingTangent | m_nOutgoingTangent |
      | --- | --- |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
    - **m_vDomainMins**:
      - 0.0
      - 1.0
    - **m_vDomainMaxs**:
      - 100.0
      - 18000.0
  - **m_mapImpactEffects**:
    - **default**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Default.BulletImpact"
    - **flesh**:
      - **m_strDecal**: 
      - **m_strParticle**: resource_name:"particles/blood_impact/blood_impact_red_01.vpcf"
      - **m_strSound**: soundevent:"Flesh.BulletImpact"
    - **concrete**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Concrete.BulletImpact"
    - **solidmetal**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"SolidMetal.BulletImpact"
    - **portals**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Player.HitInvuln"
  - **m_flCritBonusStart**: 1.15
  - **m_flCritBonusEnd**: 1.35
  - **m_flCritBonusStartRange**: 500.0
  - **m_flCritBonusEndRange**: 1500.0
  - **m_flCritBonusAgainstNPCs**: 0.25
  - **m_flShootSpreadPenaltyPerShot**: 0.0
  - **m_flShootSpreadPenaltyDecayDelay**: 0.0
  - **m_flShootSpreadPenaltyDecay**: 2.0
  - **m_flRecoilShotIndexRecoveryTimeFactor**: 0.25
  - **m_bCanZoom**: True
  - **m_strWeaponImpactEffect**: resource_name:"particles/weapon_fx/default_tracer_impact.vpcf"
  - **m_flReloadMoveSpeed**: 236.22
  - **m_strLocalPlayerBulletImpactSound**: soundevent:"Player.Bullet.Impact.Default"

---

# NPC: trooper_base

- **m_WeaponInfo**:
  - **m_Spread**: 0.5
  - **m_StandingSpread**: 1.5
  - **m_flScatterYawScale**: 1
  - **m_flShootingUpSpreadPenalty**: 2
  - **m_flZoomMoveSpeedPercent**: 0.7
  - **m_flShootMoveSpeedPercent**: 0.7
  - **m_flHorizontalPunch**: 0
  - **m_flVerticalPunch**: 0
  - **m_flRecoilRecoverySpeed**: 10.0
  - **m_VerticallRecoil**:
    - **m_Range**:
      - -0.2
      - 0.2
    - **m_flBurstSlope**: 0.0
    - **m_flBurstExponent**: 0.0
    - **m_flBurstConstant**: 0.0
  - **m_HorizontalRecoil**:
    - **m_Range**:
      - -0.1
      - 0.1
    - **m_flBurstExponent**: 0.0
  - **m_flRecoilSpeed**: 1
  - **m_flZoomFOV**: 40.0
  - **m_flDamageFalloffStartRange**: 600
  - **m_flDamageFalloffEndRange**: 1000
  - **m_flRange**: 1000
  - **m_flBulletLifetime**: 2
  - **m_flDamageFalloffEndScale**: 0.3
  - **m_flDamageFalloffBias**: 0.5
  - **m_iBullets**: 1
  - **m_flCycleTime**: 1.03
  - **m_reloadDuration**: 1.8
  - **m_iClipSize**: -1
  - **m_iBurstShotCount**: 1
  - **m_flBurstShotCooldown**: 0
  - **m_flBulletGravityScale**: 0.0
  - **m_flBulletRadius**: 3
  - **m_flBulletDrag**: 1
  - **m_flBulletDragBias**: 0.5
  - **m_flBulletReflectScale**: 0
  - **m_flBulletReflectAmount**: 1
  - **m_flBulletInheritShooterVelocityScale**: 0
  - **m_szBulletTravelTracerParticle**: resource_name:"particles/weapon_fx/trooper/trooper_bullet_travel.vpcf"
  - **m_szMuzzleFlashEffectName**: resource_name:"particles/dev/bullet_debug_muzzle_flash.vpcf"
  - **m_strShootSound**: soundevent:"TrooperRifle.Fire"
  - **m_strBulletWhizSound**: soundevent:"Base.Bullet.Whizby"
  - **m_BulletSpeedCurve**:
    - **m_spline**:
      | x | y | m_flSlopeIncoming | m_flSlopeOutgoing |
      | --- | --- | --- | --- |
      | 0.0 | 12000.0 | 0.0 | 0.0 |
      | 100.0 | 12000.0 | 0.0 | 0.0 |
    - **m_tangents**:
      | m_nIncomingTangent | m_nOutgoingTangent |
      | --- | --- |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
    - **m_vDomainMins**:
      - 0.0
      - 1.0
    - **m_vDomainMaxs**:
      - 100.0
      - 12000.0
  - **m_mapImpactEffects**:
    - **default**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Default.BulletImpact"
    - **flesh**:
      - **m_strDecal**: 
      - **m_strParticle**: resource_name:"particles/blood_impact/blood_impact_red_01.vpcf"
      - **m_strSound**: soundevent:"Flesh.BulletImpact"
    - **concrete**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Concrete.BulletImpact"
    - **solidmetal**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"SolidMetal.BulletImpact"
    - **portals**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Player.HitInvuln"
  - **m_flCritBonusStart**: 1.15
  - **m_flCritBonusEnd**: 1.35
  - **m_flCritBonusStartRange**: 500.0
  - **m_flCritBonusEndRange**: 1500.0
  - **m_flCritBonusAgainstNPCs**: 0.25
  - **m_flShootSpreadPenaltyPerShot**: 0.0
  - **m_flShootSpreadPenaltyDecayDelay**: 0.0
  - **m_flShootSpreadPenaltyDecay**: 2.0
  - **m_flRecoilShotIndexRecoveryTimeFactor**: 0.25
  - **m_bCanZoom**: True
  - **m_strWeaponImpactEffect**: resource_name:"particles/weapon_fx/default_tracer_impact.vpcf"
  - **m_flReloadMoveSpeed**: 236.22
  - **m_strLocalPlayerBulletImpactSound**: soundevent:"Player.Bullet.Impact.Trooper"
  - **m_NpcAimingSpread**:
    - 0.2
    - 0.8
  - **m_flBulletDamage**: 36
- **_not_pickable**: 2
- **_base**: weapon_base
- **_class**: npc_trooper
- **m_sModelName**: resource_name:"models/npc/trooper/trooper_humanoid.vmdl"
- **m_nMaxHealth**: 300
- **m_flSightRangePlayers**: 700.0
- **m_flSightRangeNPCs**: 1600.0
- **m_hFootstepSounds**: trooper
- **m_flTrooperDamageResistPct**: 25.0
- **m_flT1BossDamageResistPct**: 35.0
- **m_flT2BossDamageResistPct**: 20.0
- **m_flShieldDamageResistPct**: 80.0
- **m_flNearDeathDuration**: 1.0
- **m_flWalkSpeed**: 240
- **m_flRunSpeed**: 433
- **m_flAcceleration**: 200
- **m_flMeleeDamage**: 25.0
- **m_flMeleeAttemptRange**: 100
- **m_flMeleeHitRange**: 100
- **m_flMeleeDuration**: 1.0
- **m_flAttackT1BossMaxRange**: 540
- **m_flAttackTrooperMaxRange**: 700
- **m_BossAttackParticle**: resource_name:"particles/weapon_fx/trooper/trooper_bullet_bonus_dmg.vpcf"
- **m_sDefaultMaterialGroupName**: Friendly
- **m_sEnemyMaterialGroupName**: Enemy
- **m_flMeleeChargeRange**: 0
- **m_flHealthBarOffset**: 76.0
- **m_flHealthBarOffsetDucking**: 40
- **m_DeathParticle**: resource_name:"particles/trooper/trooper_death_sn.vpcf"
- **m_DeathSound**: soundevent:"Trooper.Death"
- **m_MeleeHitSound**: soundevent:"Trooper.Melee.Damage.Hit"
- **m_MeleeHitPlayerSound**: soundevent:"Player.Damage.Melee.Trooper.Impact"
- **m_HealthBarParticle**: resource_name:"particles/npc/npc_healthbar.vpcf"
- **m_sHealthBarAttachment**: head_fx
- **m_HealthBarColorFriend**:
  - 255
  - 239
  - 215
- **m_HealthBarColorEnemy**:
  - 230
  - 25
  - 25
- **m_HealthBarColorTeam1**:
  - 231
  - 182
  - 89
- **m_HealthBarColorTeam2**:
  - 91
  - 121
  - 230
- **m_HealthBarColorTeamNeutral**:
  - 0
  - 125
  - 125
- **m_MeleeSwingParticle**: resource_name:"particles/abilities/melee_swing.vpcf"
- **m_MeleeActivateParticle**: resource_name:"particles/abilities/melee/melee_activate.vpcf"
- **m_MeleeAnimName**: b_melee
- **m_LastHitParticle**: resource_name:"particles/generic/last_hit.vpcf"
- **m_strLastHitSound**: soundevent:"LastHit.Default"
- **m_bPlayLastHitSound**: True
- **m_NearDeathModifier**:
  - **subclass**:
    - **_class**: modifier_near_death_fx
    - **_my_subclass_name**: modifier_near_death_fx
    - **m_EnemyNearDeathParticle**: resource_name:"particles/status_fx/status_fx_last_hit.vpcf"
    - **m_FriendlyNearDeathParticle**: resource_name:"particles/status_fx/status_fx_last_hit_friend.vpcf"
    - **m_sSelfDestructStart**: soundevent:"Trooper.SelfDestruct_Start"
    - **m_sSelfDestructEnd**: soundevent:"Trooper.SelfDestruct_Exp"
- **m_TargetingLaserParticle**: resource_name:"particles/weapon_fx/trooper_laser_target.vpcf"
- **m_TargetingEyeFlashParticle**: resource_name:"particles/enemy_targeting_indicator.vpcf"
- **m_sCelebrationSound**: soundevent:"Trooper.Objective.Win.Cheer"
- **m_flBarrackGuardianDamageResistPct**: 67.5
- **m_sTeam1MaterialGroupName**: Amber
- **m_sTeam2MaterialGroupName**: Sapphire
- **m_flT1BossDPS**: 36.0
- **m_flT2BossDPS**: 80.0
- **m_flT3BossDPS**: 80.0
- **m_flGeneratorBossDPS**: 22
- **m_flBarrackBossDPS**: 80.0
- **m_flPlayerDPS**: 28.0
- **m_flTrooperDPS**: 35.0

---

# NPC: trooper_zipline_container

- **m_WeaponInfo**:
  - **m_Spread**: 0.5
  - **m_StandingSpread**: 1.5
  - **m_flScatterYawScale**: 1
  - **m_flShootingUpSpreadPenalty**: 2
  - **m_flZoomMoveSpeedPercent**: 0.7
  - **m_flShootMoveSpeedPercent**: 0.7
  - **m_flHorizontalPunch**: 0
  - **m_flVerticalPunch**: 0
  - **m_flRecoilRecoverySpeed**: 10.0
  - **m_VerticallRecoil**:
    - **m_Range**:
      - -0.2
      - 0.2
    - **m_flBurstSlope**: 0.0
    - **m_flBurstExponent**: 0.0
    - **m_flBurstConstant**: 0.0
  - **m_HorizontalRecoil**:
    - **m_Range**:
      - -0.1
      - 0.1
    - **m_flBurstExponent**: 0.0
  - **m_flRecoilSpeed**: 1
  - **m_flZoomFOV**: 40.0
  - **m_flDamageFalloffStartRange**: 600
  - **m_flDamageFalloffEndRange**: 1000
  - **m_flRange**: 1000
  - **m_flBulletLifetime**: 2
  - **m_flDamageFalloffEndScale**: 0.3
  - **m_flDamageFalloffBias**: 0.5
  - **m_iBullets**: 1
  - **m_flCycleTime**: 1.03
  - **m_reloadDuration**: 1.8
  - **m_iClipSize**: -1
  - **m_iBurstShotCount**: 1
  - **m_flBurstShotCooldown**: 0
  - **m_flBulletGravityScale**: 0.0
  - **m_flBulletRadius**: 3
  - **m_flBulletDrag**: 1
  - **m_flBulletDragBias**: 0.5
  - **m_flBulletReflectScale**: 0
  - **m_flBulletReflectAmount**: 1
  - **m_flBulletInheritShooterVelocityScale**: 0
  - **m_szBulletTravelTracerParticle**: resource_name:"particles/weapon_fx/trooper/trooper_bullet_travel.vpcf"
  - **m_szMuzzleFlashEffectName**: resource_name:"particles/dev/bullet_debug_muzzle_flash.vpcf"
  - **m_strShootSound**: soundevent:"TrooperRifle.Fire"
  - **m_strBulletWhizSound**: soundevent:"Base.Bullet.Whizby"
  - **m_BulletSpeedCurve**:
    - **m_spline**:
      | x | y | m_flSlopeIncoming | m_flSlopeOutgoing |
      | --- | --- | --- | --- |
      | 0.0 | 12000.0 | 0.0 | 0.0 |
      | 100.0 | 12000.0 | 0.0 | 0.0 |
    - **m_tangents**:
      | m_nIncomingTangent | m_nOutgoingTangent |
      | --- | --- |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
    - **m_vDomainMins**:
      - 0.0
      - 1.0
    - **m_vDomainMaxs**:
      - 100.0
      - 12000.0
  - **m_mapImpactEffects**:
    - **default**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Default.BulletImpact"
    - **flesh**:
      - **m_strDecal**: 
      - **m_strParticle**: resource_name:"particles/blood_impact/blood_impact_red_01.vpcf"
      - **m_strSound**: soundevent:"Flesh.BulletImpact"
    - **concrete**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Concrete.BulletImpact"
    - **solidmetal**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"SolidMetal.BulletImpact"
    - **portals**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Player.HitInvuln"
  - **m_flCritBonusStart**: 1.15
  - **m_flCritBonusEnd**: 1.35
  - **m_flCritBonusStartRange**: 500.0
  - **m_flCritBonusEndRange**: 1500.0
  - **m_flCritBonusAgainstNPCs**: 0.25
  - **m_flShootSpreadPenaltyPerShot**: 0.0
  - **m_flShootSpreadPenaltyDecayDelay**: 0.0
  - **m_flShootSpreadPenaltyDecay**: 2.0
  - **m_flRecoilShotIndexRecoveryTimeFactor**: 0.25
  - **m_bCanZoom**: True
  - **m_strWeaponImpactEffect**: resource_name:"particles/weapon_fx/default_tracer_impact.vpcf"
  - **m_flReloadMoveSpeed**: 236.22
  - **m_strLocalPlayerBulletImpactSound**: soundevent:"Player.Bullet.Impact.Trooper"
  - **m_NpcAimingSpread**:
    - 0.2
    - 0.8
  - **m_flBulletDamage**: 36
- **_base**: trooper_base
- **_class**: npc_trooper
- **m_sModelName**: resource_name:"models/npc/trooper_zipline_container/trooper_zipline_container.vmdl"
- **m_nMaxHealth**: 1
- **m_flSightRangePlayers**: 700.0
- **m_flSightRangeNPCs**: 1600.0
- **m_hFootstepSounds**: trooper
- **m_flTrooperDamageResistPct**: 25.0
- **m_flT1BossDamageResistPct**: 35.0
- **m_flT2BossDamageResistPct**: 20.0
- **m_flShieldDamageResistPct**: 80.0
- **m_flNearDeathDuration**: 0
- **m_flWalkSpeed**: 240
- **m_flRunSpeed**: 433
- **m_flAcceleration**: 200
- **m_flMeleeDamage**: 25.0
- **m_flMeleeAttemptRange**: 100
- **m_flMeleeHitRange**: 100
- **m_flMeleeDuration**: 1.0
- **m_flAttackT1BossMaxRange**: 540
- **m_flAttackTrooperMaxRange**: 700
- **m_BossAttackParticle**: resource_name:"particles/weapon_fx/trooper/trooper_bullet_bonus_dmg.vpcf"
- **m_sDefaultMaterialGroupName**: Friendly
- **m_sEnemyMaterialGroupName**: Enemy
- **m_flMeleeChargeRange**: 0
- **m_flHealthBarOffset**: 76.0
- **m_flHealthBarOffsetDucking**: 40
- **m_DeathParticle**: resource_name:"particles/trooper/trooper_zipline_landing.vpcf"
- **m_DeathSound**: soundevent:"Trooper.Deploy.Impact"
- **m_MeleeHitSound**: soundevent:"Trooper.Melee.Damage.Hit"
- **m_MeleeHitPlayerSound**: soundevent:"Player.Damage.Melee.Trooper.Impact"
- **m_HealthBarParticle**: resource_name:"particles/npc/npc_healthbar.vpcf"
- **m_sHealthBarAttachment**: head_fx
- **m_HealthBarColorFriend**:
  - 255
  - 239
  - 215
- **m_HealthBarColorEnemy**:
  - 230
  - 25
  - 25
- **m_HealthBarColorTeam1**:
  - 231
  - 182
  - 89
- **m_HealthBarColorTeam2**:
  - 91
  - 121
  - 230
- **m_HealthBarColorTeamNeutral**:
  - 0
  - 125
  - 125
- **m_MeleeSwingParticle**: resource_name:"particles/abilities/melee_swing.vpcf"
- **m_MeleeActivateParticle**: resource_name:"particles/abilities/melee/melee_activate.vpcf"
- **m_MeleeAnimName**: b_melee
- **m_LastHitParticle**: resource_name:""
- **m_strLastHitSound**: resource_name:""
- **m_bPlayLastHitSound**: False
- **m_NearDeathModifier**:
  - **subclass**:
    - **_class**: modifier_near_death_fx
    - **_my_subclass_name**: modifier_near_death_fx
    - **m_EnemyNearDeathParticle**: resource_name:"particles/status_fx/status_fx_last_hit.vpcf"
    - **m_FriendlyNearDeathParticle**: resource_name:"particles/status_fx/status_fx_last_hit_friend.vpcf"
    - **m_sSelfDestructStart**: soundevent:"Trooper.SelfDestruct_Start"
    - **m_sSelfDestructEnd**: soundevent:"Trooper.SelfDestruct_Exp"
- **m_TargetingLaserParticle**: resource_name:"particles/weapon_fx/trooper_laser_target.vpcf"
- **m_TargetingEyeFlashParticle**: resource_name:"particles/enemy_targeting_indicator.vpcf"
- **m_sCelebrationSound**: soundevent:"Trooper.Objective.Win.Cheer"
- **m_flBarrackGuardianDamageResistPct**: 67.5
- **m_sTeam1MaterialGroupName**: Amber
- **m_sTeam2MaterialGroupName**: Sapphire
- **m_flT1BossDPS**: 36.0
- **m_flT2BossDPS**: 80.0
- **m_flT3BossDPS**: 80.0
- **m_flGeneratorBossDPS**: 22
- **m_flBarrackBossDPS**: 80.0
- **m_flPlayerDPS**: 28.0
- **m_flTrooperDPS**: 35.0
- **m_TrooperType**: TROOPER_ZIPLINE_CONTAINER
- **m_mapBoundAbilities**:
  - **ESlot_Ability_ZipLine**: citadel_ability_trooper_zip_line

---

# NPC: trooper_normal

- **m_WeaponInfo**:
  - **m_Spread**: 0.5
  - **m_StandingSpread**: 1.5
  - **m_flScatterYawScale**: 1
  - **m_flShootingUpSpreadPenalty**: 2
  - **m_flZoomMoveSpeedPercent**: 0.7
  - **m_flShootMoveSpeedPercent**: 0.7
  - **m_flHorizontalPunch**: 0
  - **m_flVerticalPunch**: 0
  - **m_flRecoilRecoverySpeed**: 10.0
  - **m_VerticallRecoil**:
    - **m_Range**:
      - -0.2
      - 0.2
    - **m_flBurstSlope**: 0.0
    - **m_flBurstExponent**: 0.0
    - **m_flBurstConstant**: 0.0
  - **m_HorizontalRecoil**:
    - **m_Range**:
      - -0.1
      - 0.1
    - **m_flBurstExponent**: 0.0
  - **m_flRecoilSpeed**: 1
  - **m_flZoomFOV**: 40.0
  - **m_flDamageFalloffStartRange**: 600
  - **m_flDamageFalloffEndRange**: 1000
  - **m_flRange**: 1000
  - **m_flBulletLifetime**: 2
  - **m_flDamageFalloffEndScale**: 0.3
  - **m_flDamageFalloffBias**: 0.5
  - **m_iBullets**: 1
  - **m_flCycleTime**: 1.03
  - **m_reloadDuration**: 1.8
  - **m_iClipSize**: -1
  - **m_iBurstShotCount**: 1
  - **m_flBurstShotCooldown**: 0
  - **m_flBulletGravityScale**: 0.0
  - **m_flBulletRadius**: 3
  - **m_flBulletDrag**: 1
  - **m_flBulletDragBias**: 0.5
  - **m_flBulletReflectScale**: 0
  - **m_flBulletReflectAmount**: 1
  - **m_flBulletInheritShooterVelocityScale**: 0
  - **m_szBulletTravelTracerParticle**: resource_name:"particles/weapon_fx/trooper/trooper_bullet_travel.vpcf"
  - **m_szMuzzleFlashEffectName**: resource_name:"particles/dev/bullet_debug_muzzle_flash.vpcf"
  - **m_strShootSound**: soundevent:"TrooperRifle.Fire"
  - **m_strBulletWhizSound**: soundevent:"Base.Bullet.Whizby"
  - **m_BulletSpeedCurve**:
    - **m_spline**:
      | x | y | m_flSlopeIncoming | m_flSlopeOutgoing |
      | --- | --- | --- | --- |
      | 0.0 | 12000.0 | 0.0 | 0.0 |
      | 100.0 | 12000.0 | 0.0 | 0.0 |
    - **m_tangents**:
      | m_nIncomingTangent | m_nOutgoingTangent |
      | --- | --- |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
    - **m_vDomainMins**:
      - 0.0
      - 1.0
    - **m_vDomainMaxs**:
      - 100.0
      - 12000.0
  - **m_mapImpactEffects**:
    - **default**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"TrooperRifle.BulletImpact.Default"
    - **flesh**:
      - **m_strDecal**: 
      - **m_strParticle**: resource_name:"particles/blood_impact/blood_impact_red_01.vpcf"
      - **m_strSound**: soundevent:"Flesh.BulletImpact"
    - **concrete**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Concrete.BulletImpact"
    - **solidmetal**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"SolidMetal.BulletImpact"
    - **portals**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Player.HitInvuln"
  - **m_flCritBonusStart**: 1.15
  - **m_flCritBonusEnd**: 1.35
  - **m_flCritBonusStartRange**: 500.0
  - **m_flCritBonusEndRange**: 1500.0
  - **m_flCritBonusAgainstNPCs**: 0.25
  - **m_flShootSpreadPenaltyPerShot**: 0.0
  - **m_flShootSpreadPenaltyDecayDelay**: 0.0
  - **m_flShootSpreadPenaltyDecay**: 2.0
  - **m_flRecoilShotIndexRecoveryTimeFactor**: 0.25
  - **m_bCanZoom**: True
  - **m_strWeaponImpactEffect**: resource_name:"particles/weapon_fx/default_tracer_impact.vpcf"
  - **m_flReloadMoveSpeed**: 236.22
  - **m_strLocalPlayerBulletImpactSound**: soundevent:"Player.Bullet.Impact.Trooper"
  - **m_NpcAimingSpread**:
    - 0.2
    - 0.8
  - **m_flBulletDamage**: 36
- **_base**: trooper_base
- **_class**: npc_trooper
- **m_sModelName**: resource_name:"models/npc/trooper/trooper_humanoid.vmdl"
- **m_nMaxHealth**: 300
- **m_flSightRangePlayers**: 700.0
- **m_flSightRangeNPCs**: 1600.0
- **m_hFootstepSounds**: trooper
- **m_flTrooperDamageResistPct**: 25.0
- **m_flT1BossDamageResistPct**: 35.0
- **m_flT2BossDamageResistPct**: 20.0
- **m_flShieldDamageResistPct**: 80.0
- **m_flNearDeathDuration**: 1.0
- **m_flWalkSpeed**: 240
- **m_flRunSpeed**: 433
- **m_flAcceleration**: 200
- **m_flMeleeDamage**: 25.0
- **m_flMeleeAttemptRange**: 100
- **m_flMeleeHitRange**: 100
- **m_flMeleeDuration**: 1.0
- **m_flAttackT1BossMaxRange**: 540
- **m_flAttackTrooperMaxRange**: 700
- **m_BossAttackParticle**: resource_name:"particles/weapon_fx/trooper/trooper_bullet_bonus_dmg.vpcf"
- **m_sDefaultMaterialGroupName**: Friendly
- **m_sEnemyMaterialGroupName**: Enemy
- **m_flMeleeChargeRange**: 0
- **m_flHealthBarOffset**: 76.0
- **m_flHealthBarOffsetDucking**: 60
- **m_DeathParticle**: resource_name:"particles/trooper/trooper_death_sn.vpcf"
- **m_DeathSound**: soundevent:"Trooper.Death"
- **m_MeleeHitSound**: soundevent:"Trooper.Melee.Damage.Hit"
- **m_MeleeHitPlayerSound**: soundevent:"Player.Damage.Melee.Trooper.Impact"
- **m_HealthBarParticle**: resource_name:"particles/npc/npc_healthbar.vpcf"
- **m_sHealthBarAttachment**: head_fx
- **m_HealthBarColorFriend**:
  - 255
  - 239
  - 215
- **m_HealthBarColorEnemy**:
  - 230
  - 25
  - 25
- **m_HealthBarColorTeam1**:
  - 231
  - 182
  - 89
- **m_HealthBarColorTeam2**:
  - 91
  - 121
  - 230
- **m_HealthBarColorTeamNeutral**:
  - 0
  - 125
  - 125
- **m_MeleeSwingParticle**: resource_name:"particles/abilities/melee_swing.vpcf"
- **m_MeleeActivateParticle**: resource_name:"particles/abilities/melee/melee_activate.vpcf"
- **m_MeleeAnimName**: b_melee
- **m_LastHitParticle**: resource_name:"particles/generic/last_hit.vpcf"
- **m_strLastHitSound**: soundevent:"LastHit.Default"
- **m_bPlayLastHitSound**: True
- **m_NearDeathModifier**:
  - **subclass**:
    - **_class**: modifier_near_death_fx
    - **_my_subclass_name**: modifier_near_death_fx
    - **m_EnemyNearDeathParticle**: resource_name:"particles/status_fx/status_fx_last_hit.vpcf"
    - **m_FriendlyNearDeathParticle**: resource_name:"particles/status_fx/status_fx_last_hit_friend.vpcf"
    - **m_sSelfDestructStart**: soundevent:"Trooper.SelfDestruct_Start"
    - **m_sSelfDestructEnd**: soundevent:"Trooper.SelfDestruct_Exp"
- **m_TargetingLaserParticle**: resource_name:"particles/weapon_fx/trooper_laser_target.vpcf"
- **m_TargetingEyeFlashParticle**: resource_name:"particles/enemy_targeting_indicator.vpcf"
- **m_sCelebrationSound**: soundevent:"Trooper.Objective.Win.Cheer"
- **m_flBarrackGuardianDamageResistPct**: 67.5
- **m_sTeam1MaterialGroupName**: Amber
- **m_sTeam2MaterialGroupName**: Sapphire
- **m_flT1BossDPS**: 36.0
- **m_flT2BossDPS**: 80.0
- **m_flT3BossDPS**: 80.0
- **m_flGeneratorBossDPS**: 22
- **m_flBarrackBossDPS**: 80.0
- **m_flPlayerDPS**: 28.0
- **m_flTrooperDPS**: 35.0

---

# NPC: alt_trooper_normal

- **m_WeaponInfo**:
  - **m_Spread**: 0.5
  - **m_StandingSpread**: 1.5
  - **m_flScatterYawScale**: 1
  - **m_flShootingUpSpreadPenalty**: 2
  - **m_flZoomMoveSpeedPercent**: 0.7
  - **m_flShootMoveSpeedPercent**: 0.7
  - **m_flHorizontalPunch**: 0
  - **m_flVerticalPunch**: 0
  - **m_flRecoilRecoverySpeed**: 10.0
  - **m_VerticallRecoil**:
    - **m_Range**:
      - -0.2
      - 0.2
    - **m_flBurstSlope**: 0.0
    - **m_flBurstExponent**: 0.0
    - **m_flBurstConstant**: 0.0
  - **m_HorizontalRecoil**:
    - **m_Range**:
      - -0.1
      - 0.1
    - **m_flBurstExponent**: 0.0
  - **m_flRecoilSpeed**: 1
  - **m_flZoomFOV**: 40.0
  - **m_flDamageFalloffStartRange**: 600
  - **m_flDamageFalloffEndRange**: 1000
  - **m_flRange**: 1000
  - **m_flBulletLifetime**: 2
  - **m_flDamageFalloffEndScale**: 0.3
  - **m_flDamageFalloffBias**: 0.5
  - **m_iBullets**: 1
  - **m_flCycleTime**: 1.03
  - **m_reloadDuration**: 1.8
  - **m_iClipSize**: -1
  - **m_iBurstShotCount**: 1
  - **m_flBurstShotCooldown**: 0
  - **m_flBulletGravityScale**: 0.0
  - **m_flBulletRadius**: 3
  - **m_flBulletDrag**: 1
  - **m_flBulletDragBias**: 0.5
  - **m_flBulletReflectScale**: 0
  - **m_flBulletReflectAmount**: 1
  - **m_flBulletInheritShooterVelocityScale**: 0
  - **m_szBulletTravelTracerParticle**: resource_name:"particles/weapon_fx/trooper/trooper_bullet_travel.vpcf"
  - **m_szMuzzleFlashEffectName**: resource_name:"particles/dev/bullet_debug_muzzle_flash.vpcf"
  - **m_strShootSound**: soundevent:"TrooperRifle.Fire"
  - **m_strBulletWhizSound**: soundevent:"Base.Bullet.Whizby"
  - **m_BulletSpeedCurve**:
    - **m_spline**:
      | x | y | m_flSlopeIncoming | m_flSlopeOutgoing |
      | --- | --- | --- | --- |
      | 0.0 | 12000.0 | 0.0 | 0.0 |
      | 100.0 | 12000.0 | 0.0 | 0.0 |
    - **m_tangents**:
      | m_nIncomingTangent | m_nOutgoingTangent |
      | --- | --- |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
    - **m_vDomainMins**:
      - 0.0
      - 1.0
    - **m_vDomainMaxs**:
      - 100.0
      - 12000.0
  - **m_mapImpactEffects**:
    - **default**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"TrooperRifle.BulletImpact.Default"
    - **flesh**:
      - **m_strDecal**: 
      - **m_strParticle**: resource_name:"particles/blood_impact/blood_impact_red_01.vpcf"
      - **m_strSound**: soundevent:"Flesh.BulletImpact"
    - **concrete**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Concrete.BulletImpact"
    - **solidmetal**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"SolidMetal.BulletImpact"
    - **portals**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Player.HitInvuln"
  - **m_flCritBonusStart**: 1.15
  - **m_flCritBonusEnd**: 1.35
  - **m_flCritBonusStartRange**: 500.0
  - **m_flCritBonusEndRange**: 1500.0
  - **m_flCritBonusAgainstNPCs**: 0.25
  - **m_flShootSpreadPenaltyPerShot**: 0.0
  - **m_flShootSpreadPenaltyDecayDelay**: 0.0
  - **m_flShootSpreadPenaltyDecay**: 2.0
  - **m_flRecoilShotIndexRecoveryTimeFactor**: 0.25
  - **m_bCanZoom**: True
  - **m_strWeaponImpactEffect**: resource_name:"particles/weapon_fx/default_tracer_impact.vpcf"
  - **m_flReloadMoveSpeed**: 236.22
  - **m_strLocalPlayerBulletImpactSound**: soundevent:"Player.Bullet.Impact.Trooper"
  - **m_NpcAimingSpread**:
    - 0.2
    - 0.8
  - **m_flBulletDamage**: 36
- **_base**: trooper_normal
- **_class**: npc_trooper
- **m_sModelName**: resource_name:"models/npc/trooper/trooper_humanoid.vmdl"
- **m_nMaxHealth**: 300
- **m_flSightRangePlayers**: 700.0
- **m_flSightRangeNPCs**: 1600.0
- **m_hFootstepSounds**: trooper
- **m_flTrooperDamageResistPct**: 25.0
- **m_flT1BossDamageResistPct**: 35.0
- **m_flT2BossDamageResistPct**: 20.0
- **m_flShieldDamageResistPct**: 80.0
- **m_flNearDeathDuration**: 1.0
- **m_flWalkSpeed**: 240
- **m_flRunSpeed**: 433
- **m_flAcceleration**: 200
- **m_flMeleeDamage**: 25.0
- **m_flMeleeAttemptRange**: 100
- **m_flMeleeHitRange**: 100
- **m_flMeleeDuration**: 1.0
- **m_flAttackT1BossMaxRange**: 540
- **m_flAttackTrooperMaxRange**: 700
- **m_BossAttackParticle**: resource_name:"particles/weapon_fx/trooper/trooper_bullet_bonus_dmg.vpcf"
- **m_sDefaultMaterialGroupName**: Friendly
- **m_sEnemyMaterialGroupName**: Enemy
- **m_flMeleeChargeRange**: 0
- **m_flHealthBarOffset**: 76.0
- **m_flHealthBarOffsetDucking**: 60
- **m_DeathParticle**: resource_name:"particles/trooper/trooper_death_sn.vpcf"
- **m_DeathSound**: soundevent:"Trooper.Death"
- **m_MeleeHitSound**: soundevent:"Trooper.Melee.Damage.Hit"
- **m_MeleeHitPlayerSound**: soundevent:"Player.Damage.Melee.Trooper.Impact"
- **m_HealthBarParticle**: resource_name:"particles/npc/npc_healthbar.vpcf"
- **m_sHealthBarAttachment**: head_fx
- **m_HealthBarColorFriend**:
  - 255
  - 239
  - 215
- **m_HealthBarColorEnemy**:
  - 230
  - 25
  - 25
- **m_HealthBarColorTeam1**:
  - 231
  - 182
  - 89
- **m_HealthBarColorTeam2**:
  - 91
  - 121
  - 230
- **m_HealthBarColorTeamNeutral**:
  - 0
  - 125
  - 125
- **m_MeleeSwingParticle**: resource_name:"particles/abilities/melee_swing.vpcf"
- **m_MeleeActivateParticle**: resource_name:"particles/abilities/melee/melee_activate.vpcf"
- **m_MeleeAnimName**: b_melee
- **m_LastHitParticle**: resource_name:"particles/generic/last_hit.vpcf"
- **m_strLastHitSound**: soundevent:"LastHit.Default"
- **m_bPlayLastHitSound**: True
- **m_NearDeathModifier**:
  - **subclass**:
    - **_class**: modifier_near_death_fx
    - **_my_subclass_name**: modifier_near_death_fx
    - **m_EnemyNearDeathParticle**: resource_name:"particles/status_fx/status_fx_last_hit.vpcf"
    - **m_FriendlyNearDeathParticle**: resource_name:"particles/status_fx/status_fx_last_hit_friend.vpcf"
    - **m_sSelfDestructStart**: soundevent:"Trooper.SelfDestruct_Start"
    - **m_sSelfDestructEnd**: soundevent:"Trooper.SelfDestruct_Exp"
- **m_TargetingLaserParticle**: resource_name:"particles/weapon_fx/trooper_laser_target.vpcf"
- **m_TargetingEyeFlashParticle**: resource_name:"particles/enemy_targeting_indicator.vpcf"
- **m_sCelebrationSound**: soundevent:"Trooper.Objective.Win.Cheer"
- **m_flBarrackGuardianDamageResistPct**: 67.5
- **m_sTeam1MaterialGroupName**: Amber
- **m_sTeam2MaterialGroupName**: Sapphire
- **m_flT1BossDPS**: 36.0
- **m_flT2BossDPS**: 80.0
- **m_flT3BossDPS**: 80.0
- **m_flGeneratorBossDPS**: 22
- **m_flBarrackBossDPS**: 80.0
- **m_flPlayerDPS**: 28.0
- **m_flTrooperDPS**: 35.0

---

# NPC: trooper_medic

- **m_WeaponInfo**:
  - **m_Spread**: 0.5
  - **m_StandingSpread**: 1.5
  - **m_flScatterYawScale**: 1
  - **m_flShootingUpSpreadPenalty**: 2
  - **m_flZoomMoveSpeedPercent**: 0.7
  - **m_flShootMoveSpeedPercent**: 0.7
  - **m_flHorizontalPunch**: 0
  - **m_flVerticalPunch**: 0
  - **m_flRecoilRecoverySpeed**: 10.0
  - **m_VerticallRecoil**:
    - **m_Range**:
      - -0.2
      - 0.2
    - **m_flBurstSlope**: 0.0
    - **m_flBurstExponent**: 0.0
    - **m_flBurstConstant**: 0.0
  - **m_HorizontalRecoil**:
    - **m_Range**:
      - -0.1
      - 0.1
    - **m_flBurstExponent**: 0.0
  - **m_flRecoilSpeed**: 1
  - **m_flZoomFOV**: 40.0
  - **m_flDamageFalloffStartRange**: 600
  - **m_flDamageFalloffEndRange**: 1400
  - **m_flRange**: 1400
  - **m_flBulletLifetime**: 2
  - **m_flDamageFalloffEndScale**: 0.3
  - **m_flDamageFalloffBias**: 0.5
  - **m_iBullets**: 1
  - **m_flCycleTime**: 1.03
  - **m_reloadDuration**: 1.8
  - **m_iClipSize**: -1
  - **m_iBurstShotCount**: 1
  - **m_flBurstShotCooldown**: 0
  - **m_flBulletGravityScale**: 0.0
  - **m_flBulletRadius**: 3
  - **m_flBulletDrag**: 1
  - **m_flBulletDragBias**: 0.5
  - **m_flBulletReflectScale**: 0
  - **m_flBulletReflectAmount**: 1
  - **m_flBulletInheritShooterVelocityScale**: 0
  - **m_szBulletTravelTracerParticle**: resource_name:"particles/weapon_fx/trooper/trooper_bullet_travel.vpcf"
  - **m_szMuzzleFlashEffectName**: resource_name:"particles/dev/bullet_debug_muzzle_flash.vpcf"
  - **m_strShootSound**: soundevent:"TrooperRifle.Fire"
  - **m_strBulletWhizSound**: soundevent:"Base.Bullet.Whizby"
  - **m_BulletSpeedCurve**:
    - **m_spline**:
      | x | y | m_flSlopeIncoming | m_flSlopeOutgoing |
      | --- | --- | --- | --- |
      | 0.0 | 12000.0 | 0.0 | 0.0 |
      | 100.0 | 12000.0 | 0.0 | 0.0 |
    - **m_tangents**:
      | m_nIncomingTangent | m_nOutgoingTangent |
      | --- | --- |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
    - **m_vDomainMins**:
      - 0.0
      - 1.0
    - **m_vDomainMaxs**:
      - 100.0
      - 12000.0
  - **m_mapImpactEffects**:
    - **default**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Default.BulletImpact"
    - **flesh**:
      - **m_strDecal**: 
      - **m_strParticle**: resource_name:"particles/blood_impact/blood_impact_red_01.vpcf"
      - **m_strSound**: soundevent:"Flesh.BulletImpact"
    - **concrete**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Concrete.BulletImpact"
    - **solidmetal**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"SolidMetal.BulletImpact"
    - **portals**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Player.HitInvuln"
  - **m_flCritBonusStart**: 1.15
  - **m_flCritBonusEnd**: 1.35
  - **m_flCritBonusStartRange**: 500.0
  - **m_flCritBonusEndRange**: 1500.0
  - **m_flCritBonusAgainstNPCs**: 0.25
  - **m_flShootSpreadPenaltyPerShot**: 0.0
  - **m_flShootSpreadPenaltyDecayDelay**: 0.0
  - **m_flShootSpreadPenaltyDecay**: 2.0
  - **m_flRecoilShotIndexRecoveryTimeFactor**: 0.25
  - **m_bCanZoom**: True
  - **m_strWeaponImpactEffect**: resource_name:"particles/weapon_fx/default_tracer_impact.vpcf"
  - **m_flReloadMoveSpeed**: 236.22
  - **m_strLocalPlayerBulletImpactSound**: soundevent:"Player.Bullet.Impact.Trooper"
  - **m_NpcAimingSpread**:
    - 0.2
    - 0.8
  - **m_flBulletDamage**: 36
- **_base**: trooper_base
- **_class**: npc_trooper
- **m_sModelName**: resource_name:"models/npc/medic/medic_model.vmdl"
- **m_nMaxHealth**: 260
- **m_flSightRangePlayers**: 700.0
- **m_flSightRangeNPCs**: 1600.0
- **m_hFootstepSounds**: trooper
- **m_flTrooperDamageResistPct**: 25.0
- **m_flT1BossDamageResistPct**: 35.0
- **m_flT2BossDamageResistPct**: 20.0
- **m_flShieldDamageResistPct**: 80.0
- **m_flNearDeathDuration**: 1.0
- **m_flWalkSpeed**: 240
- **m_flRunSpeed**: 433
- **m_flAcceleration**: 200
- **m_flMeleeDamage**: 25.0
- **m_flMeleeAttemptRange**: 100
- **m_flMeleeHitRange**: 100
- **m_flMeleeDuration**: 1.0
- **m_flAttackT1BossMaxRange**: 540
- **m_flAttackTrooperMaxRange**: 700
- **m_BossAttackParticle**: resource_name:"particles/weapon_fx/trooper/trooper_bullet_bonus_dmg.vpcf"
- **m_sDefaultMaterialGroupName**: FriendlyMedic
- **m_sEnemyMaterialGroupName**: EnemyMedic
- **m_flMeleeChargeRange**: 0
- **m_flHealthBarOffset**: 76.0
- **m_flHealthBarOffsetDucking**: 40
- **m_DeathParticle**: resource_name:"particles/trooper/trooper_death_sn.vpcf"
- **m_DeathSound**: soundevent:"Trooper.Death"
- **m_MeleeHitSound**: soundevent:"Trooper.Melee.Damage.Hit"
- **m_MeleeHitPlayerSound**: soundevent:"Player.Damage.Melee.Trooper.Impact"
- **m_HealthBarParticle**: resource_name:"particles/npc/npc_healthbar.vpcf"
- **m_sHealthBarAttachment**: head_fx
- **m_HealthBarColorFriend**:
  - 255
  - 239
  - 215
- **m_HealthBarColorEnemy**:
  - 230
  - 25
  - 25
- **m_HealthBarColorTeam1**:
  - 231
  - 182
  - 89
- **m_HealthBarColorTeam2**:
  - 91
  - 121
  - 230
- **m_HealthBarColorTeamNeutral**:
  - 0
  - 125
  - 125
- **m_MeleeSwingParticle**: resource_name:"particles/abilities/melee_swing.vpcf"
- **m_MeleeActivateParticle**: resource_name:"particles/abilities/melee/melee_activate.vpcf"
- **m_MeleeAnimName**: b_melee
- **m_LastHitParticle**: resource_name:"particles/generic/last_hit.vpcf"
- **m_strLastHitSound**: soundevent:"LastHit.Default"
- **m_bPlayLastHitSound**: True
- **m_NearDeathModifier**:
  - **subclass**:
    - **_class**: modifier_near_death_fx
    - **_my_subclass_name**: modifier_near_death_fx
    - **m_EnemyNearDeathParticle**: resource_name:"particles/status_fx/status_fx_last_hit.vpcf"
    - **m_FriendlyNearDeathParticle**: resource_name:"particles/status_fx/status_fx_last_hit_friend.vpcf"
    - **m_sSelfDestructStart**: soundevent:"Trooper.SelfDestruct_Start"
    - **m_sSelfDestructEnd**: soundevent:"Trooper.SelfDestruct_Exp"
- **m_TargetingLaserParticle**: resource_name:"particles/weapon_fx/trooper_laser_target.vpcf"
- **m_TargetingEyeFlashParticle**: resource_name:"particles/enemy_targeting_indicator.vpcf"
- **m_sCelebrationSound**: soundevent:"Trooper.Objective.Win.Cheer"
- **m_flBarrackGuardianDamageResistPct**: 67.5
- **m_sTeam1MaterialGroupName**: Amber
- **m_sTeam2MaterialGroupName**: Sapphire
- **m_flT1BossDPS**: 36.0
- **m_flT2BossDPS**: 80.0
- **m_flT3BossDPS**: 80.0
- **m_flGeneratorBossDPS**: 22
- **m_flBarrackBossDPS**: 80.0
- **m_flPlayerDPS**: 28.0
- **m_flTrooperDPS**: 35.0
- **m_TrooperType**: TROOPER_MEDIC
- **m_mapBoundAbilities**:
  - **ESlot_Signature_2**: ability_medic_trooper_heal
- **m_MedicHealActiveParticle**: resource_name:"particles/trooper/trooper_medic_chargeup.vpcf"

---

# NPC: alt_trooper_medic

- **m_WeaponInfo**:
  - **m_Spread**: 0.5
  - **m_StandingSpread**: 1.5
  - **m_flScatterYawScale**: 1
  - **m_flShootingUpSpreadPenalty**: 2
  - **m_flZoomMoveSpeedPercent**: 0.7
  - **m_flShootMoveSpeedPercent**: 0.7
  - **m_flHorizontalPunch**: 0
  - **m_flVerticalPunch**: 0
  - **m_flRecoilRecoverySpeed**: 10.0
  - **m_VerticallRecoil**:
    - **m_Range**:
      - -0.2
      - 0.2
    - **m_flBurstSlope**: 0.0
    - **m_flBurstExponent**: 0.0
    - **m_flBurstConstant**: 0.0
  - **m_HorizontalRecoil**:
    - **m_Range**:
      - -0.1
      - 0.1
    - **m_flBurstExponent**: 0.0
  - **m_flRecoilSpeed**: 1
  - **m_flZoomFOV**: 40.0
  - **m_flDamageFalloffStartRange**: 600
  - **m_flDamageFalloffEndRange**: 1400
  - **m_flRange**: 1400
  - **m_flBulletLifetime**: 2
  - **m_flDamageFalloffEndScale**: 0.3
  - **m_flDamageFalloffBias**: 0.5
  - **m_iBullets**: 1
  - **m_flCycleTime**: 1.03
  - **m_reloadDuration**: 1.8
  - **m_iClipSize**: -1
  - **m_iBurstShotCount**: 1
  - **m_flBurstShotCooldown**: 0
  - **m_flBulletGravityScale**: 0.0
  - **m_flBulletRadius**: 3
  - **m_flBulletDrag**: 1
  - **m_flBulletDragBias**: 0.5
  - **m_flBulletReflectScale**: 0
  - **m_flBulletReflectAmount**: 1
  - **m_flBulletInheritShooterVelocityScale**: 0
  - **m_szBulletTravelTracerParticle**: resource_name:"particles/weapon_fx/trooper/trooper_bullet_travel.vpcf"
  - **m_szMuzzleFlashEffectName**: resource_name:"particles/dev/bullet_debug_muzzle_flash.vpcf"
  - **m_strShootSound**: soundevent:"TrooperRifle.Fire"
  - **m_strBulletWhizSound**: soundevent:"Base.Bullet.Whizby"
  - **m_BulletSpeedCurve**:
    - **m_spline**:
      | x | y | m_flSlopeIncoming | m_flSlopeOutgoing |
      | --- | --- | --- | --- |
      | 0.0 | 12000.0 | 0.0 | 0.0 |
      | 100.0 | 12000.0 | 0.0 | 0.0 |
    - **m_tangents**:
      | m_nIncomingTangent | m_nOutgoingTangent |
      | --- | --- |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
    - **m_vDomainMins**:
      - 0.0
      - 1.0
    - **m_vDomainMaxs**:
      - 100.0
      - 12000.0
  - **m_mapImpactEffects**:
    - **default**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Default.BulletImpact"
    - **flesh**:
      - **m_strDecal**: 
      - **m_strParticle**: resource_name:"particles/blood_impact/blood_impact_red_01.vpcf"
      - **m_strSound**: soundevent:"Flesh.BulletImpact"
    - **concrete**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Concrete.BulletImpact"
    - **solidmetal**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"SolidMetal.BulletImpact"
    - **portals**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Player.HitInvuln"
  - **m_flCritBonusStart**: 1.15
  - **m_flCritBonusEnd**: 1.35
  - **m_flCritBonusStartRange**: 500.0
  - **m_flCritBonusEndRange**: 1500.0
  - **m_flCritBonusAgainstNPCs**: 0.25
  - **m_flShootSpreadPenaltyPerShot**: 0.0
  - **m_flShootSpreadPenaltyDecayDelay**: 0.0
  - **m_flShootSpreadPenaltyDecay**: 2.0
  - **m_flRecoilShotIndexRecoveryTimeFactor**: 0.25
  - **m_bCanZoom**: True
  - **m_strWeaponImpactEffect**: resource_name:"particles/weapon_fx/default_tracer_impact.vpcf"
  - **m_flReloadMoveSpeed**: 236.22
  - **m_strLocalPlayerBulletImpactSound**: soundevent:"Player.Bullet.Impact.Trooper"
  - **m_NpcAimingSpread**:
    - 0.2
    - 0.8
  - **m_flBulletDamage**: 36
- **_base**: trooper_medic
- **_class**: npc_trooper
- **m_sModelName**: resource_name:"models/npc/medic/medic_model.vmdl"
- **m_nMaxHealth**: 260
- **m_flSightRangePlayers**: 700.0
- **m_flSightRangeNPCs**: 1600.0
- **m_hFootstepSounds**: trooper
- **m_flTrooperDamageResistPct**: 25.0
- **m_flT1BossDamageResistPct**: 35.0
- **m_flT2BossDamageResistPct**: 20.0
- **m_flShieldDamageResistPct**: 80.0
- **m_flNearDeathDuration**: 1.0
- **m_flWalkSpeed**: 240
- **m_flRunSpeed**: 433
- **m_flAcceleration**: 200
- **m_flMeleeDamage**: 25.0
- **m_flMeleeAttemptRange**: 100
- **m_flMeleeHitRange**: 100
- **m_flMeleeDuration**: 1.0
- **m_flAttackT1BossMaxRange**: 540
- **m_flAttackTrooperMaxRange**: 700
- **m_BossAttackParticle**: resource_name:"particles/weapon_fx/trooper/trooper_bullet_bonus_dmg.vpcf"
- **m_sDefaultMaterialGroupName**: FriendlyMedic
- **m_sEnemyMaterialGroupName**: EnemyMedic
- **m_flMeleeChargeRange**: 0
- **m_flHealthBarOffset**: 76.0
- **m_flHealthBarOffsetDucking**: 40
- **m_DeathParticle**: resource_name:"particles/trooper/trooper_death_sn.vpcf"
- **m_DeathSound**: soundevent:"Trooper.Death"
- **m_MeleeHitSound**: soundevent:"Trooper.Melee.Damage.Hit"
- **m_MeleeHitPlayerSound**: soundevent:"Player.Damage.Melee.Trooper.Impact"
- **m_HealthBarParticle**: resource_name:"particles/npc/npc_healthbar.vpcf"
- **m_sHealthBarAttachment**: head_fx
- **m_HealthBarColorFriend**:
  - 255
  - 239
  - 215
- **m_HealthBarColorEnemy**:
  - 230
  - 25
  - 25
- **m_HealthBarColorTeam1**:
  - 231
  - 182
  - 89
- **m_HealthBarColorTeam2**:
  - 91
  - 121
  - 230
- **m_HealthBarColorTeamNeutral**:
  - 0
  - 125
  - 125
- **m_MeleeSwingParticle**: resource_name:"particles/abilities/melee_swing.vpcf"
- **m_MeleeActivateParticle**: resource_name:"particles/abilities/melee/melee_activate.vpcf"
- **m_MeleeAnimName**: b_melee
- **m_LastHitParticle**: resource_name:"particles/generic/last_hit.vpcf"
- **m_strLastHitSound**: soundevent:"LastHit.Default"
- **m_bPlayLastHitSound**: True
- **m_NearDeathModifier**:
  - **subclass**:
    - **_class**: modifier_near_death_fx
    - **_my_subclass_name**: modifier_near_death_fx
    - **m_EnemyNearDeathParticle**: resource_name:"particles/status_fx/status_fx_last_hit.vpcf"
    - **m_FriendlyNearDeathParticle**: resource_name:"particles/status_fx/status_fx_last_hit_friend.vpcf"
    - **m_sSelfDestructStart**: soundevent:"Trooper.SelfDestruct_Start"
    - **m_sSelfDestructEnd**: soundevent:"Trooper.SelfDestruct_Exp"
- **m_TargetingLaserParticle**: resource_name:"particles/weapon_fx/trooper_laser_target.vpcf"
- **m_TargetingEyeFlashParticle**: resource_name:"particles/enemy_targeting_indicator.vpcf"
- **m_sCelebrationSound**: soundevent:"Trooper.Objective.Win.Cheer"
- **m_flBarrackGuardianDamageResistPct**: 67.5
- **m_sTeam1MaterialGroupName**: Amber
- **m_sTeam2MaterialGroupName**: Sapphire
- **m_flT1BossDPS**: 36.0
- **m_flT2BossDPS**: 80.0
- **m_flT3BossDPS**: 80.0
- **m_flGeneratorBossDPS**: 22
- **m_flBarrackBossDPS**: 80.0
- **m_flPlayerDPS**: 28.0
- **m_flTrooperDPS**: 35.0
- **m_TrooperType**: TROOPER_MEDIC
- **m_mapBoundAbilities**:
  - **ESlot_Signature_2**: ability_medic_trooper_heal
- **m_MedicHealActiveParticle**: resource_name:"particles/trooper/trooper_medic_chargeup.vpcf"

---

# NPC: super_trooper_normal

- **m_WeaponInfo**:
  - **m_Spread**: 0.5
  - **m_StandingSpread**: 1.5
  - **m_flScatterYawScale**: 1
  - **m_flShootingUpSpreadPenalty**: 2
  - **m_flZoomMoveSpeedPercent**: 0.7
  - **m_flShootMoveSpeedPercent**: 0.7
  - **m_flHorizontalPunch**: 0
  - **m_flVerticalPunch**: 0
  - **m_flRecoilRecoverySpeed**: 10.0
  - **m_VerticallRecoil**:
    - **m_Range**:
      - -0.2
      - 0.2
    - **m_flBurstSlope**: 0.0
    - **m_flBurstExponent**: 0.0
    - **m_flBurstConstant**: 0.0
  - **m_HorizontalRecoil**:
    - **m_Range**:
      - -0.1
      - 0.1
    - **m_flBurstExponent**: 0.0
  - **m_flRecoilSpeed**: 1
  - **m_flZoomFOV**: 40.0
  - **m_flDamageFalloffStartRange**: 600
  - **m_flDamageFalloffEndRange**: 1000
  - **m_flRange**: 1000
  - **m_flBulletLifetime**: 2
  - **m_flDamageFalloffEndScale**: 0.3
  - **m_flDamageFalloffBias**: 0.5
  - **m_iBullets**: 1
  - **m_flCycleTime**: 1.03
  - **m_reloadDuration**: 1.8
  - **m_iClipSize**: -1
  - **m_iBurstShotCount**: 1
  - **m_flBurstShotCooldown**: 0
  - **m_flBulletGravityScale**: 0.0
  - **m_flBulletRadius**: 3
  - **m_flBulletDrag**: 1
  - **m_flBulletDragBias**: 0.5
  - **m_flBulletReflectScale**: 0
  - **m_flBulletReflectAmount**: 1
  - **m_flBulletInheritShooterVelocityScale**: 0
  - **m_szBulletTravelTracerParticle**: resource_name:"particles/weapon_fx/trooper/trooper_bullet_travel.vpcf"
  - **m_szMuzzleFlashEffectName**: resource_name:"particles/dev/bullet_debug_muzzle_flash.vpcf"
  - **m_strShootSound**: soundevent:"TrooperRifle.Fire"
  - **m_strBulletWhizSound**: soundevent:"Base.Bullet.Whizby"
  - **m_BulletSpeedCurve**:
    - **m_spline**:
      | x | y | m_flSlopeIncoming | m_flSlopeOutgoing |
      | --- | --- | --- | --- |
      | 0.0 | 12000.0 | 0.0 | 0.0 |
      | 100.0 | 12000.0 | 0.0 | 0.0 |
    - **m_tangents**:
      | m_nIncomingTangent | m_nOutgoingTangent |
      | --- | --- |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
    - **m_vDomainMins**:
      - 0.0
      - 1.0
    - **m_vDomainMaxs**:
      - 100.0
      - 12000.0
  - **m_mapImpactEffects**:
    - **default**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"TrooperRifle.BulletImpact.Default"
    - **flesh**:
      - **m_strDecal**: 
      - **m_strParticle**: resource_name:"particles/blood_impact/blood_impact_red_01.vpcf"
      - **m_strSound**: soundevent:"Flesh.BulletImpact"
    - **concrete**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Concrete.BulletImpact"
    - **solidmetal**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"SolidMetal.BulletImpact"
    - **portals**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Player.HitInvuln"
  - **m_flCritBonusStart**: 1.15
  - **m_flCritBonusEnd**: 1.35
  - **m_flCritBonusStartRange**: 500.0
  - **m_flCritBonusEndRange**: 1500.0
  - **m_flCritBonusAgainstNPCs**: 0.25
  - **m_flShootSpreadPenaltyPerShot**: 0.0
  - **m_flShootSpreadPenaltyDecayDelay**: 0.0
  - **m_flShootSpreadPenaltyDecay**: 2.0
  - **m_flRecoilShotIndexRecoveryTimeFactor**: 0.25
  - **m_bCanZoom**: True
  - **m_strWeaponImpactEffect**: resource_name:"particles/weapon_fx/default_tracer_impact.vpcf"
  - **m_flReloadMoveSpeed**: 236.22
  - **m_strLocalPlayerBulletImpactSound**: soundevent:"Player.Bullet.Impact.Trooper"
  - **m_NpcAimingSpread**:
    - 0.2
    - 0.8
  - **m_flBulletDamage**: 36
- **_base**: trooper_normal
- **_class**: npc_super_trooper
- **m_sModelName**: resource_name:"models/npc/trooper/super_trooper_humanoid.vmdl"
- **m_nMaxHealth**: 300
- **m_flSightRangePlayers**: 700.0
- **m_flSightRangeNPCs**: 1600.0
- **m_hFootstepSounds**: trooper
- **m_flTrooperDamageResistPct**: 55.0
- **m_flT1BossDamageResistPct**: 35.0
- **m_flT2BossDamageResistPct**: 20.0
- **m_flShieldDamageResistPct**: 80.0
- **m_flNearDeathDuration**: 1.0
- **m_flWalkSpeed**: 240
- **m_flRunSpeed**: 433
- **m_flAcceleration**: 200
- **m_flMeleeDamage**: 25.0
- **m_flMeleeAttemptRange**: 100
- **m_flMeleeHitRange**: 100
- **m_flMeleeDuration**: 1.0
- **m_flAttackT1BossMaxRange**: 540
- **m_flAttackTrooperMaxRange**: 700
- **m_BossAttackParticle**: resource_name:"particles/weapon_fx/trooper/trooper_bullet_bonus_dmg.vpcf"
- **m_sDefaultMaterialGroupName**: Friendly
- **m_sEnemyMaterialGroupName**: Enemy
- **m_flMeleeChargeRange**: 0
- **m_flHealthBarOffset**: 76.0
- **m_flHealthBarOffsetDucking**: 60
- **m_DeathParticle**: resource_name:"particles/trooper/trooper_death_sn.vpcf"
- **m_DeathSound**: soundevent:"Trooper.Death"
- **m_MeleeHitSound**: soundevent:"Trooper.Melee.Damage.Hit"
- **m_MeleeHitPlayerSound**: soundevent:"Player.Damage.Melee.Trooper.Impact"
- **m_HealthBarParticle**: resource_name:"particles/npc/npc_healthbar.vpcf"
- **m_sHealthBarAttachment**: head_fx
- **m_HealthBarColorFriend**:
  - 255
  - 239
  - 215
- **m_HealthBarColorEnemy**:
  - 230
  - 25
  - 25
- **m_HealthBarColorTeam1**:
  - 231
  - 182
  - 89
- **m_HealthBarColorTeam2**:
  - 91
  - 121
  - 230
- **m_HealthBarColorTeamNeutral**:
  - 0
  - 125
  - 125
- **m_MeleeSwingParticle**: resource_name:"particles/abilities/melee_swing.vpcf"
- **m_MeleeActivateParticle**: resource_name:"particles/abilities/melee/melee_activate.vpcf"
- **m_MeleeAnimName**: b_melee
- **m_LastHitParticle**: resource_name:"particles/generic/last_hit.vpcf"
- **m_strLastHitSound**: soundevent:"LastHit.Default"
- **m_bPlayLastHitSound**: True
- **m_NearDeathModifier**:
  - **subclass**:
    - **_class**: modifier_near_death_fx
    - **_my_subclass_name**: modifier_near_death_fx
    - **m_EnemyNearDeathParticle**: resource_name:"particles/status_fx/status_fx_last_hit.vpcf"
    - **m_FriendlyNearDeathParticle**: resource_name:"particles/status_fx/status_fx_last_hit_friend.vpcf"
    - **m_sSelfDestructStart**: soundevent:"Trooper.SelfDestruct_Start"
    - **m_sSelfDestructEnd**: soundevent:"Trooper.SelfDestruct_Exp"
- **m_TargetingLaserParticle**: resource_name:"particles/weapon_fx/trooper_laser_target.vpcf"
- **m_TargetingEyeFlashParticle**: resource_name:"particles/enemy_targeting_indicator.vpcf"
- **m_sCelebrationSound**: soundevent:"Trooper.Objective.Win.Cheer"
- **m_flBarrackGuardianDamageResistPct**: 67.5
- **m_sTeam1MaterialGroupName**: Amber
- **m_sTeam2MaterialGroupName**: Sapphire
- **m_flT1BossDPS**: 83.6
- **m_flT2BossDPS**: 209.0
- **m_flT3BossDPS**: 209.0
- **m_flGeneratorBossDPS**: 41.8
- **m_flBarrackBossDPS**: 209.0
- **m_flPlayerDPS**: 42.0
- **m_flTrooperDPS**: 66.5
- **m_flModelScale**: 1.1

---

# NPC: super_trooper_medic

- **m_WeaponInfo**:
  - **m_Spread**: 0.5
  - **m_StandingSpread**: 1.5
  - **m_flScatterYawScale**: 1
  - **m_flShootingUpSpreadPenalty**: 2
  - **m_flZoomMoveSpeedPercent**: 0.7
  - **m_flShootMoveSpeedPercent**: 0.7
  - **m_flHorizontalPunch**: 0
  - **m_flVerticalPunch**: 0
  - **m_flRecoilRecoverySpeed**: 10.0
  - **m_VerticallRecoil**:
    - **m_Range**:
      - -0.2
      - 0.2
    - **m_flBurstSlope**: 0.0
    - **m_flBurstExponent**: 0.0
    - **m_flBurstConstant**: 0.0
  - **m_HorizontalRecoil**:
    - **m_Range**:
      - -0.1
      - 0.1
    - **m_flBurstExponent**: 0.0
  - **m_flRecoilSpeed**: 1
  - **m_flZoomFOV**: 40.0
  - **m_flDamageFalloffStartRange**: 600
  - **m_flDamageFalloffEndRange**: 1400
  - **m_flRange**: 1400
  - **m_flBulletLifetime**: 2
  - **m_flDamageFalloffEndScale**: 0.3
  - **m_flDamageFalloffBias**: 0.5
  - **m_iBullets**: 1
  - **m_flCycleTime**: 1.03
  - **m_reloadDuration**: 1.8
  - **m_iClipSize**: -1
  - **m_iBurstShotCount**: 1
  - **m_flBurstShotCooldown**: 0
  - **m_flBulletGravityScale**: 0.0
  - **m_flBulletRadius**: 3
  - **m_flBulletDrag**: 1
  - **m_flBulletDragBias**: 0.5
  - **m_flBulletReflectScale**: 0
  - **m_flBulletReflectAmount**: 1
  - **m_flBulletInheritShooterVelocityScale**: 0
  - **m_szBulletTravelTracerParticle**: resource_name:"particles/weapon_fx/trooper/trooper_bullet_travel.vpcf"
  - **m_szMuzzleFlashEffectName**: resource_name:"particles/dev/bullet_debug_muzzle_flash.vpcf"
  - **m_strShootSound**: soundevent:"TrooperRifle.Fire"
  - **m_strBulletWhizSound**: soundevent:"Base.Bullet.Whizby"
  - **m_BulletSpeedCurve**:
    - **m_spline**:
      | x | y | m_flSlopeIncoming | m_flSlopeOutgoing |
      | --- | --- | --- | --- |
      | 0.0 | 12000.0 | 0.0 | 0.0 |
      | 100.0 | 12000.0 | 0.0 | 0.0 |
    - **m_tangents**:
      | m_nIncomingTangent | m_nOutgoingTangent |
      | --- | --- |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
    - **m_vDomainMins**:
      - 0.0
      - 1.0
    - **m_vDomainMaxs**:
      - 100.0
      - 12000.0
  - **m_mapImpactEffects**:
    - **default**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Default.BulletImpact"
    - **flesh**:
      - **m_strDecal**: 
      - **m_strParticle**: resource_name:"particles/blood_impact/blood_impact_red_01.vpcf"
      - **m_strSound**: soundevent:"Flesh.BulletImpact"
    - **concrete**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Concrete.BulletImpact"
    - **solidmetal**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"SolidMetal.BulletImpact"
    - **portals**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Player.HitInvuln"
  - **m_flCritBonusStart**: 1.15
  - **m_flCritBonusEnd**: 1.35
  - **m_flCritBonusStartRange**: 500.0
  - **m_flCritBonusEndRange**: 1500.0
  - **m_flCritBonusAgainstNPCs**: 0.25
  - **m_flShootSpreadPenaltyPerShot**: 0.0
  - **m_flShootSpreadPenaltyDecayDelay**: 0.0
  - **m_flShootSpreadPenaltyDecay**: 2.0
  - **m_flRecoilShotIndexRecoveryTimeFactor**: 0.25
  - **m_bCanZoom**: True
  - **m_strWeaponImpactEffect**: resource_name:"particles/weapon_fx/default_tracer_impact.vpcf"
  - **m_flReloadMoveSpeed**: 236.22
  - **m_strLocalPlayerBulletImpactSound**: soundevent:"Player.Bullet.Impact.Trooper"
  - **m_NpcAimingSpread**:
    - 0.2
    - 0.8
  - **m_flBulletDamage**: 36
- **_base**: trooper_medic
- **_class**: npc_super_trooper
- **m_sModelName**: resource_name:"models/npc/medic/super_medic_model.vmdl"
- **m_nMaxHealth**: 260
- **m_flSightRangePlayers**: 700.0
- **m_flSightRangeNPCs**: 1600.0
- **m_hFootstepSounds**: trooper
- **m_flTrooperDamageResistPct**: 55.0
- **m_flT1BossDamageResistPct**: 35.0
- **m_flT2BossDamageResistPct**: 20.0
- **m_flShieldDamageResistPct**: 80.0
- **m_flNearDeathDuration**: 1.0
- **m_flWalkSpeed**: 240
- **m_flRunSpeed**: 433
- **m_flAcceleration**: 200
- **m_flMeleeDamage**: 25.0
- **m_flMeleeAttemptRange**: 100
- **m_flMeleeHitRange**: 100
- **m_flMeleeDuration**: 1.0
- **m_flAttackT1BossMaxRange**: 540
- **m_flAttackTrooperMaxRange**: 700
- **m_BossAttackParticle**: resource_name:"particles/weapon_fx/trooper/trooper_bullet_bonus_dmg.vpcf"
- **m_sDefaultMaterialGroupName**: FriendlyMedic
- **m_sEnemyMaterialGroupName**: EnemyMedic
- **m_flMeleeChargeRange**: 0
- **m_flHealthBarOffset**: 76.0
- **m_flHealthBarOffsetDucking**: 40
- **m_DeathParticle**: resource_name:"particles/trooper/trooper_death_sn.vpcf"
- **m_DeathSound**: soundevent:"Trooper.Death"
- **m_MeleeHitSound**: soundevent:"Trooper.Melee.Damage.Hit"
- **m_MeleeHitPlayerSound**: soundevent:"Player.Damage.Melee.Trooper.Impact"
- **m_HealthBarParticle**: resource_name:"particles/npc/npc_healthbar.vpcf"
- **m_sHealthBarAttachment**: head_fx
- **m_HealthBarColorFriend**:
  - 255
  - 239
  - 215
- **m_HealthBarColorEnemy**:
  - 230
  - 25
  - 25
- **m_HealthBarColorTeam1**:
  - 231
  - 182
  - 89
- **m_HealthBarColorTeam2**:
  - 91
  - 121
  - 230
- **m_HealthBarColorTeamNeutral**:
  - 0
  - 125
  - 125
- **m_MeleeSwingParticle**: resource_name:"particles/abilities/melee_swing.vpcf"
- **m_MeleeActivateParticle**: resource_name:"particles/abilities/melee/melee_activate.vpcf"
- **m_MeleeAnimName**: b_melee
- **m_LastHitParticle**: resource_name:"particles/generic/last_hit.vpcf"
- **m_strLastHitSound**: soundevent:"LastHit.Default"
- **m_bPlayLastHitSound**: True
- **m_NearDeathModifier**:
  - **subclass**:
    - **_class**: modifier_near_death_fx
    - **_my_subclass_name**: modifier_near_death_fx
    - **m_EnemyNearDeathParticle**: resource_name:"particles/status_fx/status_fx_last_hit.vpcf"
    - **m_FriendlyNearDeathParticle**: resource_name:"particles/status_fx/status_fx_last_hit_friend.vpcf"
    - **m_sSelfDestructStart**: soundevent:"Trooper.SelfDestruct_Start"
    - **m_sSelfDestructEnd**: soundevent:"Trooper.SelfDestruct_Exp"
- **m_TargetingLaserParticle**: resource_name:"particles/weapon_fx/trooper_laser_target.vpcf"
- **m_TargetingEyeFlashParticle**: resource_name:"particles/enemy_targeting_indicator.vpcf"
- **m_sCelebrationSound**: soundevent:"Trooper.Objective.Win.Cheer"
- **m_flBarrackGuardianDamageResistPct**: 67.5
- **m_sTeam1MaterialGroupName**: Amber
- **m_sTeam2MaterialGroupName**: Sapphire
- **m_flT1BossDPS**: 83.6
- **m_flT2BossDPS**: 209.0
- **m_flT3BossDPS**: 209.0
- **m_flGeneratorBossDPS**: 41.8
- **m_flBarrackBossDPS**: 209.0
- **m_flPlayerDPS**: 42.0
- **m_flTrooperDPS**: 66.5
- **m_TrooperType**: TROOPER_MEDIC
- **m_mapBoundAbilities**:
  - **ESlot_Signature_2**: ability_medic_trooper_heal
- **m_MedicHealActiveParticle**: resource_name:"particles/trooper/trooper_medic_chargeup.vpcf"
- **m_flModelScale**: 1.1

---

# NPC: super_trooper_melee

- **m_WeaponInfo**:
  - **m_Spread**: 0.5
  - **m_StandingSpread**: 1.5
  - **m_flScatterYawScale**: 1
  - **m_flShootingUpSpreadPenalty**: 2
  - **m_flZoomMoveSpeedPercent**: 0.7
  - **m_flShootMoveSpeedPercent**: 0.7
  - **m_flHorizontalPunch**: 0
  - **m_flVerticalPunch**: 0
  - **m_flRecoilRecoverySpeed**: 10.0
  - **m_VerticallRecoil**:
    - **m_Range**:
      - -0.2
      - 0.2
    - **m_flBurstSlope**: 0.0
    - **m_flBurstExponent**: 0.0
    - **m_flBurstConstant**: 0.0
  - **m_HorizontalRecoil**:
    - **m_Range**:
      - -0.1
      - 0.1
    - **m_flBurstExponent**: 0.0
  - **m_flRecoilSpeed**: 1
  - **m_flZoomFOV**: 40.0
  - **m_flDamageFalloffStartRange**: 600
  - **m_flDamageFalloffEndRange**: 1400
  - **m_flRange**: 1400
  - **m_flBulletLifetime**: 2
  - **m_flDamageFalloffEndScale**: 0.3
  - **m_flDamageFalloffBias**: 0.5
  - **m_iBullets**: 1
  - **m_flCycleTime**: 1.03
  - **m_reloadDuration**: 1.8
  - **m_iClipSize**: -1
  - **m_iBurstShotCount**: 1
  - **m_flBurstShotCooldown**: 0
  - **m_flBulletGravityScale**: 0.0
  - **m_flBulletRadius**: 3
  - **m_flBulletDrag**: 1
  - **m_flBulletDragBias**: 0.5
  - **m_flBulletReflectScale**: 0
  - **m_flBulletReflectAmount**: 1
  - **m_flBulletInheritShooterVelocityScale**: 0
  - **m_szBulletTravelTracerParticle**: resource_name:"particles/weapon_fx/trooper/trooper_bullet_travel.vpcf"
  - **m_szMuzzleFlashEffectName**: resource_name:"particles/dev/bullet_debug_muzzle_flash.vpcf"
  - **m_strShootSound**: soundevent:"TrooperRifle.Fire"
  - **m_strBulletWhizSound**: soundevent:"Base.Bullet.Whizby"
  - **m_BulletSpeedCurve**:
    - **m_spline**:
      | x | y | m_flSlopeIncoming | m_flSlopeOutgoing |
      | --- | --- | --- | --- |
      | 0.0 | 12000.0 | 0.0 | 0.0 |
      | 100.0 | 12000.0 | 0.0 | 0.0 |
    - **m_tangents**:
      | m_nIncomingTangent | m_nOutgoingTangent |
      | --- | --- |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
    - **m_vDomainMins**:
      - 0.0
      - 1.0
    - **m_vDomainMaxs**:
      - 100.0
      - 12000.0
  - **m_mapImpactEffects**:
    - **default**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Default.BulletImpact"
    - **flesh**:
      - **m_strDecal**: 
      - **m_strParticle**: resource_name:"particles/blood_impact/blood_impact_red_01.vpcf"
      - **m_strSound**: soundevent:"Flesh.BulletImpact"
    - **concrete**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Concrete.BulletImpact"
    - **solidmetal**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"SolidMetal.BulletImpact"
    - **portals**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Player.HitInvuln"
  - **m_flCritBonusStart**: 1.15
  - **m_flCritBonusEnd**: 1.35
  - **m_flCritBonusStartRange**: 500.0
  - **m_flCritBonusEndRange**: 1500.0
  - **m_flCritBonusAgainstNPCs**: 0.25
  - **m_flShootSpreadPenaltyPerShot**: 0.0
  - **m_flShootSpreadPenaltyDecayDelay**: 0.0
  - **m_flShootSpreadPenaltyDecay**: 2.0
  - **m_flRecoilShotIndexRecoveryTimeFactor**: 0.25
  - **m_bCanZoom**: True
  - **m_strWeaponImpactEffect**: resource_name:"particles/weapon_fx/default_tracer_impact.vpcf"
  - **m_flReloadMoveSpeed**: 236.22
  - **m_strLocalPlayerBulletImpactSound**: soundevent:"Player.Bullet.Impact.Trooper"
  - **m_NpcAimingSpread**:
    - 0.2
    - 0.8
  - **m_flBulletDamage**: 61.8
- **_base**: trooper_melee
- **_class**: npc_super_trooper
- **m_sModelName**: resource_name:"models/npc/trooper/super_trooper_melee.vmdl"
- **m_nMaxHealth**: 400
- **m_flSightRangePlayers**: 700.0
- **m_flSightRangeNPCs**: 1600.0
- **m_hFootstepSounds**: trooper
- **m_flTrooperDamageResistPct**: 55.0
- **m_flT1BossDamageResistPct**: 35.0
- **m_flT2BossDamageResistPct**: 20.0
- **m_flShieldDamageResistPct**: 80.0
- **m_flNearDeathDuration**: 1.0
- **m_flWalkSpeed**: 320
- **m_flRunSpeed**: 433
- **m_flAcceleration**: 200
- **m_flMeleeDamage**: 80.0
- **m_flMeleeAttemptRange**: 120
- **m_flMeleeHitRange**: 120
- **m_flMeleeDuration**: 1.0
- **m_flAttackT1BossMaxRange**: 540
- **m_flAttackTrooperMaxRange**: 700
- **m_BossAttackParticle**: resource_name:"particles/weapon_fx/trooper/trooper_bullet_bonus_dmg.vpcf"
- **m_sDefaultMaterialGroupName**: Friendly
- **m_sEnemyMaterialGroupName**: Enemy
- **m_flMeleeChargeRange**: 1000.0
- **m_flHealthBarOffset**: 76.0
- **m_flHealthBarOffsetDucking**: 40
- **m_DeathParticle**: resource_name:"particles/trooper/trooper_death_sn.vpcf"
- **m_DeathSound**: soundevent:"Trooper.Death"
- **m_MeleeHitSound**: soundevent:"Trooper.Melee.Damage.Hit"
- **m_MeleeHitPlayerSound**: soundevent:"Player.Damage.Melee.Trooper.Impact"
- **m_HealthBarParticle**: resource_name:"particles/npc/npc_healthbar.vpcf"
- **m_sHealthBarAttachment**: head_fx
- **m_HealthBarColorFriend**:
  - 255
  - 239
  - 215
- **m_HealthBarColorEnemy**:
  - 230
  - 25
  - 25
- **m_HealthBarColorTeam1**:
  - 231
  - 182
  - 89
- **m_HealthBarColorTeam2**:
  - 91
  - 121
  - 230
- **m_HealthBarColorTeamNeutral**:
  - 0
  - 125
  - 125
- **m_MeleeSwingParticle**: resource_name:"particles/npc/npc_melee_swing.vpcf"
- **m_MeleeActivateParticle**: resource_name:"particles/npc/npc_melee_activate.vpcf"
- **m_MeleeAnimName**: b_melee
- **m_LastHitParticle**: resource_name:"particles/generic/last_hit.vpcf"
- **m_strLastHitSound**: soundevent:"LastHit.Default"
- **m_bPlayLastHitSound**: True
- **m_NearDeathModifier**:
  - **subclass**:
    - **_class**: modifier_near_death_fx
    - **_my_subclass_name**: modifier_near_death_fx
    - **m_EnemyNearDeathParticle**: resource_name:"particles/status_fx/status_fx_last_hit.vpcf"
    - **m_FriendlyNearDeathParticle**: resource_name:"particles/status_fx/status_fx_last_hit_friend.vpcf"
    - **m_sSelfDestructStart**: soundevent:"Trooper.SelfDestruct_Start"
    - **m_sSelfDestructEnd**: soundevent:"Trooper.SelfDestruct_Exp"
- **m_TargetingLaserParticle**: resource_name:"particles/weapon_fx/trooper_laser_target.vpcf"
- **m_TargetingEyeFlashParticle**: resource_name:"particles/enemy_targeting_indicator.vpcf"
- **m_sCelebrationSound**: soundevent:"Trooper.Objective.Win.Cheer"
- **m_flBarrackGuardianDamageResistPct**: 67.5
- **m_sTeam1MaterialGroupName**: Amber
- **m_sTeam2MaterialGroupName**: Sapphire
- **m_flT1BossDPS**: 83.6
- **m_flT2BossDPS**: 209.0
- **m_flT3BossDPS**: 209.0
- **m_flGeneratorBossDPS**: 41.8
- **m_flBarrackBossDPS**: 209.0
- **m_flPlayerDPS**: 42.0
- **m_flTrooperDPS**: 66.5
- **m_TrooperType**: TROOPER_MELEE
- **m_flModelScale**: 1.1

---

# NPC: trooper_melee

- **m_WeaponInfo**:
  - **m_Spread**: 0.5
  - **m_StandingSpread**: 1.5
  - **m_flScatterYawScale**: 1
  - **m_flShootingUpSpreadPenalty**: 2
  - **m_flZoomMoveSpeedPercent**: 0.7
  - **m_flShootMoveSpeedPercent**: 0.7
  - **m_flHorizontalPunch**: 0
  - **m_flVerticalPunch**: 0
  - **m_flRecoilRecoverySpeed**: 10.0
  - **m_VerticallRecoil**:
    - **m_Range**:
      - -0.2
      - 0.2
    - **m_flBurstSlope**: 0.0
    - **m_flBurstExponent**: 0.0
    - **m_flBurstConstant**: 0.0
  - **m_HorizontalRecoil**:
    - **m_Range**:
      - -0.1
      - 0.1
    - **m_flBurstExponent**: 0.0
  - **m_flRecoilSpeed**: 1
  - **m_flZoomFOV**: 40.0
  - **m_flDamageFalloffStartRange**: 600
  - **m_flDamageFalloffEndRange**: 1400
  - **m_flRange**: 1400
  - **m_flBulletLifetime**: 2
  - **m_flDamageFalloffEndScale**: 0.3
  - **m_flDamageFalloffBias**: 0.5
  - **m_iBullets**: 1
  - **m_flCycleTime**: 1.03
  - **m_reloadDuration**: 1.8
  - **m_iClipSize**: -1
  - **m_iBurstShotCount**: 1
  - **m_flBurstShotCooldown**: 0
  - **m_flBulletGravityScale**: 0.0
  - **m_flBulletRadius**: 3
  - **m_flBulletDrag**: 1
  - **m_flBulletDragBias**: 0.5
  - **m_flBulletReflectScale**: 0
  - **m_flBulletReflectAmount**: 1
  - **m_flBulletInheritShooterVelocityScale**: 0
  - **m_szBulletTravelTracerParticle**: resource_name:"particles/weapon_fx/trooper/trooper_bullet_travel.vpcf"
  - **m_szMuzzleFlashEffectName**: resource_name:"particles/dev/bullet_debug_muzzle_flash.vpcf"
  - **m_strShootSound**: soundevent:"TrooperRifle.Fire"
  - **m_strBulletWhizSound**: soundevent:"Base.Bullet.Whizby"
  - **m_BulletSpeedCurve**:
    - **m_spline**:
      | x | y | m_flSlopeIncoming | m_flSlopeOutgoing |
      | --- | --- | --- | --- |
      | 0.0 | 12000.0 | 0.0 | 0.0 |
      | 100.0 | 12000.0 | 0.0 | 0.0 |
    - **m_tangents**:
      | m_nIncomingTangent | m_nOutgoingTangent |
      | --- | --- |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
    - **m_vDomainMins**:
      - 0.0
      - 1.0
    - **m_vDomainMaxs**:
      - 100.0
      - 12000.0
  - **m_mapImpactEffects**:
    - **default**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Default.BulletImpact"
    - **flesh**:
      - **m_strDecal**: 
      - **m_strParticle**: resource_name:"particles/blood_impact/blood_impact_red_01.vpcf"
      - **m_strSound**: soundevent:"Flesh.BulletImpact"
    - **concrete**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Concrete.BulletImpact"
    - **solidmetal**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"SolidMetal.BulletImpact"
    - **portals**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Player.HitInvuln"
  - **m_flCritBonusStart**: 1.15
  - **m_flCritBonusEnd**: 1.35
  - **m_flCritBonusStartRange**: 500.0
  - **m_flCritBonusEndRange**: 1500.0
  - **m_flCritBonusAgainstNPCs**: 0.25
  - **m_flShootSpreadPenaltyPerShot**: 0.0
  - **m_flShootSpreadPenaltyDecayDelay**: 0.0
  - **m_flShootSpreadPenaltyDecay**: 2.0
  - **m_flRecoilShotIndexRecoveryTimeFactor**: 0.25
  - **m_bCanZoom**: True
  - **m_strWeaponImpactEffect**: resource_name:"particles/weapon_fx/default_tracer_impact.vpcf"
  - **m_flReloadMoveSpeed**: 236.22
  - **m_strLocalPlayerBulletImpactSound**: soundevent:"Player.Bullet.Impact.Trooper"
  - **m_NpcAimingSpread**:
    - 0.2
    - 0.8
  - **m_flBulletDamage**: 61.8
- **_base**: trooper_base
- **_class**: npc_trooper
- **m_sModelName**: resource_name:"models/npc/trooper/trooper_melee.vmdl"
- **m_nMaxHealth**: 400
- **m_flSightRangePlayers**: 700.0
- **m_flSightRangeNPCs**: 1600.0
- **m_hFootstepSounds**: trooper
- **m_flTrooperDamageResistPct**: 25.0
- **m_flT1BossDamageResistPct**: 35.0
- **m_flT2BossDamageResistPct**: 20.0
- **m_flShieldDamageResistPct**: 80.0
- **m_flNearDeathDuration**: 1.0
- **m_flWalkSpeed**: 320
- **m_flRunSpeed**: 433
- **m_flAcceleration**: 200
- **m_flMeleeDamage**: 80.0
- **m_flMeleeAttemptRange**: 120
- **m_flMeleeHitRange**: 120
- **m_flMeleeDuration**: 1.0
- **m_flAttackT1BossMaxRange**: 540
- **m_flAttackTrooperMaxRange**: 700
- **m_BossAttackParticle**: resource_name:"particles/weapon_fx/trooper/trooper_bullet_bonus_dmg.vpcf"
- **m_sDefaultMaterialGroupName**: Friendly
- **m_sEnemyMaterialGroupName**: Enemy
- **m_flMeleeChargeRange**: 1000.0
- **m_flHealthBarOffset**: 76.0
- **m_flHealthBarOffsetDucking**: 40
- **m_DeathParticle**: resource_name:"particles/trooper/trooper_death_sn.vpcf"
- **m_DeathSound**: soundevent:"Trooper.Death"
- **m_MeleeHitSound**: soundevent:"Trooper.Melee.Damage.Hit"
- **m_MeleeHitPlayerSound**: soundevent:"Player.Damage.Melee.Trooper.Impact"
- **m_HealthBarParticle**: resource_name:"particles/npc/npc_healthbar.vpcf"
- **m_sHealthBarAttachment**: head_fx
- **m_HealthBarColorFriend**:
  - 255
  - 239
  - 215
- **m_HealthBarColorEnemy**:
  - 230
  - 25
  - 25
- **m_HealthBarColorTeam1**:
  - 231
  - 182
  - 89
- **m_HealthBarColorTeam2**:
  - 91
  - 121
  - 230
- **m_HealthBarColorTeamNeutral**:
  - 0
  - 125
  - 125
- **m_MeleeSwingParticle**: resource_name:"particles/npc/npc_melee_swing.vpcf"
- **m_MeleeActivateParticle**: resource_name:"particles/npc/npc_melee_activate.vpcf"
- **m_MeleeAnimName**: b_melee
- **m_LastHitParticle**: resource_name:"particles/generic/last_hit.vpcf"
- **m_strLastHitSound**: soundevent:"LastHit.Default"
- **m_bPlayLastHitSound**: True
- **m_NearDeathModifier**:
  - **subclass**:
    - **_class**: modifier_near_death_fx
    - **_my_subclass_name**: modifier_near_death_fx
    - **m_EnemyNearDeathParticle**: resource_name:"particles/status_fx/status_fx_last_hit.vpcf"
    - **m_FriendlyNearDeathParticle**: resource_name:"particles/status_fx/status_fx_last_hit_friend.vpcf"
    - **m_sSelfDestructStart**: soundevent:"Trooper.SelfDestruct_Start"
    - **m_sSelfDestructEnd**: soundevent:"Trooper.SelfDestruct_Exp"
- **m_TargetingLaserParticle**: resource_name:"particles/weapon_fx/trooper_laser_target.vpcf"
- **m_TargetingEyeFlashParticle**: resource_name:"particles/enemy_targeting_indicator.vpcf"
- **m_sCelebrationSound**: soundevent:"Trooper.Objective.Win.Cheer"
- **m_flBarrackGuardianDamageResistPct**: 67.5
- **m_sTeam1MaterialGroupName**: Amber
- **m_sTeam2MaterialGroupName**: Sapphire
- **m_flT1BossDPS**: 36.0
- **m_flT2BossDPS**: 80.0
- **m_flT3BossDPS**: 80.0
- **m_flGeneratorBossDPS**: 22
- **m_flBarrackBossDPS**: 80.0
- **m_flPlayerDPS**: 28.0
- **m_flTrooperDPS**: 35.0
- **m_TrooperType**: TROOPER_MELEE

---

# NPC: alt_trooper_melee

- **m_WeaponInfo**:
  - **m_Spread**: 0.5
  - **m_StandingSpread**: 1.5
  - **m_flScatterYawScale**: 1
  - **m_flShootingUpSpreadPenalty**: 2
  - **m_flZoomMoveSpeedPercent**: 0.7
  - **m_flShootMoveSpeedPercent**: 0.7
  - **m_flHorizontalPunch**: 0
  - **m_flVerticalPunch**: 0
  - **m_flRecoilRecoverySpeed**: 10.0
  - **m_VerticallRecoil**:
    - **m_Range**:
      - -0.2
      - 0.2
    - **m_flBurstSlope**: 0.0
    - **m_flBurstExponent**: 0.0
    - **m_flBurstConstant**: 0.0
  - **m_HorizontalRecoil**:
    - **m_Range**:
      - -0.1
      - 0.1
    - **m_flBurstExponent**: 0.0
  - **m_flRecoilSpeed**: 1
  - **m_flZoomFOV**: 40.0
  - **m_flDamageFalloffStartRange**: 600
  - **m_flDamageFalloffEndRange**: 1400
  - **m_flRange**: 1400
  - **m_flBulletLifetime**: 2
  - **m_flDamageFalloffEndScale**: 0.3
  - **m_flDamageFalloffBias**: 0.5
  - **m_iBullets**: 1
  - **m_flCycleTime**: 1.03
  - **m_reloadDuration**: 1.8
  - **m_iClipSize**: -1
  - **m_iBurstShotCount**: 1
  - **m_flBurstShotCooldown**: 0
  - **m_flBulletGravityScale**: 0.0
  - **m_flBulletRadius**: 3
  - **m_flBulletDrag**: 1
  - **m_flBulletDragBias**: 0.5
  - **m_flBulletReflectScale**: 0
  - **m_flBulletReflectAmount**: 1
  - **m_flBulletInheritShooterVelocityScale**: 0
  - **m_szBulletTravelTracerParticle**: resource_name:"particles/weapon_fx/trooper/trooper_bullet_travel.vpcf"
  - **m_szMuzzleFlashEffectName**: resource_name:"particles/dev/bullet_debug_muzzle_flash.vpcf"
  - **m_strShootSound**: soundevent:"TrooperRifle.Fire"
  - **m_strBulletWhizSound**: soundevent:"Base.Bullet.Whizby"
  - **m_BulletSpeedCurve**:
    - **m_spline**:
      | x | y | m_flSlopeIncoming | m_flSlopeOutgoing |
      | --- | --- | --- | --- |
      | 0.0 | 12000.0 | 0.0 | 0.0 |
      | 100.0 | 12000.0 | 0.0 | 0.0 |
    - **m_tangents**:
      | m_nIncomingTangent | m_nOutgoingTangent |
      | --- | --- |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
    - **m_vDomainMins**:
      - 0.0
      - 1.0
    - **m_vDomainMaxs**:
      - 100.0
      - 12000.0
  - **m_mapImpactEffects**:
    - **default**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Default.BulletImpact"
    - **flesh**:
      - **m_strDecal**: 
      - **m_strParticle**: resource_name:"particles/blood_impact/blood_impact_red_01.vpcf"
      - **m_strSound**: soundevent:"Flesh.BulletImpact"
    - **concrete**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Concrete.BulletImpact"
    - **solidmetal**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"SolidMetal.BulletImpact"
    - **portals**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Player.HitInvuln"
  - **m_flCritBonusStart**: 1.15
  - **m_flCritBonusEnd**: 1.35
  - **m_flCritBonusStartRange**: 500.0
  - **m_flCritBonusEndRange**: 1500.0
  - **m_flCritBonusAgainstNPCs**: 0.25
  - **m_flShootSpreadPenaltyPerShot**: 0.0
  - **m_flShootSpreadPenaltyDecayDelay**: 0.0
  - **m_flShootSpreadPenaltyDecay**: 2.0
  - **m_flRecoilShotIndexRecoveryTimeFactor**: 0.25
  - **m_bCanZoom**: True
  - **m_strWeaponImpactEffect**: resource_name:"particles/weapon_fx/default_tracer_impact.vpcf"
  - **m_flReloadMoveSpeed**: 236.22
  - **m_strLocalPlayerBulletImpactSound**: soundevent:"Player.Bullet.Impact.Trooper"
  - **m_NpcAimingSpread**:
    - 0.2
    - 0.8
  - **m_flBulletDamage**: 61.8
- **_base**: trooper_melee
- **_class**: npc_trooper
- **m_sModelName**: resource_name:"models/npc/trooper/trooper_melee.vmdl"
- **m_nMaxHealth**: 400
- **m_flSightRangePlayers**: 700.0
- **m_flSightRangeNPCs**: 1600.0
- **m_hFootstepSounds**: trooper
- **m_flTrooperDamageResistPct**: 25.0
- **m_flT1BossDamageResistPct**: 35.0
- **m_flT2BossDamageResistPct**: 20.0
- **m_flShieldDamageResistPct**: 80.0
- **m_flNearDeathDuration**: 1.0
- **m_flWalkSpeed**: 320
- **m_flRunSpeed**: 433
- **m_flAcceleration**: 200
- **m_flMeleeDamage**: 80.0
- **m_flMeleeAttemptRange**: 120
- **m_flMeleeHitRange**: 120
- **m_flMeleeDuration**: 1.0
- **m_flAttackT1BossMaxRange**: 540
- **m_flAttackTrooperMaxRange**: 700
- **m_BossAttackParticle**: resource_name:"particles/weapon_fx/trooper/trooper_bullet_bonus_dmg.vpcf"
- **m_sDefaultMaterialGroupName**: Friendly
- **m_sEnemyMaterialGroupName**: Enemy
- **m_flMeleeChargeRange**: 1000.0
- **m_flHealthBarOffset**: 76.0
- **m_flHealthBarOffsetDucking**: 40
- **m_DeathParticle**: resource_name:"particles/trooper/trooper_death_sn.vpcf"
- **m_DeathSound**: soundevent:"Trooper.Death"
- **m_MeleeHitSound**: soundevent:"Trooper.Melee.Damage.Hit"
- **m_MeleeHitPlayerSound**: soundevent:"Player.Damage.Melee.Trooper.Impact"
- **m_HealthBarParticle**: resource_name:"particles/npc/npc_healthbar.vpcf"
- **m_sHealthBarAttachment**: head_fx
- **m_HealthBarColorFriend**:
  - 255
  - 239
  - 215
- **m_HealthBarColorEnemy**:
  - 230
  - 25
  - 25
- **m_HealthBarColorTeam1**:
  - 231
  - 182
  - 89
- **m_HealthBarColorTeam2**:
  - 91
  - 121
  - 230
- **m_HealthBarColorTeamNeutral**:
  - 0
  - 125
  - 125
- **m_MeleeSwingParticle**: resource_name:"particles/npc/npc_melee_swing.vpcf"
- **m_MeleeActivateParticle**: resource_name:"particles/npc/npc_melee_activate.vpcf"
- **m_MeleeAnimName**: b_melee
- **m_LastHitParticle**: resource_name:"particles/generic/last_hit.vpcf"
- **m_strLastHitSound**: soundevent:"LastHit.Default"
- **m_bPlayLastHitSound**: True
- **m_NearDeathModifier**:
  - **subclass**:
    - **_class**: modifier_near_death_fx
    - **_my_subclass_name**: modifier_near_death_fx
    - **m_EnemyNearDeathParticle**: resource_name:"particles/status_fx/status_fx_last_hit.vpcf"
    - **m_FriendlyNearDeathParticle**: resource_name:"particles/status_fx/status_fx_last_hit_friend.vpcf"
    - **m_sSelfDestructStart**: soundevent:"Trooper.SelfDestruct_Start"
    - **m_sSelfDestructEnd**: soundevent:"Trooper.SelfDestruct_Exp"
- **m_TargetingLaserParticle**: resource_name:"particles/weapon_fx/trooper_laser_target.vpcf"
- **m_TargetingEyeFlashParticle**: resource_name:"particles/enemy_targeting_indicator.vpcf"
- **m_sCelebrationSound**: soundevent:"Trooper.Objective.Win.Cheer"
- **m_flBarrackGuardianDamageResistPct**: 67.5
- **m_sTeam1MaterialGroupName**: Amber
- **m_sTeam2MaterialGroupName**: Sapphire
- **m_flT1BossDPS**: 36.0
- **m_flT2BossDPS**: 80.0
- **m_flT3BossDPS**: 80.0
- **m_flGeneratorBossDPS**: 22
- **m_flBarrackBossDPS**: 80.0
- **m_flPlayerDPS**: 28.0
- **m_flTrooperDPS**: 35.0
- **m_TrooperType**: TROOPER_MELEE

---

# NPC: trooper_nano

- **m_WeaponInfo**:
  - **m_Spread**: 0.5
  - **m_StandingSpread**: 1.5
  - **m_flScatterYawScale**: 1
  - **m_flShootingUpSpreadPenalty**: 2
  - **m_flZoomMoveSpeedPercent**: 0.7
  - **m_flShootMoveSpeedPercent**: 0.7
  - **m_flHorizontalPunch**: 0
  - **m_flVerticalPunch**: 0
  - **m_flRecoilRecoverySpeed**: 10.0
  - **m_VerticallRecoil**:
    - **m_Range**:
      - -0.2
      - 0.2
    - **m_flBurstSlope**: 0.0
    - **m_flBurstExponent**: 0.0
    - **m_flBurstConstant**: 0.0
  - **m_HorizontalRecoil**:
    - **m_Range**:
      - -0.1
      - 0.1
    - **m_flBurstExponent**: 0.0
  - **m_flRecoilSpeed**: 1
  - **m_flZoomFOV**: 40.0
  - **m_flDamageFalloffStartRange**: 600
  - **m_flDamageFalloffEndRange**: 1000
  - **m_flRange**: 1000
  - **m_flBulletLifetime**: 2
  - **m_flDamageFalloffEndScale**: 0.3
  - **m_flDamageFalloffBias**: 0.5
  - **m_iBullets**: 1
  - **m_flCycleTime**: 0.25
  - **m_reloadDuration**: 1.2
  - **m_iClipSize**: 12
  - **m_iBurstShotCount**: 1
  - **m_flBurstShotCooldown**: 0
  - **m_flBulletGravityScale**: 0.0
  - **m_flBulletRadius**: 3
  - **m_flBulletDrag**: 1
  - **m_flBulletDragBias**: 0.5
  - **m_flBulletReflectScale**: 0
  - **m_flBulletReflectAmount**: 1
  - **m_flBulletInheritShooterVelocityScale**: 0
  - **m_szBulletTravelTracerParticle**: resource_name:"particles/weapon_fx/trooper/trooper_bullet_travel.vpcf"
  - **m_szMuzzleFlashEffectName**: resource_name:"particles/dev/bullet_debug_muzzle_flash.vpcf"
  - **m_strShootSound**: soundevent:"TrooperRifle.Fire"
  - **m_strBulletWhizSound**: soundevent:"Base.Bullet.Whizby"
  - **m_BulletSpeedCurve**:
    - **m_spline**:
      | x | y | m_flSlopeIncoming | m_flSlopeOutgoing |
      | --- | --- | --- | --- |
      | 0.0 | 12000.0 | 0.0 | 0.0 |
      | 100.0 | 12000.0 | 0.0 | 0.0 |
    - **m_tangents**:
      | m_nIncomingTangent | m_nOutgoingTangent |
      | --- | --- |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
    - **m_vDomainMins**:
      - 0.0
      - 1.0
    - **m_vDomainMaxs**:
      - 100.0
      - 12000.0
  - **m_mapImpactEffects**:
    - **default**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Default.BulletImpact"
    - **flesh**:
      - **m_strDecal**: 
      - **m_strParticle**: resource_name:"particles/blood_impact/blood_impact_red_01.vpcf"
      - **m_strSound**: soundevent:"Flesh.BulletImpact"
    - **concrete**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Concrete.BulletImpact"
    - **solidmetal**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"SolidMetal.BulletImpact"
    - **portals**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Player.HitInvuln"
  - **m_flCritBonusStart**: 1.15
  - **m_flCritBonusEnd**: 1.35
  - **m_flCritBonusStartRange**: 500.0
  - **m_flCritBonusEndRange**: 1500.0
  - **m_flCritBonusAgainstNPCs**: 0.25
  - **m_flShootSpreadPenaltyPerShot**: 0.0
  - **m_flShootSpreadPenaltyDecayDelay**: 0.0
  - **m_flShootSpreadPenaltyDecay**: 2.0
  - **m_flRecoilShotIndexRecoveryTimeFactor**: 0.25
  - **m_bCanZoom**: True
  - **m_strWeaponImpactEffect**: resource_name:"particles/weapon_fx/default_tracer_impact.vpcf"
  - **m_flReloadMoveSpeed**: 236.22
  - **m_strLocalPlayerBulletImpactSound**: soundevent:"Player.Bullet.Impact.Trooper"
  - **m_NpcAimingSpread**:
    - 0.2
    - 0.8
  - **m_flBulletDamage**: 12.5
- **_base**: trooper_base
- **_class**: npc_trooper
- **m_sModelName**: resource_name:"models/npc/trooper/trooper_humanoid.vmdl"
- **m_nMaxHealth**: 300
- **m_flSightRangePlayers**: 700.0
- **m_flSightRangeNPCs**: 1600.0
- **m_hFootstepSounds**: trooper
- **m_flTrooperDamageResistPct**: 25.0
- **m_flT1BossDamageResistPct**: 0.0
- **m_flT2BossDamageResistPct**: 0.0
- **m_flShieldDamageResistPct**: 80.0
- **m_flNearDeathDuration**: 1.0
- **m_flWalkSpeed**: 240
- **m_flRunSpeed**: 433
- **m_flAcceleration**: 200
- **m_flMeleeDamage**: 25.0
- **m_flMeleeAttemptRange**: 100
- **m_flMeleeHitRange**: 100
- **m_flMeleeDuration**: 1.0
- **m_flAttackT1BossMaxRange**: 540
- **m_flAttackTrooperMaxRange**: 700
- **m_BossAttackParticle**: resource_name:"particles/weapon_fx/trooper/trooper_bullet_bonus_dmg.vpcf"
- **m_sDefaultMaterialGroupName**: Friendly
- **m_sEnemyMaterialGroupName**: Enemy
- **m_flMeleeChargeRange**: 0
- **m_flHealthBarOffset**: 76.0
- **m_flHealthBarOffsetDucking**: 40
- **m_DeathParticle**: resource_name:"particles/trooper/trooper_death_sn.vpcf"
- **m_DeathSound**: soundevent:"Trooper.Death"
- **m_MeleeHitSound**: soundevent:"Trooper.Melee.Damage.Hit"
- **m_MeleeHitPlayerSound**: soundevent:"Player.Damage.Melee.Trooper.Impact"
- **m_HealthBarParticle**: resource_name:"particles/npc/npc_healthbar.vpcf"
- **m_sHealthBarAttachment**: head_fx
- **m_HealthBarColorFriend**:
  - 255
  - 239
  - 215
- **m_HealthBarColorEnemy**:
  - 230
  - 25
  - 25
- **m_HealthBarColorTeam1**:
  - 231
  - 182
  - 89
- **m_HealthBarColorTeam2**:
  - 91
  - 121
  - 230
- **m_HealthBarColorTeamNeutral**:
  - 0
  - 125
  - 125
- **m_MeleeSwingParticle**: resource_name:"particles/abilities/melee_swing.vpcf"
- **m_MeleeActivateParticle**: resource_name:"particles/abilities/melee/melee_activate.vpcf"
- **m_MeleeAnimName**: b_melee
- **m_LastHitParticle**: resource_name:"particles/generic/last_hit.vpcf"
- **m_strLastHitSound**: soundevent:"LastHit.Default"
- **m_bPlayLastHitSound**: True
- **m_NearDeathModifier**:
  - **subclass**:
    - **_class**: modifier_near_death_fx
    - **_my_subclass_name**: modifier_near_death_fx
    - **m_EnemyNearDeathParticle**: resource_name:"particles/status_fx/status_fx_last_hit.vpcf"
    - **m_FriendlyNearDeathParticle**: resource_name:"particles/status_fx/status_fx_last_hit_friend.vpcf"
    - **m_sSelfDestructStart**: soundevent:"Trooper.SelfDestruct_Start"
    - **m_sSelfDestructEnd**: soundevent:"Trooper.SelfDestruct_Exp"
- **m_TargetingLaserParticle**: resource_name:"particles/weapon_fx/trooper_laser_target.vpcf"
- **m_TargetingEyeFlashParticle**: resource_name:"particles/enemy_targeting_indicator.vpcf"
- **m_sCelebrationSound**: soundevent:"Trooper.Objective.Win.Cheer"
- **m_flBarrackGuardianDamageResistPct**: 67.5
- **m_sTeam1MaterialGroupName**: Amber
- **m_sTeam2MaterialGroupName**: Sapphire
- **m_flT1BossDPS**: 36.0
- **m_flT2BossDPS**: 80.0
- **m_flT3BossDPS**: 80.0
- **m_flGeneratorBossDPS**: 22
- **m_flBarrackBossDPS**: 80.0
- **m_flPlayerDPS**: 28.0
- **m_flTrooperDPS**: 35.0
- **m_TrooperType**: TROOPER_NANO_BASIC

---

# NPC: npc_boss_tier1

- **m_WeaponInfo**:
  - **m_Spread**: 0.5
  - **m_StandingSpread**: 1.5
  - **m_flScatterYawScale**: 1
  - **m_flShootingUpSpreadPenalty**: 0
  - **m_flZoomMoveSpeedPercent**: 0.7
  - **m_flShootMoveSpeedPercent**: 0.7
  - **m_flHorizontalPunch**: 0
  - **m_flVerticalPunch**: 0
  - **m_flRecoilRecoverySpeed**: 10.0
  - **m_VerticallRecoil**:
    - **m_Range**:
      - -0.2
      - 0.2
    - **m_flBurstSlope**: 0.0
    - **m_flBurstExponent**: 0.0
    - **m_flBurstConstant**: 0.0
  - **m_HorizontalRecoil**:
    - **m_Range**:
      - -0.1
      - 0.1
    - **m_flBurstExponent**: 0.0
  - **m_flRecoilSpeed**: 1
  - **m_flZoomFOV**: 40.0
  - **m_flDamageFalloffStartRange**: 2000
  - **m_flDamageFalloffEndRange**: 2000
  - **m_flRange**: 2000
  - **m_flBulletLifetime**: 2
  - **m_flDamageFalloffEndScale**: 0.3
  - **m_flDamageFalloffBias**: 0.5
  - **m_iBullets**: 1
  - **m_flCycleTime**: 0.2
  - **m_reloadDuration**: 1
  - **m_iClipSize**: -1
  - **m_iBurstShotCount**: 1
  - **m_flBurstShotCooldown**: 0
  - **m_flBulletGravityScale**: 0
  - **m_flBulletRadius**: 12
  - **m_flBulletDrag**: 1
  - **m_flBulletDragBias**: 0.5
  - **m_flBulletReflectScale**: 0
  - **m_flBulletReflectAmount**: 1
  - **m_flBulletInheritShooterVelocityScale**: 0
  - **m_szBulletTravelTracerParticle**: resource_name:"particles/weapon_fx/trooper/trooper_bullet_travel.vpcf"
  - **m_szMuzzleFlashEffectName**: resource_name:"particles/weapon_fx/tier1boss/tier1boss_muzzle_flash.vpcf"
  - **m_strShootSound**: soundevent:"TrooperRifle.Fire"
  - **m_strBulletWhizSound**: soundevent:"Base.Bullet.Whizby"
  - **m_BulletSpeedCurve**:
    - **m_spline**:
      | x | y | m_flSlopeIncoming | m_flSlopeOutgoing |
      | --- | --- | --- | --- |
      | 0.0 | 12000.0 | 0.0 | 0.0 |
      | 100.0 | 12000.0 | 0.0 | 0.0 |
    - **m_tangents**:
      | m_nIncomingTangent | m_nOutgoingTangent |
      | --- | --- |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
    - **m_vDomainMins**:
      - 0.0
      - 1.0
    - **m_vDomainMaxs**:
      - 100.0
      - 12000.0
  - **m_mapImpactEffects**:
    - **default**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Guardian.Tier1.Wpn.Impact"
    - **flesh**:
      - **m_strDecal**: 
      - **m_strParticle**: resource_name:"particles/blood_impact/blood_impact_red_01.vpcf"
      - **m_strSound**: soundevent:"Flesh.BulletImpact"
    - **concrete**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Concrete.BulletImpact"
    - **solidmetal**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"SolidMetal.BulletImpact"
    - **portals**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Player.HitInvuln"
  - **m_flCritBonusStart**: 1.15
  - **m_flCritBonusEnd**: 1.35
  - **m_flCritBonusStartRange**: 500.0
  - **m_flCritBonusEndRange**: 1500.0
  - **m_flCritBonusAgainstNPCs**: 0.25
  - **m_flShootSpreadPenaltyPerShot**: 0.0
  - **m_flShootSpreadPenaltyDecayDelay**: 0.0
  - **m_flShootSpreadPenaltyDecay**: 2.0
  - **m_flRecoilShotIndexRecoveryTimeFactor**: 0.25
  - **m_bCanZoom**: True
  - **m_strWeaponImpactEffect**: resource_name:"particles/weapon_fx/tier1boss/tier1boss_tracer_impact.vpcf"
  - **m_flReloadMoveSpeed**: 236.22
  - **m_strLocalPlayerBulletImpactSound**: soundevent:"Player.Bullet.Impact.Trooper"
  - **m_NpcAimingSpread**: 0.2
  - **m_flBulletDamage**: 16
  - **m_flAutoReplenishClip**: 2
  - **m_flBulletRadiusVsWorld**: 1
- **_base**: trooper_base
- **_class**: npc_trooper_boss
- **m_sModelName**: resource_name:"models/npc/boss_tier_01_brazier_guardian/boss_tier_01_brazier_guardian.vmdl"
- **m_nMaxHealth**: 5500
- **m_flSightRangePlayers**: 1500.0
- **m_flSightRangeNPCs**: 1500.0
- **m_hFootstepSounds**: trooper
- **m_flTrooperDamageResistPct**: 25.0
- **m_flT1BossDamageResistPct**: 35.0
- **m_flT2BossDamageResistPct**: 20.0
- **m_flShieldDamageResistPct**: 80.0
- **m_flNearDeathDuration**: 1.0
- **m_flWalkSpeed**: 240
- **m_flRunSpeed**: 300
- **m_flAcceleration**: 200
- **m_flMeleeDamage**: 100.0
- **m_flMeleeAttemptRange**: 240
- **m_flMeleeHitRange**: 314.96
- **m_flMeleeDuration**: 1.0
- **m_flAttackT1BossMaxRange**: 540
- **m_flAttackTrooperMaxRange**: 700
- **m_BossAttackParticle**: resource_name:"particles/weapon_fx/trooper/trooper_bullet_bonus_dmg.vpcf"
- **m_sDefaultMaterialGroupName**: FriendlyBoss
- **m_sEnemyMaterialGroupName**: EnemyBoss
- **m_flMeleeChargeRange**: 0.0
- **m_flHealthBarOffset**: 260.0
- **m_flHealthBarOffsetDucking**: 200.0
- **m_DeathParticle**: resource_name:"particles/trooper/trooper_death_sn.vpcf"
- **m_DeathSound**: soundevent:"Trooper.Death"
- **m_MeleeHitSound**: soundevent:"Trooper.Melee.Damage.Hit"
- **m_MeleeHitPlayerSound**: soundevent:"Player.Damage.Melee.Trooper.Impact"
- **m_HealthBarParticle**: resource_name:""
- **m_sHealthBarAttachment**: head_fx
- **m_HealthBarColorFriend**:
  - 255
  - 239
  - 215
- **m_HealthBarColorEnemy**:
  - 230
  - 25
  - 25
- **m_HealthBarColorTeam1**:
  - 231
  - 182
  - 89
- **m_HealthBarColorTeam2**:
  - 91
  - 121
  - 230
- **m_HealthBarColorTeamNeutral**:
  - 0
  - 125
  - 125
- **m_MeleeSwingParticle**: resource_name:"particles/abilities/melee_swing.vpcf"
- **m_MeleeActivateParticle**: resource_name:"particles/abilities/melee/melee_activate.vpcf"
- **m_MeleeAnimName**: b_melee
- **m_LastHitParticle**: resource_name:"particles/generic/last_hit.vpcf"
- **m_strLastHitSound**: soundevent:"LastHit.Default"
- **m_bPlayLastHitSound**: True
- **m_NearDeathModifier**:
  - **subclass**:
    - **_class**: modifier_near_death_fx
    - **_my_subclass_name**: modifier_near_death_fx
    - **m_EnemyNearDeathParticle**: resource_name:"particles/status_fx/status_fx_last_hit.vpcf"
    - **m_FriendlyNearDeathParticle**: resource_name:"particles/status_fx/status_fx_last_hit_friend.vpcf"
    - **m_sSelfDestructStart**: soundevent:"Trooper.SelfDestruct_Start"
    - **m_sSelfDestructEnd**: soundevent:"Trooper.SelfDestruct_Exp"
- **m_TargetingLaserParticle**: resource_name:"particles/weapon_fx/trooper_laser_target.vpcf"
- **m_TargetingEyeFlashParticle**: resource_name:"particles/enemy_targeting_indicator.vpcf"
- **m_sCelebrationSound**: soundevent:"Trooper.Objective.Win.Cheer"
- **m_flBarrackGuardianDamageResistPct**: 67.5
- **m_sTeam1MaterialGroupName**: Amber
- **m_sTeam2MaterialGroupName**: Sapphire
- **m_flT1BossDPS**: 36.0
- **m_flT2BossDPS**: 80.0
- **m_flT3BossDPS**: 80.0
- **m_flGeneratorBossDPS**: 22
- **m_flBarrackBossDPS**: 80.0
- **m_flPlayerDPS**: 28.0
- **m_flTrooperDPS**: 35.0
- **m_flModelScale**: 1.0
- **m_navHull**: 1
- **m_flPhysicsImpulseMultiplier**: 0.0
- **m_flTurnRate**: 360
- **m_bMitigateDamageFromPlayers**: True
- **m_flBeamWeaponWidth**: 6.0
- **m_flBeamTurnRate**: 360
- **m_BeamWeaponParticle**: resource_name:"particles/weapon_fx/npc/t1_guardian_beam.vpcf"
- **m_BeamStartSound**: soundevent:"Guardian.Tier1.Wpn.Beam.Begin"
- **m_BeamStopSound**: soundevent:"Guardian.Tier1.Wpn.Beam.End"
- **m_BeamPointStartLoopSound**: soundevent:"Guardian.Tier1.Wpn.Point.Begin.Lp"
- **m_BeamPointEndLoopSound**: soundevent:"Guardian.Tier1.Wpn.Point.End.Lp"
- **m_BeamPointClosestLoopSound**: soundevent:"Guardian.Tier1.Wpn.Point.Closest.Lp"
- **m_flMinMeleeAttackTime**: 1.5
- **m_TrooperBossInvulnModifier**:
  - **subclass**:
    - **_my_subclass_name**: trooper_boss_invuln
    - **_class**: modifier_boss_invuln

---

# NPC: npc_barrack_boss

- **m_WeaponInfo**:
  - **m_Spread**: 0.5
  - **m_StandingSpread**: 1.5
  - **m_flScatterYawScale**: 1
  - **m_flShootingUpSpreadPenalty**: 0
  - **m_flZoomMoveSpeedPercent**: 0.7
  - **m_flShootMoveSpeedPercent**: 0.7
  - **m_flHorizontalPunch**: 0
  - **m_flVerticalPunch**: 0
  - **m_flRecoilRecoverySpeed**: 10.0
  - **m_VerticallRecoil**:
    - **m_Range**:
      - -0.2
      - 0.2
    - **m_flBurstSlope**: 0.0
    - **m_flBurstExponent**: 0.0
    - **m_flBurstConstant**: 0.0
  - **m_HorizontalRecoil**:
    - **m_Range**:
      - -0.1
      - 0.1
    - **m_flBurstExponent**: 0.0
  - **m_flRecoilSpeed**: 1
  - **m_flZoomFOV**: 40.0
  - **m_flDamageFalloffStartRange**: 2000
  - **m_flDamageFalloffEndRange**: 2000
  - **m_flRange**: 2000
  - **m_flBulletLifetime**: 2
  - **m_flDamageFalloffEndScale**: 0.3
  - **m_flDamageFalloffBias**: 0.5
  - **m_iBullets**: 1
  - **m_flCycleTime**: 0.2
  - **m_reloadDuration**: 1
  - **m_iClipSize**: -1
  - **m_iBurstShotCount**: 1
  - **m_flBurstShotCooldown**: 0
  - **m_flBulletGravityScale**: 0
  - **m_flBulletRadius**: 12
  - **m_flBulletDrag**: 1
  - **m_flBulletDragBias**: 0.5
  - **m_flBulletReflectScale**: 0
  - **m_flBulletReflectAmount**: 1
  - **m_flBulletInheritShooterVelocityScale**: 0
  - **m_szBulletTravelTracerParticle**: resource_name:"particles/weapon_fx/trooper/trooper_bullet_travel.vpcf"
  - **m_szMuzzleFlashEffectName**: resource_name:"particles/weapon_fx/tier1boss/tier1boss_muzzle_flash.vpcf"
  - **m_strShootSound**: soundevent:"TrooperRifle.Fire"
  - **m_strBulletWhizSound**: soundevent:"Base.Bullet.Whizby"
  - **m_BulletSpeedCurve**:
    - **m_spline**:
      | x | y | m_flSlopeIncoming | m_flSlopeOutgoing |
      | --- | --- | --- | --- |
      | 0.0 | 12000.0 | 0.0 | 0.0 |
      | 100.0 | 12000.0 | 0.0 | 0.0 |
    - **m_tangents**:
      | m_nIncomingTangent | m_nOutgoingTangent |
      | --- | --- |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
    - **m_vDomainMins**:
      - 0.0
      - 1.0
    - **m_vDomainMaxs**:
      - 100.0
      - 12000.0
  - **m_mapImpactEffects**:
    - **default**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Guardian.Tier1.Wpn.Impact"
    - **flesh**:
      - **m_strDecal**: 
      - **m_strParticle**: resource_name:"particles/blood_impact/blood_impact_red_01.vpcf"
      - **m_strSound**: soundevent:"Flesh.BulletImpact"
    - **concrete**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Concrete.BulletImpact"
    - **solidmetal**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"SolidMetal.BulletImpact"
    - **portals**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Player.HitInvuln"
  - **m_flCritBonusStart**: 1.15
  - **m_flCritBonusEnd**: 1.35
  - **m_flCritBonusStartRange**: 500.0
  - **m_flCritBonusEndRange**: 1500.0
  - **m_flCritBonusAgainstNPCs**: 0.25
  - **m_flShootSpreadPenaltyPerShot**: 0.0
  - **m_flShootSpreadPenaltyDecayDelay**: 0.0
  - **m_flShootSpreadPenaltyDecay**: 2.0
  - **m_flRecoilShotIndexRecoveryTimeFactor**: 0.25
  - **m_bCanZoom**: True
  - **m_strWeaponImpactEffect**: resource_name:"particles/weapon_fx/tier1boss/tier1boss_tracer_impact.vpcf"
  - **m_flReloadMoveSpeed**: 236.22
  - **m_strLocalPlayerBulletImpactSound**: soundevent:"Player.Bullet.Impact.Trooper"
  - **m_NpcAimingSpread**: 0.2
  - **m_flBulletDamage**: 8
  - **m_flAutoReplenishClip**: 2
  - **m_flBulletRadiusVsWorld**: 1
- **_base**: npc_boss_tier1
- **_class**: npc_trooper_boss
- **m_sModelName**: resource_name:"models/npc/boss_tier_01_brazier_guardian/boss_tier_01_brazier_guardian.vmdl"
- **m_nMaxHealth**: 4300
- **m_flSightRangePlayers**: 1500.0
- **m_flSightRangeNPCs**: 1500.0
- **m_hFootstepSounds**: trooper
- **m_flTrooperDamageResistPct**: 25.0
- **m_flT1BossDamageResistPct**: 35.0
- **m_flT2BossDamageResistPct**: 20.0
- **m_flShieldDamageResistPct**: 80.0
- **m_flNearDeathDuration**: 1.0
- **m_flWalkSpeed**: 240
- **m_flRunSpeed**: 300
- **m_flAcceleration**: 200
- **m_flMeleeDamage**: 100.0
- **m_flMeleeAttemptRange**: 240
- **m_flMeleeHitRange**: 314.96
- **m_flMeleeDuration**: 1.0
- **m_flAttackT1BossMaxRange**: 540
- **m_flAttackTrooperMaxRange**: 700
- **m_BossAttackParticle**: resource_name:"particles/weapon_fx/trooper/trooper_bullet_bonus_dmg.vpcf"
- **m_sDefaultMaterialGroupName**: FriendlyBoss
- **m_sEnemyMaterialGroupName**: EnemyBoss
- **m_flMeleeChargeRange**: 0.0
- **m_flHealthBarOffset**: 260.0
- **m_flHealthBarOffsetDucking**: 200.0
- **m_DeathParticle**: resource_name:"particles/trooper/trooper_death_sn.vpcf"
- **m_DeathSound**: soundevent:"Trooper.Death"
- **m_MeleeHitSound**: soundevent:"Trooper.Melee.Damage.Hit"
- **m_MeleeHitPlayerSound**: soundevent:"Player.Damage.Melee.Trooper.Impact"
- **m_HealthBarParticle**: resource_name:""
- **m_sHealthBarAttachment**: head_fx
- **m_HealthBarColorFriend**:
  - 255
  - 239
  - 215
- **m_HealthBarColorEnemy**:
  - 230
  - 25
  - 25
- **m_HealthBarColorTeam1**:
  - 231
  - 182
  - 89
- **m_HealthBarColorTeam2**:
  - 91
  - 121
  - 230
- **m_HealthBarColorTeamNeutral**:
  - 0
  - 125
  - 125
- **m_MeleeSwingParticle**: resource_name:"particles/abilities/melee_swing.vpcf"
- **m_MeleeActivateParticle**: resource_name:"particles/abilities/melee/melee_activate.vpcf"
- **m_MeleeAnimName**: b_melee
- **m_LastHitParticle**: resource_name:"particles/generic/last_hit.vpcf"
- **m_strLastHitSound**: soundevent:"LastHit.Default"
- **m_bPlayLastHitSound**: True
- **m_NearDeathModifier**:
  - **subclass**:
    - **_class**: modifier_near_death_fx
    - **_my_subclass_name**: modifier_near_death_fx
    - **m_EnemyNearDeathParticle**: resource_name:"particles/status_fx/status_fx_last_hit.vpcf"
    - **m_FriendlyNearDeathParticle**: resource_name:"particles/status_fx/status_fx_last_hit_friend.vpcf"
    - **m_sSelfDestructStart**: soundevent:"Trooper.SelfDestruct_Start"
    - **m_sSelfDestructEnd**: soundevent:"Trooper.SelfDestruct_Exp"
- **m_TargetingLaserParticle**: resource_name:"particles/weapon_fx/trooper_laser_target.vpcf"
- **m_TargetingEyeFlashParticle**: resource_name:"particles/enemy_targeting_indicator.vpcf"
- **m_sCelebrationSound**: soundevent:"Trooper.Objective.Win.Cheer"
- **m_flBarrackGuardianDamageResistPct**: 67.5
- **m_sTeam1MaterialGroupName**: Amber
- **m_sTeam2MaterialGroupName**: Sapphire
- **m_flT1BossDPS**: 36.0
- **m_flT2BossDPS**: 80.0
- **m_flT3BossDPS**: 80.0
- **m_flGeneratorBossDPS**: 22
- **m_flBarrackBossDPS**: 80.0
- **m_flPlayerDPS**: 28.0
- **m_flTrooperDPS**: 35.0
- **m_flModelScale**: 1.0
- **m_navHull**: 1
- **m_flPhysicsImpulseMultiplier**: 0.0
- **m_flTurnRate**: 360
- **m_bMitigateDamageFromPlayers**: False
- **m_flBeamWeaponWidth**: 6.0
- **m_flBeamTurnRate**: 360
- **m_BeamWeaponParticle**: resource_name:"particles/weapon_fx/npc/t1_guardian_beam.vpcf"
- **m_BeamStartSound**: soundevent:"Guardian.Tier1.Wpn.Beam.Begin"
- **m_BeamStopSound**: soundevent:"Guardian.Tier1.Wpn.Beam.End"
- **m_BeamPointStartLoopSound**: soundevent:"Guardian.Tier1.Wpn.Point.Begin.Lp"
- **m_BeamPointEndLoopSound**: soundevent:"Guardian.Tier1.Wpn.Point.End.Lp"
- **m_BeamPointClosestLoopSound**: soundevent:"Guardian.Tier1.Wpn.Point.Closest.Lp"
- **m_flMinMeleeAttackTime**: 1.5
- **m_TrooperBossInvulnModifier**:
  - **subclass**:
    - **_my_subclass_name**: trooper_boss_invuln
    - **_class**: modifier_boss_invuln
- **m_bBarracksGuardian**: True
- **m_flPlayerAutoAttackRange**: 950.0
- **m_BackdoorProtectionModifier**:
  - **subclass**:
    - **_class**: modifier_citadel_backdoor_protection
    - **_my_subclass_name**: barracks_backdoor_protection
    - **m_ShieldImpactParticle**: resource_name:"particles/generic/backdoor_protection_impact.vpcf"
    - **m_ShieldActiveParticle**: resource_name:"particles/generic/backdoor_protection_aura.vpcf"
    - **m_strActiveEffectConfigName**: tier1
    - **m_flHealthPerSecondRegen**: 65.0
    - **m_flBackdoorProtectionDamageMitigationFromPlayers**: 65.0
- **m_BackdoorBulletResistModifier**:
  - **subclass**:
    - **_class**: modifier_citadel_objective_bullet_resist
    - **_my_subclass_name**: modifier_citadel_objective_bullet_resist
    - **m_BulletResist**: 40
    - **m_BulletResistReductionPerHero**: 20
- **m_ObjectiveRegen**:
  - **subclass**:
    - **_class**: modifier_citadel_objective_regen
    - **_my_subclass_name**: modifier_citadel_objective_regen
    - **m_flOutOfCombatHealthRegen**: 130
    - **m_flOutOfCombatRegenDelay**: 60

---

# NPC: destroyable_building

- **_class**: destroyable_building
- **m_iMaxHealthFinal**: 13000
- **m_iMaxHealthGenerator**: 4000
- **m_ObjectiveRegen**:
  - **subclass**:
    - **_class**: modifier_citadel_objective_regen
    - **_my_subclass_name**: modifier_citadel_objective_regen
    - **m_flOutOfCombatHealthRegen**: 160
    - **m_flOutOfCombatRegenDelay**: 60
- **m_BackdoorBulletResistModifier**:
  - **subclass**:
    - **_class**: modifier_citadel_objective_bullet_resist
    - **_my_subclass_name**: modifier_citadel_objective_bullet_resist
    - **m_BulletResist**: 60
    - **m_BulletResistReductionPerHero**: 20

---

# NPC: alt_npc_boss_tier1

- **m_WeaponInfo**:
  - **m_Spread**: 0.5
  - **m_StandingSpread**: 1.5
  - **m_flScatterYawScale**: 1
  - **m_flShootingUpSpreadPenalty**: 0
  - **m_flZoomMoveSpeedPercent**: 0.7
  - **m_flShootMoveSpeedPercent**: 0.7
  - **m_flHorizontalPunch**: 0
  - **m_flVerticalPunch**: 0
  - **m_flRecoilRecoverySpeed**: 10.0
  - **m_VerticallRecoil**:
    - **m_Range**:
      - -0.2
      - 0.2
    - **m_flBurstSlope**: 0.0
    - **m_flBurstExponent**: 0.0
    - **m_flBurstConstant**: 0.0
  - **m_HorizontalRecoil**:
    - **m_Range**:
      - -0.1
      - 0.1
    - **m_flBurstExponent**: 0.0
  - **m_flRecoilSpeed**: 1
  - **m_flZoomFOV**: 40.0
  - **m_flDamageFalloffStartRange**: 2000
  - **m_flDamageFalloffEndRange**: 2000
  - **m_flRange**: 2000
  - **m_flBulletLifetime**: 2
  - **m_flDamageFalloffEndScale**: 0.3
  - **m_flDamageFalloffBias**: 0.5
  - **m_iBullets**: 1
  - **m_flCycleTime**: 0.2
  - **m_reloadDuration**: 1
  - **m_iClipSize**: -1
  - **m_iBurstShotCount**: 1
  - **m_flBurstShotCooldown**: 0
  - **m_flBulletGravityScale**: 0
  - **m_flBulletRadius**: 12
  - **m_flBulletDrag**: 1
  - **m_flBulletDragBias**: 0.5
  - **m_flBulletReflectScale**: 0
  - **m_flBulletReflectAmount**: 1
  - **m_flBulletInheritShooterVelocityScale**: 0
  - **m_szBulletTravelTracerParticle**: resource_name:"particles/weapon_fx/trooper/trooper_bullet_travel.vpcf"
  - **m_szMuzzleFlashEffectName**: resource_name:"particles/weapon_fx/tier1boss/tier1boss_muzzle_flash.vpcf"
  - **m_strShootSound**: soundevent:"TrooperRifle.Fire"
  - **m_strBulletWhizSound**: soundevent:"Base.Bullet.Whizby"
  - **m_BulletSpeedCurve**:
    - **m_spline**:
      | x | y | m_flSlopeIncoming | m_flSlopeOutgoing |
      | --- | --- | --- | --- |
      | 0.0 | 12000.0 | 0.0 | 0.0 |
      | 100.0 | 12000.0 | 0.0 | 0.0 |
    - **m_tangents**:
      | m_nIncomingTangent | m_nOutgoingTangent |
      | --- | --- |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
    - **m_vDomainMins**:
      - 0.0
      - 1.0
    - **m_vDomainMaxs**:
      - 100.0
      - 12000.0
  - **m_mapImpactEffects**:
    - **default**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Guardian.Tier1.Wpn.Impact"
    - **flesh**:
      - **m_strDecal**: 
      - **m_strParticle**: resource_name:"particles/blood_impact/blood_impact_red_01.vpcf"
      - **m_strSound**: soundevent:"Flesh.BulletImpact"
    - **concrete**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Concrete.BulletImpact"
    - **solidmetal**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"SolidMetal.BulletImpact"
    - **portals**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Player.HitInvuln"
  - **m_flCritBonusStart**: 1.15
  - **m_flCritBonusEnd**: 1.35
  - **m_flCritBonusStartRange**: 500.0
  - **m_flCritBonusEndRange**: 1500.0
  - **m_flCritBonusAgainstNPCs**: 0.25
  - **m_flShootSpreadPenaltyPerShot**: 0.0
  - **m_flShootSpreadPenaltyDecayDelay**: 0.0
  - **m_flShootSpreadPenaltyDecay**: 2.0
  - **m_flRecoilShotIndexRecoveryTimeFactor**: 0.25
  - **m_bCanZoom**: True
  - **m_strWeaponImpactEffect**: resource_name:"particles/weapon_fx/tier1boss/tier1boss_tracer_impact.vpcf"
  - **m_flReloadMoveSpeed**: 236.22
  - **m_strLocalPlayerBulletImpactSound**: soundevent:"Player.Bullet.Impact.Trooper"
  - **m_NpcAimingSpread**: 0.2
  - **m_flBulletDamage**: 16
  - **m_flAutoReplenishClip**: 2
  - **m_flBulletRadiusVsWorld**: 1
- **_base**: npc_boss_tier1
- **_class**: npc_trooper_boss
- **m_sModelName**: resource_name:"models/npc/boss_tier_01_brazier_guardian/boss_tier_01_brazier_guardian.vmdl"
- **m_nMaxHealth**: 5500
- **m_flSightRangePlayers**: 1500.0
- **m_flSightRangeNPCs**: 1500.0
- **m_hFootstepSounds**: trooper
- **m_flTrooperDamageResistPct**: 25.0
- **m_flT1BossDamageResistPct**: 35.0
- **m_flT2BossDamageResistPct**: 20.0
- **m_flShieldDamageResistPct**: 80.0
- **m_flNearDeathDuration**: 1.0
- **m_flWalkSpeed**: 240
- **m_flRunSpeed**: 300
- **m_flAcceleration**: 200
- **m_flMeleeDamage**: 100.0
- **m_flMeleeAttemptRange**: 240
- **m_flMeleeHitRange**: 314.96
- **m_flMeleeDuration**: 1.0
- **m_flAttackT1BossMaxRange**: 540
- **m_flAttackTrooperMaxRange**: 700
- **m_BossAttackParticle**: resource_name:"particles/weapon_fx/trooper/trooper_bullet_bonus_dmg.vpcf"
- **m_sDefaultMaterialGroupName**: FriendlyBoss
- **m_sEnemyMaterialGroupName**: EnemyBoss
- **m_flMeleeChargeRange**: 0.0
- **m_flHealthBarOffset**: 260.0
- **m_flHealthBarOffsetDucking**: 200.0
- **m_DeathParticle**: resource_name:"particles/trooper/trooper_death_sn.vpcf"
- **m_DeathSound**: soundevent:"Trooper.Death"
- **m_MeleeHitSound**: soundevent:"Trooper.Melee.Damage.Hit"
- **m_MeleeHitPlayerSound**: soundevent:"Player.Damage.Melee.Trooper.Impact"
- **m_HealthBarParticle**: resource_name:""
- **m_sHealthBarAttachment**: head_fx
- **m_HealthBarColorFriend**:
  - 255
  - 239
  - 215
- **m_HealthBarColorEnemy**:
  - 230
  - 25
  - 25
- **m_HealthBarColorTeam1**:
  - 231
  - 182
  - 89
- **m_HealthBarColorTeam2**:
  - 91
  - 121
  - 230
- **m_HealthBarColorTeamNeutral**:
  - 0
  - 125
  - 125
- **m_MeleeSwingParticle**: resource_name:"particles/abilities/melee_swing.vpcf"
- **m_MeleeActivateParticle**: resource_name:"particles/abilities/melee/melee_activate.vpcf"
- **m_MeleeAnimName**: b_melee
- **m_LastHitParticle**: resource_name:"particles/generic/last_hit.vpcf"
- **m_strLastHitSound**: soundevent:"LastHit.Default"
- **m_bPlayLastHitSound**: True
- **m_NearDeathModifier**:
  - **subclass**:
    - **_class**: modifier_near_death_fx
    - **_my_subclass_name**: modifier_near_death_fx
    - **m_EnemyNearDeathParticle**: resource_name:"particles/status_fx/status_fx_last_hit.vpcf"
    - **m_FriendlyNearDeathParticle**: resource_name:"particles/status_fx/status_fx_last_hit_friend.vpcf"
    - **m_sSelfDestructStart**: soundevent:"Trooper.SelfDestruct_Start"
    - **m_sSelfDestructEnd**: soundevent:"Trooper.SelfDestruct_Exp"
- **m_TargetingLaserParticle**: resource_name:"particles/weapon_fx/trooper_laser_target.vpcf"
- **m_TargetingEyeFlashParticle**: resource_name:"particles/enemy_targeting_indicator.vpcf"
- **m_sCelebrationSound**: soundevent:"Trooper.Objective.Win.Cheer"
- **m_flBarrackGuardianDamageResistPct**: 67.5
- **m_sTeam1MaterialGroupName**: Amber
- **m_sTeam2MaterialGroupName**: Sapphire
- **m_flT1BossDPS**: 36.0
- **m_flT2BossDPS**: 80.0
- **m_flT3BossDPS**: 80.0
- **m_flGeneratorBossDPS**: 22
- **m_flBarrackBossDPS**: 80.0
- **m_flPlayerDPS**: 28.0
- **m_flTrooperDPS**: 35.0
- **m_flModelScale**: 1.0
- **m_navHull**: 1
- **m_flPhysicsImpulseMultiplier**: 0.0
- **m_flTurnRate**: 360
- **m_bMitigateDamageFromPlayers**: True
- **m_flBeamWeaponWidth**: 6.0
- **m_flBeamTurnRate**: 360
- **m_BeamWeaponParticle**: resource_name:"particles/weapon_fx/npc/t1_guardian_beam.vpcf"
- **m_BeamStartSound**: soundevent:"Guardian.Tier1.Wpn.Beam.Begin"
- **m_BeamStopSound**: soundevent:"Guardian.Tier1.Wpn.Beam.End"
- **m_BeamPointStartLoopSound**: soundevent:"Guardian.Tier1.Wpn.Point.Begin.Lp"
- **m_BeamPointEndLoopSound**: soundevent:"Guardian.Tier1.Wpn.Point.End.Lp"
- **m_BeamPointClosestLoopSound**: soundevent:"Guardian.Tier1.Wpn.Point.Closest.Lp"
- **m_flMinMeleeAttackTime**: 1.5
- **m_TrooperBossInvulnModifier**:
  - **subclass**:
    - **_my_subclass_name**: trooper_boss_invuln
    - **_class**: modifier_boss_invuln

---

# NPC: heavy_drone_rocket

- **_class**: npc_flying_drone
- **m_sModelName**: resource_name:"models/weapons/hornet/hornet_drone.vmdl"
- **m_flSightRangePlayers**: 1600.0
- **m_flSightRangeNPCs**: 1600.0

---

# NPC: npc_hero_decoy

- **_class**: npc_hero_decoy
- **m_flSightRangePlayers**: 1600.0
- **m_flSightRangeNPCs**: 1600.0
- **m_hFootstepSounds**: citadel

---

# NPC: mirage_beetle_drone

- **_class**: npc_flying_drone
- **m_sModelName**: resource_name:"models/weapons/hornet/hornet_drone.vmdl"
- **m_flSightRangePlayers**: 1600.0
- **m_flSightRangeNPCs**: 1600.0
- **m_iStartingHealth**: 200

---

# NPC: nano_rollermine

- **_class**: npc_nano_rollermine
- **m_sModelName**: resource_name:"models/heroes_staging/nano/roller/roller.vmdl"
- **m_flSightRangePlayers**: 1024.0
- **m_flSightRangeNPCs**: 1024.0
- **m_hFootstepSounds**: 
- **m_strAmbientLoopSound**: soundevent:"Nano.Predator.Travel"
- **m_DeathSound**: soundevent:""

---

# NPC: citadel_cat_animating

- **_class**: citadel_cat_animating
- **m_sModelName**: resource_name:"models/abilities/nano_cat_model.vmdl"
- **m_cGlowColor**:
  - 110
  - 27
  - 200

---

# NPC: npc_hero_clone_trooper

- **_class**: npc_hero_clone_trooper
- **m_sModelName**: resource_name:"models/heroes_staging/nano/roller/roller.vmdl"
- **m_flSightRangePlayers**: 2000.0
- **m_flSightRangeNPCs**: 2000.0
- **m_hFootstepSounds**: citadel

---

# NPC: npc_super_neutral

- **m_WeaponInfo**:
  - **m_Spread**: 0.5
  - **m_StandingSpread**: 1.5
  - **m_flScatterYawScale**: 1
  - **m_flShootingUpSpreadPenalty**: 1
  - **m_flZoomMoveSpeedPercent**: 0.7
  - **m_flShootMoveSpeedPercent**: 0.7
  - **m_flHorizontalPunch**: 0
  - **m_flVerticalPunch**: 0
  - **m_flRecoilRecoverySpeed**: 10.0
  - **m_VerticallRecoil**:
    - **m_Range**:
      - -0.2
      - 0.2
    - **m_flBurstSlope**: 0.0
    - **m_flBurstExponent**: 0.0
    - **m_flBurstConstant**: 0.0
  - **m_HorizontalRecoil**:
    - **m_Range**:
      - -0.1
      - 0.1
    - **m_flBurstExponent**: 0.0
  - **m_flRecoilSpeed**: 1
  - **m_flZoomFOV**: 40.0
  - **m_flDamageFalloffStartRange**: 1500
  - **m_flDamageFalloffEndRange**: 1500
  - **m_flRange**: 1500
  - **m_flBulletLifetime**: 2
  - **m_flDamageFalloffEndScale**: 0.3
  - **m_flDamageFalloffBias**: 0.5
  - **m_iBullets**: 1
  - **m_flCycleTime**: 0.2
  - **m_reloadDuration**: 0
  - **m_iClipSize**: -1
  - **m_iBurstShotCount**: 1
  - **m_flBurstShotCooldown**: 0
  - **m_flBulletGravityScale**: 0.0
  - **m_flBulletRadius**: 3
  - **m_flBulletDrag**: 1
  - **m_flBulletDragBias**: 0.5
  - **m_flBulletReflectScale**: 0
  - **m_flBulletReflectAmount**: 1
  - **m_flBulletInheritShooterVelocityScale**: 0
  - **m_szBulletTravelTracerParticle**: resource_name:"particles/weapon_fx/trooper/trooper_bullet_travel.vpcf"
  - **m_szMuzzleFlashEffectName**: resource_name:"particles/dev/bullet_debug_muzzle_flash.vpcf"
  - **m_strShootSound**: soundevent:"TrooperRifle.Fire"
  - **m_strBulletWhizSound**: soundevent:"Base.Bullet.Whizby"
  - **m_BulletSpeedCurve**:
    - **m_spline**:
      | x | y | m_flSlopeIncoming | m_flSlopeOutgoing |
      | --- | --- | --- | --- |
      | 0.0 | 13000.0 | 0.0 | 0.0 |
      | 100.0 | 13000.0 | 0.0 | 0.0 |
    - **m_tangents**:
      | m_nIncomingTangent | m_nOutgoingTangent |
      | --- | --- |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
    - **m_vDomainMins**:
      - 0.0
      - 1.0
    - **m_vDomainMaxs**:
      - 100.0
      - 13000.0
  - **m_mapImpactEffects**:
    - **default**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Default.BulletImpact"
    - **flesh**:
      - **m_strDecal**: 
      - **m_strParticle**: resource_name:"particles/blood_impact/blood_impact_red_01.vpcf"
      - **m_strSound**: soundevent:"Flesh.BulletImpact"
    - **concrete**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Concrete.BulletImpact"
    - **solidmetal**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"SolidMetal.BulletImpact"
    - **portals**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Player.HitInvuln"
  - **m_flCritBonusStart**: 1.15
  - **m_flCritBonusEnd**: 1.35
  - **m_flCritBonusStartRange**: 500.0
  - **m_flCritBonusEndRange**: 1500.0
  - **m_flCritBonusAgainstNPCs**: 0.25
  - **m_flShootSpreadPenaltyPerShot**: 0.0
  - **m_flShootSpreadPenaltyDecayDelay**: 0.0
  - **m_flShootSpreadPenaltyDecay**: 2.0
  - **m_flRecoilShotIndexRecoveryTimeFactor**: 0.25
  - **m_bCanZoom**: True
  - **m_strWeaponImpactEffect**: resource_name:"particles/weapon_fx/default_tracer_impact.vpcf"
  - **m_flReloadMoveSpeed**: 236.22
  - **m_strLocalPlayerBulletImpactSound**: soundevent:"Player.Bullet.Impact.Default"
  - **m_flAutoReplenishClip**: 2
  - **m_NpcAimingSpread**:
    - 0
    - 0
  - **m_flBulletDamage**: 20.0
- **_base**: weapon_base
- **_class**: npc_super_neutral
- **m_sModelName**: resource_name:"models/npc/midboss/midboss.vmdl"
- **m_mapBoundAbilities**:
  - **ESlot_Signature_1**: super_neutral_shield
  - **ESlot_Signature_2**: super_neutral_charge
- **m_hFootstepSounds**: citadel
- **m_flHealthBarOffset**: 600
- **m_flSightRangePlayers**: 1500.0
- **m_flSightRangeNPCs**: 1500.0
- **m_iHealthGainPerMinute**: 425
- **m_iStartingHealth**: 6000
- **m_flPhysicsImpulseMultiplier**: 0.0
- **m_flBeamWeaponWidth**: 24
- **m_flBeamTurnRate**: 360
- **m_BeamWeaponParticle**: resource_name:"particles/weapon_fx/npc/midboss_beam.vpcf"
- **m_BeamStartSound**: soundevent:"Guardian.Tier1.Wpn.Beam.Begin"
- **m_BeamStopSound**: soundevent:"Guardian.Tier1.Wpn.Beam.End"
- **m_BeamPointStartLoopSound**: soundevent:"Guardian.Tier1.Wpn.Point.Begin.Lp"
- **m_BeamPointEndLoopSound**: soundevent:"Guardian.Tier1.Wpn.Point.End.Lp"
- **m_BeamPointClosestLoopSound**: soundevent:"Guardian.Tier1.Wpn.Point.Closest.Lp"
- **m_DyingSmallExplosion**: resource_name:"particles/abilities/heavy_barrage_projectile_impact_explode.vpcf"
- **m_DyingFinalExplosion**: resource_name:"particles/npc/npc_explode.vpcf"
- **m_KnockbackAura**:
  - **subclass**:
    - **_class**: modifier_knockback_aura
    - **_my_subclass_name**: modifier_knockback_aura
- **m_AggroEnemy**:
  - **subclass**:
    - **_class**: modifier_midboss_aggro_enemy
    - **_my_subclass_name**: modifier_midboss_aggro_enemy
    - **m_nAttributes**: MODIFIER_ATTRIBUTE_IGNORE_INVULNERABLE | MODIFIER_ATTRIBUTE_CANNOT_BE_PURGED
- **m_flDyingDuration**: 1.4

---

# NPC: neutral_base

- **m_WeaponInfo**:
  - **m_Spread**: 0.5
  - **m_StandingSpread**: 1.5
  - **m_flScatterYawScale**: 1
  - **m_flShootingUpSpreadPenalty**: 0
  - **m_flZoomMoveSpeedPercent**: 0.7
  - **m_flShootMoveSpeedPercent**: 0.7
  - **m_flHorizontalPunch**: 0
  - **m_flVerticalPunch**: 0
  - **m_flRecoilRecoverySpeed**: 10.0
  - **m_VerticallRecoil**:
    - **m_Range**:
      - -0.2
      - 0.2
    - **m_flBurstSlope**: 0.0
    - **m_flBurstExponent**: 0.0
    - **m_flBurstConstant**: 0.0
  - **m_HorizontalRecoil**:
    - **m_Range**:
      - -0.1
      - 0.1
    - **m_flBurstExponent**: 0.0
  - **m_flRecoilSpeed**: 1
  - **m_flZoomFOV**: 40.0
  - **m_flDamageFalloffStartRange**: 2000.0
  - **m_flDamageFalloffEndRange**: 3000.0
  - **m_flRange**: 3500.0
  - **m_flBulletLifetime**: 2
  - **m_flDamageFalloffEndScale**: 0.3
  - **m_flDamageFalloffBias**: 0.5
  - **m_iBullets**: 1
  - **m_flCycleTime**: 0.3
  - **m_reloadDuration**: 1.5
  - **m_iClipSize**: 10
  - **m_iBurstShotCount**: 1
  - **m_flBurstShotCooldown**: 0
  - **m_flBulletGravityScale**: 0.8
  - **m_flBulletRadius**: 3
  - **m_flBulletDrag**: 1
  - **m_flBulletDragBias**: 0.5
  - **m_flBulletReflectScale**: 0
  - **m_flBulletReflectAmount**: 1
  - **m_flBulletInheritShooterVelocityScale**: 0
  - **m_szBulletTravelTracerParticle**: resource_name:"particles/weapon_fx/default_tracer.vpcf"
  - **m_szMuzzleFlashEffectName**: resource_name:"particles/dev/bullet_debug_muzzle_flash.vpcf"
  - **m_strShootSound**: soundevent:"Pistol.Fire"
  - **m_strBulletWhizSound**: soundevent:"Base.Bullet.Whizby"
  - **m_BulletSpeedCurve**:
    - **m_spline**:
      | x | y | m_flSlopeIncoming | m_flSlopeOutgoing |
      | --- | --- | --- | --- |
      | 0.0 | 18000.0 | 0.0 | 0.0 |
      | 100.0 | 18000.0 | 0.0 | 0.0 |
    - **m_tangents**:
      | m_nIncomingTangent | m_nOutgoingTangent |
      | --- | --- |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
    - **m_vDomainMins**:
      - 0.0
      - 1.0
    - **m_vDomainMaxs**:
      - 100.0
      - 18000.0
  - **m_mapImpactEffects**:
    - **default**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Default.BulletImpact"
    - **flesh**:
      - **m_strDecal**: 
      - **m_strParticle**: resource_name:"particles/blood_impact/blood_impact_red_01.vpcf"
      - **m_strSound**: soundevent:"Flesh.BulletImpact"
    - **concrete**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Concrete.BulletImpact"
    - **solidmetal**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"SolidMetal.BulletImpact"
    - **portals**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Player.HitInvuln"
  - **m_flCritBonusStart**: 1.15
  - **m_flCritBonusEnd**: 1.35
  - **m_flCritBonusStartRange**: 500.0
  - **m_flCritBonusEndRange**: 1500.0
  - **m_flCritBonusAgainstNPCs**: 0.25
  - **m_flShootSpreadPenaltyPerShot**: 0.0
  - **m_flShootSpreadPenaltyDecayDelay**: 0.0
  - **m_flShootSpreadPenaltyDecay**: 2.0
  - **m_flRecoilShotIndexRecoveryTimeFactor**: 0.25
  - **m_bCanZoom**: True
  - **m_strWeaponImpactEffect**: resource_name:"particles/weapon_fx/default_tracer_impact.vpcf"
  - **m_flReloadMoveSpeed**: 236.22
  - **m_strLocalPlayerBulletImpactSound**: soundevent:"Player.Bullet.Impact.Default"
- **_not_pickable**: 2
- **_base**: weapon_base
- **_class**: npc_trooper_neutral
- **m_ShieldParticle**: resource_name:""
- **m_flSightRangePlayers**: 2000.0
- **m_flMaxHealthBarDrawDistance**: 800
- **m_flShieldReactivateDelay**: 2.0
- **m_flGoldReward**: 110
- **m_flGoldRewardBonusPercentPerMinute**: 1.2
- **m_strLastHitSound**: soundevent:"LastHit.Default"

---

# NPC: neutral_trooper_weak

- **m_WeaponInfo**:
  - **m_Spread**: 0.5
  - **m_StandingSpread**: 1.5
  - **m_flScatterYawScale**: 1
  - **m_flShootingUpSpreadPenalty**: 5
  - **m_flZoomMoveSpeedPercent**: 0.7
  - **m_flShootMoveSpeedPercent**: 0.7
  - **m_flHorizontalPunch**: 0
  - **m_flVerticalPunch**: 0
  - **m_flRecoilRecoverySpeed**: 10.0
  - **m_VerticallRecoil**:
    - **m_Range**:
      - -0.2
      - 0.2
    - **m_flBurstSlope**: 0.0
    - **m_flBurstExponent**: 0.0
    - **m_flBurstConstant**: 0.0
  - **m_HorizontalRecoil**:
    - **m_Range**:
      - -0.1
      - 0.1
    - **m_flBurstExponent**: 0.0
  - **m_flRecoilSpeed**: 1
  - **m_flZoomFOV**: 40.0
  - **m_flDamageFalloffStartRange**: 1500
  - **m_flDamageFalloffEndRange**: 1500
  - **m_flRange**: 1500
  - **m_flBulletLifetime**: 2
  - **m_flDamageFalloffEndScale**: 0.3
  - **m_flDamageFalloffBias**: 0.5
  - **m_iBullets**: 1
  - **m_flCycleTime**: 0.5
  - **m_reloadDuration**: 0.25
  - **m_iClipSize**: -1
  - **m_iBurstShotCount**: 1
  - **m_flBurstShotCooldown**: 0
  - **m_flBulletGravityScale**: 0.0
  - **m_flBulletRadius**: 3
  - **m_flBulletDrag**: 1
  - **m_flBulletDragBias**: 0.5
  - **m_flBulletReflectScale**: 0
  - **m_flBulletReflectAmount**: 1
  - **m_flBulletInheritShooterVelocityScale**: 0
  - **m_szBulletTravelTracerParticle**: resource_name:"particles/weapon_fx/trooper/trooper_bullet_travel.vpcf"
  - **m_szMuzzleFlashEffectName**: resource_name:"particles/dev/bullet_debug_muzzle_flash.vpcf"
  - **m_strShootSound**: soundevent:"TrooperRifle.Fire"
  - **m_strBulletWhizSound**: soundevent:"Base.Bullet.Whizby"
  - **m_BulletSpeedCurve**:
    - **m_spline**:
      | x | y | m_flSlopeIncoming | m_flSlopeOutgoing |
      | --- | --- | --- | --- |
      | 0.0 | 13000.0 | 0.0 | 0.0 |
      | 100.0 | 13000.0 | 0.0 | 0.0 |
    - **m_tangents**:
      | m_nIncomingTangent | m_nOutgoingTangent |
      | --- | --- |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
    - **m_vDomainMins**:
      - 0.0
      - 1.0
    - **m_vDomainMaxs**:
      - 100.0
      - 13000.0
  - **m_mapImpactEffects**:
    - **default**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Default.BulletImpact"
    - **flesh**:
      - **m_strDecal**: 
      - **m_strParticle**: resource_name:"particles/blood_impact/blood_impact_red_01.vpcf"
      - **m_strSound**: soundevent:"Flesh.BulletImpact"
    - **concrete**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Concrete.BulletImpact"
    - **solidmetal**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"SolidMetal.BulletImpact"
    - **portals**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Player.HitInvuln"
  - **m_flCritBonusStart**: 1.15
  - **m_flCritBonusEnd**: 1.35
  - **m_flCritBonusStartRange**: 500.0
  - **m_flCritBonusEndRange**: 1500.0
  - **m_flCritBonusAgainstNPCs**: 0.25
  - **m_flShootSpreadPenaltyPerShot**: 0.0
  - **m_flShootSpreadPenaltyDecayDelay**: 0.0
  - **m_flShootSpreadPenaltyDecay**: 2.0
  - **m_flRecoilShotIndexRecoveryTimeFactor**: 0.25
  - **m_bCanZoom**: True
  - **m_strWeaponImpactEffect**: resource_name:"particles/weapon_fx/default_tracer_impact.vpcf"
  - **m_flReloadMoveSpeed**: 236.22
  - **m_strLocalPlayerBulletImpactSound**: soundevent:"Player.Bullet.Impact.Default"
  - **m_flAutoReplenishClip**: 4
  - **m_NpcAimingSpread**:
    - 0.2
    - 0.6
  - **m_flBulletDamage**: 3.0
- **_base**: neutral_base
- **_class**: npc_trooper_neutral
- **m_ShieldParticle**: resource_name:""
- **m_flSightRangePlayers**: 2000.0
- **m_flMaxHealthBarDrawDistance**: 800
- **m_flShieldReactivateDelay**: 2.0
- **m_flGoldReward**: 44
- **m_flGoldRewardBonusPercentPerMinute**: 1.2
- **m_strLastHitSound**: soundevent:"LastHit.Default"
- **m_sModelName**: resource_name:"models/npc/trooper/trooper_mid_boss.vmdl"
- **m_flModelScale**: 0.28
- **m_nMaxHealth**: 200
- **m_hFootstepSounds**: citadel
- **m_sDefaultMaterialGroupName**: Neutral_Weak
- **m_flHealthBarOffset**: 300.0
- **m_bCapSimultanousAttackers**: True
- **m_bFaceEnemyWhileIdle**: True
- **m_flPhysicsImpulseMultiplier**: 0.0
- **m_DeathParticle**: resource_name:"particles/npc/neutral_trooper_death.vpcf"
- **m_vecIntrinsicModifiers**:
  | subclass |
  | --- |
  | {'_my_subclass_name': 'weak_neutral_bullet_armor', '_class': 'modifier_intrinsic_base', 'm_mapAutoRegisterModifierValueFromAbilityPropertyName': {}, 'm_vecScriptValues': [{'m_eModifierValue': 'MODIFIER_VALUE_BULLET_DAMAGE_REDUCTION_PERCENT', 'm_value': 50.0}, {'m_eModifierValue': 'MODIFIER_VALUE_ABILITY_DAMAGE_REDUCTION_PERCENT', 'm_value': 30.0}]} |
- **m_eTrooperType**: NEUTRAL_TROOPER_WEAK
- **m_flHullCapsuleRadius**: 90.0
- **m_flHullCapsuleHeight**: 130.0

---

# NPC: neutral_trooper_normal

- **m_WeaponInfo**:
  - **m_Spread**: 0.5
  - **m_StandingSpread**: 1.5
  - **m_flScatterYawScale**: 1
  - **m_flShootingUpSpreadPenalty**: 5
  - **m_flZoomMoveSpeedPercent**: 0.7
  - **m_flShootMoveSpeedPercent**: 0.7
  - **m_flHorizontalPunch**: 0
  - **m_flVerticalPunch**: 0
  - **m_flRecoilRecoverySpeed**: 10.0
  - **m_VerticallRecoil**:
    - **m_Range**:
      - -0.2
      - 0.2
    - **m_flBurstSlope**: 0.0
    - **m_flBurstExponent**: 0.0
    - **m_flBurstConstant**: 0.0
  - **m_HorizontalRecoil**:
    - **m_Range**:
      - -0.1
      - 0.1
    - **m_flBurstExponent**: 0.0
  - **m_flRecoilSpeed**: 1
  - **m_flZoomFOV**: 40.0
  - **m_flDamageFalloffStartRange**: 1500
  - **m_flDamageFalloffEndRange**: 1500
  - **m_flRange**: 1500
  - **m_flBulletLifetime**: 2
  - **m_flDamageFalloffEndScale**: 0.3
  - **m_flDamageFalloffBias**: 0.5
  - **m_iBullets**: 1
  - **m_flCycleTime**: 0.5
  - **m_reloadDuration**: 0.25
  - **m_iClipSize**: -1
  - **m_iBurstShotCount**: 1
  - **m_flBurstShotCooldown**: 0
  - **m_flBulletGravityScale**: 0.0
  - **m_flBulletRadius**: 3
  - **m_flBulletDrag**: 1
  - **m_flBulletDragBias**: 0.5
  - **m_flBulletReflectScale**: 0
  - **m_flBulletReflectAmount**: 1
  - **m_flBulletInheritShooterVelocityScale**: 0
  - **m_szBulletTravelTracerParticle**: resource_name:"particles/weapon_fx/trooper/trooper_bullet_travel.vpcf"
  - **m_szMuzzleFlashEffectName**: resource_name:"particles/dev/bullet_debug_muzzle_flash.vpcf"
  - **m_strShootSound**: soundevent:"TrooperRifle.Fire"
  - **m_strBulletWhizSound**: soundevent:"Base.Bullet.Whizby"
  - **m_BulletSpeedCurve**:
    - **m_spline**:
      | x | y | m_flSlopeIncoming | m_flSlopeOutgoing |
      | --- | --- | --- | --- |
      | 0.0 | 13000.0 | 0.0 | 0.0 |
      | 100.0 | 13000.0 | 0.0 | 0.0 |
    - **m_tangents**:
      | m_nIncomingTangent | m_nOutgoingTangent |
      | --- | --- |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
    - **m_vDomainMins**:
      - 0.0
      - 1.0
    - **m_vDomainMaxs**:
      - 100.0
      - 13000.0
  - **m_mapImpactEffects**:
    - **default**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Default.BulletImpact"
    - **flesh**:
      - **m_strDecal**: 
      - **m_strParticle**: resource_name:"particles/blood_impact/blood_impact_red_01.vpcf"
      - **m_strSound**: soundevent:"Flesh.BulletImpact"
    - **concrete**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Concrete.BulletImpact"
    - **solidmetal**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"SolidMetal.BulletImpact"
    - **portals**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Player.HitInvuln"
  - **m_flCritBonusStart**: 1.15
  - **m_flCritBonusEnd**: 1.35
  - **m_flCritBonusStartRange**: 500.0
  - **m_flCritBonusEndRange**: 1500.0
  - **m_flCritBonusAgainstNPCs**: 0.25
  - **m_flShootSpreadPenaltyPerShot**: 0.0
  - **m_flShootSpreadPenaltyDecayDelay**: 0.0
  - **m_flShootSpreadPenaltyDecay**: 2.0
  - **m_flRecoilShotIndexRecoveryTimeFactor**: 0.25
  - **m_bCanZoom**: True
  - **m_strWeaponImpactEffect**: resource_name:"particles/weapon_fx/default_tracer_impact.vpcf"
  - **m_flReloadMoveSpeed**: 236.22
  - **m_strLocalPlayerBulletImpactSound**: soundevent:"Player.Bullet.Impact.Default"
  - **m_flAutoReplenishClip**: 4
  - **m_NpcAimingSpread**:
    - 0.2
    - 0.6
  - **m_flBulletDamage**: 7.0
- **_base**: neutral_base
- **_class**: npc_trooper_neutral
- **m_ShieldParticle**: resource_name:""
- **m_flSightRangePlayers**: 2000.0
- **m_flMaxHealthBarDrawDistance**: 800
- **m_flShieldReactivateDelay**: 2.0
- **m_flGoldReward**: 88
- **m_flGoldRewardBonusPercentPerMinute**: 1.2
- **m_strLastHitSound**: soundevent:"LastHit.Default"
- **m_sModelName**: resource_name:"models/npc/trooper/trooper_mid_boss.vmdl"
- **m_flModelScale**: 0.375
- **m_nMaxHealth**: 500
- **m_hFootstepSounds**: citadel
- **m_sDefaultMaterialGroupName**: Neutral_Normal
- **m_flHealthBarOffset**: 260.0
- **m_bFaceEnemyWhileIdle**: True
- **m_flPhysicsImpulseMultiplier**: 0.0
- **m_DeathParticle**: resource_name:"particles/npc/neutral_trooper_death.vpcf"
- **m_vecIntrinsicModifiers**:
  | subclass |
  | --- |
  | {'_my_subclass_name': 'normal_neutral_bullet_armor', '_class': 'modifier_intrinsic_base', 'm_vecScriptValues': [{'m_eModifierValue': 'MODIFIER_VALUE_BULLET_DAMAGE_REDUCTION_PERCENT', 'm_value': 50.0}, {'m_eModifierValue': 'MODIFIER_VALUE_ABILITY_DAMAGE_REDUCTION_PERCENT', 'm_value': 30.0}]} |
- **m_flHullCapsuleRadius**: 90.0
- **m_flHullCapsuleHeight**: 170.0

---

# NPC: neutral_vault

- **m_WeaponInfo**:
  - **m_Spread**: 0.5
  - **m_StandingSpread**: 1.5
  - **m_flScatterYawScale**: 1
  - **m_flShootingUpSpreadPenalty**: 0
  - **m_flZoomMoveSpeedPercent**: 0.7
  - **m_flShootMoveSpeedPercent**: 0.7
  - **m_flHorizontalPunch**: 0
  - **m_flVerticalPunch**: 0
  - **m_flRecoilRecoverySpeed**: 10.0
  - **m_VerticallRecoil**:
    - **m_Range**:
      - -0.2
      - 0.2
    - **m_flBurstSlope**: 0.0
    - **m_flBurstExponent**: 0.0
    - **m_flBurstConstant**: 0.0
  - **m_HorizontalRecoil**:
    - **m_Range**:
      - -0.1
      - 0.1
    - **m_flBurstExponent**: 0.0
  - **m_flRecoilSpeed**: 1
  - **m_flZoomFOV**: 40.0
  - **m_flDamageFalloffStartRange**: 2000.0
  - **m_flDamageFalloffEndRange**: 3000.0
  - **m_flRange**: 0
  - **m_flBulletLifetime**: 2
  - **m_flDamageFalloffEndScale**: 0.3
  - **m_flDamageFalloffBias**: 0.5
  - **m_iBullets**: 1
  - **m_flCycleTime**: 0.3
  - **m_reloadDuration**: 1.5
  - **m_iClipSize**: 10
  - **m_iBurstShotCount**: 1
  - **m_flBurstShotCooldown**: 0
  - **m_flBulletGravityScale**: 0.8
  - **m_flBulletRadius**: 3
  - **m_flBulletDrag**: 1
  - **m_flBulletDragBias**: 0.5
  - **m_flBulletReflectScale**: 0
  - **m_flBulletReflectAmount**: 1
  - **m_flBulletInheritShooterVelocityScale**: 0
  - **m_szBulletTravelTracerParticle**: resource_name:"particles/weapon_fx/default_tracer.vpcf"
  - **m_szMuzzleFlashEffectName**: resource_name:"particles/dev/bullet_debug_muzzle_flash.vpcf"
  - **m_strShootSound**: soundevent:"Pistol.Fire"
  - **m_strBulletWhizSound**: soundevent:"Base.Bullet.Whizby"
  - **m_BulletSpeedCurve**:
    - **m_spline**:
      | x | y | m_flSlopeIncoming | m_flSlopeOutgoing |
      | --- | --- | --- | --- |
      | 0.0 | 18000.0 | 0.0 | 0.0 |
      | 100.0 | 18000.0 | 0.0 | 0.0 |
    - **m_tangents**:
      | m_nIncomingTangent | m_nOutgoingTangent |
      | --- | --- |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
    - **m_vDomainMins**:
      - 0.0
      - 1.0
    - **m_vDomainMaxs**:
      - 100.0
      - 18000.0
  - **m_mapImpactEffects**:
    - **default**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Default.BulletImpact"
    - **flesh**:
      - **m_strDecal**: 
      - **m_strParticle**: resource_name:"particles/blood_impact/blood_impact_red_01.vpcf"
      - **m_strSound**: soundevent:"Flesh.BulletImpact"
    - **concrete**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Concrete.BulletImpact"
    - **solidmetal**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"SolidMetal.BulletImpact"
    - **portals**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Player.HitInvuln"
  - **m_flCritBonusStart**: 1.15
  - **m_flCritBonusEnd**: 1.35
  - **m_flCritBonusStartRange**: 500.0
  - **m_flCritBonusEndRange**: 1500.0
  - **m_flCritBonusAgainstNPCs**: 0.25
  - **m_flShootSpreadPenaltyPerShot**: 0.0
  - **m_flShootSpreadPenaltyDecayDelay**: 0.0
  - **m_flShootSpreadPenaltyDecay**: 2.0
  - **m_flRecoilShotIndexRecoveryTimeFactor**: 0.25
  - **m_bCanZoom**: True
  - **m_strWeaponImpactEffect**: resource_name:"particles/weapon_fx/default_tracer_impact.vpcf"
  - **m_flReloadMoveSpeed**: 236.22
  - **m_strLocalPlayerBulletImpactSound**: soundevent:"Player.Bullet.Impact.Default"
- **_base**: neutral_base
- **_class**: npc_trooper_neutral
- **m_ShieldParticle**: resource_name:""
- **m_flSightRangePlayers**: 2000.0
- **m_flMaxHealthBarDrawDistance**: 800
- **m_flShieldReactivateDelay**: 2.0
- **m_flGoldReward**: 330
- **m_flGoldRewardBonusPercentPerMinute**: 1.2
- **m_strLastHitSound**: soundevent:"LastHit.Default"
- **m_sModelName**: resource_name:"models/props_gameplay/neutral_vault/neutral_vault.vmdl"
- **m_nMaxHealth**: 500
- **m_bDamagedByBullets**: False
- **m_bDamagedByAbilities**: False
- **m_bFixedMeleeDamage**: True
- **m_retaliateParticle**: resource_name:"particles/abilities/chain_lightning.vpcf"
- **m_flRetaliateDamage**: 40.0
- **m_sHitIndicatorSound**: soundevent:"HitIndicator.Vault"
- **m_sDamageSound**: soundevent:"Props.Vault.Impact"
- **m_sHeavyDamageSound**: soundevent:"Props.Vault.HeavyImpact"
- **m_sBreakSound**: soundevent:"Props.Vault.Destruction"
- **m_flHealthBarOffset**: 94
- **m_bGiveGoldOnHit**: True
- **m_flPhysicsImpulseMultiplier**: 0
- **m_vecIntrinsicModifiers**:
  | subclass |
  | --- |
  | {'_my_subclass_name': 'neutral_vault_tech_immune', '_class': 'modifier_intrinsic_base', 'm_nEnabledStateMask': 'MODIFIER_STATE_TECH_UNTARGETABLE | MODIFIER_STATE_TECH_INVULNERABLE'} |

---

# NPC: neutral_sinners_sacrifice

- **m_WeaponInfo**:
  - **m_Spread**: 0.5
  - **m_StandingSpread**: 1.5
  - **m_flScatterYawScale**: 1
  - **m_flShootingUpSpreadPenalty**: 0
  - **m_flZoomMoveSpeedPercent**: 0.7
  - **m_flShootMoveSpeedPercent**: 0.7
  - **m_flHorizontalPunch**: 0
  - **m_flVerticalPunch**: 0
  - **m_flRecoilRecoverySpeed**: 10.0
  - **m_VerticallRecoil**:
    - **m_Range**:
      - -0.2
      - 0.2
    - **m_flBurstSlope**: 0.0
    - **m_flBurstExponent**: 0.0
    - **m_flBurstConstant**: 0.0
  - **m_HorizontalRecoil**:
    - **m_Range**:
      - -0.1
      - 0.1
    - **m_flBurstExponent**: 0.0
  - **m_flRecoilSpeed**: 1
  - **m_flZoomFOV**: 40.0
  - **m_flDamageFalloffStartRange**: 2000.0
  - **m_flDamageFalloffEndRange**: 3000.0
  - **m_flRange**: 0
  - **m_flBulletLifetime**: 2
  - **m_flDamageFalloffEndScale**: 0.3
  - **m_flDamageFalloffBias**: 0.5
  - **m_iBullets**: 1
  - **m_flCycleTime**: 0.3
  - **m_reloadDuration**: 1.5
  - **m_iClipSize**: 10
  - **m_iBurstShotCount**: 1
  - **m_flBurstShotCooldown**: 0
  - **m_flBulletGravityScale**: 0.8
  - **m_flBulletRadius**: 3
  - **m_flBulletDrag**: 1
  - **m_flBulletDragBias**: 0.5
  - **m_flBulletReflectScale**: 0
  - **m_flBulletReflectAmount**: 1
  - **m_flBulletInheritShooterVelocityScale**: 0
  - **m_szBulletTravelTracerParticle**: resource_name:"particles/weapon_fx/default_tracer.vpcf"
  - **m_szMuzzleFlashEffectName**: resource_name:"particles/dev/bullet_debug_muzzle_flash.vpcf"
  - **m_strShootSound**: soundevent:"Pistol.Fire"
  - **m_strBulletWhizSound**: soundevent:"Base.Bullet.Whizby"
  - **m_BulletSpeedCurve**:
    - **m_spline**:
      | x | y | m_flSlopeIncoming | m_flSlopeOutgoing |
      | --- | --- | --- | --- |
      | 0.0 | 18000.0 | 0.0 | 0.0 |
      | 100.0 | 18000.0 | 0.0 | 0.0 |
    - **m_tangents**:
      | m_nIncomingTangent | m_nOutgoingTangent |
      | --- | --- |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
    - **m_vDomainMins**:
      - 0.0
      - 1.0
    - **m_vDomainMaxs**:
      - 100.0
      - 18000.0
  - **m_mapImpactEffects**:
    - **default**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Default.BulletImpact"
    - **flesh**:
      - **m_strDecal**: 
      - **m_strParticle**: resource_name:"particles/blood_impact/blood_impact_red_01.vpcf"
      - **m_strSound**: soundevent:"Flesh.BulletImpact"
    - **concrete**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Concrete.BulletImpact"
    - **solidmetal**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"SolidMetal.BulletImpact"
    - **portals**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Player.HitInvuln"
  - **m_flCritBonusStart**: 1.15
  - **m_flCritBonusEnd**: 1.35
  - **m_flCritBonusStartRange**: 500.0
  - **m_flCritBonusEndRange**: 1500.0
  - **m_flCritBonusAgainstNPCs**: 0.25
  - **m_flShootSpreadPenaltyPerShot**: 0.0
  - **m_flShootSpreadPenaltyDecayDelay**: 0.0
  - **m_flShootSpreadPenaltyDecay**: 2.0
  - **m_flRecoilShotIndexRecoveryTimeFactor**: 0.25
  - **m_bCanZoom**: True
  - **m_strWeaponImpactEffect**: resource_name:"particles/weapon_fx/default_tracer_impact.vpcf"
  - **m_flReloadMoveSpeed**: 236.22
  - **m_strLocalPlayerBulletImpactSound**: soundevent:"Player.Bullet.Impact.Default"
- **_base**: neutral_base
- **_class**: npc_trooper_neutral
- **m_ShieldParticle**: resource_name:""
- **m_flSightRangePlayers**: 2000.0
- **m_flMaxHealthBarDrawDistance**: 800
- **m_flShieldReactivateDelay**: 2.0
- **m_flGoldReward**: 330
- **m_flGoldRewardBonusPercentPerMinute**: 1.2
- **m_strLastHitSound**: soundevent:"LastHit.Default"
- **m_sModelName**: resource_name:"models/props_gameplay/sinners_sacrifice_vault/sinners_sacrifice.vmdl"
- **m_nMaxHealth**: 500
- **m_bDamagedByBullets**: False
- **m_bDamagedByAbilities**: False
- **m_bFixedMeleeDamage**: True
- **m_retaliateParticle**: resource_name:"particles/environment/spirit_orb_vault_hit.vpcf"
- **m_flRetaliateDamage**: 40.0
- **m_sHitIndicatorSound**: soundevent:"HitIndicator.Vault"
- **m_sDamageSound**: soundevent:"Props.Vault.Impact"
- **m_sHeavyDamageSound**: soundevent:"Props.Vault.HeavyImpact"
- **m_sBreakSound**: soundevent:"Props.Vault.Destruction"
- **m_DeathParticle**: resource_name:"particles/environment/spirit_orb_vault_death.vpcf"
- **m_flHealthBarOffset**: 101
- **m_bGiveGoldOnHit**: True
- **m_bOrbDropper**: True
- **m_flPhysicsImpulseMultiplier**: 0
- **m_flDyingDuration**: 2.2
- **m_vecIntrinsicModifiers**:
  | subclass |
  | --- |
  | {'_my_subclass_name': 'neutral_vault_tech_immune', '_class': 'modifier_intrinsic_base', 'm_nEnabledStateMask': 'MODIFIER_STATE_TECH_UNTARGETABLE | MODIFIER_STATE_TECH_INVULNERABLE'} |

---

# NPC: neutral_trashbug

- **m_WeaponInfo**:
  - **m_Spread**: 0.5
  - **m_StandingSpread**: 1.5
  - **m_flScatterYawScale**: 1
  - **m_flShootingUpSpreadPenalty**: 5
  - **m_flZoomMoveSpeedPercent**: 0.7
  - **m_flShootMoveSpeedPercent**: 0.7
  - **m_flHorizontalPunch**: 0
  - **m_flVerticalPunch**: 0
  - **m_flRecoilRecoverySpeed**: 10.0
  - **m_VerticallRecoil**:
    - **m_Range**:
      - -0.2
      - 0.2
    - **m_flBurstSlope**: 0.0
    - **m_flBurstExponent**: 0.0
    - **m_flBurstConstant**: 0.0
  - **m_HorizontalRecoil**:
    - **m_Range**:
      - -0.1
      - 0.1
    - **m_flBurstExponent**: 0.0
  - **m_flRecoilSpeed**: 1
  - **m_flZoomFOV**: 40.0
  - **m_flDamageFalloffStartRange**: 1500
  - **m_flDamageFalloffEndRange**: 1500
  - **m_flRange**: 1500
  - **m_flBulletLifetime**: 2
  - **m_flDamageFalloffEndScale**: 0.3
  - **m_flDamageFalloffBias**: 0.5
  - **m_iBullets**: 1
  - **m_flCycleTime**: 0.5
  - **m_reloadDuration**: 0.25
  - **m_iClipSize**: -1
  - **m_iBurstShotCount**: 1
  - **m_flBurstShotCooldown**: 0
  - **m_flBulletGravityScale**: 0.0
  - **m_flBulletRadius**: 3
  - **m_flBulletDrag**: 1
  - **m_flBulletDragBias**: 0.5
  - **m_flBulletReflectScale**: 0
  - **m_flBulletReflectAmount**: 1
  - **m_flBulletInheritShooterVelocityScale**: 0
  - **m_szBulletTravelTracerParticle**: resource_name:"particles/weapon_fx/trooper/trooper_bullet_travel.vpcf"
  - **m_szMuzzleFlashEffectName**: resource_name:"particles/dev/bullet_debug_muzzle_flash.vpcf"
  - **m_strShootSound**: soundevent:"TrooperRifle.Fire"
  - **m_strBulletWhizSound**: soundevent:"Base.Bullet.Whizby"
  - **m_BulletSpeedCurve**:
    - **m_spline**:
      | x | y | m_flSlopeIncoming | m_flSlopeOutgoing |
      | --- | --- | --- | --- |
      | 0.0 | 13000.0 | 0.0 | 0.0 |
      | 100.0 | 13000.0 | 0.0 | 0.0 |
    - **m_tangents**:
      | m_nIncomingTangent | m_nOutgoingTangent |
      | --- | --- |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
    - **m_vDomainMins**:
      - 0.0
      - 1.0
    - **m_vDomainMaxs**:
      - 100.0
      - 13000.0
  - **m_mapImpactEffects**:
    - **default**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Default.BulletImpact"
    - **flesh**:
      - **m_strDecal**: 
      - **m_strParticle**: resource_name:"particles/blood_impact/blood_impact_red_01.vpcf"
      - **m_strSound**: soundevent:"Flesh.BulletImpact"
    - **concrete**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Concrete.BulletImpact"
    - **solidmetal**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"SolidMetal.BulletImpact"
    - **portals**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Player.HitInvuln"
  - **m_flCritBonusStart**: 1.15
  - **m_flCritBonusEnd**: 1.35
  - **m_flCritBonusStartRange**: 500.0
  - **m_flCritBonusEndRange**: 1500.0
  - **m_flCritBonusAgainstNPCs**: 0.25
  - **m_flShootSpreadPenaltyPerShot**: 0.0
  - **m_flShootSpreadPenaltyDecayDelay**: 0.0
  - **m_flShootSpreadPenaltyDecay**: 2.0
  - **m_flRecoilShotIndexRecoveryTimeFactor**: 0.25
  - **m_bCanZoom**: True
  - **m_strWeaponImpactEffect**: resource_name:"particles/weapon_fx/default_tracer_impact.vpcf"
  - **m_flReloadMoveSpeed**: 236.22
  - **m_strLocalPlayerBulletImpactSound**: soundevent:"Player.Bullet.Impact.Default"
  - **m_flAutoReplenishClip**: 4
  - **m_NpcAimingSpread**:
    - 0.2
    - 0.6
  - **m_flBulletDamage**: 3.0
- **_base**: neutral_trooper_weak
- **_class**: npc_trooper_neutral
- **m_ShieldParticle**: resource_name:""
- **m_flSightRangePlayers**: 2000.0
- **m_flMaxHealthBarDrawDistance**: 800
- **m_flShieldReactivateDelay**: 2.0
- **m_flGoldReward**: 44
- **m_flGoldRewardBonusPercentPerMinute**: 1.2
- **m_strLastHitSound**: soundevent:"LastHit.Default"
- **m_sModelName**: resource_name:"models/npc/trash_bug/trash_bug_drone.vmdl"
- **m_flModelScale**: 0.28
- **m_nMaxHealth**: 200
- **m_hFootstepSounds**: citadel
- **m_sDefaultMaterialGroupName**: 
- **m_flHealthBarOffset**: 84
- **m_bCapSimultanousAttackers**: True
- **m_bFaceEnemyWhileIdle**: True
- **m_flPhysicsImpulseMultiplier**: 0.0
- **m_DeathParticle**: resource_name:"particles/npc/neutral_trooper_death.vpcf"
- **m_vecIntrinsicModifiers**:
  | subclass |
  | --- |
  | {'_my_subclass_name': 'weak_neutral_bullet_armor', '_class': 'modifier_intrinsic_base', 'm_mapAutoRegisterModifierValueFromAbilityPropertyName': {}, 'm_vecScriptValues': [{'m_eModifierValue': 'MODIFIER_VALUE_BULLET_DAMAGE_REDUCTION_PERCENT', 'm_value': 50.0}, {'m_eModifierValue': 'MODIFIER_VALUE_ABILITY_DAMAGE_REDUCTION_PERCENT', 'm_value': 30.0}]} |
- **m_eTrooperType**: NEUTRAL_TROOPER_WEAK
- **m_flHullCapsuleRadius**: 90.0
- **m_flHullCapsuleHeight**: 130.0
- **m_sEnemyMaterialGroupName**: 

---

# NPC: neutral_gargoyle

- **m_WeaponInfo**:
  - **m_Spread**: 0.5
  - **m_StandingSpread**: 1.5
  - **m_flScatterYawScale**: 1
  - **m_flShootingUpSpreadPenalty**: 5
  - **m_flZoomMoveSpeedPercent**: 0.7
  - **m_flShootMoveSpeedPercent**: 0.7
  - **m_flHorizontalPunch**: 0
  - **m_flVerticalPunch**: 0
  - **m_flRecoilRecoverySpeed**: 10.0
  - **m_VerticallRecoil**:
    - **m_Range**:
      - -0.2
      - 0.2
    - **m_flBurstSlope**: 0.0
    - **m_flBurstExponent**: 0.0
    - **m_flBurstConstant**: 0.0
  - **m_HorizontalRecoil**:
    - **m_Range**:
      - -0.1
      - 0.1
    - **m_flBurstExponent**: 0.0
  - **m_flRecoilSpeed**: 1
  - **m_flZoomFOV**: 40.0
  - **m_flDamageFalloffStartRange**: 1500
  - **m_flDamageFalloffEndRange**: 1500
  - **m_flRange**: 1500
  - **m_flBulletLifetime**: 2
  - **m_flDamageFalloffEndScale**: 0.3
  - **m_flDamageFalloffBias**: 0.5
  - **m_iBullets**: 1
  - **m_flCycleTime**: 0.5
  - **m_reloadDuration**: 0.25
  - **m_iClipSize**: -1
  - **m_iBurstShotCount**: 1
  - **m_flBurstShotCooldown**: 0
  - **m_flBulletGravityScale**: 0.0
  - **m_flBulletRadius**: 16
  - **m_flBulletDrag**: 1
  - **m_flBulletDragBias**: 0.5
  - **m_flBulletReflectScale**: 0
  - **m_flBulletReflectAmount**: 1
  - **m_flBulletInheritShooterVelocityScale**: 0
  - **m_szBulletTravelTracerParticle**: resource_name:"particles/weapon_fx/npc/neutral_gargoyle_tracer.vpcf"
  - **m_szMuzzleFlashEffectName**: resource_name:"particles/dev/bullet_debug_muzzle_flash.vpcf"
  - **m_strShootSound**: soundevent:"Neutral.Gargoyle.Shoot"
  - **m_strBulletWhizSound**: soundevent:"Neutral.Gargoyle.Whizby.Base"
  - **m_BulletSpeedCurve**:
    - **m_spline**:
      | x | y | m_flSlopeIncoming | m_flSlopeOutgoing |
      | --- | --- | --- | --- |
      | 0.0 | 1800.0 | 0.0 | 0.0 |
      | 100.0 | 1800.0 | 0.0 | 0.0 |
    - **m_tangents**:
      | m_nIncomingTangent | m_nOutgoingTangent |
      | --- | --- |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
    - **m_vDomainMins**:
      - 0.0
      - 1.0
    - **m_vDomainMaxs**:
      - 100.0
      - 1800.0
  - **m_mapImpactEffects**:
    - **default**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Default.BulletImpact"
    - **flesh**:
      - **m_strDecal**: 
      - **m_strParticle**: resource_name:"particles/blood_impact/blood_impact_red_01.vpcf"
      - **m_strSound**: soundevent:"Flesh.BulletImpact"
    - **concrete**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Concrete.BulletImpact"
    - **solidmetal**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"SolidMetal.BulletImpact"
    - **portals**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Player.HitInvuln"
  - **m_flCritBonusStart**: 1.15
  - **m_flCritBonusEnd**: 1.35
  - **m_flCritBonusStartRange**: 500.0
  - **m_flCritBonusEndRange**: 1500.0
  - **m_flCritBonusAgainstNPCs**: 0.25
  - **m_flShootSpreadPenaltyPerShot**: 0.0
  - **m_flShootSpreadPenaltyDecayDelay**: 0.0
  - **m_flShootSpreadPenaltyDecay**: 2.0
  - **m_flRecoilShotIndexRecoveryTimeFactor**: 0.25
  - **m_bCanZoom**: True
  - **m_strWeaponImpactEffect**: resource_name:"particles/weapon_fx/npc/neutral_gargoyle_tracer_impact.vpcf"
  - **m_flReloadMoveSpeed**: 236.22
  - **m_strLocalPlayerBulletImpactSound**: soundevent:"SushiBot.Blade.Impact"
  - **m_flAutoReplenishClip**: 6
  - **m_NpcAimingSpread**:
    - 0.2
    - 0.6
  - **m_flBulletDamage**: 18.5
- **_base**: neutral_trooper_strong
- **_class**: npc_trooper_neutral
- **m_ShieldParticle**: resource_name:""
- **m_flSightRangePlayers**: 2000.0
- **m_flMaxHealthBarDrawDistance**: 800
- **m_flShieldReactivateDelay**: 2.0
- **m_flGoldReward**: 220
- **m_flGoldRewardBonusPercentPerMinute**: 1.2
- **m_strLastHitSound**: soundevent:"LastHit.Default"
- **m_sModelName**: resource_name:"models/npc/gargoyle/neutral_gargoyle.vmdl"
- **m_flModelScale**: 0.525
- **m_nMaxHealth**: 1760
- **m_hFootstepSounds**: citadel
- **m_sDefaultMaterialGroupName**: 
- **m_flHealthBarOffset**: 84
- **m_bFaceEnemyWhileIdle**: True
- **m_flPhysicsImpulseMultiplier**: 0.0
- **m_DeathParticle**: resource_name:"particles/npc/neutral_trooper_death.vpcf"
- **m_vecIntrinsicModifiers**:
  | subclass |
  | --- |
  | {'_my_subclass_name': 'strong_neutral_bullet_armor', '_class': 'modifier_intrinsic_base', 'm_vecScriptValues': [{'m_eModifierValue': 'MODIFIER_VALUE_BULLET_DAMAGE_REDUCTION_PERCENT', 'm_value': 60.0}, {'m_eModifierValue': 'MODIFIER_VALUE_ABILITY_DAMAGE_REDUCTION_PERCENT', 'm_value': 35.0}], 'm_strParticleEffect': 'resource_name:"particles/npc/neutral_strong_ambient_flame.vpcf"'} |
- **m_eTrooperType**: NEUTRAL_TROOPER_STRONG
- **m_vecAttachments**:
- **m_flHullCapsuleHeight**: 200.0
- **m_flHullCapsuleRadius**: 100.0
- **m_sEnemyMaterialGroupName**: 
- **m_bHasAOEAttack**: False
- **m_flAOERadius**: 600.0
- **m_flAOEDamage**: 100.0
- **m_flAOEAttackCooldown**: 8.0
- **m_AOEParticle**: resource_name:"particles/abilities/sumo_stomp.vpcf"
- **m_AOESound**: soundevent:"Neutral.Gargoyle.StompImpact"
- **m_AOEInitiateSound**: soundevent:"Neutral.Gargoyle.StompInitiate"

---

# NPC: neutral_trooper_strong

- **m_WeaponInfo**:
  - **m_Spread**: 0.5
  - **m_StandingSpread**: 1.5
  - **m_flScatterYawScale**: 1
  - **m_flShootingUpSpreadPenalty**: 5
  - **m_flZoomMoveSpeedPercent**: 0.7
  - **m_flShootMoveSpeedPercent**: 0.7
  - **m_flHorizontalPunch**: 0
  - **m_flVerticalPunch**: 0
  - **m_flRecoilRecoverySpeed**: 10.0
  - **m_VerticallRecoil**:
    - **m_Range**:
      - -0.2
      - 0.2
    - **m_flBurstSlope**: 0.0
    - **m_flBurstExponent**: 0.0
    - **m_flBurstConstant**: 0.0
  - **m_HorizontalRecoil**:
    - **m_Range**:
      - -0.1
      - 0.1
    - **m_flBurstExponent**: 0.0
  - **m_flRecoilSpeed**: 1
  - **m_flZoomFOV**: 40.0
  - **m_flDamageFalloffStartRange**: 1500
  - **m_flDamageFalloffEndRange**: 1500
  - **m_flRange**: 1500
  - **m_flBulletLifetime**: 2
  - **m_flDamageFalloffEndScale**: 0.3
  - **m_flDamageFalloffBias**: 0.5
  - **m_iBullets**: 1
  - **m_flCycleTime**: 0.5
  - **m_reloadDuration**: 0.25
  - **m_iClipSize**: -1
  - **m_iBurstShotCount**: 1
  - **m_flBurstShotCooldown**: 0
  - **m_flBulletGravityScale**: 0.0
  - **m_flBulletRadius**: 3
  - **m_flBulletDrag**: 1
  - **m_flBulletDragBias**: 0.5
  - **m_flBulletReflectScale**: 0
  - **m_flBulletReflectAmount**: 1
  - **m_flBulletInheritShooterVelocityScale**: 0
  - **m_szBulletTravelTracerParticle**: resource_name:"particles/weapon_fx/trooper/trooper_bullet_travel.vpcf"
  - **m_szMuzzleFlashEffectName**: resource_name:"particles/dev/bullet_debug_muzzle_flash.vpcf"
  - **m_strShootSound**: soundevent:"TrooperRifle.Fire"
  - **m_strBulletWhizSound**: soundevent:"Base.Bullet.Whizby"
  - **m_BulletSpeedCurve**:
    - **m_spline**:
      | x | y | m_flSlopeIncoming | m_flSlopeOutgoing |
      | --- | --- | --- | --- |
      | 0.0 | 13000.0 | 0.0 | 0.0 |
      | 100.0 | 13000.0 | 0.0 | 0.0 |
    - **m_tangents**:
      | m_nIncomingTangent | m_nOutgoingTangent |
      | --- | --- |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
    - **m_vDomainMins**:
      - 0.0
      - 1.0
    - **m_vDomainMaxs**:
      - 100.0
      - 13000.0
  - **m_mapImpactEffects**:
    - **default**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Default.BulletImpact"
    - **flesh**:
      - **m_strDecal**: 
      - **m_strParticle**: resource_name:"particles/blood_impact/blood_impact_red_01.vpcf"
      - **m_strSound**: soundevent:"Flesh.BulletImpact"
    - **concrete**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Concrete.BulletImpact"
    - **solidmetal**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"SolidMetal.BulletImpact"
    - **portals**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Player.HitInvuln"
  - **m_flCritBonusStart**: 1.15
  - **m_flCritBonusEnd**: 1.35
  - **m_flCritBonusStartRange**: 500.0
  - **m_flCritBonusEndRange**: 1500.0
  - **m_flCritBonusAgainstNPCs**: 0.25
  - **m_flShootSpreadPenaltyPerShot**: 0.0
  - **m_flShootSpreadPenaltyDecayDelay**: 0.0
  - **m_flShootSpreadPenaltyDecay**: 2.0
  - **m_flRecoilShotIndexRecoveryTimeFactor**: 0.25
  - **m_bCanZoom**: True
  - **m_strWeaponImpactEffect**: resource_name:"particles/weapon_fx/default_tracer_impact.vpcf"
  - **m_flReloadMoveSpeed**: 236.22
  - **m_strLocalPlayerBulletImpactSound**: soundevent:"Player.Bullet.Impact.Default"
  - **m_flAutoReplenishClip**: 6
  - **m_NpcAimingSpread**:
    - 0.2
    - 0.6
  - **m_flBulletDamage**: 10
- **_base**: neutral_base
- **_class**: npc_trooper_neutral
- **m_ShieldParticle**: resource_name:""
- **m_flSightRangePlayers**: 2000.0
- **m_flMaxHealthBarDrawDistance**: 800
- **m_flShieldReactivateDelay**: 2.0
- **m_flGoldReward**: 220
- **m_flGoldRewardBonusPercentPerMinute**: 1.2
- **m_strLastHitSound**: soundevent:"LastHit.Default"
- **m_sModelName**: resource_name:"models/npc/trooper/trooper_mid_boss.vmdl"
- **m_flModelScale**: 0.525
- **m_nMaxHealth**: 1760
- **m_hFootstepSounds**: citadel
- **m_sDefaultMaterialGroupName**: Neutral_Strong
- **m_flHealthBarOffset**: 250.0
- **m_bFaceEnemyWhileIdle**: True
- **m_flPhysicsImpulseMultiplier**: 0.0
- **m_DeathParticle**: resource_name:"particles/npc/neutral_trooper_death.vpcf"
- **m_vecIntrinsicModifiers**:
  | subclass |
  | --- |
  | {'_my_subclass_name': 'strong_neutral_bullet_armor', '_class': 'modifier_intrinsic_base', 'm_vecScriptValues': [{'m_eModifierValue': 'MODIFIER_VALUE_BULLET_DAMAGE_REDUCTION_PERCENT', 'm_value': 60.0}, {'m_eModifierValue': 'MODIFIER_VALUE_ABILITY_DAMAGE_REDUCTION_PERCENT', 'm_value': 35.0}], 'm_strParticleEffect': 'resource_name:"particles/npc/neutral_strong_ambient_flame.vpcf"'} |
- **m_eTrooperType**: NEUTRAL_TROOPER_STRONG
- **m_vecAttachments**:
- **m_flHullCapsuleHeight**: 200.0
- **m_flHullCapsuleRadius**: 100.0

---

# NPC: npc_boss_tier2

- **_class**: npc_boss_tier2
- **m_sModelName**: resource_name:"models/npc/boss_tier_02_sun_walker/boss_tier_02_sun_walker.vmdl"
- **m_nMaxHealth**: 5800
- **m_flSightRangePlayers**: 1600.0
- **m_flSightRangeNPCs**: 1600.0
- **m_flPlayerInitialSightRange**: 1200.0
- **m_hFootstepSounds**: citadel
- **m_strLastHitSound**: soundevent:"LastHit.Default"
- **m_navHull**: 2
- **m_mapBoundAbilities**:
  - **ESlot_Weapon_Primary**: citadel_weapon_bosstier2_set
  - **ESlot_Signature_1**: citadel_ability_tier2boss_rocket_barrage
  - **ESlot_Signature_2**: citadel_ability_tier2boss_laser_beam
  - **ESlot_Signature_3**: citadel_ability_tier2boss_stomp
- **m_sDefaultMaterialGroupName**: friendly
- **m_sEnemyMaterialGroupName**: enemy
- **m_StompImpactEffect**: resource_name:"particles/npc/tier2boss/tier2boss_stomp.vpcf"
- **m_flStompDamage**: 350.0
- **m_flStunDuration**: 2.0
- **m_flMeleeAttemptRange**: 600.0
- **m_flStompImpactRadius**: 905.51
- **m_flStompImpactHeight**: 236.22
- **m_flStompTossUpMagnitude**: 1.25
- **m_flTossSpeed**: 400.0
- **m_flSweepRadius**: 200.0
- **m_flSweepZScale**: 0.5
- **m_flSweepSpeed**: 1200.0
- **m_flSweepMaxAngle**: 0.0
- **m_flSweepMaxRange**: 0.0
- **m_flSweepAdjustSpeed**: 500.0
- **m_flHealthBarOffset**: 400.0
- **m_flBurstDuration**: 1.0
- **m_flBurstCooldown**: 0.2
- **m_flPhysicsImpulseMultiplier**: 0.0
- **m_vecWeakPoints**:
  | m_strName | m_eBreakBehavior | m_nHitGroup | m_nHealth | m_nMaxHealth | m_nOnBreakBonusDamage | m_strOnBreakAnimGraphParam |
  | --- | --- | --- | --- | --- | --- | --- |
  | head | EBreakOnceRemainDamagable | HITGROUP_T2_BOSS_HEAD_WEAKPOINT | 1000 | 1000 | 100 | stagger_s |
  | canister | EBreakOnceRemainDamagable | HITGROUP_T2_BOSS_BACK_WEAKPOINT | 1000 | 1000 | 100 | stagger_n |
  | joint_rear_left | EBreakOnceRemainDamagable | HITGROUP_T2_BOSS_REAR_LEFT_LEG_WEAKPOINT | 1000 | 1000 | 100 | stagger_ne |
  | joint_rear_right | EBreakOnceBecomeInvuln | HITGROUP_T2_BOSS_REAR_RIGHT_LEG_WEAKPOINT | 1000 | 1000 | 100 | stagger_nw |
- **m_BeamChargingEffect**: resource_name:"particles/npc/tier2boss/tier2boss_electric_beam_charge.vpcf"
- **m_BeamPreviewEffect**: resource_name:"particles/npc/tier2boss/tier2boss_pretarget.vpcf"
- **m_BeamActiveEffect**: resource_name:"particles/npc/tier2boss/tier2boss_laser_beam.vpcf"
- **m_flModelScale**: 1.0
- **m_strWIPModelName**: resource_name:"models/npc/boss_tier_02_sun_walker/boss_tier_02_sun_walker.vmdl"
- **m_sTeam1MaterialGroupName**: Amber
- **m_sTeam2MaterialGroupName**: Sapphire
- **m_BackdoorProtectionModifier**:
  - **subclass**:
    - **_class**: modifier_citadel_backdoor_protection
    - **_my_subclass_name**: tier2_backdoor_protection
    - **m_flHealthPerSecondRegen**: 65.0
    - **m_flBackdoorProtectionDamageMitigationFromPlayers**: 65.0
    - **m_strParticleEffect**: resource_name:""
    - **m_ShieldImpactParticle**: resource_name:"particles/generic/backdoor_protection_impact.vpcf"
    - **flShieldImpactDirectionOffset**: 50.0
    - **m_strParticleEffectConfig**: 
    - **m_ShieldActiveParticle**: resource_name:"particles/generic/backdoor_protection_aura.vpcf"
    - **m_strActiveEffectConfigName**: tier2
- **m_flInvulModifierRange**: 1200
- **m_InvulModifier**:
  - **subclass**:
    - **_my_subclass_name**: modifier_boss_invuln
    - **_class**: modifier_boss_invuln
    - **m_flShieldRadius**: 300
    - **m_ShieldParticle**: resource_name:"particles/trooper/tier2_boss_invulerability_shield.vpcf"

---

# NPC: alt_npc_boss_tier2

- **_class**: npc_boss_tier2
- **m_sModelName**: resource_name:"models/npc/boss_tier_02_sun_walker/boss_tier_02_sun_walker.vmdl"
- **m_nMaxHealth**: 5800
- **m_flSightRangePlayers**: 1600.0
- **m_flSightRangeNPCs**: 1600.0
- **m_flPlayerInitialSightRange**: 1200.0
- **m_hFootstepSounds**: citadel
- **m_strLastHitSound**: soundevent:"LastHit.Default"
- **m_navHull**: 2
- **m_mapBoundAbilities**:
  - **ESlot_Weapon_Primary**: citadel_weapon_bosstier2_set
  - **ESlot_Signature_1**: citadel_ability_tier2boss_rocket_barrage
  - **ESlot_Signature_2**: citadel_ability_tier2boss_laser_beam
  - **ESlot_Signature_3**: citadel_ability_tier2boss_stomp
- **m_sDefaultMaterialGroupName**: friendly
- **m_sEnemyMaterialGroupName**: enemy
- **m_StompImpactEffect**: resource_name:"particles/npc/tier2boss/tier2boss_stomp.vpcf"
- **m_flStompDamage**: 350.0
- **m_flStunDuration**: 2.0
- **m_flMeleeAttemptRange**: 600.0
- **m_flStompImpactRadius**: 905.51
- **m_flStompImpactHeight**: 236.22
- **m_flStompTossUpMagnitude**: 1.25
- **m_flTossSpeed**: 400.0
- **m_flSweepRadius**: 200.0
- **m_flSweepZScale**: 0.5
- **m_flSweepSpeed**: 1200.0
- **m_flSweepMaxAngle**: 0.0
- **m_flSweepMaxRange**: 0.0
- **m_flSweepAdjustSpeed**: 500.0
- **m_flHealthBarOffset**: 400.0
- **m_flBurstDuration**: 1.0
- **m_flBurstCooldown**: 0.2
- **m_flPhysicsImpulseMultiplier**: 0.0
- **m_vecWeakPoints**:
  | m_strName | m_eBreakBehavior | m_nHitGroup | m_nHealth | m_nMaxHealth | m_nOnBreakBonusDamage | m_strOnBreakAnimGraphParam |
  | --- | --- | --- | --- | --- | --- | --- |
  | head | EBreakOnceRemainDamagable | HITGROUP_T2_BOSS_HEAD_WEAKPOINT | 1000 | 1000 | 100 | stagger_s |
  | canister | EBreakOnceRemainDamagable | HITGROUP_T2_BOSS_BACK_WEAKPOINT | 1000 | 1000 | 100 | stagger_n |
  | joint_rear_left | EBreakOnceRemainDamagable | HITGROUP_T2_BOSS_REAR_LEFT_LEG_WEAKPOINT | 1000 | 1000 | 100 | stagger_ne |
  | joint_rear_right | EBreakOnceBecomeInvuln | HITGROUP_T2_BOSS_REAR_RIGHT_LEG_WEAKPOINT | 1000 | 1000 | 100 | stagger_nw |
- **m_BeamChargingEffect**: resource_name:"particles/npc/tier2boss/tier2boss_electric_beam_charge.vpcf"
- **m_BeamPreviewEffect**: resource_name:"particles/npc/tier2boss/tier2boss_pretarget.vpcf"
- **m_BeamActiveEffect**: resource_name:"particles/npc/tier2boss/tier2boss_laser_beam.vpcf"
- **m_flModelScale**: 1.0
- **m_strWIPModelName**: resource_name:"models/npc/boss_tier_02_sun_walker/boss_tier_02_sun_walker.vmdl"
- **m_sTeam1MaterialGroupName**: Amber
- **m_sTeam2MaterialGroupName**: Sapphire
- **m_BackdoorProtectionModifier**:
  - **subclass**:
    - **_class**: modifier_citadel_backdoor_protection
    - **_my_subclass_name**: tier2_backdoor_protection
    - **m_flHealthPerSecondRegen**: 65.0
    - **m_flBackdoorProtectionDamageMitigationFromPlayers**: 65.0
    - **m_strParticleEffect**: resource_name:""
    - **m_ShieldImpactParticle**: resource_name:"particles/generic/backdoor_protection_impact.vpcf"
    - **flShieldImpactDirectionOffset**: 50.0
    - **m_strParticleEffectConfig**: 
    - **m_ShieldActiveParticle**: resource_name:"particles/generic/backdoor_protection_aura.vpcf"
    - **m_strActiveEffectConfigName**: tier2
- **m_flInvulModifierRange**: 1200
- **m_InvulModifier**:
  - **subclass**:
    - **_my_subclass_name**: modifier_boss_invuln
    - **_class**: modifier_boss_invuln
    - **m_flShieldRadius**: 300
    - **m_ShieldParticle**: resource_name:"particles/trooper/tier2_boss_invulerability_shield.vpcf"
- **_base**: npc_boss_tier2

---

# NPC: npc_boss_tier2_weak

- **_class**: npc_boss_tier2
- **m_sModelName**: resource_name:"models/npc/boss_tier_02_sun_walker/boss_tier_02_sun_walker.vmdl"
- **m_nMaxHealth**: 5175
- **m_flSightRangePlayers**: 1600.0
- **m_flSightRangeNPCs**: 1600.0
- **m_flPlayerInitialSightRange**: 1200.0
- **m_hFootstepSounds**: citadel
- **m_strLastHitSound**: soundevent:"LastHit.Default"
- **m_navHull**: 2
- **m_mapBoundAbilities**:
  - **ESlot_Weapon_Primary**: citadel_weapon_bosstier2_set
  - **ESlot_Signature_1**: citadel_ability_tier2boss_rocket_barrage
  - **ESlot_Signature_2**: citadel_ability_tier2boss_laser_beam
  - **ESlot_Signature_3**: citadel_ability_tier2boss_stomp
- **m_sDefaultMaterialGroupName**: friendly
- **m_sEnemyMaterialGroupName**: enemy
- **m_StompImpactEffect**: resource_name:"particles/npc/tier2boss/tier2boss_stomp.vpcf"
- **m_flStompDamage**: 350.0
- **m_flStunDuration**: 2.0
- **m_flMeleeAttemptRange**: 600.0
- **m_flStompImpactRadius**: 905.51
- **m_flStompImpactHeight**: 236.22
- **m_flStompTossUpMagnitude**: 1.25
- **m_flTossSpeed**: 400.0
- **m_flSweepRadius**: 200.0
- **m_flSweepZScale**: 0.5
- **m_flSweepSpeed**: 1200.0
- **m_flSweepMaxAngle**: 0.0
- **m_flSweepMaxRange**: 0.0
- **m_flSweepAdjustSpeed**: 500.0
- **m_flHealthBarOffset**: 400.0
- **m_flBurstDuration**: 1.0
- **m_flBurstCooldown**: 0.2
- **m_flPhysicsImpulseMultiplier**: 0.0
- **m_vecWeakPoints**:
  | m_strName | m_eBreakBehavior | m_nHitGroup | m_nHealth | m_nMaxHealth | m_nOnBreakBonusDamage | m_strOnBreakAnimGraphParam |
  | --- | --- | --- | --- | --- | --- | --- |
  | head | EBreakOnceRemainDamagable | HITGROUP_T2_BOSS_HEAD_WEAKPOINT | 1000 | 1000 | 100 | stagger_s |
  | canister | EBreakOnceRemainDamagable | HITGROUP_T2_BOSS_BACK_WEAKPOINT | 1000 | 1000 | 100 | stagger_n |
  | joint_rear_left | EBreakOnceRemainDamagable | HITGROUP_T2_BOSS_REAR_LEFT_LEG_WEAKPOINT | 1000 | 1000 | 100 | stagger_ne |
  | joint_rear_right | EBreakOnceBecomeInvuln | HITGROUP_T2_BOSS_REAR_RIGHT_LEG_WEAKPOINT | 1000 | 1000 | 100 | stagger_nw |
- **m_BeamChargingEffect**: resource_name:"particles/npc/tier2boss/tier2boss_electric_beam_charge.vpcf"
- **m_BeamPreviewEffect**: resource_name:"particles/npc/tier2boss/tier2boss_pretarget.vpcf"
- **m_BeamActiveEffect**: resource_name:"particles/npc/tier2boss/tier2boss_laser_beam.vpcf"
- **m_flModelScale**: 1.0
- **m_strWIPModelName**: resource_name:"models/npc/boss_tier_02_sun_walker/boss_tier_02_sun_walker.vmdl"
- **m_sTeam1MaterialGroupName**: Amber
- **m_sTeam2MaterialGroupName**: Sapphire
- **m_BackdoorProtectionModifier**:
  - **subclass**:
    - **_class**: modifier_citadel_backdoor_protection
    - **_my_subclass_name**: tier2_backdoor_protection
    - **m_flHealthPerSecondRegen**: 65.0
    - **m_flBackdoorProtectionDamageMitigationFromPlayers**: 65.0
    - **m_strParticleEffect**: resource_name:""
    - **m_ShieldImpactParticle**: resource_name:"particles/generic/backdoor_protection_impact.vpcf"
    - **flShieldImpactDirectionOffset**: 50.0
    - **m_strParticleEffectConfig**: 
    - **m_ShieldActiveParticle**: resource_name:"particles/generic/backdoor_protection_aura.vpcf"
    - **m_strActiveEffectConfigName**: tier2
- **m_flInvulModifierRange**: 1200
- **m_InvulModifier**:
  - **subclass**:
    - **_my_subclass_name**: modifier_boss_invuln
    - **_class**: modifier_boss_invuln
    - **m_flShieldRadius**: 300
    - **m_ShieldParticle**: resource_name:"particles/trooper/tier2_boss_invulerability_shield.vpcf"
- **_base**: npc_boss_tier2

---

# NPC: alt_npc_boss_tier2_weak

- **_class**: npc_boss_tier2
- **m_sModelName**: resource_name:"models/npc/boss_tier_02_sun_walker/boss_tier_02_sun_walker.vmdl"
- **m_nMaxHealth**: 5175
- **m_flSightRangePlayers**: 1600.0
- **m_flSightRangeNPCs**: 1600.0
- **m_flPlayerInitialSightRange**: 1200.0
- **m_hFootstepSounds**: citadel
- **m_strLastHitSound**: soundevent:"LastHit.Default"
- **m_navHull**: 2
- **m_mapBoundAbilities**:
  - **ESlot_Weapon_Primary**: citadel_weapon_bosstier2_set
  - **ESlot_Signature_1**: citadel_ability_tier2boss_rocket_barrage
  - **ESlot_Signature_2**: citadel_ability_tier2boss_laser_beam
  - **ESlot_Signature_3**: citadel_ability_tier2boss_stomp
- **m_sDefaultMaterialGroupName**: friendly
- **m_sEnemyMaterialGroupName**: enemy
- **m_StompImpactEffect**: resource_name:"particles/npc/tier2boss/tier2boss_stomp.vpcf"
- **m_flStompDamage**: 350.0
- **m_flStunDuration**: 2.0
- **m_flMeleeAttemptRange**: 600.0
- **m_flStompImpactRadius**: 905.51
- **m_flStompImpactHeight**: 236.22
- **m_flStompTossUpMagnitude**: 1.25
- **m_flTossSpeed**: 400.0
- **m_flSweepRadius**: 200.0
- **m_flSweepZScale**: 0.5
- **m_flSweepSpeed**: 1200.0
- **m_flSweepMaxAngle**: 0.0
- **m_flSweepMaxRange**: 0.0
- **m_flSweepAdjustSpeed**: 500.0
- **m_flHealthBarOffset**: 400.0
- **m_flBurstDuration**: 1.0
- **m_flBurstCooldown**: 0.2
- **m_flPhysicsImpulseMultiplier**: 0.0
- **m_vecWeakPoints**:
  | m_strName | m_eBreakBehavior | m_nHitGroup | m_nHealth | m_nMaxHealth | m_nOnBreakBonusDamage | m_strOnBreakAnimGraphParam |
  | --- | --- | --- | --- | --- | --- | --- |
  | head | EBreakOnceRemainDamagable | HITGROUP_T2_BOSS_HEAD_WEAKPOINT | 1000 | 1000 | 100 | stagger_s |
  | canister | EBreakOnceRemainDamagable | HITGROUP_T2_BOSS_BACK_WEAKPOINT | 1000 | 1000 | 100 | stagger_n |
  | joint_rear_left | EBreakOnceRemainDamagable | HITGROUP_T2_BOSS_REAR_LEFT_LEG_WEAKPOINT | 1000 | 1000 | 100 | stagger_ne |
  | joint_rear_right | EBreakOnceBecomeInvuln | HITGROUP_T2_BOSS_REAR_RIGHT_LEG_WEAKPOINT | 1000 | 1000 | 100 | stagger_nw |
- **m_BeamChargingEffect**: resource_name:"particles/npc/tier2boss/tier2boss_electric_beam_charge.vpcf"
- **m_BeamPreviewEffect**: resource_name:"particles/npc/tier2boss/tier2boss_pretarget.vpcf"
- **m_BeamActiveEffect**: resource_name:"particles/npc/tier2boss/tier2boss_laser_beam.vpcf"
- **m_flModelScale**: 1.0
- **m_strWIPModelName**: resource_name:"models/npc/boss_tier_02_sun_walker/boss_tier_02_sun_walker.vmdl"
- **m_sTeam1MaterialGroupName**: Amber
- **m_sTeam2MaterialGroupName**: Sapphire
- **m_BackdoorProtectionModifier**:
  - **subclass**:
    - **_class**: modifier_citadel_backdoor_protection
    - **_my_subclass_name**: tier2_backdoor_protection
    - **m_flHealthPerSecondRegen**: 65.0
    - **m_flBackdoorProtectionDamageMitigationFromPlayers**: 65.0
    - **m_strParticleEffect**: resource_name:""
    - **m_ShieldImpactParticle**: resource_name:"particles/generic/backdoor_protection_impact.vpcf"
    - **flShieldImpactDirectionOffset**: 50.0
    - **m_strParticleEffectConfig**: 
    - **m_ShieldActiveParticle**: resource_name:"particles/generic/backdoor_protection_aura.vpcf"
    - **m_strActiveEffectConfigName**: tier2
- **m_flInvulModifierRange**: 1200
- **m_InvulModifier**:
  - **subclass**:
    - **_my_subclass_name**: modifier_boss_invuln
    - **_class**: modifier_boss_invuln
    - **m_flShieldRadius**: 300
    - **m_ShieldParticle**: resource_name:"particles/trooper/tier2_boss_invulerability_shield.vpcf"
- **_base**: npc_boss_tier2_weak

---

# NPC: npc_boss_tier3

- **_class**: npc_boss_tier3
- **m_sModelName**: resource_name:"models/npc/titan_v2/titan.vmdl"
- **m_nMaxHealth**: 10000
- **m_hFootstepSounds**: citadel
- **m_mapBoundAbilities**:
  - **ESlot_Weapon_Primary**: citadel_weapon_bosstier3_set
  - **ESlot_Signature_1**: citadel_ability_tier3boss_laser_beam
  - **ESlot_Signature_2**: citadel_ability_tier3boss_damage_pulse
- **m_sDefaultMaterialGroupName**: Friendly
- **m_sEnemyMaterialGroupName**: Enemy
- **m_flModelScale**: 1.0
- **m_LaserBeamModifier**:
  - **subclass**:
    - **_my_subclass_name**: modifier_tier3boss_electric_beam
    - **_class**: modifier_tier3boss_electric_beam
- **m_flHealthBarOffset**: 0.0
- **m_LaserChargingParticle**: resource_name:"particles/npc/tier3boss/tier3_boss_beam_charge.vpcf"
- **m_DeathLargeExplosionParticle**: resource_name:"particles/npc/tier3boss/tier3_boss_death_finale.vpcf"
- **m_WeakpointBrokenExplosionParticle**: resource_name:"particles/abilities/heavy_barrage_projectile_impact_explode.vpcf"
- **m_DeathSmallExplosionParticle**: resource_name:"particles/abilities/heavy_barrage_projectile_impact_explode.vpcf"
- **m_LaserBeamEffect**: resource_name:"particles/npc/tier3boss/tier3_boss_beam.vpcf"
- **m_LaserDamageEffect**: resource_name:"particles/modifiers/beam_damage.vpcf"
- **m_flPhysicsImpulseMultiplier**: 0
- **m_LaserPreviewEffect**: resource_name:"particles/npc/tier3boss/tier3_boss_beam_preview.vpcf"
- **m_flLaserTargetingZOffset**: 75.0
- **m_flDefaultMoveSpeed**: 200.0
- **m_flLaserDPSToPlayers**: 440.0
- **m_flLaserDPSToNPCs**: 80.0
- **m_flLaserTrackingSpeed**: 1000.0
- **m_flLaserTrackingMaxSpeed**: 1000.0
- **m_flLaserCastingTrackSpeed**: 10000.0
- **m_flLaserCastingTrackMaxSpeed**: 10000.0
- **m_flNoShieldMoveSpeed**: 500.0
- **m_flNoShieldLaserDPSToPlayers**: 780
- **m_flNoShieldLaserDPSToNPCs**: 210
- **m_flNoShieldLaserTrackingSpeed**: 2000.0
- **m_flNoShieldLaserTrackingMaxSpeed**: 2000.0
- **m_flNoShieldLaserCastingTrackSpeed**: 20000.0
- **m_flNoShieldLaserCastingTrackMaxSpeed**: 20000.0
- **m_LaserSound**: soundevent:"Ability.Tier2Boss.LaserBeam.Fire"
- **m_DyingModifier**:
  - **subclass**:
    - **_class**: modifier_base
    - **_my_subclass_name**: dying
    - **m_nEnabledStateMask**: MODIFIER_STATE_INVULNERABLE | MODIFIER_STATE_TECH_INVULNERABLE | MODIFIER_STATE_TECH_DAMAGE_INVULNERABLE | MODIFIER_STATE_TECH_UNTARGETABLE_BY_ENEMIES | MODIFIER_STATE_STATUS_IMMUNE | MODIFIER_STATE_UNKILLABLE
    - **m_strParticleEffect**: resource_name:"particles/npc/tier3boss/tier3_boss_death.vpcf"
- **m_VulnerableModifier**:
  - **subclass**:
    - **_my_subclass_name**: vulnerable
    - **_class**: modifier_base
- **m_flMovingToFinalPositionSpeed**: 20.0
- **m_ChargeUpExplosionParticle**: resource_name:"particles/npc/tier3boss/tier3_boss_death_chargeup.vpcf"
- **m_DyingSmallExplosion**: soundevent:"Boss.Titan.DeathSmallExplode"
- **m_Phase1Modifier**:
  - **subclass**:
    - **_my_subclass_name**: phase1
    - **_class**: modifier_base
    - **m_nEnabledStateMask**: MODIFIER_STATE_UNKILLABLE
- **m_PatronKilledSound**: soundevent:"Patron.DeathExplode"
- **m_AvatarKilledSound**: soundevent:"Boss.Titan.BecomeVulnerable"
- **m_AvatarBecomePatronSound**: soundevent:"Boss.Titan.BecomeVulnerable"
- **m_sTeam1MaterialGroupName**: Amber
- **m_sTeam2MaterialGroupName**: Sapphire
- **m_flSightRangePlayers**: 3000.0
- **m_flSightRangeNPCs**: 3000.0
- **m_BackdoorProtection**:
  - **subclass**:
    - **_class**: modifier_citadel_backdoor_protection
    - **_my_subclass_name**: tier3_backdoor_protection
    - **m_ShieldActiveParticle**: resource_name:"particles/generic/backdoor_protection_aura.vpcf"
    - **m_strActiveEffectConfigName**: tier3
    - **m_flHealthPerSecondRegen**: 75.0
    - **m_flBackdoorProtectionDamageMitigationFromPlayers**: 65.0
    - **m_ShieldImpactParticle**: resource_name:"particles/generic/backdoor_protection_impact.vpcf"
- **m_ObjectiveRegen**:
  - **subclass**:
    - **_class**: modifier_citadel_objective_regen
    - **_my_subclass_name**: tier3_regen
    - **m_flOutOfCombatHealthRegen**: 120.0
    - **m_flOutOfCombatRegenDelay**: 20.0

---

# NPC: alt_npc_boss_tier3

- **_class**: npc_boss_tier3
- **m_sModelName**: resource_name:"models/npc/titan_v2/titan.vmdl"
- **m_nMaxHealth**: 10000
- **m_hFootstepSounds**: citadel
- **m_mapBoundAbilities**:
  - **ESlot_Weapon_Primary**: citadel_weapon_bosstier3_set
  - **ESlot_Signature_1**: citadel_ability_tier3boss_laser_beam
  - **ESlot_Signature_2**: citadel_ability_tier3boss_damage_pulse
- **m_sDefaultMaterialGroupName**: Friendly
- **m_sEnemyMaterialGroupName**: Enemy
- **m_flModelScale**: 1.0
- **m_LaserBeamModifier**:
  - **subclass**:
    - **_my_subclass_name**: modifier_tier3boss_electric_beam
    - **_class**: modifier_tier3boss_electric_beam
- **m_flHealthBarOffset**: 0.0
- **m_LaserChargingParticle**: resource_name:"particles/npc/tier3boss/tier3_boss_beam_charge.vpcf"
- **m_DeathLargeExplosionParticle**: resource_name:"particles/npc/tier3boss/tier3_boss_death_finale.vpcf"
- **m_WeakpointBrokenExplosionParticle**: resource_name:"particles/abilities/heavy_barrage_projectile_impact_explode.vpcf"
- **m_DeathSmallExplosionParticle**: resource_name:"particles/abilities/heavy_barrage_projectile_impact_explode.vpcf"
- **m_LaserBeamEffect**: resource_name:"particles/npc/tier3boss/tier3_boss_beam.vpcf"
- **m_LaserDamageEffect**: resource_name:"particles/modifiers/beam_damage.vpcf"
- **m_flPhysicsImpulseMultiplier**: 0
- **m_LaserPreviewEffect**: resource_name:"particles/npc/tier3boss/tier3_boss_beam_preview.vpcf"
- **m_flLaserTargetingZOffset**: 75.0
- **m_flDefaultMoveSpeed**: 200.0
- **m_flLaserDPSToPlayers**: 440.0
- **m_flLaserDPSToNPCs**: 80.0
- **m_flLaserTrackingSpeed**: 1000.0
- **m_flLaserTrackingMaxSpeed**: 1000.0
- **m_flLaserCastingTrackSpeed**: 10000.0
- **m_flLaserCastingTrackMaxSpeed**: 10000.0
- **m_flNoShieldMoveSpeed**: 500.0
- **m_flNoShieldLaserDPSToPlayers**: 780
- **m_flNoShieldLaserDPSToNPCs**: 210
- **m_flNoShieldLaserTrackingSpeed**: 2000.0
- **m_flNoShieldLaserTrackingMaxSpeed**: 2000.0
- **m_flNoShieldLaserCastingTrackSpeed**: 20000.0
- **m_flNoShieldLaserCastingTrackMaxSpeed**: 20000.0
- **m_LaserSound**: soundevent:"Ability.Tier2Boss.LaserBeam.Fire"
- **m_DyingModifier**:
  - **subclass**:
    - **_class**: modifier_base
    - **_my_subclass_name**: dying
    - **m_nEnabledStateMask**: MODIFIER_STATE_INVULNERABLE | MODIFIER_STATE_TECH_INVULNERABLE | MODIFIER_STATE_TECH_DAMAGE_INVULNERABLE | MODIFIER_STATE_TECH_UNTARGETABLE_BY_ENEMIES | MODIFIER_STATE_STATUS_IMMUNE | MODIFIER_STATE_UNKILLABLE
    - **m_strParticleEffect**: resource_name:"particles/npc/tier3boss/tier3_boss_death.vpcf"
- **m_VulnerableModifier**:
  - **subclass**:
    - **_my_subclass_name**: vulnerable
    - **_class**: modifier_base
- **m_flMovingToFinalPositionSpeed**: 20.0
- **m_ChargeUpExplosionParticle**: resource_name:"particles/npc/tier3boss/tier3_boss_death_chargeup.vpcf"
- **m_DyingSmallExplosion**: soundevent:"Boss.Titan.DeathSmallExplode"
- **m_Phase1Modifier**:
  - **subclass**:
    - **_my_subclass_name**: phase1
    - **_class**: modifier_base
    - **m_nEnabledStateMask**: MODIFIER_STATE_UNKILLABLE
- **m_PatronKilledSound**: soundevent:"Patron.DeathExplode"
- **m_AvatarKilledSound**: soundevent:"Boss.Titan.BecomeVulnerable"
- **m_AvatarBecomePatronSound**: soundevent:"Boss.Titan.BecomeVulnerable"
- **m_sTeam1MaterialGroupName**: Amber
- **m_sTeam2MaterialGroupName**: Sapphire
- **m_flSightRangePlayers**: 3000.0
- **m_flSightRangeNPCs**: 3000.0
- **m_BackdoorProtection**:
  - **subclass**:
    - **_class**: modifier_citadel_backdoor_protection
    - **_my_subclass_name**: tier3_backdoor_protection
    - **m_ShieldActiveParticle**: resource_name:"particles/generic/backdoor_protection_aura.vpcf"
    - **m_strActiveEffectConfigName**: tier3
    - **m_flHealthPerSecondRegen**: 75.0
    - **m_flBackdoorProtectionDamageMitigationFromPlayers**: 65.0
    - **m_ShieldImpactParticle**: resource_name:"particles/generic/backdoor_protection_impact.vpcf"
- **m_ObjectiveRegen**:
  - **subclass**:
    - **_class**: modifier_citadel_objective_regen
    - **_my_subclass_name**: tier3_regen
    - **m_flOutOfCombatHealthRegen**: 120.0
    - **m_flOutOfCombatRegenDelay**: 20.0
- **_base**: npc_boss_tier3

---

# NPC: npc_yakuza_kobun_summon

- **m_WeaponInfo**:
  - **m_Spread**: 0.5
  - **m_StandingSpread**: 1.5
  - **m_flScatterYawScale**: 1
  - **m_flShootingUpSpreadPenalty**: 0
  - **m_flZoomMoveSpeedPercent**: 0.7
  - **m_flShootMoveSpeedPercent**: 0.7
  - **m_flHorizontalPunch**: 0
  - **m_flVerticalPunch**: 0
  - **m_flRecoilRecoverySpeed**: 10.0
  - **m_VerticallRecoil**:
    - **m_Range**:
      - -0.2
      - 0.2
    - **m_flBurstSlope**: 0.0
    - **m_flBurstExponent**: 0.0
    - **m_flBurstConstant**: 0.0
  - **m_HorizontalRecoil**:
    - **m_Range**:
      - -0.1
      - 0.1
    - **m_flBurstExponent**: 0.0
  - **m_flRecoilSpeed**: 1
  - **m_flZoomFOV**: 40.0
  - **m_flDamageFalloffStartRange**: 2000.0
  - **m_flDamageFalloffEndRange**: 3000.0
  - **m_flRange**: 3500.0
  - **m_flBulletLifetime**: 2
  - **m_flDamageFalloffEndScale**: 0.3
  - **m_flDamageFalloffBias**: 0.5
  - **m_iBullets**: 5
  - **m_flCycleTime**: 0.5
  - **m_reloadDuration**: 1.5
  - **m_iClipSize**: 10
  - **m_iBurstShotCount**: 1
  - **m_flBurstShotCooldown**: 0
  - **m_flBulletGravityScale**: 0.8
  - **m_flBulletRadius**: 3
  - **m_flBulletDrag**: 1
  - **m_flBulletDragBias**: 0.5
  - **m_flBulletReflectScale**: 0
  - **m_flBulletReflectAmount**: 1
  - **m_flBulletInheritShooterVelocityScale**: 0
  - **m_szBulletTravelTracerParticle**: resource_name:"particles/weapon_fx/default_tracer.vpcf"
  - **m_szMuzzleFlashEffectName**: resource_name:"particles/dev/bullet_debug_muzzle_flash.vpcf"
  - **m_strShootSound**: soundevent:"Forge.Turret.Shoot"
  - **m_strBulletWhizSound**: soundevent:"Base.Bullet.Whizby"
  - **m_BulletSpeedCurve**:
    - **m_spline**:
      | x | y | m_flSlopeIncoming | m_flSlopeOutgoing |
      | --- | --- | --- | --- |
      | 0.0 | 5000.0 | 0.0 | 0.0 |
      | 100.0 | 5000.0 | 0.0 | 0.0 |
    - **m_tangents**:
      | m_nIncomingTangent | m_nOutgoingTangent |
      | --- | --- |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
    - **m_vDomainMins**:
      - 0.0
      - 1.0
    - **m_vDomainMaxs**:
      - 100.0
      - 5000.0
  - **m_mapImpactEffects**:
    - **default**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Default.BulletImpact"
    - **flesh**:
      - **m_strDecal**: 
      - **m_strParticle**: resource_name:"particles/blood_impact/blood_impact_red_01.vpcf"
      - **m_strSound**: soundevent:"Flesh.BulletImpact"
    - **concrete**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Concrete.BulletImpact"
    - **solidmetal**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"SolidMetal.BulletImpact"
    - **portals**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Player.HitInvuln"
  - **m_flCritBonusStart**: 1.15
  - **m_flCritBonusEnd**: 1.35
  - **m_flCritBonusStartRange**: 500.0
  - **m_flCritBonusEndRange**: 1500.0
  - **m_flCritBonusAgainstNPCs**: 0.25
  - **m_flShootSpreadPenaltyPerShot**: 0.0
  - **m_flShootSpreadPenaltyDecayDelay**: 0.0
  - **m_flShootSpreadPenaltyDecay**: 2.0
  - **m_flRecoilShotIndexRecoveryTimeFactor**: 0.25
  - **m_bCanZoom**: True
  - **m_strWeaponImpactEffect**: resource_name:"particles/weapon_fx/default_tracer_impact.vpcf"
  - **m_flReloadMoveSpeed**: 236.22
  - **m_strLocalPlayerBulletImpactSound**: soundevent:"Player.Bullet.Impact.Default"
  - **m_vecScatterOffsets**:
    - - 0.0
      - 0.0
    - - -1.0
      - 0.0
    - - 1.0
      - 0.0
    - - 0.0
      - -1.0
    - - 0.0
      - 1.0
  - **m_flPelletScatterFactor**: 2.0
  - **m_flBulletDamage**: 5.0
- **_class**: npc_hero_clone_trooper
- **m_flSightRange**: 1000.0
- **m_hFootstepSounds**: citadel
- **m_bMeleeOnly**: False
- **m_bChargeForward**: False
- **m_flMeleeAttemptRange**: 100.0
- **m_flMeleeHitRange**: 100.0
- **m_flAcceleration**: 600
- **m_flMeleeChargeRange**: 0
- **m_MeleeActivateParticle**: resource_name:"particles/npc/npc_melee_activate.vpcf"
- **m_MeleeSwingParticle**: resource_name:"particles/npc/npc_melee_swing.vpcf"
- **m_strAmbientLoopSound**: soundevent:""
- **m_sModelName**: resource_name:"models/heroes_staging/gen_man/gen_man.vmdl"
- **m_flModelScale**: 1.0
- **m_bCloneOwnerWeapon**: False
- **_base**: weapon_base
- **m_bFaceTargetEvenWhenMoving**: True

---

# NPC: npc_shielded_sentry

- **_class**: npc_shielded_sentry
- **m_sModelName**: resource_name:"models/props_gameplay/turret/turret.vmdl"
- **m_LaserSightParticle**: resource_name:"particles/abilities/engineer/engineer_sentry_laser_sight.vpcf"
- **m_KillExplosionParticle**: resource_name:"particles/abilities/engineer/engineer_sentry_death.vpcf"
- **m_sSpawnSound**: soundevent:"Forge.Turret.Place"
- **m_sKillExplosionSound**: soundevent:"Forge.Turret.Explosion"
- **m_sTargetAcquiredLocalSound**: soundevent:"Forge.Turret.LockOn.LocalClient"
- **m_sTargetAcquiredSound**: soundevent:"Forge.Turret.LockOn"
- **m_flIdleTurnSpeed**: 15.0
- **m_DeployProgressModifier**:
  - **subclass**:
    - **_class**: modifier_base
    - **_my_subclass_name**: modifier_sentry_deploy
    - **m_sLocalizationName**: modifier_sentry_deploy
    - **m_bDrawOverheadStatus**: True
    - **m_bReverseHudProgressBar**: True
- **m_flIdleTurnAngles**: 60.0
- **m_flTrooperTakeDamageMult**: 0.5
- **m_flNearDeathDuration**: 0.8
- **m_NearDeathModifier**:
  - **subclass**:
    - **_class**: modifier_near_death_fx
    - **_my_subclass_name**: modifier_near_death_fx
    - **m_EnemyNearDeathParticle**: resource_name:"particles/status_fx/status_fx_last_hit.vpcf"
    - **m_FriendlyNearDeathParticle**: resource_name:"particles/status_fx/status_fx_last_hit_friend.vpcf"
    - **m_sSelfDestructStart**: soundevent:"Trooper.SelfDestruct_Start"
    - **m_sSelfDestructEnd**: soundevent:"Trooper.SelfDestruct_Exp"
- **m_IntrinsicModifier**:
  - **subclass**:
    - **_class**: modifier_base
    - **_my_subclass_name**: modifier_sentry_instrinsic
    - **m_nEnabledStateMask**: MODIFIER_STATE_TAKES_FULLDAMAGE_NO_FALLOFF
- **m_flZShootPostionOffset**: 25.0

---

# NPC: npc_yakuza_gangster

- **_class**: npc_yakuza_gangster
- **m_sModelName**: resource_name:"models/heroes_staging/gen_man/gen_man.vmdl"
- **m_flSightRange**: 1600.0
- **m_flMeleeAttemptRange**: 0.0

---

# NPC: citadel_bounce_pad

- **_class**: citadel_bounce_pad
- **m_strOtherHeroBounceSound**: soundevent:"Ability.Astro.BouncePad.Solo"
- **m_strCasterBounceSound**: soundevent:"Ability.Astro.BouncePad.Launch"
- **m_strBarrelBounceSound**: soundevent:"Ability.Astro.BouncePad.Solo"
- **m_strExpiredSound**: soundevent:"Astro.BouncePad.Expire"
- **m_DestroyParticle**: resource_name:"particles/abilities/astro/astro_bounce_pad_destroy.vpcf"
- **m_BounceParticle**: resource_name:"particles/abilities/astro/astro_bounce_pad_bounce.vpcf"
- **m_IdleParticle**: resource_name:"particles/abilities/astro/astro_bounce_pad.vpcf"
- **m_sModelName**: resource_name:"models/particle/cowboy_launchpad.vmdl"

---

# NPC: citadel_viscous_ball

- **_class**: citadel_viscous_ball
- **m_sModelName**: resource_name:"models/heroes_staging/viscous/viscous_inflated.vmdl"
- **m_flPhysicsRadius**: 40.0

---

# NPC: npc_base_defense_sentry

- **_class**: npc_base_defense_sentry
- **m_sModelName**: resource_name:"models/npc/gargoyle/neutral_gargoyle.vmdl"
- **m_SentryExplosionParticle**: resource_name:"particles/weapon_fx/weapon_grenade_explosion.vpcf"
- **m_AbilityWeapon**: citadel_weapon_base_defense_turret
- **m_flPhysicsImpulseMultiplier**: 0
- **m_flTimeToStartScale**: 15.0
- **m_flTimeToEndScale**: 50.0
- **m_flMaxScale**: 2.0

---

# NPC: neutral_whack_a_ghost

- **m_WeaponInfo**:
  - **m_Spread**: 0.5
  - **m_StandingSpread**: 1.5
  - **m_flScatterYawScale**: 1
  - **m_flShootingUpSpreadPenalty**: 5
  - **m_flZoomMoveSpeedPercent**: 0.7
  - **m_flShootMoveSpeedPercent**: 0.7
  - **m_flHorizontalPunch**: 0
  - **m_flVerticalPunch**: 0
  - **m_flRecoilRecoverySpeed**: 10.0
  - **m_VerticallRecoil**:
    - **m_Range**:
      - -0.2
      - 0.2
    - **m_flBurstSlope**: 0.0
    - **m_flBurstExponent**: 0.0
    - **m_flBurstConstant**: 0.0
  - **m_HorizontalRecoil**:
    - **m_Range**:
      - -0.1
      - 0.1
    - **m_flBurstExponent**: 0.0
  - **m_flRecoilSpeed**: 1
  - **m_flZoomFOV**: 40.0
  - **m_flDamageFalloffStartRange**: 1500
  - **m_flDamageFalloffEndRange**: 1500
  - **m_flRange**: 1500
  - **m_flBulletLifetime**: 2
  - **m_flDamageFalloffEndScale**: 0.3
  - **m_flDamageFalloffBias**: 0.5
  - **m_iBullets**: 1
  - **m_flCycleTime**: 0.5
  - **m_reloadDuration**: 0.25
  - **m_iClipSize**: -1
  - **m_iBurstShotCount**: 1
  - **m_flBurstShotCooldown**: 0
  - **m_flBulletGravityScale**: 0.0
  - **m_flBulletRadius**: 3
  - **m_flBulletDrag**: 1
  - **m_flBulletDragBias**: 0.5
  - **m_flBulletReflectScale**: 0
  - **m_flBulletReflectAmount**: 1
  - **m_flBulletInheritShooterVelocityScale**: 0
  - **m_szBulletTravelTracerParticle**: resource_name:"particles/weapon_fx/npc/neutral_gargoyle_tracer.vpcf"
  - **m_szMuzzleFlashEffectName**: resource_name:"particles/dev/bullet_debug_muzzle_flash.vpcf"
  - **m_strShootSound**: soundevent:"Neutral.Gargoyle.Shoot"
  - **m_strBulletWhizSound**: soundevent:"Neutral.Gargoyle.Whizby.Base"
  - **m_BulletSpeedCurve**:
    - **m_spline**:
      | x | y | m_flSlopeIncoming | m_flSlopeOutgoing |
      | --- | --- | --- | --- |
      | 0.0 | 900.0 | 0.0 | 0.0 |
      | 100.0 | 900.0 | 0.0 | 0.0 |
    - **m_tangents**:
      | m_nIncomingTangent | m_nOutgoingTangent |
      | --- | --- |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
    - **m_vDomainMins**:
      - 0.0
      - 1.0
    - **m_vDomainMaxs**:
      - 100.0
      - 900.0
  - **m_mapImpactEffects**:
    - **default**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Default.BulletImpact"
    - **flesh**:
      - **m_strDecal**: 
      - **m_strParticle**: resource_name:"particles/blood_impact/blood_impact_red_01.vpcf"
      - **m_strSound**: soundevent:"Flesh.BulletImpact"
    - **concrete**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Concrete.BulletImpact"
    - **solidmetal**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"SolidMetal.BulletImpact"
    - **portals**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Player.HitInvuln"
  - **m_flCritBonusStart**: 1.15
  - **m_flCritBonusEnd**: 1.35
  - **m_flCritBonusStartRange**: 500.0
  - **m_flCritBonusEndRange**: 1500.0
  - **m_flCritBonusAgainstNPCs**: 0.25
  - **m_flShootSpreadPenaltyPerShot**: 0.0
  - **m_flShootSpreadPenaltyDecayDelay**: 0.0
  - **m_flShootSpreadPenaltyDecay**: 2.0
  - **m_flRecoilShotIndexRecoveryTimeFactor**: 0.25
  - **m_bCanZoom**: True
  - **m_strWeaponImpactEffect**: resource_name:"particles/weapon_fx/npc/neutral_gargoyle_tracer_impact.vpcf"
  - **m_flReloadMoveSpeed**: 236.22
  - **m_strLocalPlayerBulletImpactSound**: soundevent:"SushiBot.Blade.Impact"
  - **m_flAutoReplenishClip**: 4
  - **m_NpcAimingSpread**:
    - 0.2
    - 0.6
  - **m_flBulletDamage**: 10.0
- **_base**: neutral_trooper_normal
- **_class**: npc_trooper_node_mover
- **m_ShieldParticle**: resource_name:""
- **m_flSightRangePlayers**: 2000.0
- **m_flMaxHealthBarDrawDistance**: 800
- **m_flShieldReactivateDelay**: 2.0
- **m_flGoldReward**: 88
- **m_flGoldRewardBonusPercentPerMinute**: 1.2
- **m_strLastHitSound**: soundevent:"LastHit.Default"
- **m_sModelName**: resource_name:"models/npc/box_ghost/box_ghost.vmdl"
- **m_flModelScale**: 0.375
- **m_nMaxHealth**: 500
- **m_hFootstepSounds**: citadel
- **m_sDefaultMaterialGroupName**: 
- **m_flHealthBarOffset**: 84
- **m_bFaceEnemyWhileIdle**: False
- **m_flPhysicsImpulseMultiplier**: 0.0
- **m_DeathParticle**: resource_name:"particles/npc/neutral_trooper_death_fireball.vpcf"
- **m_vecIntrinsicModifiers**:
  | subclass |
  | --- |
  | {'_my_subclass_name': 'normal_neutral_bullet_armor', '_class': 'modifier_intrinsic_base', 'm_vecScriptValues': [{'m_eModifierValue': 'MODIFIER_VALUE_ABILITY_DAMAGE_REDUCTION_PERCENT', 'm_value': 50.0}]} |
- **m_flHullCapsuleRadius**: 90.0
- **m_flHullCapsuleHeight**: 170.0
- **m_sEnemyMaterialGroupName**: 
- **m_bEnableMovementToNodes**: True
- **m_eTrooperType**: NEUTRAL_WHACK_A_GHOST
- **m_MoveType**: MOVETYPE_NOCLIP
- **m_flExposedDuration**:
  - 0.25
  - 1.5
- **m_flHideDuration**:
  - 2.0
  - 3.0
- **m_flWalkSpeed**: 400.0
- **m_HidingModifier**:
  - **subclass**:
    - **_class**: modifier_base
    - **_my_subclass_name**: hiding
    - **m_nEnabledStateMask**: MODIFIER_STATE_INVULNERABLE | MODIFIER_STATE_TECH_UNTARGETABLE_BY_ENEMIES | MODIFIER_STATE_IGNORE_BULLETS | MODIFIER_STATE_IGNORE_MELEE

---

# NPC: npc_field_sentry

- **_class**: npc_field_sentry
- **m_DeployProgressModifier**:
  - **subclass**:
    - **_my_subclass_name**: modifier_sentry_deploy
    - **_class**: modifier_base
- **m_sModelName**: resource_name:"models/heroes_staging/engineer/turret/turret.vmdl"
- **m_LaserSightParticle**: resource_name:"particles/abilities/engineer/engineer_sentry_laser_sight.vpcf"
- **m_KillExplosionParticle**: resource_name:"particles/weapon_fx/weapon_grenade_explosion.vpcf"
- **m_sSpawnSound**: soundevent:"Forge.Turret.Place"
- **m_sKillExplosionSound**: soundevent:"Forge.Turret.Explosion"
- **m_sTargetAcquiredLocalSound**: soundevent:"Forge.Turret.LockOn.LocalClient"
- **m_sTargetAcquiredSound**: soundevent:"Forge.Turret.LockOn"
- **m_flIdleTurnSpeed**: 15.0
- **m_flIdleTurnAngles**: 60.0

---

# NPC: npc_player_bot_brain

- **_class**: npc_player_bot_brain
- **m_flSightRangePlayers**: 1600.0
- **m_flSightRangeNPCs**: 1600.0
- **m_flSightRange**: 1600.0
- **m_flTurnRate**: 15.0
- **m_flFaceTargetDistance**: 1200.0
- **m_flJumpMaxRise**: 350.0
- **m_flAirJumpMin**: 200.0
- **m_flJumpMaxDrop**: 1024.0
- **m_flJumpMaxDist**: 200.0
- **m_flJumpMinDist**: 50.0
- **m_flClimbUpCostBase**: 32.0
- **m_flClimbUpCostScalar**: 0.5
- **m_flVerticalAttachOffset**: 16.0
- **m_flNavGoalTolerance**: 32.0
- **m_flStuckTime**: 1.5
- **m_flStuckTimeAir**: 3.0
- **m_flMaxPathDistance**: 1300.0
- **m_flMinLanePathDistance**: 250.0
- **m_flEnemyDistanceForReload**: 1200
- **m_flReloadEnemyFarPct**: 0.5
- **m_flReloadEnemyLoSPct**: 0.5
- **m_flReloadEnemyLosTime**: 0.5
- **m_flMinShootTimeToReload**: 0.75
- **m_flDashDamageThreshold**: 0.05
- **m_flDashDamageTickDown**: 0.2
- **m_flMinDesiredDashDist**: 200.0
- **m_flDisengageFromEnemyToLaneDist**: 1200.0
- **m_flDefendBaseSearchRadius**: 1800.0

---

# NPC: bullet_time_warp

- **_class**: bullet_time_warp
- **m_TimeWallHitParticle**: resource_name:"particles/abilities/chrono/chrono_time_stop_entry.vpcf"
- **m_TimeWallHitTimerParticle**: resource_name:"particles/abilities/chrono/chrono_time_wall_bullet_hit.vpcf"

---

# NPC: alt_super_trooper_medic

- **m_WeaponInfo**:
  - **m_Spread**: 0.5
  - **m_StandingSpread**: 1.5
  - **m_flScatterYawScale**: 1
  - **m_flShootingUpSpreadPenalty**: 2
  - **m_flZoomMoveSpeedPercent**: 0.7
  - **m_flShootMoveSpeedPercent**: 0.7
  - **m_flHorizontalPunch**: 0
  - **m_flVerticalPunch**: 0
  - **m_flRecoilRecoverySpeed**: 10.0
  - **m_VerticallRecoil**:
    - **m_Range**:
      - -0.2
      - 0.2
    - **m_flBurstSlope**: 0.0
    - **m_flBurstExponent**: 0.0
    - **m_flBurstConstant**: 0.0
  - **m_HorizontalRecoil**:
    - **m_Range**:
      - -0.1
      - 0.1
    - **m_flBurstExponent**: 0.0
  - **m_flRecoilSpeed**: 1
  - **m_flZoomFOV**: 40.0
  - **m_flDamageFalloffStartRange**: 600
  - **m_flDamageFalloffEndRange**: 1400
  - **m_flRange**: 1400
  - **m_flBulletLifetime**: 2
  - **m_flDamageFalloffEndScale**: 0.3
  - **m_flDamageFalloffBias**: 0.5
  - **m_iBullets**: 1
  - **m_flCycleTime**: 1.03
  - **m_reloadDuration**: 1.8
  - **m_iClipSize**: -1
  - **m_iBurstShotCount**: 1
  - **m_flBurstShotCooldown**: 0
  - **m_flBulletGravityScale**: 0.0
  - **m_flBulletRadius**: 3
  - **m_flBulletDrag**: 1
  - **m_flBulletDragBias**: 0.5
  - **m_flBulletReflectScale**: 0
  - **m_flBulletReflectAmount**: 1
  - **m_flBulletInheritShooterVelocityScale**: 0
  - **m_szBulletTravelTracerParticle**: resource_name:"particles/weapon_fx/trooper/trooper_bullet_travel.vpcf"
  - **m_szMuzzleFlashEffectName**: resource_name:"particles/dev/bullet_debug_muzzle_flash.vpcf"
  - **m_strShootSound**: soundevent:"TrooperRifle.Fire"
  - **m_strBulletWhizSound**: soundevent:"Base.Bullet.Whizby"
  - **m_BulletSpeedCurve**:
    - **m_spline**:
      | x | y | m_flSlopeIncoming | m_flSlopeOutgoing |
      | --- | --- | --- | --- |
      | 0.0 | 12000.0 | 0.0 | 0.0 |
      | 100.0 | 12000.0 | 0.0 | 0.0 |
    - **m_tangents**:
      | m_nIncomingTangent | m_nOutgoingTangent |
      | --- | --- |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
    - **m_vDomainMins**:
      - 0.0
      - 1.0
    - **m_vDomainMaxs**:
      - 100.0
      - 12000.0
  - **m_mapImpactEffects**:
    - **default**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Default.BulletImpact"
    - **flesh**:
      - **m_strDecal**: 
      - **m_strParticle**: resource_name:"particles/blood_impact/blood_impact_red_01.vpcf"
      - **m_strSound**: soundevent:"Flesh.BulletImpact"
    - **concrete**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Concrete.BulletImpact"
    - **solidmetal**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"SolidMetal.BulletImpact"
    - **portals**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Player.HitInvuln"
  - **m_flCritBonusStart**: 1.15
  - **m_flCritBonusEnd**: 1.35
  - **m_flCritBonusStartRange**: 500.0
  - **m_flCritBonusEndRange**: 1500.0
  - **m_flCritBonusAgainstNPCs**: 0.25
  - **m_flShootSpreadPenaltyPerShot**: 0.0
  - **m_flShootSpreadPenaltyDecayDelay**: 0.0
  - **m_flShootSpreadPenaltyDecay**: 2.0
  - **m_flRecoilShotIndexRecoveryTimeFactor**: 0.25
  - **m_bCanZoom**: True
  - **m_strWeaponImpactEffect**: resource_name:"particles/weapon_fx/default_tracer_impact.vpcf"
  - **m_flReloadMoveSpeed**: 236.22
  - **m_strLocalPlayerBulletImpactSound**: soundevent:"Player.Bullet.Impact.Trooper"
  - **m_NpcAimingSpread**:
    - 0.2
    - 0.8
  - **m_flBulletDamage**: 36
- **_base**: super_trooper_medic
- **_class**: npc_super_trooper
- **m_sModelName**: resource_name:"models/npc/medic/super_medic_model.vmdl"
- **m_nMaxHealth**: 260
- **m_flSightRangePlayers**: 700.0
- **m_flSightRangeNPCs**: 1600.0
- **m_hFootstepSounds**: trooper
- **m_flTrooperDamageResistPct**: 55.0
- **m_flT1BossDamageResistPct**: 35.0
- **m_flT2BossDamageResistPct**: 20.0
- **m_flShieldDamageResistPct**: 80.0
- **m_flNearDeathDuration**: 1.0
- **m_flWalkSpeed**: 240
- **m_flRunSpeed**: 433
- **m_flAcceleration**: 200
- **m_flMeleeDamage**: 25.0
- **m_flMeleeAttemptRange**: 100
- **m_flMeleeHitRange**: 100
- **m_flMeleeDuration**: 1.0
- **m_flAttackT1BossMaxRange**: 540
- **m_flAttackTrooperMaxRange**: 700
- **m_BossAttackParticle**: resource_name:"particles/weapon_fx/trooper/trooper_bullet_bonus_dmg.vpcf"
- **m_sDefaultMaterialGroupName**: FriendlyMedic
- **m_sEnemyMaterialGroupName**: EnemyMedic
- **m_flMeleeChargeRange**: 0
- **m_flHealthBarOffset**: 76.0
- **m_flHealthBarOffsetDucking**: 40
- **m_DeathParticle**: resource_name:"particles/trooper/trooper_death_sn.vpcf"
- **m_DeathSound**: soundevent:"Trooper.Death"
- **m_MeleeHitSound**: soundevent:"Trooper.Melee.Damage.Hit"
- **m_MeleeHitPlayerSound**: soundevent:"Player.Damage.Melee.Trooper.Impact"
- **m_HealthBarParticle**: resource_name:"particles/npc/npc_healthbar.vpcf"
- **m_sHealthBarAttachment**: head_fx
- **m_HealthBarColorFriend**:
  - 255
  - 239
  - 215
- **m_HealthBarColorEnemy**:
  - 230
  - 25
  - 25
- **m_HealthBarColorTeam1**:
  - 231
  - 182
  - 89
- **m_HealthBarColorTeam2**:
  - 91
  - 121
  - 230
- **m_HealthBarColorTeamNeutral**:
  - 0
  - 125
  - 125
- **m_MeleeSwingParticle**: resource_name:"particles/abilities/melee_swing.vpcf"
- **m_MeleeActivateParticle**: resource_name:"particles/abilities/melee/melee_activate.vpcf"
- **m_MeleeAnimName**: b_melee
- **m_LastHitParticle**: resource_name:"particles/generic/last_hit.vpcf"
- **m_strLastHitSound**: soundevent:"LastHit.Default"
- **m_bPlayLastHitSound**: True
- **m_NearDeathModifier**:
  - **subclass**:
    - **_class**: modifier_near_death_fx
    - **_my_subclass_name**: modifier_near_death_fx
    - **m_EnemyNearDeathParticle**: resource_name:"particles/status_fx/status_fx_last_hit.vpcf"
    - **m_FriendlyNearDeathParticle**: resource_name:"particles/status_fx/status_fx_last_hit_friend.vpcf"
    - **m_sSelfDestructStart**: soundevent:"Trooper.SelfDestruct_Start"
    - **m_sSelfDestructEnd**: soundevent:"Trooper.SelfDestruct_Exp"
- **m_TargetingLaserParticle**: resource_name:"particles/weapon_fx/trooper_laser_target.vpcf"
- **m_TargetingEyeFlashParticle**: resource_name:"particles/enemy_targeting_indicator.vpcf"
- **m_sCelebrationSound**: soundevent:"Trooper.Objective.Win.Cheer"
- **m_flBarrackGuardianDamageResistPct**: 67.5
- **m_sTeam1MaterialGroupName**: Amber
- **m_sTeam2MaterialGroupName**: Sapphire
- **m_flT1BossDPS**: 83.6
- **m_flT2BossDPS**: 209.0
- **m_flT3BossDPS**: 209.0
- **m_flGeneratorBossDPS**: 41.8
- **m_flBarrackBossDPS**: 209.0
- **m_flPlayerDPS**: 42.0
- **m_flTrooperDPS**: 66.5
- **m_TrooperType**: TROOPER_MEDIC
- **m_mapBoundAbilities**:
  - **ESlot_Signature_2**: ability_medic_trooper_heal
- **m_MedicHealActiveParticle**: resource_name:"particles/trooper/trooper_medic_chargeup.vpcf"
- **m_flModelScale**: 1.1

---

# NPC: alt_super_trooper_melee

- **m_WeaponInfo**:
  - **m_Spread**: 0.5
  - **m_StandingSpread**: 1.5
  - **m_flScatterYawScale**: 1
  - **m_flShootingUpSpreadPenalty**: 2
  - **m_flZoomMoveSpeedPercent**: 0.7
  - **m_flShootMoveSpeedPercent**: 0.7
  - **m_flHorizontalPunch**: 0
  - **m_flVerticalPunch**: 0
  - **m_flRecoilRecoverySpeed**: 10.0
  - **m_VerticallRecoil**:
    - **m_Range**:
      - -0.2
      - 0.2
    - **m_flBurstSlope**: 0.0
    - **m_flBurstExponent**: 0.0
    - **m_flBurstConstant**: 0.0
  - **m_HorizontalRecoil**:
    - **m_Range**:
      - -0.1
      - 0.1
    - **m_flBurstExponent**: 0.0
  - **m_flRecoilSpeed**: 1
  - **m_flZoomFOV**: 40.0
  - **m_flDamageFalloffStartRange**: 600
  - **m_flDamageFalloffEndRange**: 1400
  - **m_flRange**: 1400
  - **m_flBulletLifetime**: 2
  - **m_flDamageFalloffEndScale**: 0.3
  - **m_flDamageFalloffBias**: 0.5
  - **m_iBullets**: 1
  - **m_flCycleTime**: 1.03
  - **m_reloadDuration**: 1.8
  - **m_iClipSize**: -1
  - **m_iBurstShotCount**: 1
  - **m_flBurstShotCooldown**: 0
  - **m_flBulletGravityScale**: 0.0
  - **m_flBulletRadius**: 3
  - **m_flBulletDrag**: 1
  - **m_flBulletDragBias**: 0.5
  - **m_flBulletReflectScale**: 0
  - **m_flBulletReflectAmount**: 1
  - **m_flBulletInheritShooterVelocityScale**: 0
  - **m_szBulletTravelTracerParticle**: resource_name:"particles/weapon_fx/trooper/trooper_bullet_travel.vpcf"
  - **m_szMuzzleFlashEffectName**: resource_name:"particles/dev/bullet_debug_muzzle_flash.vpcf"
  - **m_strShootSound**: soundevent:"TrooperRifle.Fire"
  - **m_strBulletWhizSound**: soundevent:"Base.Bullet.Whizby"
  - **m_BulletSpeedCurve**:
    - **m_spline**:
      | x | y | m_flSlopeIncoming | m_flSlopeOutgoing |
      | --- | --- | --- | --- |
      | 0.0 | 12000.0 | 0.0 | 0.0 |
      | 100.0 | 12000.0 | 0.0 | 0.0 |
    - **m_tangents**:
      | m_nIncomingTangent | m_nOutgoingTangent |
      | --- | --- |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
    - **m_vDomainMins**:
      - 0.0
      - 1.0
    - **m_vDomainMaxs**:
      - 100.0
      - 12000.0
  - **m_mapImpactEffects**:
    - **default**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Default.BulletImpact"
    - **flesh**:
      - **m_strDecal**: 
      - **m_strParticle**: resource_name:"particles/blood_impact/blood_impact_red_01.vpcf"
      - **m_strSound**: soundevent:"Flesh.BulletImpact"
    - **concrete**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Concrete.BulletImpact"
    - **solidmetal**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"SolidMetal.BulletImpact"
    - **portals**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Player.HitInvuln"
  - **m_flCritBonusStart**: 1.15
  - **m_flCritBonusEnd**: 1.35
  - **m_flCritBonusStartRange**: 500.0
  - **m_flCritBonusEndRange**: 1500.0
  - **m_flCritBonusAgainstNPCs**: 0.25
  - **m_flShootSpreadPenaltyPerShot**: 0.0
  - **m_flShootSpreadPenaltyDecayDelay**: 0.0
  - **m_flShootSpreadPenaltyDecay**: 2.0
  - **m_flRecoilShotIndexRecoveryTimeFactor**: 0.25
  - **m_bCanZoom**: True
  - **m_strWeaponImpactEffect**: resource_name:"particles/weapon_fx/default_tracer_impact.vpcf"
  - **m_flReloadMoveSpeed**: 236.22
  - **m_strLocalPlayerBulletImpactSound**: soundevent:"Player.Bullet.Impact.Trooper"
  - **m_NpcAimingSpread**:
    - 0.2
    - 0.8
  - **m_flBulletDamage**: 61.8
- **_base**: super_trooper_melee
- **_class**: npc_super_trooper
- **m_sModelName**: resource_name:"models/npc/trooper/super_trooper_melee.vmdl"
- **m_nMaxHealth**: 400
- **m_flSightRangePlayers**: 700.0
- **m_flSightRangeNPCs**: 1600.0
- **m_hFootstepSounds**: trooper
- **m_flTrooperDamageResistPct**: 55.0
- **m_flT1BossDamageResistPct**: 35.0
- **m_flT2BossDamageResistPct**: 20.0
- **m_flShieldDamageResistPct**: 80.0
- **m_flNearDeathDuration**: 1.0
- **m_flWalkSpeed**: 320
- **m_flRunSpeed**: 433
- **m_flAcceleration**: 200
- **m_flMeleeDamage**: 80.0
- **m_flMeleeAttemptRange**: 120
- **m_flMeleeHitRange**: 120
- **m_flMeleeDuration**: 1.0
- **m_flAttackT1BossMaxRange**: 540
- **m_flAttackTrooperMaxRange**: 700
- **m_BossAttackParticle**: resource_name:"particles/weapon_fx/trooper/trooper_bullet_bonus_dmg.vpcf"
- **m_sDefaultMaterialGroupName**: Friendly
- **m_sEnemyMaterialGroupName**: Enemy
- **m_flMeleeChargeRange**: 1000.0
- **m_flHealthBarOffset**: 76.0
- **m_flHealthBarOffsetDucking**: 40
- **m_DeathParticle**: resource_name:"particles/trooper/trooper_death_sn.vpcf"
- **m_DeathSound**: soundevent:"Trooper.Death"
- **m_MeleeHitSound**: soundevent:"Trooper.Melee.Damage.Hit"
- **m_MeleeHitPlayerSound**: soundevent:"Player.Damage.Melee.Trooper.Impact"
- **m_HealthBarParticle**: resource_name:"particles/npc/npc_healthbar.vpcf"
- **m_sHealthBarAttachment**: head_fx
- **m_HealthBarColorFriend**:
  - 255
  - 239
  - 215
- **m_HealthBarColorEnemy**:
  - 230
  - 25
  - 25
- **m_HealthBarColorTeam1**:
  - 231
  - 182
  - 89
- **m_HealthBarColorTeam2**:
  - 91
  - 121
  - 230
- **m_HealthBarColorTeamNeutral**:
  - 0
  - 125
  - 125
- **m_MeleeSwingParticle**: resource_name:"particles/npc/npc_melee_swing.vpcf"
- **m_MeleeActivateParticle**: resource_name:"particles/npc/npc_melee_activate.vpcf"
- **m_MeleeAnimName**: b_melee
- **m_LastHitParticle**: resource_name:"particles/generic/last_hit.vpcf"
- **m_strLastHitSound**: soundevent:"LastHit.Default"
- **m_bPlayLastHitSound**: True
- **m_NearDeathModifier**:
  - **subclass**:
    - **_class**: modifier_near_death_fx
    - **_my_subclass_name**: modifier_near_death_fx
    - **m_EnemyNearDeathParticle**: resource_name:"particles/status_fx/status_fx_last_hit.vpcf"
    - **m_FriendlyNearDeathParticle**: resource_name:"particles/status_fx/status_fx_last_hit_friend.vpcf"
    - **m_sSelfDestructStart**: soundevent:"Trooper.SelfDestruct_Start"
    - **m_sSelfDestructEnd**: soundevent:"Trooper.SelfDestruct_Exp"
- **m_TargetingLaserParticle**: resource_name:"particles/weapon_fx/trooper_laser_target.vpcf"
- **m_TargetingEyeFlashParticle**: resource_name:"particles/enemy_targeting_indicator.vpcf"
- **m_sCelebrationSound**: soundevent:"Trooper.Objective.Win.Cheer"
- **m_flBarrackGuardianDamageResistPct**: 67.5
- **m_sTeam1MaterialGroupName**: Amber
- **m_sTeam2MaterialGroupName**: Sapphire
- **m_flT1BossDPS**: 83.6
- **m_flT2BossDPS**: 209.0
- **m_flT3BossDPS**: 209.0
- **m_flGeneratorBossDPS**: 41.8
- **m_flBarrackBossDPS**: 209.0
- **m_flPlayerDPS**: 42.0
- **m_flTrooperDPS**: 66.5
- **m_TrooperType**: TROOPER_MELEE
- **m_flModelScale**: 1.1

---

# NPC: alt_super_trooper_normal

- **m_WeaponInfo**:
  - **m_Spread**: 0.5
  - **m_StandingSpread**: 1.5
  - **m_flScatterYawScale**: 1
  - **m_flShootingUpSpreadPenalty**: 2
  - **m_flZoomMoveSpeedPercent**: 0.7
  - **m_flShootMoveSpeedPercent**: 0.7
  - **m_flHorizontalPunch**: 0
  - **m_flVerticalPunch**: 0
  - **m_flRecoilRecoverySpeed**: 10.0
  - **m_VerticallRecoil**:
    - **m_Range**:
      - -0.2
      - 0.2
    - **m_flBurstSlope**: 0.0
    - **m_flBurstExponent**: 0.0
    - **m_flBurstConstant**: 0.0
  - **m_HorizontalRecoil**:
    - **m_Range**:
      - -0.1
      - 0.1
    - **m_flBurstExponent**: 0.0
  - **m_flRecoilSpeed**: 1
  - **m_flZoomFOV**: 40.0
  - **m_flDamageFalloffStartRange**: 600
  - **m_flDamageFalloffEndRange**: 1000
  - **m_flRange**: 1000
  - **m_flBulletLifetime**: 2
  - **m_flDamageFalloffEndScale**: 0.3
  - **m_flDamageFalloffBias**: 0.5
  - **m_iBullets**: 1
  - **m_flCycleTime**: 1.03
  - **m_reloadDuration**: 1.8
  - **m_iClipSize**: -1
  - **m_iBurstShotCount**: 1
  - **m_flBurstShotCooldown**: 0
  - **m_flBulletGravityScale**: 0.0
  - **m_flBulletRadius**: 3
  - **m_flBulletDrag**: 1
  - **m_flBulletDragBias**: 0.5
  - **m_flBulletReflectScale**: 0
  - **m_flBulletReflectAmount**: 1
  - **m_flBulletInheritShooterVelocityScale**: 0
  - **m_szBulletTravelTracerParticle**: resource_name:"particles/weapon_fx/trooper/trooper_bullet_travel.vpcf"
  - **m_szMuzzleFlashEffectName**: resource_name:"particles/dev/bullet_debug_muzzle_flash.vpcf"
  - **m_strShootSound**: soundevent:"TrooperRifle.Fire"
  - **m_strBulletWhizSound**: soundevent:"Base.Bullet.Whizby"
  - **m_BulletSpeedCurve**:
    - **m_spline**:
      | x | y | m_flSlopeIncoming | m_flSlopeOutgoing |
      | --- | --- | --- | --- |
      | 0.0 | 12000.0 | 0.0 | 0.0 |
      | 100.0 | 12000.0 | 0.0 | 0.0 |
    - **m_tangents**:
      | m_nIncomingTangent | m_nOutgoingTangent |
      | --- | --- |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
    - **m_vDomainMins**:
      - 0.0
      - 1.0
    - **m_vDomainMaxs**:
      - 100.0
      - 12000.0
  - **m_mapImpactEffects**:
    - **default**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"TrooperRifle.BulletImpact.Default"
    - **flesh**:
      - **m_strDecal**: 
      - **m_strParticle**: resource_name:"particles/blood_impact/blood_impact_red_01.vpcf"
      - **m_strSound**: soundevent:"Flesh.BulletImpact"
    - **concrete**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Concrete.BulletImpact"
    - **solidmetal**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"SolidMetal.BulletImpact"
    - **portals**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Player.HitInvuln"
  - **m_flCritBonusStart**: 1.15
  - **m_flCritBonusEnd**: 1.35
  - **m_flCritBonusStartRange**: 500.0
  - **m_flCritBonusEndRange**: 1500.0
  - **m_flCritBonusAgainstNPCs**: 0.25
  - **m_flShootSpreadPenaltyPerShot**: 0.0
  - **m_flShootSpreadPenaltyDecayDelay**: 0.0
  - **m_flShootSpreadPenaltyDecay**: 2.0
  - **m_flRecoilShotIndexRecoveryTimeFactor**: 0.25
  - **m_bCanZoom**: True
  - **m_strWeaponImpactEffect**: resource_name:"particles/weapon_fx/default_tracer_impact.vpcf"
  - **m_flReloadMoveSpeed**: 236.22
  - **m_strLocalPlayerBulletImpactSound**: soundevent:"Player.Bullet.Impact.Trooper"
  - **m_NpcAimingSpread**:
    - 0.2
    - 0.8
  - **m_flBulletDamage**: 36
- **_base**: super_trooper_normal
- **_class**: npc_super_trooper
- **m_sModelName**: resource_name:"models/npc/trooper/super_trooper_humanoid.vmdl"
- **m_nMaxHealth**: 300
- **m_flSightRangePlayers**: 700.0
- **m_flSightRangeNPCs**: 1600.0
- **m_hFootstepSounds**: trooper
- **m_flTrooperDamageResistPct**: 55.0
- **m_flT1BossDamageResistPct**: 35.0
- **m_flT2BossDamageResistPct**: 20.0
- **m_flShieldDamageResistPct**: 80.0
- **m_flNearDeathDuration**: 1.0
- **m_flWalkSpeed**: 240
- **m_flRunSpeed**: 433
- **m_flAcceleration**: 200
- **m_flMeleeDamage**: 25.0
- **m_flMeleeAttemptRange**: 100
- **m_flMeleeHitRange**: 100
- **m_flMeleeDuration**: 1.0
- **m_flAttackT1BossMaxRange**: 540
- **m_flAttackTrooperMaxRange**: 700
- **m_BossAttackParticle**: resource_name:"particles/weapon_fx/trooper/trooper_bullet_bonus_dmg.vpcf"
- **m_sDefaultMaterialGroupName**: Friendly
- **m_sEnemyMaterialGroupName**: Enemy
- **m_flMeleeChargeRange**: 0
- **m_flHealthBarOffset**: 76.0
- **m_flHealthBarOffsetDucking**: 60
- **m_DeathParticle**: resource_name:"particles/trooper/trooper_death_sn.vpcf"
- **m_DeathSound**: soundevent:"Trooper.Death"
- **m_MeleeHitSound**: soundevent:"Trooper.Melee.Damage.Hit"
- **m_MeleeHitPlayerSound**: soundevent:"Player.Damage.Melee.Trooper.Impact"
- **m_HealthBarParticle**: resource_name:"particles/npc/npc_healthbar.vpcf"
- **m_sHealthBarAttachment**: head_fx
- **m_HealthBarColorFriend**:
  - 255
  - 239
  - 215
- **m_HealthBarColorEnemy**:
  - 230
  - 25
  - 25
- **m_HealthBarColorTeam1**:
  - 231
  - 182
  - 89
- **m_HealthBarColorTeam2**:
  - 91
  - 121
  - 230
- **m_HealthBarColorTeamNeutral**:
  - 0
  - 125
  - 125
- **m_MeleeSwingParticle**: resource_name:"particles/abilities/melee_swing.vpcf"
- **m_MeleeActivateParticle**: resource_name:"particles/abilities/melee/melee_activate.vpcf"
- **m_MeleeAnimName**: b_melee
- **m_LastHitParticle**: resource_name:"particles/generic/last_hit.vpcf"
- **m_strLastHitSound**: soundevent:"LastHit.Default"
- **m_bPlayLastHitSound**: True
- **m_NearDeathModifier**:
  - **subclass**:
    - **_class**: modifier_near_death_fx
    - **_my_subclass_name**: modifier_near_death_fx
    - **m_EnemyNearDeathParticle**: resource_name:"particles/status_fx/status_fx_last_hit.vpcf"
    - **m_FriendlyNearDeathParticle**: resource_name:"particles/status_fx/status_fx_last_hit_friend.vpcf"
    - **m_sSelfDestructStart**: soundevent:"Trooper.SelfDestruct_Start"
    - **m_sSelfDestructEnd**: soundevent:"Trooper.SelfDestruct_Exp"
- **m_TargetingLaserParticle**: resource_name:"particles/weapon_fx/trooper_laser_target.vpcf"
- **m_TargetingEyeFlashParticle**: resource_name:"particles/enemy_targeting_indicator.vpcf"
- **m_sCelebrationSound**: soundevent:"Trooper.Objective.Win.Cheer"
- **m_flBarrackGuardianDamageResistPct**: 67.5
- **m_sTeam1MaterialGroupName**: Amber
- **m_sTeam2MaterialGroupName**: Sapphire
- **m_flT1BossDPS**: 83.6
- **m_flT2BossDPS**: 209.0
- **m_flT3BossDPS**: 209.0
- **m_flGeneratorBossDPS**: 41.8
- **m_flBarrackBossDPS**: 209.0
- **m_flPlayerDPS**: 42.0
- **m_flTrooperDPS**: 66.5
- **m_flModelScale**: 1.1

---

# NPC: citadel_item_pickup_rejuv

- **_class**: citadel_item_pickup_rejuv
- **m_AbilityProjectile**: ability_item_pickup_effects
- **m_RejuvModifier**:
  - **subclass**:
    - **_class**: modifier_citadel_respawn_credit
    - **_my_subclass_name**: modifier_citadel_respawn_credit
    - **m_sExpireSound**: soundevent:""
    - **m_strParticleEffect**: resource_name:"particles/modifiers/respawn_credit_buff.vpcf"
    - **m_flBonusClipSize**: 0.0
    - **m_flBonusFirerate**: 20.0
    - **m_flBonusHealth**: 200.0
    - **m_flBonusMoveSpeedMeterPerSecond**: 1.0
    - **m_sLocalizationName**: modifier_citadel_respawn_credit
    - **m_eRespawnMechanic**: RejuvenatorRespawnMechanic_PercentOfNormal
- **m_PunchPickupModifier**:
  - **subclass**:
    - **_class**: modifier_item_pickup_punchable
    - **_my_subclass_name**: modifier_item_pickup_punchable
    - **m_nEnabledStateMask**: MODIFIER_STATE_IS_MELEE_TARGET
    - **m_IsDroppingParticle**: resource_name:"particles/environment/rejuv_ambient.vpcf"
    - **m_IsPunchableParticle**: resource_name:"particles/environment/rejuv_attackable.vpcf"
    - **m_bIsHidden**: True
    - **m_NearRejuvAuraModifier**:
      - **subclass**:
        - **_class**: modifier_base_aura
        - **_my_subclass_name**: near_rejuv
        - **m_bIsHidden**: True
        - **m_flAuraRadius**: 300.0
        - **m_modifierProvidedByAura**:
          - **subclass**:
            - **_class**: modifier_base
            - **_my_subclass_name**: target_near_rejuv
            - **m_bIsHidden**: True
            - **m_nEnabledStateMask**: MODIFIER_STATE_NEAR_REJUVINATOR
        - **m_iAuraSearchType**: CITADEL_UNIT_TARGET_HERO

---

