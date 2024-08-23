# NPC: npc_super_neutral

## General Stats

- **m_flHealthBarOffset**: 600
- **m_flSightRangePlayers**: 1500.0
- **m_flSightRangeNPCs**: 1500.0
- **m_iHealthGainPerMinute**: 425
- **m_iStartingHealth**: 6000
- **m_flPhysicsImpulseMultiplier**: 0.0
- **m_flBeamWeaponWidth**: 24
- **m_flBeamTurnRate**: 360
- **m_flDyingDuration**: 1.4

## Weapon Info

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

## Other Information

- **_base**: weapon_base
- **_class**: npc_super_neutral
- **m_sModelName**: resource_name:"models/npc/midboss/midboss.vmdl"
- **m_mapBoundAbilities**:
  - **ESlot_Signature_1**: super_neutral_shield
  - **ESlot_Signature_2**: super_neutral_charge
- **m_hFootstepSounds**: citadel
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
