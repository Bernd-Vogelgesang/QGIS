FILE(GLOB PY_FILES *.py)
FILE(GLOB OTHER_FILES copyright.txt)

PLUGIN_INSTALL(processing ./algs/mmqgisx ${PY_FILES} ${OTHER_FILES})

