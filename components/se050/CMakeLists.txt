#for Plug & Trust v03.00.02_20200826 https://github.com/NXP/plug-and-trust

set(COMPONENT_SRCDIRS   "plug-and-trust/hostlib/hostLib/se05x/src"
                        "plug-and-trust/hostlib/hostLib/se05x_03_xx_xx"
                        "plug-and-trust/sss/src"
                        "plug-and-trust/sss/src/se05x"
                        "."
                        )


set(COMPONENT_SRCS      "${COMPONENT_DIR}/plug-and-trust/hostlib/hostLib/inc/se05x_const.h"
                        "${COMPONENT_DIR}/plug-and-trust/hostlib/hostLib/inc/se05x_ecc_curves.h"
                        "${COMPONENT_DIR}/plug-and-trust/hostlib/hostLib/inc/se05x_ecc_curves_inc.h"
                        "${COMPONENT_DIR}/plug-and-trust/hostlib/hostLib/inc/se05x_ecc_curves_values.h"
                        "${COMPONENT_DIR}/plug-and-trust/hostlib/hostLib/inc/se05x_enums.h"
                        "${COMPONENT_DIR}/plug-and-trust/hostlib/hostLib/inc/se05x_ftr.h"
                        "${COMPONENT_DIR}/plug-and-trust/hostlib/hostLib/inc/se05x_tlv.h"
                        "${COMPONENT_DIR}/plug-and-trust/hostlib/hostLib/libCommon/nxScp/nxScp03_Com.c"
                        "${COMPONENT_DIR}/plug-and-trust/hostlib/hostLib/libCommon/smCom/smCom.c"
                        "${COMPONENT_DIR}/plug-and-trust/hostlib/hostLib/libCommon/smCom/smCom.h"
                        "${COMPONENT_DIR}/plug-and-trust/hostlib/hostLib/libCommon/smCom/smComT1oI2C.h"
                        "${COMPONENT_DIR}/plug-and-trust/hostlib/hostLib/libCommon/smCom/smComT1oI2C.c"
                        "${COMPONENT_DIR}/plug-and-trust/hostlib/hostLib/libCommon/smCom/T1oI2C/phEseStatus.h"
                        "${COMPONENT_DIR}/plug-and-trust/hostlib/hostLib/libCommon/smCom/T1oI2C/phEseTypes.h"
                        "${COMPONENT_DIR}/plug-and-trust/hostlib/hostLib/libCommon/smCom/T1oI2C/phNxpEse_Api.c"
                        "${COMPONENT_DIR}/plug-and-trust/hostlib/hostLib/libCommon/smCom/T1oI2C/phNxpEse_Api.h"
                        "${COMPONENT_DIR}/plug-and-trust/hostlib/hostLib/libCommon/smCom/T1oI2C/phNxpEse_Internal.h"
                        "${COMPONENT_DIR}/plug-and-trust/hostlib/hostLib/libCommon/smCom/T1oI2C/phNxpEsePal_i2c.h"
                        "${COMPONENT_DIR}/plug-and-trust/hostlib/hostLib/libCommon/smCom/T1oI2C/phNxpEsePal_i2c.c"
                        "${COMPONENT_DIR}/plug-and-trust/hostlib/hostLib/libCommon/smCom/T1oI2C/phNxpEseProto7816_3.h"
                        "${COMPONENT_DIR}/plug-and-trust/hostlib/hostLib/libCommon/smCom/T1oI2C/phNxpEseProto7816_3.c"
                        "${COMPONENT_DIR}/plug-and-trust/hostlib/hostLib/libCommon/infra/global_platf.h"
                        "${COMPONENT_DIR}/plug-and-trust/hostlib/hostLib/libCommon/infra/global_platf.c"
                        "${COMPONENT_DIR}/plug-and-trust/hostlib/hostLib/libCommon/infra/sm_apdu.c"
                        "${COMPONENT_DIR}/plug-and-trust/hostlib/hostLib/libCommon/infra/sm_apdu.h"
                        "${COMPONENT_DIR}/plug-and-trust/hostlib/hostLib/libCommon/infra/sm_connect.c"
                        "${COMPONENT_DIR}/plug-and-trust/hostlib/hostLib/libCommon/infra/sm_errors.c"
                        "${COMPONENT_DIR}/plug-and-trust/hostlib/hostLib/libCommon/infra/sm_errors.h"
                        "${COMPONENT_DIR}/plug-and-trust/hostlib/hostLib/libCommon/infra/sm_printf.c"
                        "${COMPONENT_DIR}/plug-and-trust/hostlib/hostLib/libCommon/infra/nxLog.c"
                        "${COMPONENT_DIR}/plug-and-trust/hostlib/hostLib/libCommon/infra/nxLog.h"
                        "${COMPONENT_DIR}/plug-and-trust/hostlib/hostLib/libCommon/infra/nxLog_App.h"
                        "${COMPONENT_DIR}/plug-and-trust/hostlib/hostLib/libCommon/infra/nxLog_DefaultConfig.h"
                        "${COMPONENT_DIR}/plug-and-trust/hostlib/hostLib/libCommon/infra/nxLog_hostLib.h"
                        "${COMPONENT_DIR}/plug-and-trust/hostlib/hostLib/libCommon/infra/nxLog_mbedtls.h"
                        "${COMPONENT_DIR}/plug-and-trust/hostlib/hostLib/libCommon/infra/nxLog_scp.h"
                        "${COMPONENT_DIR}/plug-and-trust/hostlib/hostLib/libCommon/infra/nxLog_smCom.h"
                        "${COMPONENT_DIR}/plug-and-trust/hostlib/hostLib/libCommon/infra/nxLog_sss.h"
                        "${COMPONENT_DIR}/plug-and-trust/hostlib/hostLib/inc/nxScp03_Apis.h"
                        "${COMPONENT_DIR}/plug-and-trust/hostlib/hostLib/inc/nxScp03_Const.h"
                        "${COMPONENT_DIR}/plug-and-trust/hostlib/hostLib/inc/nxScp03_Types.h"
                        "${COMPONENT_DIR}/plug-and-trust/sss/src/mbedtls/fsl_sss_mbedtls_apis.c"
                        "${COMPONENT_DIR}/plug-and-trust/sss/ex/src/ex_sss_boot.c"
                        "${COMPONENT_DIR}/plug-and-trust/sss/ex/src/ex_sss_boot_connectstring.c"
                        "${COMPONENT_DIR}/plug-and-trust/sss/ex/src/ex_sss_se05x.c"
                        "${COMPONENT_DIR}/plug-and-trust/sss/ex/src/ex_sss_se05x_auth.c"
                        "${COMPONENT_DIR}/plug-and-trust/sss/ex/src/ex_sss_scp03_auth.c"
                        "${COMPONENT_DIR}/plug-and-trust/sss/src/keystore/keystore_cmn.c"
                        "${COMPONENT_DIR}/plug-and-trust/sss/src/keystore/keystore_pc.c"
                        "${COMPONENT_DIR}/plug-and-trust/sss/port/default/fsl_sss_types.h"
                        )


set(COMPONENT_INCLUDEDIRS   
                        "."
                        "plug-and-trust/hostlib/hostLib/inc"
                        "plug-and-trust/hostlib/hostLib/platform/inc"
                        "plug-and-trust/hostlib/hostLib/libCommon/infra"
                        "plug-and-trust/hostlib/hostLib/libCommon/smCom"
                        "plug-and-trust/hostlib/hostLib/libCommon/smCom/T1oI2C"
                        "plug-and-trust/hostlib/hostLib/se05x_03_xx_xx"
                        "plug-and-trust/sss/inc"
                        "plug-and-trust/sss/ex/inc"
                        "plug-and-trust/sss/ex/src"
                        "plug-and-trust/sss/port/default"
                        "plug-and-trust/sss/plugin/mbedtls"
                        )

set(COMPONENT_REQUIRES  "mbedtls" "freertos" "driver")

set(COMPONENT_EXCLUDE_SRCS  
                        "plug-and-trust/sss/ex/inc/ex_sss_auth.h"
                        "plug-and-trust/sss/ex/inc/ex_scp03_puf.h"
                        "plug-and-trust/sss/inc/fsl_sss_ftr_default.h"
                        "plug-and-trust/fsl_sss_ftr.h"
                        )

set(COMPONENT_CFLAGS 
                        "ESP32"
                        "SE05X_C"
                        "T1oI2C"
                        "T1oI2C_UM11225"
                        "SSS_USE_FTR_FILE"
                        "USE_RTOS"
                        "SDK_OS_FREE_RTOS"
                        "FSL_RTOS_FREE_RTOS"
                        "SE05X_Auth=PlatfSCP03"
                        "SSS_HAVE_SE05X_AUTH_PLATFSCP03"
                        "SSS_MALLOC=malloc"
                        "SSS_FREE=free"
                        )

idf_component_register(
    SRC_DIRS "${COMPONENT_SRCDIRS}" 
    INCLUDE_DIRS "${COMPONENT_INCLUDEDIRS}" 
    REQUIRES "${COMPONENT_REQUIRES}" 
    EXCLUDE_SRCS "${COMPONENT_EXCLUDE_SRCS}"
    )

idf_component_get_property(mbedtls_dir mbedtls COMPONENT_DIR)

target_sources(${COMPONENT_LIB} PRIVATE ${COMPONENT_SRCS})
target_compile_definitions(${COMPONENT_LIB} PRIVATE ${COMPONENT_CFLAGS})
target_compile_options(${COMPONENT_LIB} PRIVATE -Wno-unused-variable -Wno-format-truncation -DMBEDTLS_CONFIG_FILE="mbedtls/esp_config.h" -I${mbedtls_dir}/mbedtls/port/include -I${mbedtls_dir}/mbedtls/mbedtls/include -I${mbedtls_dir}/mbedtls/mbedtls/include/mbedtls)

idf_component_get_property(freertos_dir freertos COMPONENT_DIR)
set_source_files_properties(plug-and-trust/hostlib/hostLib/libCommon/smCom/T1oI2C/phNxpEse_Api.c PROPERTIES COMPILE_FLAGS -I${freertos_dir}/include/freertos)