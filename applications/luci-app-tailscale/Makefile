# Copyright (C) 2024 asvow

include $(TOPDIR)/rules.mk

NAME:=luci-app-tailscale
PKG_NAME:=luci-app-tailscale

LUCI_TITLE:=LuCI for Tailscale
LUCI_DEPENDS:=+tailscale
LUCI_PKGARCH:=all

PKG_VERSION:=1.2.6
PKG_RELEASE:=0.1


 define Package/$(PKG_NAME)/conffiles
 /etc/config/tailscale
 /etc/init.d/tailscale
 endef

define Package/$(PKG_NAME)/postinst
endef

include $(TOPDIR)/feeds/luci/luci.mk

# call BuildPackage - OpenWrt buildroot signature
