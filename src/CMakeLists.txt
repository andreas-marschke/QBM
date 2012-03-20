configure_file(
	"${PROJECT_SOURCE_DIR}/src/qbm_config.h.in"
	"${PROJECT_BINARY_DIR}/src/qbm_config.h"
)
set(QBM_SRC qbm.c)
add_executable(qbm ${QBM_SRC})
