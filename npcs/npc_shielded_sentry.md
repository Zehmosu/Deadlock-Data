# NPC: npc_shielded_sentry

## General Stats

- **m_flIdleTurnSpeed**: 15.0
- **m_flIdleTurnAngles**: 60.0
- **m_flTrooperTakeDamageMult**: 0.5
- **m_flNearDeathDuration**: 0.8
- **m_flZShootPostionOffset**: 25.0

## Weapon Info


## Other Information

- **_class**: npc_shielded_sentry
- **m_sModelName**: resource_name:"models/props_gameplay/turret/turret.vmdl"
- **m_LaserSightParticle**: resource_name:"particles/abilities/engineer/engineer_sentry_laser_sight.vpcf"
- **m_KillExplosionParticle**: resource_name:"particles/abilities/engineer/engineer_sentry_death.vpcf"
- **m_sSpawnSound**: soundevent:"Forge.Turret.Place"
- **m_sKillExplosionSound**: soundevent:"Forge.Turret.Explosion"
- **m_sTargetAcquiredLocalSound**: soundevent:"Forge.Turret.LockOn.LocalClient"
- **m_sTargetAcquiredSound**: soundevent:"Forge.Turret.LockOn"
- **m_DeployProgressModifier**:
  - **subclass**:
    - **_class**: modifier_base
    - **_my_subclass_name**: modifier_sentry_deploy
    - **m_sLocalizationName**: modifier_sentry_deploy
    - **m_bDrawOverheadStatus**: True
    - **m_bReverseHudProgressBar**: True
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
