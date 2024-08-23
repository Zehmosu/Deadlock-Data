# NPC: neutral_gargoyle

## General Stats

- **m_flSightRangePlayers**: 2000.0
- **m_flMaxHealthBarDrawDistance**: 800
- **m_flShieldReactivateDelay**: 2.0
- **m_flGoldReward**: 220
- **m_flGoldRewardBonusPercentPerMinute**: 1.2
- **m_flModelScale**: 0.525
- **m_nMaxHealth**: 1760
- **m_flHealthBarOffset**: 84
- **m_bFaceEnemyWhileIdle**: True
- **m_flPhysicsImpulseMultiplier**: 0.0
- **m_flHullCapsuleHeight**: 200.0
- **m_flHullCapsuleRadius**: 100.0
- **m_bHasAOEAttack**: False
- **m_flAOERadius**: 600.0
- **m_flAOEDamage**: 100.0
- **m_flAOEAttackCooldown**: 8.0

## Weapon Info

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

## Other Information

- **_base**: neutral_trooper_strong
- **_class**: npc_trooper_neutral
- **m_ShieldParticle**: resource_name:""
- **m_strLastHitSound**: soundevent:"LastHit.Default"
- **m_sModelName**: resource_name:"models/npc/gargoyle/neutral_gargoyle.vmdl"
- **m_hFootstepSounds**: citadel
- **m_sDefaultMaterialGroupName**: 
- **m_DeathParticle**: resource_name:"particles/npc/neutral_trooper_death.vpcf"
- **m_vecIntrinsicModifiers**:
  | subclass |
  | --- |
  | {'_my_subclass_name': 'strong_neutral_bullet_armor', '_class': 'modifier_intrinsic_base', 'm_vecScriptValues': [{'m_eModifierValue': 'MODIFIER_VALUE_BULLET_DAMAGE_REDUCTION_PERCENT', 'm_value': 60.0}, {'m_eModifierValue': 'MODIFIER_VALUE_ABILITY_DAMAGE_REDUCTION_PERCENT', 'm_value': 35.0}], 'm_strParticleEffect': 'resource_name:"particles/npc/neutral_strong_ambient_flame.vpcf"'} |
- **m_eTrooperType**: NEUTRAL_TROOPER_STRONG
- **m_vecAttachments**:
- **m_sEnemyMaterialGroupName**: 
- **m_AOEParticle**: resource_name:"particles/abilities/sumo_stomp.vpcf"
- **m_AOESound**: soundevent:"Neutral.Gargoyle.StompImpact"
- **m_AOEInitiateSound**: soundevent:"Neutral.Gargoyle.StompInitiate"
