# SPDX-License-Identifier: GPL-2.0
dtb-y += exynos/exynos7-espresso.dtb
dtbo-y += exynos/board/erd/s5e3830-erd3830.dtbo
dtb-y += exynos/exynos5433-tm2.dtb
dtb-y += exynos/exynos5433-tm2e.dtb
dtb-y += exynos/s5e3830.dtb
dtbo-y += samsung/a14/a14_eur_open_w00_r04.dtbo
dtbo-y += samsung/a14/a14_eur_open_w00_r03.dtbo
dtbo-y += samsung/a14/a14_eur_open_w00_r02.dtbo
dtbo-y += samsung/a14/a14_eur_open_w00_r01.dtbo
dtbo-y += samsung/a14/a14_eur_open_w00_r00.dtbo

targets += dtbs
DTB_LIST  := $(dtb-y) $(dtbo-y)
always-y    := $(DTB_LIST)

dtbs: $(addprefix $(obj)/, $(DTB_LIST))

clean-files := *.dtb*
