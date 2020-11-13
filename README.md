# Computer System A Programmer's Perspective Lab


- [ ] Bomblab
- [ ] Attacklab
- [ ] Cachelab
- [ ] PerformanceLab
- [ ] mallocLab
- [ ] ShellLab
- [ ] ProxyLab


| C      | Intel data type  | Assembly-code suffix | Size(bytes) |
| ------ | ---------------- | :------------------: | :---------: |
| char   | byte             |          b           |      1      |
| short  | word             |          w           |      2      |
| int    | double word      |          l           |      4      |
| long   | four word        |          q           |      8      |
| char*  | four word        |          q           |      8      |
| float  | Single Precision |          s           |      4      |
| double | Double Precision |          l           |      8      |


`movq Src, Dst`

| Instruction | Effect | Description      |
| ----------- | ------ | ---------------- |
| MOV S,D     | D<-S   | MOVE             |
| movb        |        | move byte        |
| movw        |        | Move Word        |
| movl        |        | Move Double Word |
| movq        |        | Move Quad Word   |

## Bomblab

(gdb) x/s $esi 

Print the string value of $esi

### Phase 1

Border relations with Canada have never been better.

