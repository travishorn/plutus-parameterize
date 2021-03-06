# Parameterize a Plutus Contract

`Vesting.hs` is a Plutus contract which allows someone to lock ADA in a smart
contract with a given beneficiary and a deadline. Once the deadline passes, the
beneficiary can grab the ADA from the contract.

[Watch the IOGAcademy video about this
script.](https://www.youtube.com/watch?v=ae7U_yKIQ0Y&list=PLNEK_Ejlx3x2zxcfoVGARFExzOHwXFCCL&index=4)

In this first video, `Vesting.hs` is **not** parameterized.

[Watch the IOGAcademy video about parameterizing this
script.](https://www.youtube.com/watch?v=XqFILXV_ACM&list=PLNEK_Ejlx3x2zxcfoVGARFExzOHwXFCCL&index=5)

[View the diff between these two versions in this
repository.](https://github.com/travishorn/plutus-parameterize/commit/3767c5665e412ab319b2244d74dc325e62541071#diff-2eb8c7c47462afd2b1de86ff9473b6d9c3cd071ea432004179bcdecc4cfea465)
