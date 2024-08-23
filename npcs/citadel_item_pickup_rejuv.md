# NPC: citadel_item_pickup_rejuv

## General Stats


## Weapon Info


## Other Information

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
