## TESTING TYPORA



|  NO  | DESCRIPTION     | REMARK   |
| :--: | :-------------- | -------- |
|  1   | - Hello         | Greeting |
|  2   | - lol<br> -haha | Laughing |
|  3   | - Nothing here  |          |

<p align=center><em>Table 1.0: Testing</em></p>



Today Task

- [ ] Trying Typora
- [ ] To find the alternative parts
- [ ] To update block diagram
- [ ] To prepare the document

<details>
  <summary>Companies</summary>
  - Subnero<br>
  - Fizix<br>
  - GTS Electronic<br>
  - Rextec System<br>
</details>


------

🥰😍 Typora if free version

![subnero](/Users/soe/Pictures/subnero.png)

> Give more than get



<u>Hello</u>

<u>**Summary** (28-Sep-2023)</u>





> We should have only 1 of these and ideally we should replace the old one with a new one. Github will automatically do the versioning for us.

Yes Just noticed it a few day ago and now I kept updating on "BlockDiagrm-BabyEchoV5.00.pdf". Will delete the other two files.

> Also, it looks like the files are inside the "images" inside the meetings folder. The meetings folder is only for meeting minutes. We should put the designs in the Architecture or Design-doc folder and link to it.

I will do the same.

> The 12 bit ADC is still sigma-delta, we may not need a sigma-delta, a normal one may do (and less power draw possibly). Again, this is a minor comment.

Could not find the ADC with low bit and normal processing instead of signal-delta for I2C communication. That is why we finally decided to use it. Yes, it is less power draw chip.

> Have you already added the 12V PSU to the block diagram?

Not yet and working on it.

> "But not description for other voltages." -> Not sure what this means

Datasheet said the value of IQ at Vin 48V. Not details about other voltage of input eg: 10V, 12V, 24V and 36V.

> "IQ = 94uA is the measured values at 24V input" -> This is not measured by us rt? Isn't this from the datasheet?

That is measured by us during design verification of BabyEcho v4.11. Will update it as "IQ = 94uA is the measured values at 24V input during design verificatoin of BabyEcho v4.11"

> For the test plan, we will measure the current draw too, rt?

Yes, We will.

> Instead of doing ":Revision: 5.00 (29-Sep-2029)", can you please use either v5.00-draft till we finalize it so that we can assigned 5.0 then. Or 5.01, 5.02 etc. Now we have same revision with different dates.

Look I am a time traveler :sweat_smile: and I apologize for my error in typing. The changes made to the block diagram on the specific date are what I am referring to. I realize now that using "5.00" here would create confusion, especially with the BabyEcho version. What if I label it as "The changes on 29-Sep-2023"? 
