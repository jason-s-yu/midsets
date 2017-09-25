# Modified midsets calculator

This is a command line utility for calculating midsets. Based off of [midset](https://github.com/spencer-p/midset) - formatting is the same.

## Building it

```
git clone https://github.com/Jason-FTW/midsets
cd midset
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

See [mvt1-in](https://github.com/Jason-FTW/midsets/blob/master/data/mvt1-in).

Output for the example is in the same folder. 
