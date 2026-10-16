### Hi, I'm David — C / C++ developer at École 42

I write low-level software in C and C++: event loops, processes, threads, parsers, memory.
I am looking for a **6-month software development internship in the space or aerospace industry** (embedded, ground segment, simulation or tooling), starting **January 2027**, in Île-de-France.

> 🇫🇷 Étudiant à l'École 42, je recherche un **stage de 6 mois en développement logiciel pour le spatial ou l'aéronautique** (embarqué, segment sol, simulation ou outils) à partir de **janvier 2027**, en Île-de-France.

<a href="https://www.linkedin.com/in/david-samuel-5522b7195"><img src="https://img.shields.io/badge/LinkedIn-David%20Samuel-0A66C2?logo=linkedin&logoColor=white" alt="LinkedIn"></a>
<img src="https://img.shields.io/badge/Internship-from%20Jan%202027-2EA44F" alt="Available for an internship from January 2027">

---

#### Selected work

| Project | What it is | What it shows |
|---|---|---|
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
- **Next:** bare-metal C on AVR (ATmega328P), then STM32

#### Background

Before 42, I was an optician-optometrist, then ran my own small transport company.
I switched to software in 2025. I grew up in French Guiana, home of Europe's spaceport.

<sub>Most projects here were built at <a href="https://42.fr">École 42</a>: project-based, peer-reviewed, no teachers.</sub>
