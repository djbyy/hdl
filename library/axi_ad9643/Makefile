####################################################################################
####################################################################################
## Copyright 2011(c) Analog Devices, Inc.
## Auto-generated, do not modify!
####################################################################################
####################################################################################

M_DEPS := axi_ad9643_ip.tcl
M_DEPS += ../scripts/adi_env.tcl
M_DEPS += ../scripts/adi_ip.tcl
M_DEPS += ../common/ad_rst.v
M_DEPS += ../common/ad_mul.v
M_DEPS += ../common/ad_lvds_clk.v
M_DEPS += ../common/ad_lvds_in.v
M_DEPS += ../common/ad_pnmon.v
M_DEPS += ../common/ad_datafmt.v
M_DEPS += ../common/ad_dcfilter.v
M_DEPS += ../common/ad_iqcor.v
M_DEPS += ../common/up_axi.v
M_DEPS += ../common/up_xfer_cntrl.v
M_DEPS += ../common/up_xfer_status.v
M_DEPS += ../common/up_clock_mon.v
M_DEPS += ../common/up_delay_cntrl.v
M_DEPS += ../common/up_adc_common.v
M_DEPS += ../common/up_adc_channel.v
M_DEPS += axi_ad9643_pnmon.v
M_DEPS += axi_ad9643_channel.v
M_DEPS += axi_ad9643_if.v
M_DEPS += axi_ad9643_constr.xdc
M_DEPS += axi_ad9643.v

M_VIVADO := vivado -mode batch -source

M_FLIST := *.cache
M_FLIST += *.data
M_FLIST += *.xpr
M_FLIST += *.log
M_FLIST += component.xml
M_FLIST += *.jou
M_FLIST +=  xgui
M_FLIST += .Xil



.PHONY: all clean clean-all
all: axi_ad9643.xpr


clean:clean-all


clean-all:
	rm -rf $(M_FLIST)


axi_ad9643.xpr: $(M_DEPS)
	rm -rf $(M_FLIST)
	$(M_VIVADO) axi_ad9643_ip.tcl  >> axi_ad9643_ip.log 2>&1

####################################################################################
####################################################################################
