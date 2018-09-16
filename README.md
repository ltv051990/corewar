# Corewar

   In this project, you will see a virtual “arena” in which programs will fight
against one another (the “Champions”). You will also use an assembler to compile
those Champions as well as a Champion to show the world that you can create life from
coffee.

<img width="2054" alt="screen shot 2018-09-16 at 6 21 58 pm" src="https://user-images.githubusercontent.com/26527567/45599071-11fdc980-b9ee-11e8-98ec-3d0d500bf662.png">

  Corewar is a very peculiar game. It’s about bringing “players” together around a
“virtual machine”, which will load some “champions” who will fight against one another
with the support of “processes”, with the objective being for these champions
to stay “alive”.

  • The processes are executed sequentially within the same virtual machine and memory
space. They can therefore, among other things, write and rewrite on top of
each others so to corrupt one another, force the others to execute instructions that
can damage them, try to rewrite on the go the coding equivalent of a Côtes du
Rhône 1982 (that is one delicious French wine!), etc...

  • The game ends when all the processes are dead. The winner is the last player
reported to be “alive”.

<img width="2054" alt="test" src="https://user-images.githubusercontent.com/26527567/45599097-820c4f80-b9ee-11e8-9c75-999b52eb9144.png">


  **Breakdown of the project’s objectives**
This project can be broken down into three distinctive parts:

  • **The assembler:** this is the program that will compile your champions and translate
them from the language you will write them in (assembly language) into “Bytecode”.Bytecode
is a machine code, which will be directly interpreted by the virtual
machine.

  • **The virtual machine:** It’s the “arena” in which your champions will be executed.
It offers various functions, all of which will be useful for the battle of the champions.
Obviously, the virtual machine should allow for numerous simultaneous processes;
we are asking you for a gladiator fight, not a one-man show simulator.

  • **The champion:** This one is a special case. Later, in the championship, you will
need to render a super powerful champion, who will scare the staff team to death.
However, rendering this kind of champion is serious work. And since, for now, we
are mostly interested in your capacity to create Corewar’s other programs (i.e. the
assembler and virtual machine), your current champion will only need to prove to
us that you can write bits and pieces of Corewar ASM. This means that the champion
you should render for this project only needs to scare the bejesus out of a
neurasthenic hedgehog.

<img width="2061" alt="screen shot 2018-09-16 at 6 22 59 pm" src="https://user-images.githubusercontent.com/26527567/45599073-15915080-b9ee-11e8-8818-39279b8d88e6.png">

    There will also be a Corewar championship, for which you will create new champions
that will fight in a series of epic battles. The highpoint of this championship will make
Game of Thrones look like nap time at kindergarten.
Please note that the championship is a separate project for which you will render a
new champion. It would therefore be wise for you to keep your most twisted strategies to
yourself, so that you don’t become, so to speak, the laughing stock of this championship
of utmost seriousness.
