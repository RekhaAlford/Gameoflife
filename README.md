# Gameoflife
const {verifyCell} = require('./Gameoflife.js');

describe("neighbours", ()=>{

    it("is 1 neighbours",()=>{
      const result = verifyCell(1);
      expect(result).toBe("Dead");
    })   

    it("is 4 neighbours",()=>{
        const result = verifyCell(4);
        expect(result).toBe("Dead");
    })
  
    it("is 2 neighbours",()=>{
     const result = verifyCell(2);
      expect(result).toBe("Live");
    })

      it("is Dead with 3 Live neighbours", ()=>{
      const result = verifyCell(3);
      expect(result).toBe("Live");
    })
  }) 



 PASS  ./Gameoflife.test.js
  neighbours
    √ is 1 neighbours (3 ms)                                                                                                                                               
    √ is 4 neighbours                                                                                                                                                      
    √ is 2 neighbours                                                                                                                                                      
    √ is Dead with 3 Live neighbours                                                                                                                                       
                                                                                                                                                                           
Test Suites: 1 passed, 1 total                                                                                                                                             
Tests:       4 passed, 4 total                                                                                                                                             
Snapshots:   0 total
Time:        0.652 s, estimated 1 s
Ran all test suites.
