<p align="center">
  <a href="https://github.com/sigkill-1337">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&duration=3000&pause=800&color=07F700&center=true&vCenter=true&width=500&lines=ch3rry;sigkill+aka+IoT;homelab+%7C+networking+%7C+security" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=sigkill-1337&color=07F700&style=flat-square&label=profile+views" alt="Profile views" />
  <a href="https://instagram.com/cs_net_py"><img src="https://img.shields.io/badge/Instagram-E4405F?style=flat-square&logo=instagram&logoColor=white" alt="Instagram" /></a>
</p>

```nasm
; whoami.asm — x86-64 Linux
section .data
    msg     db  "sigkill", 10
            db  "twice best gg btw", 10
    len     equ $ - msg

section .text
    global _start

_start:
    mov     rax, 1          ; sys_write
    mov     rdi, 1          ; stdout
    lea     rsi, [rel msg]
    mov     rdx, len
    syscall

    mov     rax, 60         ; sys_exit
    xor     rdi, rdi        ; return 0
    syscall
```

```console
sigkill@homelab:~$ nasm -f elf64 whoami.asm -o whoami.o
sigkill@homelab:~$ ld whoami.o -o whoami
sigkill@homelab:~$ ./whoami
sigkill
twice best gg btw
sigkill@homelab:~$ ls -lh whoami
-rwxr-xr-x 1 sigkill sigkill 8.7K Oct  1 02:27 whoami
sigkill@homelab:~$ echo $?
0
```

## 👾 About me

- 🖥️ **Homelab enjoyer** — Proxmox VE, VMware, VLANs, firewalls
- 🌐 **Networking** — Cisco, Aruba, MikroTik
- 🔐 **Interested in** systems and cybersecurity

## 🛠️ Tech stack

**Languages & frameworks**

![Assembly](https://img.shields.io/badge/Assembly-654FF0?style=for-the-badge&logo=assemblyscript&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)

**Infra & virtualization**

![Proxmox](https://img.shields.io/badge/Proxmox-E57000?style=for-the-badge&logo=proxmox&logoColor=white)
![VMware](https://img.shields.io/badge/VMware-607078?style=for-the-badge&logo=vmware&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

**Cloud**

![AWS](https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)
![OVH](https://img.shields.io/badge/OVH-123F6D?style=for-the-badge&logo=ovh&logoColor=white)

**Networking**

![Cisco](https://img.shields.io/badge/Cisco-049FD9?style=for-the-badge&logo=cisco&logoColor=white)
![MikroTik](https://img.shields.io/badge/MikroTik-293239?style=for-the-badge&logo=mikrotik&logoColor=white)
![Aruba](https://img.shields.io/badge/Aruba-FF8300?style=for-the-badge&logo=arubanetworks&logoColor=white)

**Data & monitoring**

![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&logo=mariadb&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)

## 📊 GitHub stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=sigkill-1337&theme=cobalt&show_icons=true&hide_border=true&count_private=true" alt="GitHub stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=sigkill-1337&theme=cobalt&layout=compact&hide_border=true" alt="Top languages" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=sigkill-1337&theme=cobalt&hide_border=true" alt="GitHub streak" />
</p>

### 🔝 Top contributed repos

<p align="center">
  <img src="https://github-contributor-stats.vercel.app/api?username=sigkill-1337&limit=5&theme=dark&combine_all_yearly_contributions=true" alt="Top contributed repos" />
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=07F700&height=80&section=footer" />
</p>
