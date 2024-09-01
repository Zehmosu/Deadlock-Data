# NPC: alt_npc_boss_tier2_weak

## General Stats

- **m_nMaxHealth**: 5175
- **m_flSightRangePlayers**: 1600.0
- **m_flSightRangeNPCs**: 1600.0
- **m_flPlayerInitialSightRange**: 1200.0
- **m_navHull**: 2
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
- **m_flModelScale**: 1.0
- **m_flInvulModifierRange**: 1278.74

## Weapon Info


## Other Information

- **_class**: npc_boss_tier2
- **m_sModelName**: resource_name:"models/npc/boss_tier_02_sun_walker/boss_tier_02_sun_walker.vmdl"
- **m_hFootstepSounds**: citadel
- **m_strLastHitSound**: soundevent:"LastHit.Default"
- **m_mapBoundAbilities**:
  - **ESlot_Weapon_Primary**: citadel_weapon_bosstier2_set
  - **ESlot_Signature_1**: citadel_ability_tier2boss_rocket_barrage
  - **ESlot_Signature_2**: citadel_ability_tier2boss_laser_beam
  - **ESlot_Signature_3**: citadel_ability_tier2boss_stomp
- **m_sDefaultMaterialGroupName**: friendly
- **m_sEnemyMaterialGroupName**: enemy
- **m_StompImpactEffect**: resource_name:"particles/npc/tier2boss/tier2boss_stomp.vpcf"
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
- **m_InvulModifier**:
  - **subclass**:
    - **_my_subclass_name**: modifier_boss_invuln
    - **_class**: modifier_boss_invuln
    - **m_flShieldRadius**: 300
    - **m_ShieldParticle**: resource_name:"particles/trooper/tier2_boss_invulerability_shield.vpcf"
- **_base**: npc_boss_tier2_weak
