# 
# Copyright (C) 2007 OpenWrt.org
#
# This is free software, licensed under the GNU General Public License v2.
# See /LICENSE for more information.
#

include $(TOPDIR)/rules.mk

PKG_NAME:=header
PKG_VERSION:=0.1
PKG_RELEASE:=1

include $(INCLUDE_DIR)/package.mk

define Package/header
  SECTION:=utils
  CATEGORY:=Utilities
  TITLE:=ESR1750 firmware header tool
  DEPENDS:=@TARGET_ar71xx_generic_ESR1750
  MAINTAINER:=Jon Suphammer <jon@suphammer.net>
endef

define Package/header/description
 ESR1750 firmware header tool.
endef

define Build/Configure
endef

define Build/Compile
endef

define Package/header/install
	$(INSTALL_DIR) $(1)/bin
	$(INSTALL_BIN) ./files/header $(1)/bin/
endef

$(eval $(call BuildPackage,header))
