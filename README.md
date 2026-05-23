<p align="center">

<h1 align="center"> gustavo</h1>

<p align="center">
  <b>offsec raider 🏴‍☠️ | 19 y'old</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/status-hacking%20the%20planet-red?style=flat-square&logo=gnu-bash&logoColor=white" />
</p>

---

## 🐱‍👤 ```__aboutme()```

- web/api, mobile, ad and cloud exploitation
- back-end web and mobile developer
- computer engineering academic @ CIn-UFPE
- [my linkedin](https://linkedin.com/in/gustavo-linhares0xf)
- [my technical blog](https://b4sh0xf.github.io)

```c
typedef int (*ptrace_ptr_t)(int _request, pid_t _pid, caddr_t _addr, int _data);
void killDbg() {
    ptrace_ptr_t ptrace_ptr = (ptrace_ptr_t) dlsym(RTLD_SELF, "ptrace");
    ptrace_ptr(31, 0, 0, 0); // deny attach
}
```
