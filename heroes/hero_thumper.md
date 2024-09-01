# Hero: hero_thumper

## Hero Stats

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

## Abilities

### ESlot_Weapon_Primary

- **_class**: citadel_ability_primary_weapon
- **m_mapAbilityProperties**:
  - **AbilityCooldown**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: cooldown
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_single_stat
        - **_my_subclass_name**: AbilityCooldown_scale_function
        - **m_eSpecificStatScaleType**: ETechCooldown
  - **AbilityDuration**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: duration
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_single_stat
        - **_my_subclass_name**: AbilityDuration_scale_function
        - **m_eSpecificStatScaleType**: ETechDuration
  - **AbilityCastRange**:
    - **m_strValue**: 0
    - **m_eDisplayUnits**: EDisplayUnit_Meters
    - **m_strCSSClass**: range
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_single_stat
        - **_my_subclass_name**: AbilityCastRange_scale_function
        - **m_eSpecificStatScaleType**: ETechRange
  - **AbilityUnitTargetLimit**:
    - **m_strValue**: 1
    - **m_bCanSetTokenOverride**: True
  - **AbilityCastDelay**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: cast
    - **m_bCanSetTokenOverride**: True
  - **AbilityChannelTime**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: cast
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_multi_stats
        - **_my_subclass_name**: scale_duration
        - **m_vecScalingStats**:
          - EChannelDuration
          - ETechDuration
  - **AbilityPostCastDuration**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
  - **AbilityCharges**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: cast
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_single_stat
        - **_my_subclass_name**: AbilityCharges_scale_function
        - **m_eSpecificStatScaleType**: EMaxChargesIncrease
  - **AbilityCooldownBetweenCharge**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: charge_cooldown
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_single_stat
        - **_my_subclass_name**: AbilityCooldownBetweenCharge_scale_function
        - **m_eSpecificStatScaleType**: ETechCooldownBetweenChargeUses
  - **ChannelMoveSpeed**:
    - **m_strValue**: 50
    - **m_eDisplayUnits**: EDisplayUnit_MetersPerSecond
    - **m_strCSSClass**: move_speed
    - **m_bCanSetTokenOverride**: True
  - **AbilityResourceCost**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_bCanSetTokenOverride**: True
    - **m_strCSSClass**: cast
  - **TechPower**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_bCanSetTokenOverride**: True
    - **m_eProvidedPropertyType**: MODIFIER_VALUE_TECH_POWER
  - **WeaponPower**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_bCanSetTokenOverride**: True
    - **m_eProvidedPropertyType**: MODIFIER_VALUE_WEAPON_POWER
  - **Radius**:
    - **m_strValue**: 3m
    - **m_strCSSClass**: distance
- **m_bitsPostCastEnabledStateMask**: MODIFIER_STATE_BUSY_WITH_ACTION
- **_editor**:
  - **folder_name**: Base
- **m_WeaponInfo**:
  - **m_BulletSpeedCurve**:
    - **m_spline**:
      | x | y | m_flSlopeIncoming | m_flSlopeOutgoing |
      | --- | --- | --- | --- |
      | 0.0 | 4900.0 | 0.0 | 0.0 |
      | 100.0 | 4900.0 | 0.0 | 0.0 |
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
      - 4900.0
  - **m_Spread**: 0.25
  - **m_StandingSpread**: 0.45
  - **m_flScatterYawScale**: 1
  - **m_flShootingUpSpreadPenalty**: 0
  - **m_flZoomMoveSpeedPercent**: 1.0
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
  - **m_flZoomFOV**: 35.0
  - **m_flDamageFalloffStartRange**: 866.0
  - **m_flDamageFalloffEndRange**: 2264.0
  - **m_flRange**: 7000.0
  - **m_flBulletLifetime**: 2
  - **m_flDamageFalloffStartScale**: 1.0
  - **m_flDamageFalloffEndScale**: 0.1
  - **m_flDamageFalloffBias**: 0.5
  - **m_iBullets**: 1
  - **m_flCycleTime**: 0.6
  - **m_reloadDuration**: 2.1
  - **m_iClipSize**: 6
  - **m_iBurstShotCount**: 1
  - **m_flBurstShotCooldown**: 0
  - **m_flBulletGravityScale**: 0.25
  - **m_flBulletRadius**: 8
  - **m_flBulletReflectScale**: 0
  - **m_flBulletReflectAmount**: 1
  - **m_flBulletInheritShooterVelocityScale**: 0
  - **m_szBulletTravelTracerParticle**: resource_name:"particles/weapon_fx/warden/warden_tracer.vpcf"
  - **m_szMuzzleFlashEffectName**: resource_name:"particles/weapon_fx/default_muzzle_flash.vpcf"
  - **m_strShootSound**: soundevent:"Tokamak.Fire"
  - **m_strBulletWhizSound**: soundevent:"Base.Bullet.Whizby"
  - **m_flBulletWhizDistance**: 150
  - **m_mapImpactEffects**:
    - **default**:
      - **m_strDecal**: Impact.Concrete
      - **m_strParticle**: resource_name:"particles/impact_fx/impact_spark_spray_large.vpcf"
      - **m_strSound**: soundevent:"Spade.Wpn.Impact"
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
    - **dirt**:
      - **m_strSound**: soundevent:"Dirt.BulletImpact"
    - **metalvehicle**:
      - **m_strSound**: soundevent:"MetalVehicle.BulletImpact"
    - **metal**:
      - **m_strSound**: soundevent:"SolidMetal.BulletImpact"
    - **leafy_tree**:
      - **m_strSound**: soundevent:"Foliage.BulletImpact"
    - **wood**:
      - **m_strSound**: soundevent:"Wood.BulletImpact"
    - **wood_plank**:
      - **m_strSound**: soundevent:"Wood_Plank.BulletImpact"
  - **m_flCritBonusStart**: 1.9
  - **m_flCritBonusEnd**: 1.9
  - **m_flCritBonusStartRange**: 500.0
  - **m_flCritBonusEndRange**: 1500.0
  - **m_flCritBonusAgainstNPCs**: 0
  - **m_flShootSpreadPenaltyPerShot**: 0.0
  - **m_flShootSpreadPenaltyDecayDelay**: 0.0
  - **m_flShootSpreadPenaltyDecay**: 2.0
  - **m_flRecoilShotIndexRecoveryTimeFactor**: 0.25
  - **m_bCanZoom**: True
  - **m_strWeaponImpactEffect**: resource_name:"particles/weapon_fx/default_tracer_impact.vpcf"
  - **m_flReloadMoveSpeed**: 10000
  - **m_strLocalPlayerBulletImpactSound**: soundevent:"Player.Bullet.Impact.Hero"
  - **m_strLocalPlayerBulletImpactHeavySound**: soundevent:"Player.Bullet.Impact.Hero.Large"
  - **m_strReloadSound**: soundevent:""
  - **m_strReloadEndSound**: soundevent:"Player.WpnReload.Shared.Clip.In"
  - **m_strZoomInSound**: soundevent:"Default.ZoomIn"
  - **m_strZoomOutSound**: soundevent:"Default.ZoomOut"
  - **m_bBulletShouldUseVerlet**: True
  - **m_strBulletWhizStraightSound**: soundevent:""
  - **m_flBulletDamage**: 34.2
- **_multibase**:
  - hero_weapon_base
- **m_bStartTrained**: True
- **m_eAbilityTargetingLocation**: CITADEL_ABILITY_TARGETING_LOCATION_SELF
- **m_eAbilityActivation**: CITADEL_ABILITY_ACTIVATION_ON_BUTTON_IS_DOWN
- **m_nAbilityBehaviors**: CITADEL_ABILITY_BEHAVIOR_DONT_INTERRUPT_SPRINT | CITADEL_ABILITY_BEHAVIOR_IS_PRIMARY_WEAPON | CITADEL_ABILITY_BEHAVIOR_NO_TARGET | CITADEL_ABILITY_BEHAVIOR_SILENT_CAST_FAILURE_FEEDBACK | CITADEL_ABILITY_BEHAVIOR_DISARMABLE | CITADEL_ABILITY_BEHAVIOR_NOT_SILENCABLE | CITADEL_ABILITY_BEHAVIOR_WEAPON_TOGGLE
- **m_bitsInterruptingStates**: MODIFIER_STATE_STUNNED | MODIFIER_STATE_IS_ASLEEP
- **m_eAbilityType**: EAbilityType_Weapon
- **m_strAbilityImage**: panorama:"file://{images}/hud/abilities/weapon_damage.psd"
- **m_nAbilityPointsCost**: 1
- **m_HUDPanel**:
  - **m_vecHUDElements**:
    | m_strContext | m_eType |
    | --- | --- |
    | gun | CITADEL_ABILITY_HUD_ELEMENT_TYPE_GUN |
- **m_sObstructedShotSound**: soundevent:"Gameplay.Obstructed.Shot.Impact"
- **m_DOFWhileZoomed**:
  - **m_flDofNearCrisp**: 200.0
  - **m_flDofFarCrisp**: 100.0
  - **m_flDofFarBlurry**: 7000.0
- **m_sDisarmedSound**: soundevent:"Player.Weapon.Jammed"
- **m_flMinDisarmedSoundInterval**: 0.1
- **m_nAbilityTargetTypes**: CITADEL_UNIT_TARGET_ALL_ENEMY
- **m_AutoIntrinsicModifiers**:
  | subclass |
  | --- |
  | {'_class': 'modifier_thumper_bullet_watcher', '_my_subclass_name': 'modifier_thumper_bullet_watcher', 'm_bIsHidden': True, 'm_ExplodeParticle': 'resource_name:"particles/weapon_fx/demoman/demoman_tracer_explode.vpcf"', 'm_ExplodeSound': 'soundevent:"Mods.ExplosiveBullets.Explode"'} |

### ESlot_Weapon_Melee

- **_class**: citadel_ability_hold_melee
- **m_mapAbilityProperties**:
  - **AbilityCooldown**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: cooldown
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_single_stat
        - **_my_subclass_name**: AbilityCooldown_scale_function
        - **m_eSpecificStatScaleType**: ETechCooldown
  - **AbilityDuration**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: duration
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_single_stat
        - **_my_subclass_name**: AbilityDuration_scale_function
        - **m_eSpecificStatScaleType**: ETechDuration
  - **AbilityCastRange**:
    - **m_strValue**: 0
    - **m_eDisplayUnits**: EDisplayUnit_Meters
    - **m_strCSSClass**: range
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_single_stat
        - **_my_subclass_name**: AbilityCastRange_scale_function
        - **m_eSpecificStatScaleType**: ETechRange
  - **AbilityUnitTargetLimit**:
    - **m_strValue**: 1
    - **m_bCanSetTokenOverride**: True
  - **AbilityCastDelay**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: cast
    - **m_bCanSetTokenOverride**: True
  - **AbilityChannelTime**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: cast
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_multi_stats
        - **_my_subclass_name**: scale_duration
        - **m_vecScalingStats**:
          - EChannelDuration
          - ETechDuration
  - **AbilityPostCastDuration**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
  - **AbilityCharges**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: cast
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_single_stat
        - **_my_subclass_name**: AbilityCharges_scale_function
        - **m_eSpecificStatScaleType**: EMaxChargesIncrease
  - **AbilityCooldownBetweenCharge**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: charge_cooldown
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_single_stat
        - **_my_subclass_name**: AbilityCooldownBetweenCharge_scale_function
        - **m_eSpecificStatScaleType**: ETechCooldownBetweenChargeUses
  - **ChannelMoveSpeed**:
    - **m_strValue**: 50
    - **m_eDisplayUnits**: EDisplayUnit_MetersPerSecond
    - **m_strCSSClass**: move_speed
    - **m_bCanSetTokenOverride**: True
  - **AbilityResourceCost**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_bCanSetTokenOverride**: True
    - **m_strCSSClass**: cast
  - **TechPower**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_bCanSetTokenOverride**: True
    - **m_eProvidedPropertyType**: MODIFIER_VALUE_TECH_POWER
  - **WeaponPower**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_bCanSetTokenOverride**: True
    - **m_eProvidedPropertyType**: MODIFIER_VALUE_WEAPON_POWER
  - **MeleeHalfAngle**:
    - **m_strValue**: 30
  - **MeleeAttackLength**:
    - **m_strValue**: 5m
    - **m_strCSSClass**: distance
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_single_stat
        - **_my_subclass_name**: MeleeAttackLength_scale_function
        - **m_eSpecificStatScaleType**: EMeleeRange
  - **MeleeDamageTakenScale**:
    - **m_eProvidedPropertyType**: MODIFIER_VALUE_MELEE_DAMAGE_INCREASE_PERCENT
    - **m_UsageFlags**: APUsageFlag_ModifierConditional
    - **m_strValue**: 35
- **m_bitsPostCastEnabledStateMask**: MODIFIER_STATE_BUSY_WITH_ACTION
- **_editor**:
  - **folder_name**: Base
- **m_WeaponInfo**:
  - **m_BulletSpeedCurve**:
    - **m_spline**:
      | x | y | m_flSlopeIncoming | m_flSlopeOutgoing |
      | --- | --- | --- | --- |
      | 0.0 | 10000.0 | 0.0 | 0.0 |
      | 100.0 | 10000.0 | 0.0 | 0.0 |
    - **m_tangents**:
      | m_nIncomingTangent | m_nOutgoingTangent |
      | --- | --- |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
    - **m_vDomainMins**:
      - 0.0
      - 0.0
    - **m_vDomainMaxs**:
      - 100.0
      - 10000.0
- **_multibase**:
  - inherent_base
  - citadel_hold_melee
- **m_eAbilityType**: EAbilityType_Weapon
- **m_bStartTrained**: True
- **m_iMaxLevel**: 1
- **m_eAbilityActivation**: CITADEL_ABILITY_ACTIVATION_INSTANT_CAST
- **m_eAbilityTargetingLocation**: CITADEL_ABILITY_TARGETING_LOCATION_SELF
- **m_nAbilityBehaviors**: CITADEL_ABILITY_BEHAVIOR_HIDDEN | CITADEL_ABILITY_BEHAVIOR_SILENT_CAST_FAILURE_FEEDBACK  | CITADEL_ABILITY_BEHAVIOR_NOT_SILENCABLE | CITADEL_ABILITY_BEHAVIOR_NO_TARGET | CITADEL_ABILITY_BEHAVIOR_CASTABLE_WHILE_HIDDEN
- **m_nAbilityTargetTypes**: CITADEL_UNIT_TARGET_ALL_ENEMY | CITADEL_UNIT_TARGET_TROPHY_ENEMY
- **m_nAbilityTargetFlags**: CITADEL_UNIT_TARGET_FLAG_PENETRATE_INVULNERABLE
- **m_bitsInterruptingStates**: MODIFIER_STATE_STUNNED | MODIFIER_STATE_IS_ASLEEP
- **m_strAbilityImage**: panorama:"file://{images}/hud/abilities/melee_damage.psd"
- **m_MeleeDamageFlags**: DFLAG_TRIGGER_FLINCH
- **m_flCollisionDistance**: 50.0
- **m_cameraSequenceHoldStart**:
  - **m_vecFOVOperations**:
    | m_flMaintainDuration | m_eCameraOperation |
    | --- | --- |
    | 0.1 | k_ECameraOp_Maintain |
    |  | k_ECameraOp_Lerp |
    |  | k_ECameraOp_Spring |
  - **m_vecDistanceOperations**:
    | m_flMaintainDuration | m_eCameraOperation |
    | --- | --- |
    | 0.1 | k_ECameraOp_Maintain |
    |  | k_ECameraOp_Lerp |
    |  | k_ECameraOp_Spring |
- **m_strHoldBegin**: soundevent:"Player.Melee.Hold.Shared"
- **m_HoldBeginEffect**: resource_name:"particles/abilities/melee/melee_heavy_activate_charge.vpcf"
- **m_cameraSequenceHitImpact**:
  - **m_vecDistanceOperations**:
    | m_bValuesAreRelative | m_flApproachTarget |
    | --- | --- |
    | True | -20.0 |
    | True | 20.0 |
- **m_ParryVictimModifier**:
  - **subclass**:
    - **_my_subclass_name**: modifier_citadel_parried_stun
    - **_class**: modifier_citadel_stunned
    - **m_strParticleEffect**: resource_name:"particles/abilities/melee/melee_parry_debuff.vpcf"
    - **m_OnCreateResponse**:
      - **m_nConcept**: TLK_CITADEL_INTERACT_WITH_ABILITY
      - **m_nSpeakerType**: MODIFIER_RR_SPEAKER_CASTER
    - **m_vecSetAndTrackedAnimGraphParams**:
      | m_strName | m_strSetValue | m_strRestoreValue |
      | --- | --- | --- |
      | b_Stumble | 1 | 0 |
    - **m_vecAutoRegisterModifierValueFromAbilityPropertyName**:
      - MeleeDamageTakenScale
- **m_SuccessfulParryParticle**: resource_name:"particles/abilities/melee/melee_parry_success.vpcf"
- **m_strSuccessfulParrySound**: soundevent:"Player.Melee.Parry.Shared"
- **m_flParryWindow**: 0.28
- **m_flParryStunTime**: 1.1
- **m_ParryActivateParticle**: resource_name:"particles/abilities/melee/melee_parry_attack.vpcf"
- **m_AirMeleeUpScale**:
  - 20.0
  - -45.0
  - 1.0
  - 0.1
- **m_mapAttacks**:
  - **EAttackType_Light**:
    - **m_Trigger**: light
    - **m_flCooldownOnHit**: 0.75
    - **m_flCooldownOnMiss**: 0.75
    - **m_SpeedBonusCurve**:
      - **m_spline**:
        | x | y | m_flSlopeIncoming | m_flSlopeOutgoing |
        | --- | --- | --- | --- |
        | 0.0 | 0.0 | 0.0 | 0.0 |
        | 0.224286 | 0.0 | -1296.296265 | -1296.296265 |
        | 0.231429 | -300.0 | 0.0 | 0.0 |
        | 0.705714 | 0.0 | 632.53009 | 632.53009 |
      - **m_tangents**:
        | m_nIncomingTangent | m_nOutgoingTangent |
        | --- | --- |
        | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
        | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
        | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
        | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
      - **m_vDomainMins**:
        - 0.0
        - -300.0
      - **m_vDomainMaxs**:
        - 1.0
        - 0.0
    - **m_MovementSpeedCurve**:
      - **m_spline**:
        | x | y | m_flSlopeIncoming | m_flSlopeOutgoing |
        | --- | --- | --- | --- |
        | 0.0 | 128.545456 | 2650.541992 | 2650.541992 |
        | 0.140143 | 500.0 | 1689.520264 | 1689.520264 |
        | 0.219858 | 500.0 | -6140.309082 | -6140.309082 |
        | 0.221572 | 0.0 | -291716.78125 | -291716.78125 |
      - **m_tangents**:
        | m_nIncomingTangent | m_nOutgoingTangent |
        | --- | --- |
        | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
        | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
        | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
        | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
      - **m_vDomainMins**:
        - 0.0
        - 0.0
      - **m_vDomainMaxs**:
        - 0.3
        - 500.0
    - **m_MeleeActivateParticle**: resource_name:""
    - **m_strHitSound**: soundevent:"Ability.Melee.Impact.Player"
    - **m_MeleeImpactParticle**: resource_name:"particles/abilities/melee_impact.vpcf"
    - **m_flAttackStateTime**: 0.5
    - **m_MeleeSwingParticle**: resource_name:"particles/abilities/melee_quick.vpcf"
    - **m_strHitDebrisSound**: soundevent:"Player.Melee.Hit.Physics"
    - **m_strHitHeroSound**: soundevent:"Ability.Melee.Impact.Player"
  - **EAttackType_Heavy**:
    - **m_cameraSequenceAttackStart**:
      - **m_vecTargetPosOperations**:
        | m_flLagMinDuration | m_flLagTime | m_flLagMaxSpeed | m_flLagSpringStrength | m_eCameraOperation |
        | --- | --- | --- | --- | --- |
        | 0.2 | 0.1 | 20.0 | 5.0 | k_ECameraOp_Lag |
      - **m_vecFOVOperations**:
    - **m_Trigger**: heavy
    - **m_flCooldownOnHit**: 0.9
    - **m_flCooldownOnMiss**: 0.9
    - **m_bApplyScreenShake**: True
    - **m_SpeedBonusCurve**:
      - **m_spline**:
        | x | y | m_flSlopeIncoming | m_flSlopeOutgoing |
        | --- | --- | --- | --- |
        | 0.0 | -300.0 | 0.0 | 0.0 |
        | 0.271158 | -300.0 | 669.14325 | 669.14325 |
        | 0.345788 | -68.618172 | 1323.338623 | 1323.338623 |
        | 0.497857 | 0.0 | 451.231018 | 451.231018 |
      - **m_tangents**:
        | m_nIncomingTangent | m_nOutgoingTangent |
        | --- | --- |
        | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
        | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
        | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
        | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
      - **m_vDomainMins**:
        - 0.0
        - -300.0
      - **m_vDomainMaxs**:
        - 0.5
        - 0.0
    - **m_MovementSpeedCurve**:
      - **m_spline**:
        | x | y | m_flSlopeIncoming | m_flSlopeOutgoing |
        | --- | --- | --- | --- |
        | 8e-05 | 470.10907 | 1842.533813 | 1842.533813 |
        | 0.179122 | 800.0 | 940.240601 | 940.240601 |
        | 0.350938 | 800.0 | -4623.689453 | -4623.689453 |
        | 0.352144 | 0.0 | -663344.125 | -663344.125 |
      - **m_tangents**:
        | m_nIncomingTangent | m_nOutgoingTangent |
        | --- | --- |
        | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
        | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
        | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
        | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
      - **m_vDomainMins**:
        - 0.0
        - 0.0
      - **m_vDomainMaxs**:
        - 0.4
        - 800.0
    - **m_flAttackEventTime**: 0.95
    - **bIsHeavyAttack**: True
    - **m_strActivateSound**: soundevent:""
    - **m_flMovementAcc**: 200000.0
    - **m_strHitSound**: soundevent:"Ability.Melee.Impact.Player"
    - **m_strDashStart**: soundevent:"Player.AirJump.Execute.Whoosh"
    - **m_MeleeSwingParticle**: resource_name:"particles/abilities/melee_swing_heavy.vpcf"
    - **m_MeleeActivateParticle**: resource_name:""
    - **m_MeleeImpactParticle**: resource_name:"particles/abilities/melee/melee_impact_heavy.vpcf"
    - **m_strHitHeroSound**: soundevent:"Ability.Melee.Impact.Player"
    - **m_strHitDebrisSound**: soundevent:"Player.Melee.Hit.Physics"
    - **m_MeleeAttackParticle**: resource_name:"particles/abilities/melee/melee_heavy_activate.vpcf"
  - **EAttackType_HeavyAir**:
    - **m_Trigger**: heavy
    - **bIsHeavyAttack**: True
    - **m_flCooldownOnHit**: 0.9
    - **m_flCooldownOnMiss**: 0.9
    - **m_bApplyScreenShake**: True
    - **m_SpeedBonusCurve**:
      - **m_spline**:
        | x | y | m_flSlopeIncoming | m_flSlopeOutgoing |
        | --- | --- | --- | --- |
        | 0.0 | -300.0 | 0.0 | 0.0 |
        | 0.199155 | -300.0 | 707.983032 | 707.983032 |
        | 0.303474 | -85.145447 | 1004.345276 | 1004.345276 |
        | 0.497857 | 0.0 | 438.029633 | 438.029633 |
      - **m_tangents**:
        | m_nIncomingTangent | m_nOutgoingTangent |
        | --- | --- |
        | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
        | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
        | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
        | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
      - **m_vDomainMins**:
        - 0.0
        - -300.0
      - **m_vDomainMaxs**:
        - 0.5
        - 0.0
    - **m_MovementSpeedCurve**:
      - **m_spline**:
        | x | y | m_flSlopeIncoming | m_flSlopeOutgoing |
        | --- | --- | --- | --- |
        | 0.0 | 337.890869 | 2661.166016 | 2661.166016 |
        | 0.173649 | 800.0 | 1357.308105 | 1357.308105 |
        | 0.34046 | 800.0 | -4768.748535 | -4768.748535 |
        | 0.341408 | 0.0 | -843871.3125 | -843871.3125 |
      - **m_tangents**:
        | m_nIncomingTangent | m_nOutgoingTangent |
        | --- | --- |
        | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
        | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
        | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
        | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
      - **m_vDomainMins**:
        - 0.0
        - 0.0
      - **m_vDomainMaxs**:
        - 0.4
        - 800.0
    - **m_flMovementAcc**: 200000.0
    - **m_cameraSequenceAttackStart**:
      - **m_vecDistanceOperations**:
      - **m_vecFOVOperations**:
        | m_bValuesAreRelative | m_flApproachTarget | m_flApproachSpeed | m_flApproachAcceleration |
        | --- | --- | --- | --- |
        | True | -10.0 | 5.0 | 10.0 |
        |  |  |  |  |
    - **m_flAttackStateTime**: 0.3
    - **m_strHitHeroSound**: soundevent:"Ability.Melee.Impact.Player"
    - **m_MeleeAttackParticle**: resource_name:"particles/abilities/melee/melee_heavy_activate.vpcf"
- **m_HUDPanel**:
  - **m_vecButtonHints**:
    | m_strLocToken | m_eHintSide | m_strBindingOverride1 | m_strContext |
    | --- | --- | --- | --- |
    | #AbilityButtonHint_MeleeRejuvinator | EButtonSide_Bottom | in_weapon1 | melee_rejuv |

### ESlot_Ability_Mantle

- **_class**: citadel_ability_mantle
- **m_mapAbilityProperties**:
  - **AbilityCooldown**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: cooldown
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_single_stat
        - **_my_subclass_name**: AbilityCooldown_scale_function
        - **m_eSpecificStatScaleType**: ETechCooldown
  - **AbilityDuration**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: duration
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_single_stat
        - **_my_subclass_name**: AbilityDuration_scale_function
        - **m_eSpecificStatScaleType**: ETechDuration
  - **AbilityCastRange**:
    - **m_strValue**: 0
    - **m_eDisplayUnits**: EDisplayUnit_Meters
    - **m_strCSSClass**: range
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_single_stat
        - **_my_subclass_name**: AbilityCastRange_scale_function
        - **m_eSpecificStatScaleType**: ETechRange
  - **AbilityUnitTargetLimit**:
    - **m_strValue**: 1
    - **m_bCanSetTokenOverride**: True
  - **AbilityCastDelay**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: cast
    - **m_bCanSetTokenOverride**: True
  - **AbilityChannelTime**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: cast
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_multi_stats
        - **_my_subclass_name**: scale_duration
        - **m_vecScalingStats**:
          - EChannelDuration
          - ETechDuration
  - **AbilityPostCastDuration**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
  - **AbilityCharges**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: cast
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_single_stat
        - **_my_subclass_name**: AbilityCharges_scale_function
        - **m_eSpecificStatScaleType**: EMaxChargesIncrease
  - **AbilityCooldownBetweenCharge**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: charge_cooldown
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_single_stat
        - **_my_subclass_name**: AbilityCooldownBetweenCharge_scale_function
        - **m_eSpecificStatScaleType**: ETechCooldownBetweenChargeUses
  - **ChannelMoveSpeed**:
    - **m_strValue**: 50
    - **m_eDisplayUnits**: EDisplayUnit_MetersPerSecond
    - **m_strCSSClass**: move_speed
    - **m_bCanSetTokenOverride**: True
  - **AbilityResourceCost**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_bCanSetTokenOverride**: True
    - **m_strCSSClass**: cast
  - **TechPower**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_bCanSetTokenOverride**: True
    - **m_eProvidedPropertyType**: MODIFIER_VALUE_TECH_POWER
  - **WeaponPower**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_bCanSetTokenOverride**: True
    - **m_eProvidedPropertyType**: MODIFIER_VALUE_WEAPON_POWER
- **m_bitsPostCastEnabledStateMask**: MODIFIER_STATE_BUSY_WITH_ACTION
- **_editor**:
  - **folder_name**: Base
- **m_WeaponInfo**:
  - **m_BulletSpeedCurve**:
    - **m_spline**:
      | x | y | m_flSlopeIncoming | m_flSlopeOutgoing |
      | --- | --- | --- | --- |
      | 0.0 | 10000.0 | 0.0 | 0.0 |
      | 100.0 | 10000.0 | 0.0 | 0.0 |
    - **m_tangents**:
      | m_nIncomingTangent | m_nOutgoingTangent |
      | --- | --- |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
    - **m_vDomainMins**:
      - 0.0
      - 0.0
    - **m_vDomainMaxs**:
      - 100.0
      - 10000.0
- **_multibase**:
  - inherent_base
- **m_eAbilityType**: EAbilityType_Innate
- **m_bStartTrained**: True
- **m_iMaxLevel**: 1
- **m_eAbilityTargetingLocation**: CITADEL_ABILITY_TARGETING_LOCATION_SELF
- **m_eAbilityActivation**: CITADEL_ABILITY_ACTIVATION_INSTANT_CAST
- **m_nAbilityBehaviors**: CITADEL_ABILITY_BEHAVIOR_HIDDEN | CITADEL_ABILITY_BEHAVIOR_DONT_BREAK_INVISIBILITY | CITADEL_ABILITY_BEHAVIOR_SILENT_CAST_FAILURE_FEEDBACK | CITADEL_ABILITY_BEHAVIOR_DONT_INTERRUPT_SPRINT | CITADEL_ABILITY_BEHAVIOR_INPUT_DIRECTIONAL_2D | CITADEL_ABILITY_BEHAVIOR_CASTABLE_WHILE_BUSY | CITADEL_ABILITY_BEHAVIOR_NOT_SILENCABLE | CITADEL_ABILITY_BEHAVIOR_NO_TARGET | CITADEL_ABILITY_BEHAVIOR_NON_COMBAT | CITADEL_ABILITY_BEHAVIOR_CASTABLE_WHILE_HIDDEN
- **m_bitsInterruptingStates**: MODIFIER_STATE_IMMOBILIZED | MODIFIER_STATE_STUNNED | MODIFIER_STATE_IS_ASLEEP
- **m_vecMantleTypes**:
  | m_eMantleType | m_flMaxHeight | m_flAnimHeight |
  | --- | --- | --- |
  | EMantle32 | 64.0 | 32.0 |
  | EMantle64 | 96.0 | 64.0 |
  | EMantle96 | 128.0 | 96.0 |
  | EMantle128 | 160.0 | 128.0 |

### ESlot_Ability_Jump

- **_class**: citadel_ability_jump
- **m_mapAbilityProperties**:
  - **AbilityCooldown**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: cooldown
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_single_stat
        - **_my_subclass_name**: AbilityCooldown_scale_function
        - **m_eSpecificStatScaleType**: ETechCooldown
  - **AbilityDuration**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: duration
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_single_stat
        - **_my_subclass_name**: AbilityDuration_scale_function
        - **m_eSpecificStatScaleType**: ETechDuration
  - **AbilityCastRange**:
    - **m_strValue**: 0
    - **m_eDisplayUnits**: EDisplayUnit_Meters
    - **m_strCSSClass**: range
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_single_stat
        - **_my_subclass_name**: AbilityCastRange_scale_function
        - **m_eSpecificStatScaleType**: ETechRange
  - **AbilityUnitTargetLimit**:
    - **m_strValue**: 1
    - **m_bCanSetTokenOverride**: True
  - **AbilityCastDelay**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: cast
    - **m_bCanSetTokenOverride**: True
  - **AbilityChannelTime**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: cast
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_multi_stats
        - **_my_subclass_name**: scale_duration
        - **m_vecScalingStats**:
          - EChannelDuration
          - ETechDuration
  - **AbilityPostCastDuration**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
  - **AbilityCharges**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: cast
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_single_stat
        - **_my_subclass_name**: AbilityCharges_scale_function
        - **m_eSpecificStatScaleType**: EMaxChargesIncrease
  - **AbilityCooldownBetweenCharge**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: charge_cooldown
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_single_stat
        - **_my_subclass_name**: AbilityCooldownBetweenCharge_scale_function
        - **m_eSpecificStatScaleType**: ETechCooldownBetweenChargeUses
  - **ChannelMoveSpeed**:
    - **m_strValue**: 50
    - **m_eDisplayUnits**: EDisplayUnit_MetersPerSecond
    - **m_strCSSClass**: move_speed
    - **m_bCanSetTokenOverride**: True
  - **AbilityResourceCost**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_bCanSetTokenOverride**: True
    - **m_strCSSClass**: cast
  - **TechPower**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_bCanSetTokenOverride**: True
    - **m_eProvidedPropertyType**: MODIFIER_VALUE_TECH_POWER
  - **WeaponPower**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_bCanSetTokenOverride**: True
    - **m_eProvidedPropertyType**: MODIFIER_VALUE_WEAPON_POWER
  - **VerticalSpeed**:
    - **m_strValue**: 300
  - **SlideLeapSpeedPenaltyMax**:
    - **m_strValue**: 100
  - **SlideLeapSpeedPenaltyTime**:
    - **m_strValue**: 0.2
  - **WeaponSpreadPenalty**:
    - **m_strValue**: 3
  - **AirJumpVerticalSpeedPercent**:
    - **m_strValue**: 75
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_single_stat
        - **_my_subclass_name**: AirJumpVerticalSpeedPercent_scale_function
        - **m_eSpecificStatScaleType**: EAirMoveDistanceScale
- **m_bitsPostCastEnabledStateMask**: MODIFIER_STATE_BUSY_WITH_ACTION
- **_editor**:
  - **folder_name**: Base
- **m_WeaponInfo**:
  - **m_BulletSpeedCurve**:
    - **m_spline**:
      | x | y | m_flSlopeIncoming | m_flSlopeOutgoing |
      | --- | --- | --- | --- |
      | 0.0 | 10000.0 | 0.0 | 0.0 |
      | 100.0 | 10000.0 | 0.0 | 0.0 |
    - **m_tangents**:
      | m_nIncomingTangent | m_nOutgoingTangent |
      | --- | --- |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
    - **m_vDomainMins**:
      - 0.0
      - 0.0
    - **m_vDomainMaxs**:
      - 100.0
      - 10000.0
- **_multibase**:
  - inherent_base
- **m_eAbilityType**: EAbilityType_Innate
- **m_bStartTrained**: True
- **m_iMaxLevel**: 1
- **m_eAbilityTargetingLocation**: CITADEL_ABILITY_TARGETING_LOCATION_SELF
- **m_eAbilityActivation**: CITADEL_ABILITY_ACTIVATION_INSTANT_CAST
- **m_nAbilityBehaviors**: CITADEL_ABILITY_BEHAVIOR_HIDDEN | CITADEL_ABILITY_BEHAVIOR_DONT_BREAK_INVISIBILITY | CITADEL_ABILITY_BEHAVIOR_SILENT_CAST_FAILURE_FEEDBACK | CITADEL_ABILITY_BEHAVIOR_DONT_INTERRUPT_SPRINT | CITADEL_ABILITY_BEHAVIOR_INPUT_DIRECTIONAL_2D | CITADEL_ABILITY_BEHAVIOR_NOT_SILENCABLE | CITADEL_ABILITY_BEHAVIOR_NO_TARGET | CITADEL_ABILITY_BEHAVIOR_NON_COMBAT | CITADEL_ABILITY_BEHAVIOR_CASTABLE_WHILE_HIDDEN
- **m_flDashJumpEndTime**: 0.5
- **m_flDashJumpMissMaxSpeed**: 250.0
- **m_strDashJumpActivate**: soundevent:"Player.RollJump.Activate"
- **m_flDashJumpStartTime**: 0.3
- **m_flMantleRefundWindow**: 0.1
- **m_AirJumpParticle**: resource_name:"particles/generic/air_jump.vpcf"
- **m_DashJumpParticle**: resource_name:"particles/generic/roll_jump.vpcf"
- **m_AirJumpExecutedSound**: soundevent:"Player.AirJump.Execute"
- **m_flLateJumpGraceWindow**: 0.15
- **m_flDashJumpVerticalSpeed**: 400.0
- **m_flDashJumpDistanceInMeters**: 18.0
- **m_flWallJumpSpeed**: 600.0
- **m_WallJumpParticle**: resource_name:"particles/generic/wall_jump.vpcf"
- **m_WallJumpExecutedSound**: soundevent:"Player.WallJump"
- **m_WallJumpAirDragCurve**:
  - **m_spline**:
    | x | y | m_flSlopeIncoming | m_flSlopeOutgoing |
    | --- | --- | --- | --- |
    | 0.0 | 2.203636 | -4.451692 | -4.451692 |
    | 0.495011 | 0.0 | -4.451692 | -4.451692 |
  - **m_tangents**:
    | m_nIncomingTangent | m_nOutgoingTangent |
    | --- | --- |
    | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
    | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
  - **m_vDomainMins**:
    - 0.0
    - 0.0
  - **m_vDomainMaxs**:
    - 1.0
    - 5.0
- **m_flWallJumpNormalSpeed**: 400.0

### ESlot_Ability_Slide

- **_class**: citadel_ability_slide
- **m_mapAbilityProperties**:
  - **AbilityCooldown**:
    - **m_strValue**: 0.6
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: cooldown
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_single_stat
        - **_my_subclass_name**: AbilityCooldown_scale_function
        - **m_eSpecificStatScaleType**: ETechCooldown
  - **AbilityDuration**:
    - **m_strValue**: 0.6
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: duration
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_single_stat
        - **_my_subclass_name**: AbilityDuration_scale_function
        - **m_eSpecificStatScaleType**: ETechDuration
  - **AbilityCastRange**:
    - **m_strValue**: 0
    - **m_eDisplayUnits**: EDisplayUnit_Meters
    - **m_strCSSClass**: range
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_single_stat
        - **_my_subclass_name**: AbilityCastRange_scale_function
        - **m_eSpecificStatScaleType**: ETechRange
  - **AbilityUnitTargetLimit**:
    - **m_strValue**: 1
    - **m_bCanSetTokenOverride**: True
  - **AbilityCastDelay**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: cast
    - **m_bCanSetTokenOverride**: True
  - **AbilityChannelTime**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: cast
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_multi_stats
        - **_my_subclass_name**: scale_duration
        - **m_vecScalingStats**:
          - EChannelDuration
          - ETechDuration
  - **AbilityPostCastDuration**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
  - **AbilityCharges**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: cast
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_single_stat
        - **_my_subclass_name**: AbilityCharges_scale_function
        - **m_eSpecificStatScaleType**: EMaxChargesIncrease
  - **AbilityCooldownBetweenCharge**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: charge_cooldown
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_single_stat
        - **_my_subclass_name**: AbilityCooldownBetweenCharge_scale_function
        - **m_eSpecificStatScaleType**: ETechCooldownBetweenChargeUses
  - **ChannelMoveSpeed**:
    - **m_strValue**: 50
    - **m_eDisplayUnits**: EDisplayUnit_MetersPerSecond
    - **m_strCSSClass**: move_speed
    - **m_bCanSetTokenOverride**: True
  - **AbilityResourceCost**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_bCanSetTokenOverride**: True
    - **m_strCSSClass**: cast
  - **TechPower**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_bCanSetTokenOverride**: True
    - **m_eProvidedPropertyType**: MODIFIER_VALUE_TECH_POWER
  - **WeaponPower**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_bCanSetTokenOverride**: True
    - **m_eProvidedPropertyType**: MODIFIER_VALUE_WEAPON_POWER
- **m_bitsPostCastEnabledStateMask**: MODIFIER_STATE_BUSY_WITH_ACTION
- **_editor**:
  - **folder_name**: Base
- **m_WeaponInfo**:
  - **m_BulletSpeedCurve**:
    - **m_spline**:
      | x | y | m_flSlopeIncoming | m_flSlopeOutgoing |
      | --- | --- | --- | --- |
      | 0.0 | 10000.0 | 0.0 | 0.0 |
      | 100.0 | 10000.0 | 0.0 | 0.0 |
    - **m_tangents**:
      | m_nIncomingTangent | m_nOutgoingTangent |
      | --- | --- |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
    - **m_vDomainMins**:
      - 0.0
      - 0.0
    - **m_vDomainMaxs**:
      - 100.0
      - 10000.0
- **_multibase**:
  - inherent_base
- **m_eAbilityType**: EAbilityType_Innate
- **m_bStartTrained**: True
- **m_iMaxLevel**: 1
- **m_bitsInterruptingStates**: MODIFIER_STATE_STUNNED | MODIFIER_STATE_IS_ASLEEP
- **m_eAbilityTargetingLocation**: CITADEL_ABILITY_TARGETING_LOCATION_SELF
- **m_eAbilityActivation**: CITADEL_ABILITY_ACTIVATION_HOLD_TOGGLE
- **m_nAbilityBehaviors**: CITADEL_ABILITY_BEHAVIOR_NO_TARGET | CITADEL_ABILITY_BEHAVIOR_HIDDEN | CITADEL_ABILITY_BEHAVIOR_DONT_BREAK_INVISIBILITY | CITADEL_ABILITY_BEHAVIOR_INPUT_DIRECTIONAL_2D | CITADEL_ABILITY_BEHAVIOR_SILENT_CAST_FAILURE_FEEDBACK | CITADEL_ABILITY_BEHAVIOR_DONT_INTERRUPT_SPRINT | CITADEL_ABILITY_BEHAVIOR_NON_COMBAT | CITADEL_ABILITY_BEHAVIOR_CASTABLE_WHILE_HIDDEN
- **m_flTurnSpeed**: 90.0
- **m_flTurnMinAngDiff**: 5.0
- **m_flTurnMaxAngDiff**: 2.0
- **m_flSprintBoostSpeed**: 300.0
- **m_flMinSustainSpeed**: 170.0
- **m_flMinActivationSpeed**: 350.0
- **m_flBoostMinSpeed**: 100.0
- **m_flBoostMaxSpeed**: 600.0
- **m_flButtonPressWindow**: 5.0
- **m_flBoostMinTriggerSpeed**: 300.0
- **m_flBoostMaxTriggerSpeed**: 700.0
- **m_flAccMaxSlopeDeg**: 45.0
- **m_flAccMinSlopeDeg**: 5.0
- **m_flAccMinSlopeScale**: 0.5
- **m_flSlideActivationProbeForwardOffset**: 200.0
- **m_flSlopeFacingAngleToActivate**: 75.0
- **m_flAirDragAfterJump**: 2.0
- **m_flAirDragAfterJumpTime**: 0.5
- **m_flAirDragMaxAngle**: 2.0
- **m_flDashSlideSpeed**: 650.0
- **m_flDashMinActivationSpeed**: 250.0
- **m_flFrictionMaxSlope**: 0.15
- **m_flFrictionMinSlope**: 0.15
- **m_flFrictionFlatGround**: 0.8
- **m_flFlatGroundFrictionGraceTime**: 0.6
- **m_flMinAngleToConsiderASlope**: 8.0
- **m_flFrictionFlatGroundGrace**: 0.05
- **m_flAirDragResetTime**: 0.5
- **m_flLateSlideJumpWindow**: 0.25
- **m_cameraSequenceCastStart**:
  - **m_strToken**: 
  - **m_bIsEmpty**: False
  - **m_vecDistanceOperations**:
  - **m_vecFOVOperations**:
  - **m_vecTargetPosOperations**:
  - **m_vecVertOffsetOperations**:
  - **m_vecHorizOffsetOperations**:
- **m_cameraSequenceStartSliding**:
  - **m_vecFOVOperations**:
    | m_flApproachTarget | m_flApproachSpeed | m_flApproachAcceleration |
    | --- | --- | --- |
    | 85.0 | 50.0 | 100.0 |
    |  |  |  |
- **m_cameraSequenceEndSliding**:
  - **m_vecFOVOperations**:
    | m_flSpringStrength | m_eCameraOperation |
    | --- | --- |
    | 6.0 | k_ECameraOp_Spring |
- **m_flLandedFlatGroundFrictionGraceTime**: 0.75
- **m_flSlideMaxSlopeMaxAccSpeed**: 1500.0
- **m_flSlideMinSlopeMaxAccSpeed**: 1200.0
- **m_flSlideMaxSlopeAcceleration**: 850.0
- **m_flSlideMinSlopeAcceleration**: 500.0
- **m_flLandingSlopeScaleBias**: 0.6
- **m_flFrictionUphillMinSlope**: 1.0
- **m_flFrictionUphillMaxSlope**: 1.5
- **m_flInitialSlideUseForwardProbeTime**: 0.25
- **m_SlideParticle**: resource_name:"particles/generic/slide.vpcf"
- **m_flSlideProbeForwardOffset**: 60.0
- **m_flMaxDistanceBetweenProbeSamples**: 20.0
- **m_flCurrentSlopeSampleDistance**: 20.0
- **m_flSampleVelDiffStdDevScaleCutoff**: 1.0
- **m_strStartSound**: soundevent:"Gameplay.Slide.Enter"
- **m_strStopSound**: soundevent:"Gameplay.Slide.Exit"
- **m_strLoopingSound**: soundevent:"Gameplay.Slide.Lp"
- **m_SlideEffectRemap**:
  - 250.0
  - 700.0
  - 0.1
  - 1.0
- **m_flDashSlideFrictionTime**: 1.0
- **m_flDashSlideFriction**: 0.175
- **m_flDashSlideFailSpeed**: 450.0
- **m_flDashSlideStartTime**: 0.3
- **m_strDashSlideActivate**: soundevent:"Player.RollJump.Activate"
- **m_GetupSpeedCurve**:
  - **m_spline**:
    | x | y | m_flSlopeIncoming | m_flSlopeOutgoing |
    | --- | --- | --- | --- |
    | 0.0 | -20.0 | 3.954919 | 3.954919 |
    | 0.650053 | -17.429092 | 26.666666 | 26.666666 |
    | 0.75 | 0.0 | 174.383698 | 174.383698 |
  - **m_tangents**:
    | m_nIncomingTangent | m_nOutgoingTangent |
    | --- | --- |
    | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
    | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
    | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
  - **m_vDomainMins**:
    - 0.0
    - -20.0
  - **m_vDomainMaxs**:
    - 0.75
    - 0.0
- **m_flGetupBusyDuration**: 0.35

### ESlot_Ability_ZipLine

- **_class**: citadel_ability_zip_line
- **m_mapAbilityProperties**:
  - **AbilityCooldown**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: cooldown
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_single_stat
        - **_my_subclass_name**: AbilityCooldown_scale_function
        - **m_eSpecificStatScaleType**: ETechCooldown
  - **AbilityDuration**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: duration
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_single_stat
        - **_my_subclass_name**: AbilityDuration_scale_function
        - **m_eSpecificStatScaleType**: ETechDuration
  - **AbilityCastRange**:
    - **m_strValue**: 0
    - **m_eDisplayUnits**: EDisplayUnit_Meters
    - **m_strCSSClass**: range
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_single_stat
        - **_my_subclass_name**: AbilityCastRange_scale_function
        - **m_eSpecificStatScaleType**: ETechRange
  - **AbilityUnitTargetLimit**:
    - **m_strValue**: 1
    - **m_bCanSetTokenOverride**: True
  - **AbilityCastDelay**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: cast
    - **m_bCanSetTokenOverride**: True
  - **AbilityChannelTime**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: cast
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_multi_stats
        - **_my_subclass_name**: scale_duration
        - **m_vecScalingStats**:
          - EChannelDuration
          - ETechDuration
  - **AbilityPostCastDuration**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
  - **AbilityCharges**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: cast
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_single_stat
        - **_my_subclass_name**: AbilityCharges_scale_function
        - **m_eSpecificStatScaleType**: EMaxChargesIncrease
  - **AbilityCooldownBetweenCharge**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: charge_cooldown
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_single_stat
        - **_my_subclass_name**: AbilityCooldownBetweenCharge_scale_function
        - **m_eSpecificStatScaleType**: ETechCooldownBetweenChargeUses
  - **ChannelMoveSpeed**:
    - **m_strValue**: 50
    - **m_eDisplayUnits**: EDisplayUnit_MetersPerSecond
    - **m_strCSSClass**: move_speed
    - **m_bCanSetTokenOverride**: True
  - **AbilityResourceCost**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_bCanSetTokenOverride**: True
    - **m_strCSSClass**: cast
  - **TechPower**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_bCanSetTokenOverride**: True
    - **m_eProvidedPropertyType**: MODIFIER_VALUE_TECH_POWER
  - **WeaponPower**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_bCanSetTokenOverride**: True
    - **m_eProvidedPropertyType**: MODIFIER_VALUE_WEAPON_POWER
  - **MaxMountDistance2D**:
    - **m_strValue**: 15m
  - **StunDuration**:
    - **m_strValue**: 3
    - **m_strCSSClass**: duration
  - **SlowDuration**:
    - **m_strValue**: 8
  - **KnockedOffDamagePct**:
    - **m_strValue**: 15
  - **DismountHorizontalMinSpeedPercent**:
    - **m_strValue**: 40
  - **DismountHorizontalMaxSpeedPercent**:
    - **m_strValue**: 85
  - **PlayerSpeedCheckScale**:
    - **m_strValue**: 0.65
  - **DismountVerticalSpeed**:
    - **m_strValue**: 300
  - **DamageCooldown**:
    - **m_strValue**: 3
    - **m_strCSSClass**: cooldown
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_single_stat
        - **_my_subclass_name**: DamageCooldown_scale_function
        - **m_eSpecificStatScaleType**: ETechCooldown
  - **ZipSpeedInner**:
    - **m_strValue**: 693
  - **ZipSpeedOuter**:
    - **m_strValue**: 693
  - **ZipAcc**:
    - **m_strValue**: 1000
  - **ZipMasteryAccelerationWaitTime**:
    - **m_strValue**: 2
  - **ZipMasteryExtraAcc**:
    - **m_strValue**: 150
  - **ZipMasteryDamageCooldown**:
    - **m_strValue**: 3
    - **m_strCSSClass**: cooldown
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_single_stat
        - **_my_subclass_name**: ZipMasteryDamageCooldown_scale_function
        - **m_eSpecificStatScaleType**: ETechCooldown
  - **ZipMasteryExtraSpeedBonus**:
    - **m_strValue**: 125
  - **LatchSpeed**:
    - **m_strValue**: 1500
  - **LatchInitialSpeed**:
    - **m_strValue**: 600
  - **LatchEndSpeed**:
    - **m_strValue**: 500
  - **LatchReelAcc**:
    - **m_strValue**: 4000
  - **LatchVisualSnapProgress**:
    - **m_strValue**: 0.85
  - **ZiplineProtectionSlowDurationOnHit**:
    - **m_strValue**: 2.0
  - **ZiplineProtectionDamageAmp**:
    - **m_strVAlue**: 35
- **m_bitsPostCastEnabledStateMask**: MODIFIER_STATE_BUSY_WITH_ACTION
- **_editor**:
  - **folder_name**: Base
- **m_WeaponInfo**:
  - **m_BulletSpeedCurve**:
    - **m_spline**:
      | x | y | m_flSlopeIncoming | m_flSlopeOutgoing |
      | --- | --- | --- | --- |
      | 0.0 | 10000.0 | 0.0 | 0.0 |
      | 100.0 | 10000.0 | 0.0 | 0.0 |
    - **m_tangents**:
      | m_nIncomingTangent | m_nOutgoingTangent |
      | --- | --- |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
    - **m_vDomainMins**:
      - 0.0
      - 0.0
    - **m_vDomainMaxs**:
      - 100.0
      - 10000.0
- **_multibase**:
  - inherent_base
- **m_eAbilityType**: EAbilityType_Innate
- **m_bStartTrained**: True
- **m_iMaxLevel**: 1
- **m_eAbilityTargetingLocation**: CITADEL_ABILITY_TARGETING_LOCATION_SELF
- **m_eAbilityActivation**: CITADEL_ABILITY_ACTIVATION_ON_BUTTON_IS_DOWN
- **m_nAbilityBehaviors**: CITADEL_ABILITY_BEHAVIOR_DONT_BREAK_INVISIBILITY | CITADEL_ABILITY_BEHAVIOR_DONT_INTERRUPT_SPRINT | CITADEL_ABILITY_BEHAVIOR_NOT_SILENCABLE | CITADEL_ABILITY_BEHAVIOR_NO_TARGET | CITADEL_ABILITY_BEHAVIOR_NON_COMBAT | CITADEL_ABILITY_BEHAVIOR_CASTABLE_WHILE_HIDDEN
- **m_bitsInterruptingStates**: MODIFIER_STATE_IMMOBILIZED | MODIFIER_STATE_STUNNED | MODIFIER_STATE_IS_ASLEEP
- **m_strZipLineStartSound**: soundevent:"Ability.ZipLine.Start"
- **m_ZipLinePreviewParticle**: resource_name:"particles/environment/zip_line_path_preview.vpcf"
- **m_ZipLineSpeedParticle**: resource_name:"particles/items/zip_line_speed.vpcf"
- **m_ZipLineTetherParticle**: resource_name:"particles/environment/zip_line_path_universal_attach.vpcf"
- **m_ZipLineTetherAttachParticle**: resource_name:"particles/environment/zip_line_path_universal_attach_end.vpcf"
- **m_strZipLineSummonSound**: soundevent:"Ability.ZipLine.Summon"
- **m_strZipLineLatchedSound**: soundevent:"Ability.ZipLine.Summon.Latched"
- **m_flMinButtonHoldTimeToActivate**: 0.175
- **m_flCrouchDropSpeedFraction**: 1.0
- **m_flCrouchDropAirDragSuppressDuration**: 2.0
- **m_RidingZipLineModifier**:
  - **subclass**:
    - **_class**: modifier_base
    - **_my_subclass_name**: modifier_riding_zipline
    - **m_sAmbientLoopingSound**: soundevent:"Ability.ZipLine.Loop"
    - **m_sEndSound**: soundevent:"Ability.ZipLine.End"
    - **m_bIsHidden**: True
- **m_KnockedOffSlowModifier**:
  - **subclass**:
    - **_class**: modifier_diminishing_slow
    - **_my_subclass_name**: modifier_knocked_off_zipline_slow
    - **m_sLocalizationName**: modifier_knocked_off_zipline_slow
    - **m_eDebuffType**: MODIFIER_DEBUFF_YES
- **m_ZipLineIntroModifier**:
  - **subclass**:
    - **_class**: modifier_base
    - **_my_subclass_name**: modifier_zipline_intro
    - **m_nEnabledStateMask**: MODIFIER_STATE_ZIPLINE_INTRO
    - **m_bIsHidden**: True
- **m_cameraSequenceAwaitingTether**:
  - **m_vecDistanceOperations**:
    | m_bLerpEndAtDefault | m_flLerpEnd | m_flLerpDuration | m_eCameraOperation | m_bValuesAreRelative |
    | --- | --- | --- | --- | --- |
    | False | 20.0 | 0.5 | k_ECameraOp_Lerp | True |
    |  |  |  | k_ECameraOp_Maintain |  |
  - **m_vecFOVOperations**:
    | m_flLerpBias | m_flLerpDuration | m_bLerpEndAtDefault | m_flLerpEnd | m_eCameraOperation | m_bValuesAreRelative |
    | --- | --- | --- | --- | --- | --- |
    | 0.8 | 0.5 | False | -10.0 | k_ECameraOp_Lerp | True |
    |  |  |  |  | k_ECameraOp_Maintain |  |
- **m_cameraSequenceLatched**:
  - **m_vecFOVOperations**:
    | m_bLerpEndAtDefault | m_flLerpEnd | m_flLerpBias | m_flLerpDuration | m_eCameraOperation | m_bValuesAreRelative |
    | --- | --- | --- | --- | --- | --- |
    | False | 10.0 | 0.8 | 0.4 | k_ECameraOp_Lerp | True |
    | False | 0.0 |  | 4.0 | k_ECameraOp_Lerp | True |
  - **m_vecTargetPosOperations**:
    | m_flLagMinDuration | m_flLagTime | m_flLagSpringStrength | m_flLagMaxSpeed | m_eCameraOperation |
    | --- | --- | --- | --- | --- |
    | 0.0 | 0.1 | 5.0 | 75.0 | k_ECameraOp_Lag |
- **m_cameraSequenceAttached**:
  - **m_vecFOVOperations**:
    | m_flLerpDuration | m_eCameraOperation |
    | --- | --- |
    | 5.6 | k_ECameraOp_Lerp |
  - **m_vecDistanceOperations**:
    | m_flLerpDuration | m_bLerpEndAtDefault | m_flLerpEnd | m_eCameraOperation | m_bValuesAreRelative |
    | --- | --- | --- | --- | --- |
    | 5.6 | False | 0.0 | k_ECameraOp_Lerp | True |
    |  |  |  | k_ECameraOp_Maintain |  |
  - **m_vecVertOffsetOperations**:
- **m_cameraSequenceClear**:
  - **m_vecDistanceOperations**:
    | m_eCameraOperation |
    | --- |
    | k_ECameraOp_Spring |
  - **m_vecFOVOperations**:
    | m_eCameraOperation |
    | --- |
    | k_ECameraOp_Spring |
- **m_DOFWhileZiplining**:
  - **m_flDofNearCrisp**: 200.0
  - **m_flDofFarCrisp**: 1000000.0
  - **m_flDofFarBlurry**: 1000001.0
- **m_ZipLineEnemyKnockdownProtectionParticle**: resource_name:"particles/generic/zipline_bullet_safe_buff.vpcf"
- **m_ZipLineSelfKnockdownProtectionParticle**: resource_name:"particles/generic/zipline_bullet_safe_buff_player.vpcf"
- **m_ZipLineKnockdownProtectionStatusParticle**: resource_name:"particles/status_fx/status_fx_zipline_knockdown_protection.vpcf"
- **m_ZipLineKnockdownImmuneModifier**:
  - **subclass**:
    - **_class**: modifier_zipline_knockdown_immune
    - **_my_subclass_name**: modifier_zipline_knockdown_immune
    - **m_ZipLineEnemyKnockdownProtectionParticle**: resource_name:"particles/generic/zipline_bullet_safe_buff.vpcf"
    - **m_ZipLineSelfKnockdownProtectionParticle**: resource_name:"particles/generic/zipline_bullet_safe_buff_player.vpcf"
    - **m_ZipLineKnockdownProtectionStatusParticle**: resource_name:"particles/status_fx/status_fx_zipline_knockdown_protection_player.vpcf"
    - **m_sLocalizationName**: modifier_zipline_knockdown_immune
    - **m_eDebuffType**: MODIFIER_DEBUFF_NO
    - **m_bIsHidden**: True
    - **m_ZipLineKnockdownProtectionStatusEnemyParticle**: resource_name:"particles/status_fx/status_fx_zipline_knockdown_protection.vpcf"
- **m_ZipLineSlowModifier**:
  - **subclass**:
    - **_my_subclass_name**: zipline_protection_slow
    - **_class**: modifier_zipline_speed
    - **m_flRampUpTime**: 2.0
    - **m_flPercentageMultiplierStart**: -70
    - **m_flPercentageMultiplierEnd**: 0
    - **m_bIsHidden**: True
- **m_flCameraWobbleIntensity**: 0.3

### ESlot_Ability_ZipLineBoost

- **_class**: citadel_ability_zipline_boost
- **m_mapAbilityProperties**:
  - **AbilityCooldown**:
    - **m_strValue**: 340
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: cooldown
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_single_stat
        - **_my_subclass_name**: AbilityCooldown_scale_function
        - **m_eSpecificStatScaleType**: ETechCooldown
    - **m_eScaleType**: EStatsInvalid
  - **AbilityDuration**:
    - **m_strValue**: 32
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: duration
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_single_stat
        - **_my_subclass_name**: AbilityDuration_scale_function
        - **m_eSpecificStatScaleType**: ETechDuration
  - **AbilityCastRange**:
    - **m_strValue**: 0
    - **m_eDisplayUnits**: EDisplayUnit_Meters
    - **m_strCSSClass**: range
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_single_stat
        - **_my_subclass_name**: AbilityCastRange_scale_function
        - **m_eSpecificStatScaleType**: ETechRange
  - **AbilityUnitTargetLimit**:
    - **m_strValue**: 1
    - **m_bCanSetTokenOverride**: True
  - **AbilityCastDelay**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: cast
    - **m_bCanSetTokenOverride**: True
  - **AbilityChannelTime**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: cast
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_multi_stats
        - **_my_subclass_name**: scale_duration
        - **m_vecScalingStats**:
          - EChannelDuration
          - ETechDuration
  - **AbilityPostCastDuration**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
  - **AbilityCharges**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: cast
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_single_stat
        - **_my_subclass_name**: AbilityCharges_scale_function
        - **m_eSpecificStatScaleType**: EMaxChargesIncrease
  - **AbilityCooldownBetweenCharge**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: charge_cooldown
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_single_stat
        - **_my_subclass_name**: AbilityCooldownBetweenCharge_scale_function
        - **m_eSpecificStatScaleType**: ETechCooldownBetweenChargeUses
  - **ChannelMoveSpeed**:
    - **m_strValue**: 50
    - **m_eDisplayUnits**: EDisplayUnit_MetersPerSecond
    - **m_strCSSClass**: move_speed
    - **m_bCanSetTokenOverride**: True
  - **AbilityResourceCost**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_bCanSetTokenOverride**: True
    - **m_strCSSClass**: cast
  - **TechPower**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_bCanSetTokenOverride**: True
    - **m_eProvidedPropertyType**: MODIFIER_VALUE_TECH_POWER
  - **WeaponPower**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_bCanSetTokenOverride**: True
    - **m_eProvidedPropertyType**: MODIFIER_VALUE_WEAPON_POWER
- **m_bitsPostCastEnabledStateMask**: MODIFIER_STATE_BUSY_WITH_ACTION
- **_editor**:
  - **folder_name**: Base
- **m_WeaponInfo**:
  - **m_BulletSpeedCurve**:
    - **m_spline**:
      | x | y | m_flSlopeIncoming | m_flSlopeOutgoing |
      | --- | --- | --- | --- |
      | 0.0 | 10000.0 | 0.0 | 0.0 |
      | 100.0 | 10000.0 | 0.0 | 0.0 |
    - **m_tangents**:
      | m_nIncomingTangent | m_nOutgoingTangent |
      | --- | --- |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
    - **m_vDomainMins**:
      - 0.0
      - 0.0
    - **m_vDomainMaxs**:
      - 100.0
      - 10000.0
- **_multibase**:
  - inherent_base
- **m_eAbilityType**: EAbilityType_Innate
- **m_bStartTrained**: True
- **m_iMaxLevel**: 1
- **m_eAbilityTargetingLocation**: CITADEL_ABILITY_TARGETING_LOCATION_SELF
- **m_eAbilityActivation**: CITADEL_ABILITY_ACTIVATION_INSTANT_CAST
- **m_nAbilityBehaviors**: CITADEL_ABILITY_BEHAVIOR_SILENT_CAST_FAILURE_FEEDBACK | CITADEL_ABILITY_BEHAVIOR_NO_TARGET | CITADEL_ABILITY_BEHAVIOR_CAN_CAST_ON_ZIPLINE | CITADEL_ABILITY_BEHAVIOR_MOVEMENT
- **m_bitsInterruptingStates**: MODIFIER_STATE_IMMOBILIZED | MODIFIER_STATE_STUNNED | MODIFIER_STATE_IS_ASLEEP | MODIFIER_STATE_SILENCE_MOVEMENT_ABILITES
- **m_strCSSClass**: ziplineMastery
- **m_strAbilityImage**: panorama:"file://{images}/upgrades/mods_utility/zipline_mastery.psd"
- **m_ZipboostModifier**:
  - **subclass**:
    - **_class**: modifier_zipline_boost
    - **_my_subclass_name**: modifier_zipline_boost
    - **m_strSmallIconCssClass**: zipline_speed_pickup
    - **m_strParticleEffect**: resource_name:"particles/upgrades/zipline_mastery_landing_buff.vpcf"
    - **m_sLocalizationName**: zipline_boost
    - **m_flRampUpTime**: 1.0
    - **m_flPercentageSpeedIncrease**: 130.0
    - **m_cameraSequenceStartBoost**:
      - **m_vecFOVOperations**:
        | m_flApproachTarget | m_flApproachSpeed | m_flApproachMinDuration | m_bLerpEndAtDefault | m_flLerpEnd | m_flLerpBias | m_flLerpDuration | m_eCameraOperation |
        | --- | --- | --- | --- | --- | --- | --- | --- |
        | 40.0 | 10.0 | 1.0 | False | 110.0 | 0.75 | 1.0 | k_ECameraOp_Lerp |
        |  |  |  |  |  |  |  | k_ECameraOp_Maintain |
      - **m_vecDistanceOperations**:
        | m_flApproachSpeed | m_flApproachTarget | m_flApproachMinDuration | m_bLerpEndAtDefault | m_flLerpEnd | m_flLerpDuration | m_eCameraOperation |
        | --- | --- | --- | --- | --- | --- | --- |
        | 60.0 | 1000.0 | 1.0 | False | 200.0 | 1.0 | k_ECameraOp_Lerp |
        |  |  |  |  |  |  | k_ECameraOp_Maintain |
      - **m_vecTargetPosOperations**:
    - **m_sStartSound**: soundevent:"Gameplay.World.Zipline.Speed.Boost.Start"
- **m_HUDPanel**:
  - **m_vecButtonHints**:
    | m_eButton1 | m_strLocToken | m_eHintSide | m_bShowAbilityIcon | m_bIsHintShownWhileOnCooldown |
    | --- | --- | --- | --- | --- |
    | EButtonHint_Parry | #AbilityButtonHint_ZipLineBoost | EButtonSide_Right | True | True |
  - **m_vecHUDElements**:
- **m_flTimeForHint**: 1.0

### ESlot_Ability_ClimbRope

- **_class**: citadel_ability_climb_rope
- **m_mapAbilityProperties**:
  - **AbilityCooldown**:
    - **m_strValue**: 0.1
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: cooldown
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_single_stat
        - **_my_subclass_name**: AbilityCooldown_scale_function
        - **m_eSpecificStatScaleType**: ETechCooldown
  - **AbilityDuration**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: duration
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_single_stat
        - **_my_subclass_name**: AbilityDuration_scale_function
        - **m_eSpecificStatScaleType**: ETechDuration
  - **AbilityCastRange**:
    - **m_strValue**: 0
    - **m_eDisplayUnits**: EDisplayUnit_Meters
    - **m_strCSSClass**: range
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_single_stat
        - **_my_subclass_name**: AbilityCastRange_scale_function
        - **m_eSpecificStatScaleType**: ETechRange
  - **AbilityUnitTargetLimit**:
    - **m_strValue**: 1
    - **m_bCanSetTokenOverride**: True
  - **AbilityCastDelay**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: cast
    - **m_bCanSetTokenOverride**: True
  - **AbilityChannelTime**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: cast
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_multi_stats
        - **_my_subclass_name**: scale_duration
        - **m_vecScalingStats**:
          - EChannelDuration
          - ETechDuration
  - **AbilityPostCastDuration**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
  - **AbilityCharges**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: cast
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_single_stat
        - **_my_subclass_name**: AbilityCharges_scale_function
        - **m_eSpecificStatScaleType**: EMaxChargesIncrease
  - **AbilityCooldownBetweenCharge**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: charge_cooldown
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_single_stat
        - **_my_subclass_name**: AbilityCooldownBetweenCharge_scale_function
        - **m_eSpecificStatScaleType**: ETechCooldownBetweenChargeUses
  - **ChannelMoveSpeed**:
    - **m_strValue**: 50
    - **m_eDisplayUnits**: EDisplayUnit_MetersPerSecond
    - **m_strCSSClass**: move_speed
    - **m_bCanSetTokenOverride**: True
  - **AbilityResourceCost**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_bCanSetTokenOverride**: True
    - **m_strCSSClass**: cast
  - **TechPower**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_bCanSetTokenOverride**: True
    - **m_eProvidedPropertyType**: MODIFIER_VALUE_TECH_POWER
  - **WeaponPower**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_bCanSetTokenOverride**: True
    - **m_eProvidedPropertyType**: MODIFIER_VALUE_WEAPON_POWER
- **m_bitsPostCastEnabledStateMask**: MODIFIER_STATE_BUSY_WITH_ACTION
- **_editor**:
  - **folder_name**: Base
- **m_WeaponInfo**:
  - **m_BulletSpeedCurve**:
    - **m_spline**:
      | x | y | m_flSlopeIncoming | m_flSlopeOutgoing |
      | --- | --- | --- | --- |
      | 0.0 | 10000.0 | 0.0 | 0.0 |
      | 100.0 | 10000.0 | 0.0 | 0.0 |
    - **m_tangents**:
      | m_nIncomingTangent | m_nOutgoingTangent |
      | --- | --- |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
    - **m_vDomainMins**:
      - 0.0
      - 0.0
    - **m_vDomainMaxs**:
      - 100.0
      - 10000.0
- **_multibase**:
  - inherent_base
- **m_eAbilityType**: EAbilityType_Innate
- **m_bStartTrained**: True
- **m_iMaxLevel**: 1
- **m_eAbilityTargetingLocation**: CITADEL_ABILITY_TARGETING_LOCATION_SELF
- **m_eAbilityActivation**: CITADEL_ABILITY_ACTIVATION_ON_BUTTON_IS_DOWN
- **m_nAbilityBehaviors**: CITADEL_ABILITY_BEHAVIOR_HIDDEN | CITADEL_ABILITY_BEHAVIOR_DONT_BREAK_INVISIBILITY | CITADEL_ABILITY_BEHAVIOR_SILENT_CAST_FAILURE_FEEDBACK | CITADEL_ABILITY_BEHAVIOR_DONT_INTERRUPT_SPRINT | CITADEL_ABILITY_BEHAVIOR_NOT_SILENCABLE | CITADEL_ABILITY_BEHAVIOR_NO_TARGET | CITADEL_ABILITY_BEHAVIOR_NON_COMBAT | CITADEL_ABILITY_BEHAVIOR_CASTABLE_WHILE_HIDDEN
- **m_bitsInterruptingStates**: MODIFIER_STATE_IMMOBILIZED | MODIFIER_STATE_STUNNED | MODIFIER_STATE_IS_ASLEEP
- **m_flActivateRange**: 90.0
- **m_flMinButtonHoldTimeToActivate**: 0.15
- **m_flClimbSpeedUp**: 11.0
- **m_flClimbSpeedDown**: 12.0
- **m_flClimbSpeedDownMax**: 30.0
- **m_flClimbDownAccelTime**: 1.0
- **m_flLatchSpeed**: 400
- **m_flAttachOffset**: 70.0
- **m_flMinReconnectTime**: 0.5
- **m_flSideMoveReduction**: -100.0
- **m_flTopOffset**: 40.0
- **m_flBottomOffset**: 60.0
- **m_flTraceRadiusSize**: 96.0
- **m_flStopTimeToShoot**: 0.2
- **m_flJumpOffVertical**: 250.0
- **m_flJumpOffHorizontal**: 400.0
- **m_flDuckOffVertical**: 100.0
- **m_flDuckOffHorizontal**: 400.0
- **m_flJumpToRoofRayCheckDist**: 160.0
- **m_flMinTimeToRoofCheck**: 0.7
- **m_HUDPanel**:
  - **m_vecButtonHints**:
    | m_strLocToken | m_eHintSide | m_strBindingOverride1 | m_strContext |
    | --- | --- | --- | --- |
    | #AbilityButtonHint_ClimbRope | EButtonSide_Bottom | in_mantle | climb_rope |

### ESlot_Ability_Innate_1

- **_class**: citadel_ability_dash
- **m_mapAbilityProperties**:
  - **AbilityCooldown**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: cooldown
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_single_stat
        - **_my_subclass_name**: AbilityCooldown_scale_function
        - **m_eSpecificStatScaleType**: ETechCooldown
  - **AbilityDuration**:
    - **m_strValue**: 0.6
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: duration
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_single_stat
        - **_my_subclass_name**: AbilityDuration_scale_function
        - **m_eSpecificStatScaleType**: ETechDuration
  - **AbilityCastRange**:
    - **m_strValue**: 0
    - **m_eDisplayUnits**: EDisplayUnit_Meters
    - **m_strCSSClass**: range
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_single_stat
        - **_my_subclass_name**: AbilityCastRange_scale_function
        - **m_eSpecificStatScaleType**: ETechRange
  - **AbilityUnitTargetLimit**:
    - **m_strValue**: 1
    - **m_bCanSetTokenOverride**: True
  - **AbilityCastDelay**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: cast
    - **m_bCanSetTokenOverride**: True
  - **AbilityChannelTime**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: cast
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_multi_stats
        - **_my_subclass_name**: scale_duration
        - **m_vecScalingStats**:
          - EChannelDuration
          - ETechDuration
  - **AbilityPostCastDuration**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
  - **AbilityCharges**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: cast
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_single_stat
        - **_my_subclass_name**: AbilityCharges_scale_function
        - **m_eSpecificStatScaleType**: EMaxChargesIncrease
  - **AbilityCooldownBetweenCharge**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: charge_cooldown
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_single_stat
        - **_my_subclass_name**: AbilityCooldownBetweenCharge_scale_function
        - **m_eSpecificStatScaleType**: ETechCooldownBetweenChargeUses
  - **ChannelMoveSpeed**:
    - **m_strValue**: 50
    - **m_eDisplayUnits**: EDisplayUnit_MetersPerSecond
    - **m_strCSSClass**: move_speed
    - **m_bCanSetTokenOverride**: True
  - **AbilityResourceCost**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_bCanSetTokenOverride**: True
    - **m_strCSSClass**: cast
  - **TechPower**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_bCanSetTokenOverride**: True
    - **m_eProvidedPropertyType**: MODIFIER_VALUE_TECH_POWER
  - **WeaponPower**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_bCanSetTokenOverride**: True
    - **m_eProvidedPropertyType**: MODIFIER_VALUE_WEAPON_POWER
  - **PostGroundDashSpeed**:
    - **m_strValue**: 25
  - **PostGroundDashSpeedTime**:
    - **m_strValue**: 1.6
  - **PostGroundDashSpreadPenalty**:
    - **m_strValue**: 3
  - **AirDashTravelTime**:
    - **m_strValue**: 0.45
  - **AirDashDistance**:
    - **m_strValue**: 8m
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_single_stat
        - **_my_subclass_name**: AirDashDistance_scale_function
        - **m_eSpecificStatScaleType**: EAirMoveDistanceScale
  - **AirDashTravelTimeBias**:
    - **m_strValue**: 0.5
- **m_bitsPostCastEnabledStateMask**: MODIFIER_STATE_BUSY_WITH_ACTION
- **_editor**:
  - **folder_name**: Base
- **m_WeaponInfo**:
  - **m_BulletSpeedCurve**:
    - **m_spline**:
      | x | y | m_flSlopeIncoming | m_flSlopeOutgoing |
      | --- | --- | --- | --- |
      | 0.0 | 10000.0 | 0.0 | 0.0 |
      | 100.0 | 10000.0 | 0.0 | 0.0 |
    - **m_tangents**:
      | m_nIncomingTangent | m_nOutgoingTangent |
      | --- | --- |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
    - **m_vDomainMins**:
      - 0.0
      - 0.0
    - **m_vDomainMaxs**:
      - 100.0
      - 10000.0
- **_multibase**:
  - inherent_base
- **m_eAbilityType**: EAbilityType_Innate
- **m_bStartTrained**: True
- **m_iMaxLevel**: 1
- **m_eAbilityTargetingLocation**: CITADEL_ABILITY_TARGETING_LOCATION_NONE
- **m_eAbilityActivation**: CITADEL_ABILITY_ACTIVATION_INSTANT_CAST
- **m_nAbilityBehaviors**: CITADEL_ABILITY_BEHAVIOR_HIDDEN | CITADEL_ABILITY_BEHAVIOR_DONT_BREAK_INVISIBILITY | CITADEL_ABILITY_BEHAVIOR_DONT_INTERRUPT_SPRINT | CITADEL_ABILITY_BEHAVIOR_INPUT_DIRECTIONAL_2D | CITADEL_ABILITY_BEHAVIOR_NOT_SILENCABLE | CITADEL_ABILITY_BEHAVIOR_NO_TARGET | CITADEL_ABILITY_BEHAVIOR_NON_COMBAT | CITADEL_ABILITY_BEHAVIOR_CASTABLE_WHILE_HIDDEN
- **m_HUDPanel**:
  - **m_vecHUDElements**:
    | m_eType | m_Layout | m_strContext |
    | --- | --- | --- |
    | CITADEL_ABILITY_HUD_ELEMENT_TYPE_PROGRESS | file://{resources}/layout/ability_hud_elements/element_charges.vxml | charges |
- **m_flMaxMoveIterationScale**: 2.0
- **m_flMaxAngDiff**: 90.0
- **m_strDashActivate**: soundevent:"Player.AirJump.Execute"
- **m_flDurationScaleForSpeed**: 0.4
- **m_flAirDashEndVelocityScale**: 0.2
- **m_bitsInterruptingStates**: MODIFIER_STATE_IMMOBILIZED | MODIFIER_STATE_STUNNED | MODIFIER_STATE_IS_ASLEEP | MODIFIER_STATE_MOVEMENT_ABILITY_RESTRICTED
- **m_DashParticle**: resource_name:"particles/generic/air_dash.vpcf"
- **m_flPostDragDuration**: 0.1
- **m_flPostDrag**: 4.0
- **m_flAirDashAccPct**: -40.0
- **m_flSlideEarlyOutWindow**: 0.2
- **m_flSlideLockoutTime**: 0.3
- **m_flGroundDashAirbornDrag**: 0.7
- **m_strGroundDashActivate**: soundevent:"Player.Ground.Roll.Execute"
- **m_curvePosition**:
  - **m_spline**:
    | x | y | m_flSlopeIncoming | m_flSlopeOutgoing |
    | --- | --- | --- | --- |
    | 0.0 | 0.0 | 1.006771 | 1.006771 |
    | 0.948487 | 0.954909 | 1.0 | 1.0 |
    | 1.0 | 1.0 | 0.875335 | 0.875335 |
  - **m_tangents**:
    | m_nIncomingTangent | m_nOutgoingTangent |
    | --- | --- |
    | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
    | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
    | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
  - **m_vDomainMins**:
    - 0.0
    - 0.0
  - **m_vDomainMaxs**:
    - 1.0
    - 1.0
- **m_flGroundDashDistanceInMeters**: 10.0
- **m_cameraSequenceGroundDashActivate**:
  - **m_vecTargetPosOperations**:
    | m_eCameraOperation | m_flLagTime | m_flLagMaxSpeed | m_flLagSpringStrength |
    | --- | --- | --- | --- |
    | k_ECameraOp_Lag | 0.2 | 150.0 | 10.0 |
- **m_cameraSequenceAirDashActivate**:
  - **m_vecFOVOperations**:
    | m_eCameraOperation | m_bValuesAreRelative | m_bLerpEndAtDefault | m_flLerpEnd | m_flLerpDuration |
    | --- | --- | --- | --- | --- |
    | k_ECameraOp_Lerp | True | False | -5.0 | 0.4 |
    | k_ECameraOp_Lerp | False |  |  | 0.5 |
  - **m_vecTargetPosOperations**:
    | m_eCameraOperation | m_flLagMinDuration | m_flLagTime | m_flLagSpringStrength | m_flLagMaxSpeed |
    | --- | --- | --- | --- | --- |
    | k_ECameraOp_Lag | 0.0 | 0.1 | 5.0 | 50.0 |
- **m_strStaminaDrainedSound**: soundevent:"Damage.Stamina.Drain"
- **m_DownDashParticle**: resource_name:"particles/generic/down_dash.vpcf"
- **m_bPlayMeepMop**: False

### ESlot_Ability_Innate_2

- **_class**: citadel_ability_sprint
- **m_mapAbilityProperties**:
  - **AbilityCooldown**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: cooldown
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_single_stat
        - **_my_subclass_name**: AbilityCooldown_scale_function
        - **m_eSpecificStatScaleType**: ETechCooldown
  - **AbilityDuration**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: duration
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_single_stat
        - **_my_subclass_name**: AbilityDuration_scale_function
        - **m_eSpecificStatScaleType**: ETechDuration
  - **AbilityCastRange**:
    - **m_strValue**: 0
    - **m_eDisplayUnits**: EDisplayUnit_Meters
    - **m_strCSSClass**: range
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_single_stat
        - **_my_subclass_name**: AbilityCastRange_scale_function
        - **m_eSpecificStatScaleType**: ETechRange
  - **AbilityUnitTargetLimit**:
    - **m_strValue**: 1
    - **m_bCanSetTokenOverride**: True
  - **AbilityCastDelay**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: cast
    - **m_bCanSetTokenOverride**: True
  - **AbilityChannelTime**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: cast
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_multi_stats
        - **_my_subclass_name**: scale_duration
        - **m_vecScalingStats**:
          - EChannelDuration
          - ETechDuration
  - **AbilityPostCastDuration**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
  - **AbilityCharges**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: cast
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_single_stat
        - **_my_subclass_name**: AbilityCharges_scale_function
        - **m_eSpecificStatScaleType**: EMaxChargesIncrease
  - **AbilityCooldownBetweenCharge**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: charge_cooldown
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_single_stat
        - **_my_subclass_name**: AbilityCooldownBetweenCharge_scale_function
        - **m_eSpecificStatScaleType**: ETechCooldownBetweenChargeUses
  - **ChannelMoveSpeed**:
    - **m_strValue**: 50
    - **m_eDisplayUnits**: EDisplayUnit_MetersPerSecond
    - **m_strCSSClass**: move_speed
    - **m_bCanSetTokenOverride**: True
  - **AbilityResourceCost**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_bCanSetTokenOverride**: True
    - **m_strCSSClass**: cast
  - **TechPower**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_bCanSetTokenOverride**: True
    - **m_eProvidedPropertyType**: MODIFIER_VALUE_TECH_POWER
  - **WeaponPower**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_bCanSetTokenOverride**: True
    - **m_eProvidedPropertyType**: MODIFIER_VALUE_WEAPON_POWER
- **m_bitsPostCastEnabledStateMask**: MODIFIER_STATE_BUSY_WITH_ACTION
- **_editor**:
  - **folder_name**: Base
- **m_WeaponInfo**:
  - **m_BulletSpeedCurve**:
    - **m_spline**:
      | x | y | m_flSlopeIncoming | m_flSlopeOutgoing |
      | --- | --- | --- | --- |
      | 0.0 | 10000.0 | 0.0 | 0.0 |
      | 100.0 | 10000.0 | 0.0 | 0.0 |
    - **m_tangents**:
      | m_nIncomingTangent | m_nOutgoingTangent |
      | --- | --- |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
    - **m_vDomainMins**:
      - 0.0
      - 0.0
    - **m_vDomainMaxs**:
      - 100.0
      - 10000.0
- **_multibase**:
  - inherent_base
- **m_eAbilityType**: EAbilityType_Innate
- **m_bStartTrained**: True
- **m_iMaxLevel**: 1
- **m_iUpdateTime**: 1663028546
- **m_bitsInterruptingStates**: MODIFIER_STATE_STUNNED | MODIFIER_STATE_IS_ASLEEP
- **m_eAbilityTargetingLocation**: CITADEL_ABILITY_TARGETING_LOCATION_SELF
- **m_eAbilityActivation**: CITADEL_ABILITY_ACTIVATION_PASSIVE
- **m_nAbilityBehaviors**: CITADEL_ABILITY_BEHAVIOR_HIDDEN | CITADEL_ABILITY_BEHAVIOR_DONT_INTERRUPT_SPRINT | CITADEL_ABILITY_BEHAVIOR_NOT_SILENCABLE | CITADEL_ABILITY_BEHAVIOR_NO_TARGET | CITADEL_ABILITY_BEHAVIOR_NON_COMBAT | CITADEL_ABILITY_BEHAVIOR_CASTABLE_WHILE_HIDDEN
- **m_SprintParticle**: resource_name:"particles/generic/sprint.vpcf"
- **m_strSprintSound**: soundevent:"Player.Sprint"

### ESlot_Ability_Innate_3

- **_class**: citadel_ability_melee_parry
- **m_mapAbilityProperties**:
  - **AbilityCooldown**:
    - **m_strValue**: 5
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: cooldown
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_single_stat
        - **_my_subclass_name**: AbilityCooldown_scale_function
        - **m_eSpecificStatScaleType**: ETechCooldown
        - **m_bFunctionDisabled**: True
  - **AbilityDuration**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: duration
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_single_stat
        - **_my_subclass_name**: AbilityDuration_scale_function
        - **m_eSpecificStatScaleType**: ETechDuration
  - **AbilityCastRange**:
    - **m_strValue**: 0
    - **m_eDisplayUnits**: EDisplayUnit_Meters
    - **m_strCSSClass**: range
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_single_stat
        - **_my_subclass_name**: AbilityCastRange_scale_function
        - **m_eSpecificStatScaleType**: ETechRange
  - **AbilityUnitTargetLimit**:
    - **m_strValue**: 1
    - **m_bCanSetTokenOverride**: True
  - **AbilityCastDelay**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: cast
    - **m_bCanSetTokenOverride**: True
  - **AbilityChannelTime**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: cast
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_multi_stats
        - **_my_subclass_name**: scale_duration
        - **m_vecScalingStats**:
          - EChannelDuration
          - ETechDuration
  - **AbilityPostCastDuration**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
  - **AbilityCharges**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: cast
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_single_stat
        - **_my_subclass_name**: AbilityCharges_scale_function
        - **m_eSpecificStatScaleType**: EMaxChargesIncrease
  - **AbilityCooldownBetweenCharge**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: charge_cooldown
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_single_stat
        - **_my_subclass_name**: AbilityCooldownBetweenCharge_scale_function
        - **m_eSpecificStatScaleType**: ETechCooldownBetweenChargeUses
  - **ChannelMoveSpeed**:
    - **m_strValue**: 50
    - **m_eDisplayUnits**: EDisplayUnit_MetersPerSecond
    - **m_strCSSClass**: move_speed
    - **m_bCanSetTokenOverride**: True
  - **AbilityResourceCost**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_bCanSetTokenOverride**: True
    - **m_strCSSClass**: cast
  - **TechPower**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_bCanSetTokenOverride**: True
    - **m_eProvidedPropertyType**: MODIFIER_VALUE_TECH_POWER
  - **WeaponPower**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_bCanSetTokenOverride**: True
    - **m_eProvidedPropertyType**: MODIFIER_VALUE_WEAPON_POWER
  - **ParriedStunTime**:
    - **m_strValue**: 2.75
  - **MeleeDamageTakenScale**:
    - **m_strValue**: 35
  - **ParryMoveSpeed**:
    - **m_strValue**: 50
- **m_bitsPostCastEnabledStateMask**: MODIFIER_STATE_BUSY_WITH_ACTION
- **_editor**:
  - **folder_name**: Base
- **m_WeaponInfo**:
  - **m_BulletSpeedCurve**:
    - **m_spline**:
      | x | y | m_flSlopeIncoming | m_flSlopeOutgoing |
      | --- | --- | --- | --- |
      | 0.0 | 10000.0 | 0.0 | 0.0 |
      | 100.0 | 10000.0 | 0.0 | 0.0 |
    - **m_tangents**:
      | m_nIncomingTangent | m_nOutgoingTangent |
      | --- | --- |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
    - **m_vDomainMins**:
      - 0.0
      - 0.0
    - **m_vDomainMaxs**:
      - 100.0
      - 10000.0
- **_multibase**:
  - inherent_base
- **m_eAbilityType**: EAbilityType_Innate
- **m_bStartTrained**: True
- **m_iMaxLevel**: 1
- **m_nAbilityBehaviors**: CITADEL_ABILITY_BEHAVIOR_NOT_SILENCABLE | CITADEL_ABILITY_BEHAVIOR_NO_TARGET
- **m_eAbilityActivation**: CITADEL_ABILITY_ACTIVATION_INSTANT_CAST
- **m_SuccessfulParryParticle**: resource_name:"particles/abilities/melee/melee_parry_success.vpcf"
- **m_strCastSound**: soundevent:"Player.Melee.Parry.Shared"
- **m_strSuccessfulParrySound**: soundevent:"Player.Melee.Parry.Success.Shared"
- **m_HUDPanel**:
  - **m_vecHUDElements**:
    | m_eType | m_Layout | m_strContext |
    | --- | --- | --- |
    | CITADEL_ABILITY_HUD_ELEMENT_TYPE_PROGRESS | file://{resources}/layout/ability_hud_elements/element_empty.vxml | cooldown |
- **m_ParryActiveModifier**:
  - **subclass**:
    - **_class**: modifier_citadel_parry
    - **_my_subclass_name**: modifier_citadel_parry
    - **m_strParticleStatusEffect**: resource_name:""
    - **m_strParticleEffect**: resource_name:"particles/abilities/melee/melee_parry.vpcf"
- **m_ParryVictimModifier**:
  - **subclass**:
    - **_my_subclass_name**: modifier_citadel_parried_stun
    - **_class**: modifier_citadel_parried_stun
    - **m_strParticleEffect**: resource_name:"particles/abilities/melee/melee_parry_debuff.vpcf"
    - **m_OnCreateResponse**:
      - **m_nConcept**: TLK_CITADEL_INTERACT_WITH_ABILITY
      - **m_nSpeakerType**: MODIFIER_RR_SPEAKER_CASTER
- **m_flBossVictimNoMeleeTime**: 7.0
- **m_flBossVictimCalmTime**: 2.25
- **m_ParryBossVictimNoMeleeModifier**:
  - **subclass**:
    - **_my_subclass_name**: boss_victim_no_melee
    - **_class**: modifier_base
    - **m_bIsHidden**: True
    - **m_nEnabledStateMask**: MODIFIER_STATE_MELEE_DISABLED
- **m_ParryBossVictimCalmModifier**:
  - **subclass**:
    - **_my_subclass_name**: boss_victim_calm
    - **_class**: modifier_base
    - **m_bIsHidden**: True
    - **m_nEnabledStateMask**: MODIFIER_STATE_AI_FORCE_CALM
- **m_flActiveTime**: 0.7
- **m_flWhiffDuration**: 1.0
- **m_flMovementRestrictionTime**: 0
- **m_ParryCooldownModifier**:
  - **subclass**:
    - **_my_subclass_name**: parry_cooldown_display
    - **_class**: modifier_base
    - **m_eDrawOverheadStatus**: OVERHEAD_DRAW_FOR_EVERYONE
    - **m_bIsHidden**: True
- **m_flParryEndVisualTime**: 0.6
- **m_ParryEndVisualModifier**:
  - **subclass**:
    - **_my_subclass_name**: parry_end_visuals
    - **_class**: modifier_base
    - **m_bIsHidden**: True
    - **m_strParticleEffect**: resource_name:"particles/abilities/melee/melee_parry_end.vpcf"
    - **m_strParticleStatusEffect**: resource_name:"particles/status_fx/status_fx_melee_parry_end.vpcf"
    - **m_nStatusEffectPriority**: 100
- **m_flSuccessActiveTime**: 0.3

### ESlot_Signature_1

- **_class**: thumper_ability_1
- **m_mapAbilityProperties**:
  - **AbilityCooldown**:
    - **m_strValue**: 16
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: cooldown
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_single_stat
        - **_my_subclass_name**: AbilityCooldown_scale_function
        - **m_eSpecificStatScaleType**: ETechCooldown
  - **AbilityDuration**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: duration
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_single_stat
        - **_my_subclass_name**: AbilityDuration_scale_function
        - **m_eSpecificStatScaleType**: ETechDuration
  - **AbilityCastRange**:
    - **m_strValue**: 40m
    - **m_eDisplayUnits**: EDisplayUnit_Meters
    - **m_strCSSClass**: distance
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_single_stat
        - **_my_subclass_name**: AbilityCastRange_scale_function
        - **m_eSpecificStatScaleType**: ETechRange
  - **AbilityUnitTargetLimit**:
    - **m_strValue**: 1
    - **m_bCanSetTokenOverride**: True
  - **AbilityCastDelay**:
    - **m_strValue**: 0.1
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: cast
    - **m_bCanSetTokenOverride**: True
  - **AbilityChannelTime**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: cast
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_multi_stats
        - **_my_subclass_name**: scale_duration
        - **m_vecScalingStats**:
          - EChannelDuration
          - ETechDuration
  - **AbilityPostCastDuration**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
  - **AbilityCharges**:
    - **m_strValue**: 1
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: cast
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_single_stat
        - **_my_subclass_name**: AbilityCharges_scale_function
        - **m_eSpecificStatScaleType**: EMaxChargesIncrease
  - **AbilityCooldownBetweenCharge**:
    - **m_strValue**: 4
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: charge_cooldown
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_single_stat
        - **_my_subclass_name**: AbilityCooldownBetweenCharge_scale_function
        - **m_eSpecificStatScaleType**: ETechCooldownBetweenChargeUses
  - **ChannelMoveSpeed**:
    - **m_strValue**: 50
    - **m_eDisplayUnits**: EDisplayUnit_MetersPerSecond
    - **m_strCSSClass**: move_speed
    - **m_bCanSetTokenOverride**: True
  - **AbilityResourceCost**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_bCanSetTokenOverride**: True
    - **m_strCSSClass**: cast
  - **TechPower**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_bCanSetTokenOverride**: True
    - **m_eProvidedPropertyType**: MODIFIER_VALUE_TECH_POWER
  - **WeaponPower**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_bCanSetTokenOverride**: True
    - **m_eProvidedPropertyType**: MODIFIER_VALUE_WEAPON_POWER
  - **BounceRange**:
    - **m_strValue**: 20m
    - **m_strCSSClass**: distance
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_single_stat
        - **_my_subclass_name**: BounceRange_scale_function
        - **m_eSpecificStatScaleType**: ETechRange
  - **Damage**:
    - **m_strValue**: 120
    - **m_strCSSClass**: tech_damage
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_tech_damage
        - **_my_subclass_name**: Damage_scale_function
        - **m_flStatScale**: 0.6552
  - **PlaneSpread**:
    - **m_strValue**: 30
  - **BounceRadians**:
    - **m_strValue**: 0.5
  - **PushSpeedMax**:
    - **m_strValue**: 1000
  - **PushSpeedMid**:
    - **m_strValue**: 600
  - **PushSpeedMin**:
    - **m_strValue**: 100
  - **MaxPlaneDistance**:
    - **m_strValue**: 1m
- **m_bitsPostCastEnabledStateMask**: MODIFIER_STATE_BUSY_WITH_ACTION
- **_editor**:
  - **folder_name**: Base
- **m_WeaponInfo**:
  - **m_BulletSpeedCurve**:
    - **m_spline**:
      | x | y | m_flSlopeIncoming | m_flSlopeOutgoing |
      | --- | --- | --- | --- |
      | 0.0 | 8000.0 | 0.0 | 0.0 |
      | 100.0 | 8000.0 | 0.0 | 0.0 |
    - **m_tangents**:
      | m_nIncomingTangent | m_nOutgoingTangent |
      | --- | --- |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
    - **m_vDomainMins**:
      - 0.0
      - 0.0
    - **m_vDomainMaxs**:
      - 100.0
      - 8000.0
  - **m_flBulletLifetime**: 5
  - **m_szBulletTravelTracerParticle**: resource_name:"particles/abilities/archer/archer_charged_shot_proj.vpcf"
  - **m_flBulletGravityScale**: 0.3
  - **m_iClipSize**: 1
  - **m_flBulletRadius**: 64
  - **m_flPenetrationPercent**: 100
  - **m_flRange**: 1000
  - **m_flDamageFalloffStartRange**: -1.0
  - **m_flDamageFalloffEndRange**: -1.0
  - **m_vecScatterOffsets**:
    - - 0.0
      - 0.0
    - - 1.0
      - 0.0
    - - -1.0
      - 0.0
  - **m_flPelletScatterFactor**: 2.0
  - **m_bHitOnceAcrossAllBullets**: True
  - **m_mapImpactEffects**:
    - **default**:
      - **m_strSound**: soundevent:"Orion.Charged.Shot.Proj.Impact"
  - **m_strBulletWhizSound**: soundevent:"Orion.Charged.Shot.Whizby"
  - **m_strLocalPlayerBulletImpactSound**: soundevent:"Orion.Charged.Shot.Proj.Impact"
  - **m_szMuzzleFlashEffectName**: resource_name:""
  - **m_strWeaponImpactEffect**: resource_name:""
- **m_strCancelAbilityKey**: +in_cancel_ability
- **m_HUDPanel**:
  - **m_vecButtonHints**:
    | m_strContext | m_eButton1 | m_eHintSide | m_strLocToken |
    | --- | --- | --- | --- |
    | throw | EButtonHint_Attack | EButtonSide_Bottom | #AbilityButtonHint_Throw |
    | deploy | EButtonHint_Attack | EButtonSide_Bottom | #AbilityButtonHint_Deploy |
    | cast_on_target | EButtonHint_Attack | EButtonSide_Bottom | #AbilityButtonHint_CastOnTarget |
    | alt_cast_hold_hint | EButtonHint_AbilityKey | EButtonSide_Bottom | #AbilityButtonHint_HoldToSelfCast |
    | alt_cast_double_tap_hint | EButtonHint_AbilityKey | EButtonSide_Bottom | #AbilityButtonHint_DoubleTapToSelfCast |
    | alt_cast_modifier_key_hint |  | EButtonSide_Bottom | #AbilityButtonHint_ModifierKeyToSelfCast |
    | alt_cast_select_then_alt_cast_key_hint |  | EButtonSide_Bottom | #AbilityButtonHint_SelectThenSelfCastButton |
    | deselect | EButtonHint_AbilityKey | EButtonSide_Bottom | #AbilityButtonHint_Deselect |
    | unit_target_activate | EButtonHint_AbilityKey | EButtonSide_Bottom | #AbilityButtonHint_Activate |
- **_multibase**:
  - signature_base
- **m_bStartTrained**: False
- **m_nAbilityPointsCost**: 0
- **m_nAbillityUnlocksCost**: 1
- **m_eAbilityType**: EAbilityType_Signature
- **m_iMaxLevel**: 1
- **m_bitsInterruptingStates**: MODIFIER_STATE_STUNNED
- **m_PreviewPathParticle**: resource_name:"particles/generic/generic_arc.vpcf"
- **m_strAbilityOffCooldownSound**: soundevent:""
- **m_strAbilityChargeReadySound**: soundevent:""
- **m_skillshotMissParticle**: resource_name:"particles/abilities/skillshot_default_miss_owner.vpcf"
- **m_eAbilityTargetingLocation**: CITADEL_ABILITY_TARGETING_LOCATION_SELF
- **m_eAbilityTargetingShape**: CITADEL_ABILITY_TARGETING_SHAPE_SPHERE
- **m_eAbilityActivation**: CITADEL_ABILITY_ACTIVATION_PRESS
- **m_nAbilityBehaviors**: CITADEL_ABILITY_BEHAVIOR_NO_TARGET | CITADEL_ABILITY_BEHAVIOR_DONT_TRIGGER_SPELL_BLOCK | CITADEL_ABILITY_BEHAVIOR_DISPLAYS_DAMAGE_IMPACT | CITADEL_ABILITY_BEHAVIOR_ALWAYS_PREVIEW_RADIUS
- **m_nAbilityTargetTypes**: CITADEL_UNIT_TARGET_ALL_ENEMY
- **m_strAbilityImage**: panorama:"file://{images}/hud/abilities/thumper/thumper_ability_1.psd"
- **m_vecAbilityUpgrades**:
  | m_vecPropertyUpgrades |
  | --- |
  | [{'m_strPropertyName': 'AbilityCharges', 'm_strBonus': '1'}] |
  | [{'m_strPropertyName': 'Damage', 'm_strBonus': '60'}] |
  | [{'m_strPropertyName': 'AbilityCooldownBetweenCharge', 'm_strBonus': '-3'}, {'m_strPropertyName': 'AbilityCooldown', 'm_strBonus': '-4'}] |

### ESlot_Signature_2

- **_class**: thumper_ability_2
- **m_mapAbilityProperties**:
  - **AbilityCooldown**:
    - **m_strValue**: 25
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: cooldown
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_single_stat
        - **_my_subclass_name**: AbilityCooldown_scale_function
        - **m_eSpecificStatScaleType**: ETechCooldown
  - **AbilityDuration**:
    - **m_strValue**: 6
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: duration
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_single_stat
        - **_my_subclass_name**: AbilityDuration_scale_function
        - **m_eSpecificStatScaleType**: ETechDuration
  - **AbilityCastRange**:
    - **m_strValue**: 0
    - **m_eDisplayUnits**: EDisplayUnit_Meters
    - **m_strCSSClass**: range
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_single_stat
        - **_my_subclass_name**: AbilityCastRange_scale_function
        - **m_eSpecificStatScaleType**: ETechRange
  - **AbilityUnitTargetLimit**:
    - **m_strValue**: 1
    - **m_bCanSetTokenOverride**: True
  - **AbilityCastDelay**:
    - **m_strValue**: 0.42
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: cast
    - **m_bCanSetTokenOverride**: True
  - **AbilityChannelTime**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: cast
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_multi_stats
        - **_my_subclass_name**: scale_duration
        - **m_vecScalingStats**:
          - EChannelDuration
          - ETechDuration
  - **AbilityPostCastDuration**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
  - **AbilityCharges**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: cast
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_single_stat
        - **_my_subclass_name**: AbilityCharges_scale_function
        - **m_eSpecificStatScaleType**: EMaxChargesIncrease
  - **AbilityCooldownBetweenCharge**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: charge_cooldown
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_single_stat
        - **_my_subclass_name**: AbilityCooldownBetweenCharge_scale_function
        - **m_eSpecificStatScaleType**: ETechCooldownBetweenChargeUses
  - **ChannelMoveSpeed**:
    - **m_strValue**: 50
    - **m_eDisplayUnits**: EDisplayUnit_MetersPerSecond
    - **m_strCSSClass**: move_speed
    - **m_bCanSetTokenOverride**: True
  - **AbilityResourceCost**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_bCanSetTokenOverride**: True
    - **m_strCSSClass**: cast
  - **TechPower**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_bCanSetTokenOverride**: True
    - **m_eProvidedPropertyType**: MODIFIER_VALUE_TECH_POWER
  - **WeaponPower**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_bCanSetTokenOverride**: True
    - **m_eProvidedPropertyType**: MODIFIER_VALUE_WEAPON_POWER
  - **TechCleaveExpireTime**:
    - **m_strValue**: 0.2
  - **Damage**:
    - **m_strValue**: 125
    - **m_strCSSClass**: tech_damage
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_tech_damage
        - **_my_subclass_name**: Damage_scale_function
        - **m_flStatScale**: 0.6552
  - **VerticalDifferenceTolerance**:
    - **m_strValue**: 2.5m
  - **ImpactInterval**:
    - **m_strValue**: 0.1
  - **StompRange**:
    - **m_strValue**: 25m
    - **m_strCSSClass**: distance
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_single_stat
        - **_my_subclass_name**: StompRange_scale_function
        - **m_eSpecificStatScaleType**: ETechRange
  - **BonusFireRate**:
    - **m_strValue**: 0
    - **m_eProvidedPropertyType**: MODIFIER_VALUE_FIRE_RATE
  - **WeaponPowerBuffDuration**:
    - **m_strValue**: 0
    - **m_strCSSClass**: duration
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_single_stat
        - **_my_subclass_name**: WeaponPowerBuffDuration_scale_function
        - **m_eSpecificStatScaleType**: ETechDuration
  - **BarbedWireSlow**:
    - **m_strValue**: 50
    - **m_strCSSClass**: slow
  - **BarbedWireDPS**:
    - **m_strValue**: 10
    - **m_strCSSClass**: tech_damage
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_tech_damage
        - **_my_subclass_name**: BarbedWireDPS_scale_function
        - **m_flStatScale**: 0.6552
  - **BarbedWireDamagePerMeter**:
    - **m_strValue**: 30
    - **m_strCSSClass**: tech_damage
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_tech_damage
        - **_my_subclass_name**: BarbedWireDamagePerMeter_scale_function
        - **m_flStatScale**: 0.6552
  - **BarbedWireRadius**:
    - **m_strValue**: 4m
    - **m_strCSSClass**: distance
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_single_stat
        - **_my_subclass_name**: BarbedWireRadius_scale_function
        - **m_eSpecificStatScaleType**: ETechRadius
  - **BarbedWireHeightOffGround**:
    - **m_strValue**: 1m
  - **BarbedWireTickRate**:
    - **m_strValue**: 0.5
- **m_bitsPostCastEnabledStateMask**: MODIFIER_STATE_BUSY_WITH_ACTION
- **_editor**:
  - **folder_name**: Base
- **m_WeaponInfo**:
  - **m_BulletSpeedCurve**:
    - **m_spline**:
      | x | y | m_flSlopeIncoming | m_flSlopeOutgoing |
      | --- | --- | --- | --- |
      | 0.0 | 10000.0 | 0.0 | 0.0 |
      | 100.0 | 10000.0 | 0.0 | 0.0 |
    - **m_tangents**:
      | m_nIncomingTangent | m_nOutgoingTangent |
      | --- | --- |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
    - **m_vDomainMins**:
      - 0.0
      - 0.0
    - **m_vDomainMaxs**:
      - 100.0
      - 10000.0
- **m_strCancelAbilityKey**: +in_cancel_ability
- **m_HUDPanel**:
  - **m_vecButtonHints**:
    | m_strContext | m_eButton1 | m_eHintSide | m_strLocToken |
    | --- | --- | --- | --- |
    | throw | EButtonHint_Attack | EButtonSide_Bottom | #AbilityButtonHint_Throw |
    | deploy | EButtonHint_Attack | EButtonSide_Bottom | #AbilityButtonHint_Deploy |
    | cast_on_target | EButtonHint_Attack | EButtonSide_Bottom | #AbilityButtonHint_CastOnTarget |
    | alt_cast_hold_hint | EButtonHint_AbilityKey | EButtonSide_Bottom | #AbilityButtonHint_HoldToSelfCast |
    | alt_cast_double_tap_hint | EButtonHint_AbilityKey | EButtonSide_Bottom | #AbilityButtonHint_DoubleTapToSelfCast |
    | alt_cast_modifier_key_hint |  | EButtonSide_Bottom | #AbilityButtonHint_ModifierKeyToSelfCast |
    | alt_cast_select_then_alt_cast_key_hint |  | EButtonSide_Bottom | #AbilityButtonHint_SelectThenSelfCastButton |
    | deselect | EButtonHint_AbilityKey | EButtonSide_Bottom | #AbilityButtonHint_Deselect |
    | unit_target_activate | EButtonHint_AbilityKey | EButtonSide_Bottom | #AbilityButtonHint_Activate |
- **_multibase**:
  - signature_base
- **m_bStartTrained**: False
- **m_nAbilityPointsCost**: 0
- **m_nAbillityUnlocksCost**: 1
- **m_eAbilityType**: EAbilityType_Signature
- **m_iMaxLevel**: 1
- **m_bitsInterruptingStates**: MODIFIER_STATE_STUNNED
- **m_PreviewPathParticle**: resource_name:"particles/generic/generic_arc.vpcf"
- **m_strAbilityOffCooldownSound**: soundevent:""
- **m_strAbilityChargeReadySound**: soundevent:""
- **m_skillshotMissParticle**: resource_name:"particles/abilities/skillshot_default_miss_owner.vpcf"
- **m_eAbilityTargetingLocation**: CITADEL_ABILITY_TARGETING_LOCATION_SELF
- **m_eAbilityActivation**: CITADEL_ABILITY_ACTIVATION_INSTANT_CAST
- **m_eAbilityTargetingShape**: CITADEL_ABILITY_TARGETING_SHAPE_LINE
- **m_nAbilityBehaviors**: CITADEL_ABILITY_BEHAVIOR_DISPLAYS_DAMAGE_IMPACT | CITADEL_ABILITY_BEHAVIOR_SHOW_CAST_RANGE_AS_SAT_SPHERE_WHILE_CASTING
- **m_nAbilityTargetTypes**: CITADEL_UNIT_TARGET_HERO_ENEMY | CITADEL_UNIT_TARGET_MINION_ENEMY | CITADEL_UNIT_TARGET_CREEP_ENEMY
- **m_nAbilityTargetFlags**: CITADEL_UNIT_TARGET_FLAG_PENETRATE_INVULNERABLE
- **m_strAbilityImage**: panorama:"file://{images}/hud/abilities/thumper/thumper_ability_2.psd"
- **m_strCastAnimGraphParam**: e_CastStomp
- **m_vecAbilityUpgrades**:
  | m_vecPropertyUpgrades |
  | --- |
  | [{'m_strPropertyName': 'AbilityDuration', 'm_strBonus': '2'}] |
  | [{'m_strPropertyName': 'BarbedWireRadius', 'm_strBonus': '3m'}] |
  | [{'m_strPropertyName': 'BarbedWireDamagePerMeter', 'm_strBonus': '30'}] |
- **m_BarbedWireAuraModifier**:
  - **subclass**:
    - **_class**: modifier_thumper_ability_2_aura
    - **_my_subclass_name**: modifier_thumper_ability_2_aura
    - **m_modifierProvidedByAura**:
      - **subclass**:
        - **_my_subclass_name**: modifier_thumper_ability_2
        - **_class**: modifier_thumper_ability_2
        - **m_strParticleStatusEffect**: resource_name:"particles/status_fx/status_fx_generic_slow_debuff.vpcf"
        - **m_nEnabledStateMask**: MODIFIER_STATE_SLOWED | MODIFIER_STATE_GLOW_THROUGH_WALLS_TO_ENEMY
        - **m_strParticleEffect**: resource_name:"particles/generic/generic_slow_debuff.vpcf"
        - **m_nStatusEffectPriority**: 100
    - **m_sStartSound**: soundevent:"Forge.FissureWall.TakeDamage"
    - **m_AoEParticle**: resource_name:"particles/abilities/engineer/engineer_wall_barbed_aoe.vpcf"
- **m_strCastDelaySound**: soundevent:"Dynamo.Stomp.PreCast"
- **m_StompParticle**: resource_name:"particles/abilities/sumo/sumo_stomp_impact.vpcf"
- **m_strCastSound**: soundevent:"Dynamo.Stomp.Cast"
- **m_strStompExplosionSound**: soundevent:"Dynamo.Stomp.Explode"

### ESlot_Signature_3

- **_class**: thumper_ability_3
- **m_mapAbilityProperties**:
  - **AbilityCooldown**:
    - **m_strValue**: 40
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: cooldown
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_single_stat
        - **_my_subclass_name**: AbilityCooldown_scale_function
        - **m_eSpecificStatScaleType**: ETechCooldown
  - **AbilityDuration**:
    - **m_strValue**: 8
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: duration
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_single_stat
        - **_my_subclass_name**: AbilityDuration_scale_function
        - **m_eSpecificStatScaleType**: ETechDuration
  - **AbilityCastRange**:
    - **m_strValue**: 30m
    - **m_eDisplayUnits**: EDisplayUnit_Meters
    - **m_strCSSClass**: range
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_single_stat
        - **_my_subclass_name**: AbilityCastRange_scale_function
        - **m_eSpecificStatScaleType**: ETechRange
  - **AbilityUnitTargetLimit**:
    - **m_strValue**: 1
    - **m_bCanSetTokenOverride**: True
  - **AbilityCastDelay**:
    - **m_strValue**: 0.2
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: cast
    - **m_bCanSetTokenOverride**: True
  - **AbilityChannelTime**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: cast
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_multi_stats
        - **_my_subclass_name**: scale_duration
        - **m_vecScalingStats**:
          - EChannelDuration
          - ETechDuration
  - **AbilityPostCastDuration**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
  - **AbilityCharges**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: cast
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_single_stat
        - **_my_subclass_name**: AbilityCharges_scale_function
        - **m_eSpecificStatScaleType**: EMaxChargesIncrease
  - **AbilityCooldownBetweenCharge**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: charge_cooldown
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_single_stat
        - **_my_subclass_name**: AbilityCooldownBetweenCharge_scale_function
        - **m_eSpecificStatScaleType**: ETechCooldownBetweenChargeUses
  - **ChannelMoveSpeed**:
    - **m_strValue**: 50
    - **m_eDisplayUnits**: EDisplayUnit_MetersPerSecond
    - **m_strCSSClass**: move_speed
    - **m_bCanSetTokenOverride**: True
  - **AbilityResourceCost**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_bCanSetTokenOverride**: True
    - **m_strCSSClass**: cast
  - **TechPower**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_bCanSetTokenOverride**: True
    - **m_eProvidedPropertyType**: MODIFIER_VALUE_TECH_POWER
  - **WeaponPower**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_bCanSetTokenOverride**: True
    - **m_eProvidedPropertyType**: MODIFIER_VALUE_WEAPON_POWER
  - **DPS**:
    - **m_strValue**: 8
    - **m_strCSSClass**: tech_damage
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_tech_damage
        - **_my_subclass_name**: DPS_scale_function
        - **m_flStatScale**: 0.6552
  - **TickInterval**:
    - **m_strValue**: 0.5
  - **VisibilityTime**:
    - **m_strValue**: 0.2
- **m_bitsPostCastEnabledStateMask**: MODIFIER_STATE_BUSY_WITH_ACTION
- **_editor**:
  - **folder_name**: Base
- **m_WeaponInfo**:
  - **m_BulletSpeedCurve**:
    - **m_spline**:
      | x | y | m_flSlopeIncoming | m_flSlopeOutgoing |
      | --- | --- | --- | --- |
      | 0.0 | 10000.0 | 0.0 | 0.0 |
      | 100.0 | 10000.0 | 0.0 | 0.0 |
    - **m_tangents**:
      | m_nIncomingTangent | m_nOutgoingTangent |
      | --- | --- |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
    - **m_vDomainMins**:
      - 0.0
      - 0.0
    - **m_vDomainMaxs**:
      - 100.0
      - 10000.0
- **m_strCancelAbilityKey**: +in_cancel_ability
- **m_HUDPanel**:
  - **m_vecButtonHints**:
    | m_strContext | m_eButton1 | m_eHintSide | m_strLocToken |
    | --- | --- | --- | --- |
    | throw | EButtonHint_Attack | EButtonSide_Bottom | #AbilityButtonHint_Throw |
    | deploy | EButtonHint_Attack | EButtonSide_Bottom | #AbilityButtonHint_Deploy |
    | cast_on_target | EButtonHint_Attack | EButtonSide_Bottom | #AbilityButtonHint_CastOnTarget |
    | alt_cast_hold_hint | EButtonHint_AbilityKey | EButtonSide_Bottom | #AbilityButtonHint_HoldToSelfCast |
    | alt_cast_double_tap_hint | EButtonHint_AbilityKey | EButtonSide_Bottom | #AbilityButtonHint_DoubleTapToSelfCast |
    | alt_cast_modifier_key_hint |  | EButtonSide_Bottom | #AbilityButtonHint_ModifierKeyToSelfCast |
    | alt_cast_select_then_alt_cast_key_hint |  | EButtonSide_Bottom | #AbilityButtonHint_SelectThenSelfCastButton |
    | deselect | EButtonHint_AbilityKey | EButtonSide_Bottom | #AbilityButtonHint_Deselect |
    | unit_target_activate | EButtonHint_AbilityKey | EButtonSide_Bottom | #AbilityButtonHint_Activate |
- **_multibase**:
  - signature_base
- **m_bStartTrained**: False
- **m_nAbilityPointsCost**: 0
- **m_nAbillityUnlocksCost**: 1
- **m_eAbilityType**: EAbilityType_Signature
- **m_iMaxLevel**: 1
- **m_bitsInterruptingStates**: MODIFIER_STATE_STUNNED
- **m_PreviewPathParticle**: resource_name:"particles/generic/generic_arc.vpcf"
- **m_strAbilityOffCooldownSound**: soundevent:""
- **m_strAbilityChargeReadySound**: soundevent:""
- **m_skillshotMissParticle**: resource_name:"particles/abilities/skillshot_default_miss_owner.vpcf"
- **m_eAbilityTargetingLocation**: CITADEL_ABILITY_TARGETING_LOCATION_UNIT
- **m_eAbilityActivation**: CITADEL_ABILITY_ACTIVATION_PRESS
- **m_eAbilityTargetingShape**: CITADEL_ABILITY_TARGETING_SHAPE_CONE
- **m_nAbilityBehaviors**: CITADEL_ABILITY_BEHAVIOR_DISPLAYS_DAMAGE_IMPACT | CITADEL_ABILITY_BEHAVIOR_ALWAYS_PREVIEW_RADIUS
- **m_flTargetingConeAngle**: 20
- **m_nAbilityTargetTypes**: CITADEL_UNIT_TARGET_HERO_ENEMY
- **m_strAbilityImage**: panorama:"file://{images}/hud/abilities/thumper/thumper_ability_3.psd"
- **m_DroneParticle**: resource_name:"particles/abilities/ballista/ballista_fusion_bomb_siren.vpcf"
- **m_vecAbilityUpgrades**:
  | m_vecPropertyUpgrades |
  | --- |
  | [{'m_strPropertyName': 'AbilityCooldown', 'm_strBonus': '-1'}] |
  | [{'m_strPropertyName': 'AbilityCooldown', 'm_strBonus': '-1'}] |
  | [{'m_strPropertyName': 'AbilityCooldown', 'm_strBonus': '-1'}] |
- **m_DroneModifier**:
  - **subclass**:
    - **_class**: modifier_thumper_drone
    - **_my_subclass_name**: modifier_thumper_drone
    - **m_DroneParticle**: resource_name:"particles/abilities/ballista/ballista_fusion_bomb_siren.vpcf"
    - **m_LoopSound**: soundevent:"Zealot.SpiritOrb.Lp"
- **m_projectileInfo**:
  - **m_HitSound**: soundevent:"Zealot.SpiritOrb.Impact"
- **m_strCastSound**: soundevent:"Zealot.SpiritOrb.Cast"

### ESlot_Signature_4

- **_class**: thumper_ability_4
- **m_mapAbilityProperties**:
  - **AbilityCooldown**:
    - **m_strValue**: 10
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: cooldown
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_single_stat
        - **_my_subclass_name**: AbilityCooldown_scale_function
        - **m_eSpecificStatScaleType**: ETechCooldown
  - **AbilityDuration**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: duration
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_single_stat
        - **_my_subclass_name**: AbilityDuration_scale_function
        - **m_eSpecificStatScaleType**: ETechDuration
  - **AbilityCastRange**:
    - **m_strValue**: 0
    - **m_eDisplayUnits**: EDisplayUnit_Meters
    - **m_strCSSClass**: range
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_single_stat
        - **_my_subclass_name**: AbilityCastRange_scale_function
        - **m_eSpecificStatScaleType**: ETechRange
  - **AbilityUnitTargetLimit**:
    - **m_strValue**: 1
    - **m_bCanSetTokenOverride**: True
  - **AbilityCastDelay**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: cast
    - **m_bCanSetTokenOverride**: True
  - **AbilityChannelTime**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: cast
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_multi_stats
        - **_my_subclass_name**: scale_duration
        - **m_vecScalingStats**:
          - EChannelDuration
          - ETechDuration
  - **AbilityPostCastDuration**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
  - **AbilityCharges**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: cast
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_single_stat
        - **_my_subclass_name**: AbilityCharges_scale_function
        - **m_eSpecificStatScaleType**: EMaxChargesIncrease
  - **AbilityCooldownBetweenCharge**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_strCSSClass**: charge_cooldown
    - **m_bCanSetTokenOverride**: True
    - **m_subclassScaleFunction**:
      - **subclass**:
        - **_class**: scale_function_single_stat
        - **_my_subclass_name**: AbilityCooldownBetweenCharge_scale_function
        - **m_eSpecificStatScaleType**: ETechCooldownBetweenChargeUses
  - **ChannelMoveSpeed**:
    - **m_strValue**: 50
    - **m_eDisplayUnits**: EDisplayUnit_MetersPerSecond
    - **m_strCSSClass**: move_speed
    - **m_bCanSetTokenOverride**: True
  - **AbilityResourceCost**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_bCanSetTokenOverride**: True
    - **m_strCSSClass**: cast
  - **TechPower**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_bCanSetTokenOverride**: True
    - **m_eProvidedPropertyType**: MODIFIER_VALUE_TECH_POWER
  - **WeaponPower**:
    - **m_strValue**: 0
    - **m_strDisableValue**: 0
    - **m_bCanSetTokenOverride**: True
    - **m_eProvidedPropertyType**: MODIFIER_VALUE_WEAPON_POWER
  - **Radius**:
    - **m_strValue**: 15m
  - **Duration**:
    - **m_strValue**: 4
  - **InitialForce**:
    - **m_strValue**: 300
  - **PushAccel**:
    - **m_strValue**: 1000
  - **PushNPCSpeed**:
    - **m_strValue**: 800
  - **DistanceAboveGround**:
    - **m_strValue**: 2m
  - **ClimbHeight**:
    - **m_strValue**: 1m
  - **DropDownRate**:
    - **m_strValue**: 2
  - **TornadoSpeed**:
    - **m_strValue**: 350
- **m_bitsPostCastEnabledStateMask**: MODIFIER_STATE_BUSY_WITH_ACTION
- **_editor**:
  - **folder_name**: Base
- **m_WeaponInfo**:
  - **m_BulletSpeedCurve**:
    - **m_spline**:
      | x | y | m_flSlopeIncoming | m_flSlopeOutgoing |
      | --- | --- | --- | --- |
      | 0.0 | 10000.0 | 0.0 | 0.0 |
      | 100.0 | 10000.0 | 0.0 | 0.0 |
    - **m_tangents**:
      | m_nIncomingTangent | m_nOutgoingTangent |
      | --- | --- |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
      | CURVE_TANGENT_SPLINE | CURVE_TANGENT_SPLINE |
    - **m_vDomainMins**:
      - 0.0
      - 0.0
    - **m_vDomainMaxs**:
      - 100.0
      - 10000.0
- **m_strCancelAbilityKey**: +in_cancel_ability
- **m_HUDPanel**:
  - **m_vecButtonHints**:
    | m_strContext | m_eButton1 | m_eHintSide | m_strLocToken |
    | --- | --- | --- | --- |
    | throw | EButtonHint_Attack | EButtonSide_Bottom | #AbilityButtonHint_Throw |
    | deploy | EButtonHint_Attack | EButtonSide_Bottom | #AbilityButtonHint_Deploy |
    | cast_on_target | EButtonHint_Attack | EButtonSide_Bottom | #AbilityButtonHint_CastOnTarget |
    | alt_cast_hold_hint | EButtonHint_AbilityKey | EButtonSide_Bottom | #AbilityButtonHint_HoldToSelfCast |
    | alt_cast_double_tap_hint | EButtonHint_AbilityKey | EButtonSide_Bottom | #AbilityButtonHint_DoubleTapToSelfCast |
    | alt_cast_modifier_key_hint |  | EButtonSide_Bottom | #AbilityButtonHint_ModifierKeyToSelfCast |
    | alt_cast_select_then_alt_cast_key_hint |  | EButtonSide_Bottom | #AbilityButtonHint_SelectThenSelfCastButton |
    | deselect | EButtonHint_AbilityKey | EButtonSide_Bottom | #AbilityButtonHint_Deselect |
    | unit_target_activate | EButtonHint_AbilityKey | EButtonSide_Bottom | #AbilityButtonHint_Activate |
- **_multibase**:
  - ultimate_base
- **m_bStartTrained**: False
- **m_nAbilityPointsCost**: 0
- **m_nAbillityUnlocksCost**: 1
- **m_eAbilityType**: EAbilityType_Ultimate
- **m_iMaxLevel**: 1
- **m_bitsInterruptingStates**: MODIFIER_STATE_STUNNED
- **m_PreviewPathParticle**: resource_name:"particles/generic/generic_arc.vpcf"
- **m_strAbilityOffCooldownSound**: soundevent:""
- **m_strAbilityChargeReadySound**: soundevent:""
- **m_skillshotMissParticle**: resource_name:"particles/abilities/skillshot_default_miss_owner.vpcf"
- **m_eAbilityTargetingLocation**: CITADEL_ABILITY_TARGETING_LOCATION_NONE
- **m_eAbilityTargetingShape**: CITADEL_ABILITY_TARGETING_SHAPE_LINE
- **m_eAbilityActivation**: CITADEL_ABILITY_ACTIVATION_INSTANT_CAST
- **m_nAbilityBehaviors**: CITADEL_ABILITY_BEHAVIOR_DISPLAYS_DAMAGE_IMPACT
- **m_nAbilityTargetTypes**: CITADEL_UNIT_TARGET_ALL
- **m_projectileInfo**:
  - **m_flUpSpeed**: 0
  - **m_flSpeed**: 1600
  - **m_bHideImpactParticle**: 1
  - **m_bHideWarningParticle**: 1
  - **m_flVerticalAimBias**: 5.0
- **m_strAbilityImage**: panorama:"file://{images}/hud/abilities/thumper/thumper_ability_4.psd"
- **m_vecAbilityUpgrades**:
  | m_vecPropertyUpgrades |
  | --- |
  | [{'m_strPropertyName': 'AbilityCooldown', 'm_strBonus': '-1'}] |
  | [{'m_strPropertyName': 'AbilityCooldown', 'm_strBonus': '-1'}] |
  | [{'m_strPropertyName': 'AbilityCooldown', 'm_strBonus': '-1'}] |
- **m_PullAOEModifier**:
  - **subclass**:
    - **_class**: modifier_thumper_pull_aoe
    - **_my_subclass_name**: modifier_thumper_pull_aoe
    - **m_iAuraSearchType**: CITADEL_UNIT_TARGET_HERO_ENEMY | CITADEL_UNIT_TARGET_TROOPER_ENEMY | CITADEL_UNIT_TARGET_MINION_ENEMY
    - **m_modifierProvidedByAura**:
      - **subclass**:
        - **_class**: modifier_thumper_enemy_pulled
        - **_my_subclass_name**: modifier_thumper_enemy_pulled
        - **m_sLocalizationName**: modifier_thumper_enemy_pulled
        - **m_strParticleEffect**: resource_name:"particles/abilities/tokamak/tokamak_breach_buff.vpcf"
    - **m_sLocalizationName**: modifier_thumper_pull_aoe
    - **m_strParticleEffect**: resource_name:""
    - **m_sAmbientLoopingSound**: soundevent:"Kali.A1.WhirlingBlade.Duration.Lp"
    - **m_strParticleStatusEffect**: resource_name:"particles/abilities/kali/kali_tornado_blade.vpcf"
    - **m_sEndSound**: soundevent:"Kali.A1.WhirlingBlade.End"

## Other Information

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
- **m_flCollisionRadius**: 20
- **m_flCollisionHeight**: 80
- **m_flStepHeight**: 32
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
    - **m_unRequiredGold**: 3500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **9**:
    - **m_unRequiredGold**: 4500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **10**:
    - **m_unRequiredGold**: 5200
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **11**:
    - **m_unRequiredGold**: 6000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **12**:
    - **m_unRequiredGold**: 7500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **13**:
    - **m_unRequiredGold**: 8000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **14**:
    - **m_unRequiredGold**: 9000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **15**:
    - **m_unRequiredGold**: 9700
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **16**:
    - **m_unRequiredGold**: 10500
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **17**:
    - **m_unRequiredGold**: 12000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **18**:
    - **m_unRequiredGold**: 13000
    - **m_bUseStandardUpgrade**: True
  - **19**:
    - **m_unRequiredGold**: 14000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
    - **m_bUseStandardUpgrade**: True
  - **20**:
    - **m_unRequiredGold**: 15000
    - **m_bUseStandardUpgrade**: True
  - **21**:
    - **m_unRequiredGold**: 16000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **22**:
    - **m_unRequiredGold**: 18000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **23**:
    - **m_unRequiredGold**: 20000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **24**:
    - **m_unRequiredGold**: 22000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **25**:
    - **m_unRequiredGold**: 24000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **26**:
    - **m_unRequiredGold**: 27000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **27**:
    - **m_unRequiredGold**: 30000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **28**:
    - **m_unRequiredGold**: 33000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **29**:
    - **m_unRequiredGold**: 36000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **30**:
    - **m_unRequiredGold**: 39000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **31**:
    - **m_unRequiredGold**: 42000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **32**:
    - **m_unRequiredGold**: 45000
    - **m_mapBonusCurrencies**:
      - **EAbilityPoints**: 1
  - **33**:
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
      - EHealingOutput
      - EDebuffResist
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
- **m_strIconHeroCard**: panorama:"file://{images}/heroes/thumper_sm.psd"
- **m_strUIShopAnimGraph**: resource_name:"models/heroes_staging/thumper/ui_shop_thumper.vanmgrph"
- **m_strUIShoppingMap**: maps/ui/hero_shop/thumper_shop.vmap
