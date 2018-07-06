
## For Debian and Ubuntu
<input type="text" id="ubusnat" value="wget https://git.io/fbpaR -O serverSetupSNAT && chmod +x serverSetupSNAT && ./serverSetupSNAT" readonly="true" style="width:90%" /><button onclick="copyx(this,'ubusnat')">Copy</button>


### LBC Install (No SE Server Setup):

<input type="text" id="lbcins" value="wget https://git.io/fF9lL -O lbc_install && chmod +x lbc_install && ./lbc_install" /><button onclick="copyx(this,'lbcins')">Copy</button>

## CentOS
1. yum install wget -y

### SNAT
2.a) <input type="text" id="centsnat" value="wget https://git.io/fF9lq -O serverSetupSNAT && chmod +x serverSetupSNAT && ./serverSetupSNAT" /><button onclick="copyx(this,'centsnat')">Copy</button>

### LBC
2.b) <input type="text" id="centlbc" value="wget https://git.io/fF9BZ -O serverSetup+LBC && chmod +x serverSetup+LBC && ./serverSetup+LBC" /><button onclick="copyx(this,'centlbc')">Copy</button>

**dnsmasq IP Fixer**

<input type="text" id="dnsfixer" value="wget https://git.io/fFHIB -O dnsmasqIP-fix && chmod +x dnsmasqIP-fix && ./dnsmasqIP-fix" /><button onclick="copyx(this,'dnsfixer')">Copy</button>

> Note: **Use the appropriate script according to your OS. Operate your server using SE Server Manager.**

SE Server Manager Link: [Click Me](http://www.softether-download.com/files/softether/v4.27-9668-beta-2018.05.29-tree/Windows/SoftEther_VPN_Server_and_VPN_Bridge/softether-vpnserver_vpnbridge-v4.27-9668-beta-2018.05.29-windows-x86_x64-intel.exe)

SE Client Manager Link: [Click Me](http://www.softether-download.com/files/softether/v4.27-9668-beta-2018.05.29-tree/Windows/SoftEther_VPN_Client/softether-vpnclient-v4.27-9668-beta-2018.05.29-windows-x86_x64-intel.exe)


:heavy_check_mark: SE Server Setup

:heavy_check_mark: Ubuntu/Debian LBC and SNat Setup

:x: Pre-made hub

:heavy_check_mark: CentOS LBC, SNAT, and DNSMASQ IP Fixer


<script language="javascript">
  function copyx(bttn,txtbox) {
  bttn.innerHTML="Copied";
  var copyText = document.getElementById(txtbox);
  copyText.select();
  document.execCommand("copy");}
</script>
