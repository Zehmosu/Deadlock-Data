# NPC: npc_boss_tier3

## General Stats

- **m_nMaxHealth**: 10000
- **m_flModelScale**: 1.0
- **m_flHealthBarOffset**: 0.0
- **m_flPhysicsImpulseMultiplier**: 0
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
- **m_flMovingToFinalPositionSpeed**: 20.0
- **m_flSightRangePlayers**: 3000.0
- **m_flSightRangeNPCs**: 3000.0

## Weapon Info


## Other Information

- **_class**: npc_boss_tier3
- **m_sModelName**: resource_name:"models/npc/titan_v2/titan.vmdl"
- **m_hFootstepSounds**: citadel
- **m_mapBoundAbilities**:
  - **ESlot_Weapon_Primary**: citadel_weapon_bosstier3_set
  - **ESlot_Signature_1**: citadel_ability_tier3boss_laser_beam
  - **ESlot_Signature_2**: citadel_ability_tier3boss_damage_pulse
- **m_sDefaultMaterialGroupName**: Friendly
- **m_sEnemyMaterialGroupName**: Enemy
- **m_LaserBeamModifier**:
  - **subclass**:
    - **_my_subclass_name**: modifier_tier3boss_electric_beam
    - **_class**: modifier_tier3boss_electric_beam
- **m_LaserChargingParticle**: resource_name:"particles/npc/tier3boss/tier3_boss_beam_charge.vpcf"
- **m_DeathLargeExplosionParticle**: resource_name:"particles/npc/tier3boss/tier3_boss_death_finale.vpcf"
- **m_WeakpointBrokenExplosionParticle**: resource_name:"particles/abilities/heavy_barrage_projectile_impact_explode.vpcf"
- **m_DeathSmallExplosionParticle**: resource_name:"particles/abilities/heavy_barrage_projectile_impact_explode.vpcf"
- **m_LaserBeamEffect**: resource_name:"particles/npc/tier3boss/tier3_boss_beam.vpcf"
- **m_LaserDamageEffect**: resource_name:"particles/modifiers/beam_damage.vpcf"
- **m_LaserPreviewEffect**: resource_name:"particles/npc/tier3boss/tier3_boss_beam_preview.vpcf"
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
