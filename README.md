# RolePlayImmersion
Exiled API plugin designed to improve immersion on SCP SL RP servers

# Features
- Prohibit all SCPs from detonating the warhead.
- Prohibit all SCPs, except SCP-049, from interacting with the warhead panel or disabling generators.
- Infinite tokens for MTF/CI spawning.
- Prohibition against leaving by lift from SCP-096.
- Hide the player's nickname when speaking on the radio.

# Default config
```
RolePlayImmersion:
  is_enabled: true
  debug: false
  is_infinity_mtf_and_ci_tokens_enabled: true
  # Hide players nicknames when using the radio?
  is_unknown_transmitting_enabled: true
  # A Text replacing player's nickname on the radio
  radio_custom_name: '???'
  # How many times is it possible to escape by elevator from SCP-096?
  escaping_by_elevator_max_times: 2
  # 096 blocking calling elevator message
  hint_message: 'SCP-096 will catch up with you, it won''t work'
```
