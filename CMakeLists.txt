# Asoul storage engine plugin
 
SET(ASOUL_PLUGIN_STATIC "asoul")
SET(ASOUL_PLUGIN_DYNAMIC "asoul")
 
SET(ASOUL_SOURCES ha_asoul.cc ha_asoul.h asoul_data.cc asoul_data.h)
MYSQL_ADD_PLUGIN(asoul ${ASOUL_SOURCES} STORAGE_ENGINE MODULE_ONLY)