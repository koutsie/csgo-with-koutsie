# csgo-with-koutsie
A ~~nice~~ autoexec for CS:GO by me.<br>
Are you ready for CS:2 to rip autoexec's out :D<br>
<a href="https://koutsie.github.io/csgo-with-koutsie/autoexec.cfg">download autoexec.cfg</a>

<details>
  <summary>preview the autoexect </summary>
<br>

```
echo ""
echo ""
echo ""
echo ""
echo ""
echo ""
echo "BBBBQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQ"
echo "QQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQ"
echo "QQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQ"
echo "QQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQ"
echo "QQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQ"
echo "QQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQ"
echo "QQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQ"
echo "QQQQQQQQQQ9    OQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQ"
echo "QQQQQQQQQQK    HQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQ"
echo "QQQQQQQQQQO    DQQQQQQQQQQQQQQQ##QQQQQQQQQQQQQQQQQ"
echo "QQQQQQQQQQO    DQQ]'```;HQQo^'    '>EQQQQQQQQQQQQQ"
echo "QQQQQQQQQQO    Dh'   'E@@K'   `:_`   ~#QQQQQQQQQQQ"
echo "QQQQQQQQQQO    ,   `z@@QQ`   ?@@@Q;   :@QQQQQQQQQQ"
echo "QQQQQQQQQQO        6@QQQe    Q@QQ@D    &@QQQQQQQQQ"
echo "QQQQQQQQQQO        `vQQQm    QQQQ@O    g@QQQQQQQQQ"
echo "QQQQQQQQQQd    KR-   :N@Q-   rQQQB:   ;@@QQQQQQQQQ"
echo "QQQQQQQQQQd    &@Q;   -e@W,   `,'    :Q@@QQQQQQQQQ"
echo "QQQQQQQQQQR''''gQ@@S''''c@@q|~`  `:iR@@@QQQQQQQQQQ"
echo "QQQQQQQQQQ@@@@@@QQQ@@@@@@@@@@@@@@@@@@@QQQQQQQQQQQQ"
echo "QQQQQQQQQQQQQQQQQQQQQQQQQQQQQQ@@@@QQQQQQQQQQQQQQQQ"
echo "QQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQ"
echo "QQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQ"
echo "QQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQ"
echo "QQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQ"
echo "QQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQ"
echo ""
echo ""
echo ""
echo ""
echo ""
echo ""

// radar settings
cl_hud_radar_scale 1.3
cl_radar_scale 0.35
cl_radar_icon_scale_min 1
cl_radar_always_centered 1
cl_radar_rotate 0
cl_teammate_colors_show "2"

// no interpolation + cmdrate + disablefreezecam
cl_interp "0"
cl_interp_ratio "1"
cl_cmdrate "128"
cl_updaterate "128"
cl_disablefreezecam 1
r_dynamic 0

// get rid of bobbing
cl_bobamt_lat "0"
cl_bobamt_vert "0"
cl_bobcycle "2"
cl_bob_lower_amt "0"

// get rid of viewmodel shift
cl_viewmodel_shift_left_amt "0"
cl_viewmodel_shift_right_amt "0"

// damage filter + maxping + ducking fix
con_enable "1"
developer "1"
con_filter_text "Damage given"
con_filter_text_out "Player:"
con_filter_enable "2"
ui_steam_overlay_notification_position "bottomright"
player_nevershow_communityservermessage "1"
mm_dedicated_search_maxping "75"
gameinstructor_enable "0"
option_duck_method "0"
option_speed_method "0"

// nosounds + no motd + showteammates [R.I.P forcepreload]
cl_downloadfilter "nosounds"
cl_disablehtmlmotd "1"
cl_autohelp "0"
cl_showhelp "0"
cl_disablefreezecam "1"
cl_teammate_colors_show "1"
cl_autowepswitch "0"
cl_use_opens_buy_menu "1"

// close buy menu on buy + cl righthand + showloadout + showfps + viewmodel settings + only deathnotices + matq2 + rate 128000
mat_queue_mode "2"
rate "128000"
closeonbuy "0"
hud_takesshots "1"
hud_scaling "0.5"
hud_showtargetid "1"
cl_draw_only_deathnotices "0"
cl_righthand "1"
cl_showloadout "1"
cl_showpos "1"
cl_showfps "0"
viewmodel_presetpos "3"
viewmodel_fov "62"
viewmodel_offset_x "2"
viewmodel_offset_y "2"
viewmodel_offset_z "-2"

// tracer settings
r_drawtracers_firstperson "0"
r_dynamic "1"

// crosshair settings
cl_crosshair_drawoutline "0"
cl_crosshair_dynamic_maxdist_splitratio "0.35"
cl_crosshair_dynamic_splitalpha_innermod "1"
cl_crosshair_dynamic_splitalpha_outermod "0.5"
cl_crosshair_dynamic_splitdist "7"
cl_crosshair_outlinethickness "1"
cl_crosshair_sniper_show_normal_inaccuracy "0"
cl_crosshair_sniper_width "1"
cl_crosshair_t "0"
cl_crosshairalpha "255"
cl_crosshaircolor "5"
cl_crosshaircolor_b "255"
cl_crosshaircolor_g "0"
cl_crosshaircolor_r "255"
cl_crosshairdot "0"
cl_crosshairgap "-6.5"
cl_crosshairgap_useweaponvalue "0"
cl_crosshairsize "1.5"
cl_crosshairstyle "4"
cl_crosshairthickness "1.5"
cl_crosshairusealpha "1"
cl_fixedcrosshairgap "1000"
r_drawtracers_firstperson "0"

// remove eye movement
r_eyegloss "0"
r_eyemove "0"
r_eyeshift_x "0"
r_eyeshift_y "0"
r_eyeshift_z "0"
r_eyesize "0"

// misc
fps_max 244
snd_mixahead "0.05"
cl_color 255 255 255
@panorama_debug_overlay_opacity "0.35"

host_writeconfig

echo "Ready to play CS:GO"
echo "v2.0.0 by koutsie (@k@layer8.space)
echo "check for updates at:"
echo "https://k0.tel/l/csgocfg"
```
</details>
