# ProyectoInvierno
ProyectoInvierno's target is manage specific programs in containers from a custom shell. All programs will be under containers, each one will be independent from the others and will be isolated. <br />
Then ProyectoInvierno will be handle the information between them without the requeriment of SystemD, just the Kernel Linux. But in the future the idea is hack this to work on any kernel.<br />

## Roadmap
[ ] Design architecture.
[ ] Integrate RunC bindings into libproyectoinvierno.
[ ] Create shell for use RunC and administrate it.
[ ] Create "service" files to specify automatic inits.
[ ] Create, as a module, curses TUI (Text User Interface).
[ ] Identify ProyectoInvierno's dependencies (at system level) to do it free of SystemD.
[ ] Create AppArmor's profiles for ProyectoInvierno and specific "services".

### License
GNU General Public License v3: <br />
https://www.gnu.org/licenses/gpl-3.0.en.html <br />

## Hack
This is the new build of my last, same name, project; ProyectoInvierno-OLD which try to use this in the same way but in C. As is usual, is complicated for a no senior dev, so I am working on this in Rust, which will provide more acuracy, quality and speed on this.
