PINEAPPLE_BASE_DTB += ../qcom/pineapple-v2.dtb
PINEAPPLE_APQ_BASE_DTB += ../qcom/pineapplep-sg-v2.dtb ../qcom/pineapplep-v2.dtb

SAMSUNG_PINEAPPLE_BOARDS += \
    e3q_eur_openx_w00_r00_v1.dtbo \
    e3q_eur_openx_w00_r00.dtbo \
    e3q_eur_openx_w00_r01.dtbo \
    e3q_eur_openx_w00_r02.dtbo \
    e3q_eur_openx_w00_r03.dtbo \
    e3q_eur_openx_w00_r04.dtbo \
    e3q_eur_openx_w00_r05.dtbo \
    e3q_eur_openx_w00_r07.dtbo \
    e3q_eur_openx_w00_r08.dtbo \
    e3q_eur_openx_w00_r09.dtbo

pineapple-overlays-dtb-y += $(SAMSUNG_PINEAPPLE_BOARDS) $(PINEAPPLE_BASE_DTB) $(PINEAPPLE_APQ_BASE_DTB)
dtb-y += $(SAMSUNG_PINEAPPLE_BOARDS) $(PINEAPPLE_BASE_DTB) $(PINEAPPLE_APQ_BASE_DTB)

always-y := $(dtb-y)
subdir-y := $(dts-dirs)
clean-files := *.dtb *.reverse.dts *.dtbo
