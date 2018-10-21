# Modified midsets calculator

This is a command line utility for calculating midsets. All show dots are converted from one file into a midset file in one go (as opposed to other online tools in which you have to input each one individually)

## Building it

```
git clone https://github.com/Jason-FTW/midsets
cd midsets
make
```
Or you can clone with `git clone git@github.com:Jason-FTW/midsets.git`

## Usage

### Input

```
./midset input.txt
```

### Building

```
./midset [file]
	Accepts a file to read, otherwise stdin
	-u: ugly output
	-n: output set numbers
	-a: also print input sets
	-d [n]: division of sets (2, 4, 8...)
```

### Format

`[side] [steps] [in/out] [yard] [steps] [front/back] [fh/bh/fs/bs]`
Where side is the side of the field

Steps, in/out and yard are for side to side

Steps, front/back and fh/bh/fs/bs is for front-back

### Examples

See [mvnt1-in](./data/mvnt1-in).

Output for the example is in the same folder. 

### Upcoming/Todo

- [ ] Patch formatting for copy-paste
- [ ] web client
