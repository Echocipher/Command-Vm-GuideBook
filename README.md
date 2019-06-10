# Command-Vm-GuideBook #
总结一下Command-Vm中的工具简介和用法，由于利用碎片化时间整理以及个人能力限制，难免有遗漏或失误，如有问题或建议，希望能得到您的交流。

## 版权 ##

author：Echocipher

mail：echocipher@163.com

blog：https://www.jianshu.com/u/1f2643f05298

## 说明 ##

本项目仅进行漏洞探测工作，无漏洞利用、攻击性行为，开发初衷仅为方便安全人员对授权项目完成测试工作和学习交流使用，**请使用者遵守当地相关法律，勿用于非授权测试，如作他用所承受的法律责任一概与作者无关，下载使用即代表使用者同意上述观点**。

附《[中华人民共和国网络安全法](http://www.npc.gov.cn/npc/xinwen/2016-11/07/content_2001605.htm)》。

## Command-Vm ##
<p align="center">
  <img width="300" src="https://github.com/Echocipher/Command-Vm-GuideBook/blob/master/Pic/Commando.png?raw=true" alt="Commando VM"/>
</p>  
Welcome to CommandoVM - a fully customized, Windows-based security distribution for penetration testing and red teaming.

本项目只是探究Command-Vm的工具用法，安装教程详见《[项目地址](https://github.com/fireeye/commando-vm)》

## 工具列表 ##

### Active Directory Tools ###

├─Active Directory Tools
│      Administration Tools.lnk
│      sqlcmd.lnk
│      Sysinternals.lnk
│      
├─Command & Control
│      Covenant.lnk
│      Elite.lnk
│      PoshC2-StartC2Server.lnk
│      PoshC2-StartC2Viewer.lnk
│      WMImplant.lnk
│      WMIOps.lnk
│      
├─Debuggers
│      windbgx64.lnk
│      windbgx86.lnk
│      x32dbg.lnk
│      x64dbg.lnk
│      
├─Developer Tools
│      VSCode.lnk
│      
├─dotNET
│      dnSpy-x86.lnk
│      dnSpy.lnk
│      ilspy.lnk
│      
├─Evasion
│      CheckPlease.lnk
│      demiguise.lnk
│      DotNetToJScript.lnk
│      Invoke-CradleCrafter.lnk
│      Invoke-DOSfuscation.lnk
│      Invoke-Obfuscation.lnk
│      Invoke-Phant0m.lnk
│      nps.lnk
│      pafishmacro.lnk
│      PowerLessShell.lnk
│      PowerShdll.lnk
│      PSAmsi.lnk
│      PSAttack.lnk
│      StarFighters.lnk
│      
├─Exploitation
│  │  ADAPE.lnk
│  │  API Monitor x64.lnk
│  │  API Monitor x86.lnk
│  │  CrackMapExecWin.lnk
│  │  DAMP.lnk
│  │  Exchange-AD-Privesc.lnk
│  │  Generate-Macro.lnk
│  │  Invoke-ACLPwn.lnk
│  │  Invoke-DCOM.lnk
│  │  Invoke-GoFetch.lnk
│  │  Invoke-PowerThIEf.lnk
│  │  Invoke-PSImage.lnk
│  │  luckystrike.lnk
│  │  metatwin.lnk
│  │  NetshHelperBeacon.lnk
│  │  nishang.lnk
│  │  Orca.lnk
│  │  PowerLurk.lnk
│  │  PowerPriv.lnk
│  │  PowerShell-Suite.lnk
│  │  PowerSploit.lnk
│  │  PowerUpSQL.lnk
│  │  PSReflect.lnk
│  │  RedTeamPowershellScripts.lnk
│  │  ruler.lnk
│  │  Sharp-Suite.lnk
│  │  SharpExchangePriv.lnk
│  │  SpoolSample.lnk
│  │  UACME.lnk
│  │  vssown.lnk
│  │  
│  ├─GhostPack
│  │      Rubeus.lnk
│  │      SafetyKatz.lnk
│  │      Seatbelt.lnk
│  │      SharpDPAPI.lnk
│  │      SharpDump.lnk
│  │      SharpRoast.lnk
│  │      SharpUp.lnk
│  │      SharpWMI.lnk
│  │      
│  ├─impacket-examples-windows
│  │      atexec.lnk
│  │      dcomexec.lnk
│  │      esentutl.lnk
│  │      GetADUsers.lnk
│  │      getArch.lnk
│  │      GetNPUsers.lnk
│  │      getOSandSMBproperties.lnk
│  │      getPac.lnk
│  │      getTGT.lnk
│  │      GetUserSPNs.lnk
│  │      goldenPac.lnk
│  │      ifmap.lnk
│  │      karmaSMB.lnk
│  │      lookupsid.lnk
│  │      loopchain.lnk
│  │      mimikatz.lnk
│  │      mmcexec.lnk
│  │      mqtt_check.lnk
│  │      mssqlclient.lnk
│  │      mssqlinstance.lnk
│  │      netview.lnk
│  │      nmapAnswerMachine.lnk
│  │      ntfs-read.lnk
│  │      ntlmrelayx.lnk
│  │      opdump.lnk
│  │      os_ident.lnk
│  │      ping.lnk
│  │      ping6.lnk
│  │      psexec.lnk
│  │      raiseChild.lnk
│  │      rdp_check.lnk
│  │      reg.lnk
│  │      registry-read.lnk
│  │      rpcdump.lnk
│  │      sambaPipe.lnk
│  │      samrdump.lnk
│  │      secretsdump.lnk
│  │      services.lnk
│  │      smbclient.lnk
│  │      smbexec.lnk
│  │      smbrelayx.lnk
│  │      smbserver.lnk
│  │      smbtorture.lnk
│  │      sniff.lnk
│  │      sniffer.lnk
│  │      split.lnk
│  │      ticketer.lnk
│  │      tracer.lnk
│  │      uncrc32.lnk
│  │      wmiexec.lnk
│  │      wmipersist.lnk
│  │      wmiquery.lnk
│  │      
│  ├─kali-windows-binaries
│  │      cachedump.lnk
│  │      cachedump64.lnk
│  │      enum.lnk
│  │      exe2bat.lnk
│  │      fgdump.lnk
│  │      fgexec.lnk
│  │      Fport.lnk
│  │      klogger.lnk
│  │      mbenum.lnk
│  │      nbtenum.lnk
│  │      nc.lnk
│  │      ncat.lnk
│  │      plink.lnk
│  │      pstgdump.lnk
│  │      PwDump.lnk
│  │      radmin.lnk
│  │      sbd.lnk
│  │      servpw.lnk
│  │      servpw64.lnk
│  │      vncviewer.lnk
│  │      wget.lnk
│  │      whoami.lnk
│  │      
│  ├─metasploit
│  │      msfbinscan.lnk
│  │      msfconsole.lnk
│  │      msfd.lnk
│  │      msfdb.lnk
│  │      msfelfscan.lnk
│  │      msfmachscan.lnk
│  │      msfpescan.lnk
│  │      msfremove.lnk
│  │      msfrop.lnk
│  │      msfrpc.lnk
│  │      msfrpcd.lnk
│  │      msfupdate.lnk
│  │      msfvenom.lnk
│  │      
│  └─PrivExchange
│          httpattack.lnk
│          PrivExchange.lnk
│          
├─Information Gathering
│      ADACLScanner.lnk
│      ADExplorer.lnk
│      ADOffline.lnk
│      ADRecon.lnk
│      BloodHound.lnk
│      Get-ReconInfo.lnk
│      gowitness.lnk
│      nmap.lnk
│      PowerView.lnk
│      PowerView_dev.lnk
│      SharpHound.exe.lnk
│      SharpHound.ps1.lnk
│      SharpView.lnk
│      SpoolerScanner.lnk
│      zenmap.lnk
│      
├─Networking Tools
│      Citrix Receiver.lnk
│      OpenVPN.lnk
│      ProxyCap.lnk
│      PuTTY.lnk
│      telnet.lnk
│      VMware Horizon Client.lnk
│      VMware vSphere Client.lnk
│      VNC-Viewer.lnk
│      windump.lnk
│      WinSCP.lnk
│      Wireshark.lnk
│      
├─Password Attacks
│      ASREPRoast.lnk
│      CredNinja_ps.lnk
│      CredNinja_py.lnk
│      DSInternals.lnk
│      Get-LAPSPasswords.lnk
│      hashcat.lnk
│      Internal-Monologue.lnk
│      Inveigh.lnk
│      Invoke-TheHash.lnk
│      KeeFarce.lnk
│      KeeThief.lnk
│      LAPSToolkit.lnk
│      MailSniper.lnk
│      mimikatz.x64.lnk
│      mimikatz.x86.lnk
│      mimikittenz.lnk
│      RiskySPN.lnk
│      SessionGopher.lnk
│      
├─Utilities
│      Adobe Reader.lnk
│      AutoIt3.lnk
│      cmder.lnk
│      CyberChef.lnk
│      DB Browser for SQLite.lnk
│      FLOSS.lnk
│      Gimp.lnk
│      Greenshot.lnk
│      HexChat.lnk
│      HxD.lnk
│      KeepPass.lnk
│      MobaXterm.lnk
│      neo4j-community.lnk
│      Neo4j_start.bat
│      Neo4j_stop.bat
│      peview.lnk
│      Pidgin.lnk
│      ProcessHacker.lnk
│      ScreenToGif.lnk
│      shellcode_launcher.lnk
│      SublimeText3.lnk
│      Thunderbird.lnk
│      vlc.lnk
│      yed.lnk
│      
├─Vulnerability Analysis
│      Egress-Assess.lnk
│      Grouper2.lnk
│      zBang.lnk
│      
├─Web Application
│      BurpSuite Free Edition.lnk
│      Fiddler.lnk
│      Firefox.lnk
│      OWASP ZAP.lnk
│      
└─Wordlists
        fuzzdb.lnk
        PayloadsAllTheThings.lnk
