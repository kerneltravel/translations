cmake_minimum_required(VERSION 3.0.2 FATAL_ERROR)

project(lxqt-panel)

option(WITH_LXQT_PANEL_CLOCK "Build lxqt-panel plugin-clock translations" ON)
option(WITH_LXQT_PANEL_COLORPICKER "Build lxqt-panel plugin-colorpicker translations" ON)
option(WITH_LXQT_PANEL_CPULOAD "Build lxqt-panel plugin-cpuload translations" ON)
option(WITH_LXQT_PANEL_DESKTOPSWITCH "Build lxqt-panel plugin-desktopswitch translations" ON)
option(WITH_LXQT_PANEL_DIRECTORYMENU "Build lxqt-panel plugin-directorymenu translations" ON)
option(WITH_LXQT_PANEL_DOM "Build lxqt-panel plugin-dom translations" ON)
option(WITH_LXQT_PANEL_KBINDICATOR "Build lxqt-panel plugin-kbindicator translations" ON)
option(WITH_LXQT_PANEL_MAINMENU "Build lxqt-panel plugin-mainmenu translations" ON)
option(WITH_LXQT_PANEL_MOUNT "Build lxqt-panel plugin-mount translations" ON)
option(WITH_LXQT_PANEL_NETWORKMONITOR "Build lxqt-panel plugin-networkmonitor translations" ON)
option(WITH_LXQT_PANEL_QUICKLAUNCH "Build lxqt-panel plugin-quicklaunch translations" ON)
option(WITH_LXQT_PANEL_SCREENSAVER "Build lxqt-panel plugin-screensaver translations" ON)
option(WITH_LXQT_PANEL_SENSORS "Build lxqt-panel plugin-sensors translations" ON)
option(WITH_LXQT_PANEL_SHOWDESKTOP "Build lxqt-panel plugin-showdesktop translations" ON)
option(WITH_LXQT_PANEL_SPACER "Build lxqt-panel plugin-spacer translations" ON)
option(WITH_LXQT_PANEL_STATUSNOTIFIER "Build lxqt-panel plugin-statusnotifier translations" ON)
option(WITH_LXQT_PANEL_SYSSTAT "Build lxqt-panel plugin-sysstat translations" ON)
option(WITH_LXQT_PANEL_TASKBAR "Build lxqt-panel plugin-taskbar translations" ON)
option(WITH_LXQT_PANEL_TRAY "Build lxqt-panel plugin-tray translations" ON)
option(WITH_LXQT_PANEL_VOLUME "Build lxqt-panel plugin-volume translations" ON)
option(WITH_LXQT_PANEL_WORLDCLOCK "Build lxqt-panel plugin-worldclock translations" ON)


#panel
build_component("panel" "")

#plugins
build_sub_component(WITH_LXQT_PANEL_CLOCK plugin-clock clock)
build_sub_component(WITH_LXQT_PANEL_COLORPICKER plugin-colorpicker colorpicker)
build_sub_component(WITH_LXQT_PANEL_CPULOAD plugin-cpuload cpuload)
build_sub_component(WITH_LXQT_PANEL_DESKTOPSWITCH plugin-desktopswitch desktopswitch)
build_sub_component(WITH_LXQT_PANEL_DIRECTORYMENU plugin-directorymenu directorymenu)
build_sub_component(WITH_LXQT_PANEL_DOM plugin-dom dom)
build_sub_component(WITH_LXQT_PANEL_KBINDICATOR plugin-kbindicator kbindicator)
build_sub_component(WITH_LXQT_PANEL_MAINMENU plugin-mainmenu mainmenu)
build_sub_component(WITH_LXQT_PANEL_MOUNT plugin-mount mount)
build_sub_component(WITH_LXQT_PANEL_NETWORKMONITOR plugin-networkmonitor networkmonitor)
build_sub_component(WITH_LXQT_PANEL_QUICKLAUNCH plugin-quicklaunch quicklaunch)
build_sub_component(WITH_LXQT_PANEL_SCREENSAVER plugin-screensaver screensaver)
build_sub_component(WITH_LXQT_PANEL_SENSORS plugin-sensors sensors)
build_sub_component(WITH_LXQT_PANEL_SHOWDESKTOP plugin-showdesktop showdesktop)
build_sub_component(WITH_LXQT_PANEL_SPACER plugin-spacer spacer)
build_sub_component(WITH_LXQT_PANEL_STATUSNOTIFIER plugin-statusnotifier statusnotifier)
build_sub_component(WITH_LXQT_PANEL_SYSSTAT plugin-sysstat sysstat)
build_sub_component(WITH_LXQT_PANEL_TASKBAR plugin-taskbar taskbar)
build_sub_component(WITH_LXQT_PANEL_TRAY plugin-tray tray)
build_sub_component(WITH_LXQT_PANEL_VOLUME plugin-volume volume)
build_sub_component(WITH_LXQT_PANEL_WORLDCLOCK plugin-worldclock worldclock)
