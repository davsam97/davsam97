### Hi, I'm David, C/C++ developer at École 42

I write low-level software in C and C++: event loops, processes, threads, parsers, memory.
I am looking for a 6-month software development internship starting January 2027, anywhere in France or in a neighbouring country. Space and aerospace interest me most, and I am also open to back-end and tooling roles.

> Étudiant à l'École 42, je cherche un stage de développement logiciel de 6 mois à partir de janvier 2027, partout en France ou dans un pays voisin. Le spatial et l'aéronautique m'intéressent le plus, mais les postes back-end et les outils internes m'intéressent aussi.

<a href="https://www.linkedin.com/in/david-samuel-5522b7195"><img src="https://img.shields.io/badge/LinkedIn-David%20Samuel-0A66C2?logo=linkedin&logoColor=white" alt="LinkedIn"></a>
<img src="https://img.shields.io/badge/Internship-from%20Jan%202027-2EA44F" alt="Available for an internship from January 2027">

---

#### Selected work

| Project | What it is | What it shows |
|---|---|---|
| **[malloc](https://github.com/davsam97/malloc)** | Thread-safe reimplementation of `malloc` / `free` / `realloc` as a shared library, built only on `mmap` / `munmap`. Runs `ls`, `git`, `vim` and `python3` through `LD_PRELOAD`. *Solo, 125/100.* | Virtual memory and paging, allocator design (zones, segregated free lists, coalescing), shared libraries and symbol interposition, thread safety |
| **[webserv](https://github.com/davsam97/webserv)** | Non-blocking HTTP/1.0 server in C++98, in the spirit of NGINX. One `poll()` loop serves every client, CGI runs asynchronously. *Team of 2.* | Sockets and event-driven I/O, `fork`/`execve`/pipes, protocol work from the RFCs, resource ownership in C++ |
| **[miniRT](https://github.com/davsam97/miniRT)** | Ray tracer written from scratch in C: spheres, planes, cylinders, cones, Phong lighting, shadows, textures and bump mapping. *Team of 2.* | 3D math (vectors, intersections, TBN frames), rendering pipeline, modular C architecture |
| **[minishell](https://github.com/davsam97/minishell)** | A bash-like Unix shell in C: AST parser, pipes, subshells, `&&` / `\|\|`, heredocs, wildcards, signals. *Team of 2.* | Parsing, process management, Unix signals, careful error handling |
| **[philosophers](https://github.com/davsam97/philosophers)** | The dining-philosophers problem, solved twice: threads + mutexes, then processes + named semaphores. | Concurrency without deadlocks or data races, timing-sensitive monitoring |

Also: [push_swap](https://github.com/davsam97/push_swap) (sorting under constraints) · [so_long](https://github.com/davsam97/so_long) (2D game, MiniLibX) · [pipex](https://github.com/davsam97/pipex) · [Libft](https://github.com/davsam97/Libft) · [ft_printf](https://github.com/davsam97/ft_printf) · [get_next_line](https://github.com/davsam97/get_next_line)

<!-- Add when the repo is public:
| **[malloc](https://github.com/davsam97/malloc)** | My own `malloc` / `free` / `realloc` as a shared library (`libft_malloc.so`). | Memory layout, `mmap`, alignment, fragmentation |
-->
<!-- Add when a public link exists:
**Team project:** [ft_transcendence](LINK) — real-time quiz platform (FastAPI, PostgreSQL, Nuxt). I took over the backend core and worked on the WebSocket layer.
-->

#### Toolbox

- **Languages:** C (main), C++98, Bash, Python
- **Systems:** POSIX processes and signals · pthreads, mutexes, semaphores · sockets and `poll()` · manual memory management
- **Tools:** Linux, Git, Make, GCC / Clang, Valgrind, Docker
- **Now:** bare-metal C on AVR (ATmega328P) in 42's embedded track, then STM32

#### Background

Before 42, I was an optician-optometrist, then ran my own small transport company.
I switched to software in 2025. I grew up in French Guiana, home of Europe's spaceport.

<sub>Most projects here were built at <a href="https://42.fr">École 42</a>: project-based, peer-reviewed, no teachers.</sub>
