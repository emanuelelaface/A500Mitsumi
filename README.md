# PCB Replacement for the Amiga 500 MITSUMI keyboard controller.

This board was designed to replace the PCB controller of the Amiga 500 and WAS NOT YET TESTED.
THE PROJECT IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY,
WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

Here there is the BOM for this board with the original component pats. Unfortunately not all of them are available
and some of them are very expensive. If I will have time I will try to build a cheap replacement.

## ICs, crystal and transistors<br>
**MOS 6570-036**: this is the Commodore Controller, it exists only on eBay or similar.<br>
**74LS123** https://www.aliexpress.com/w/wholesale-74LS123.html<br>
**74LS27** https://www.aliexpress.com/w/wholesale-74LS27.html<br>
**HA17555** https://www.aliexpress.com/w/wholesale-HA17555.html<br>

**Crystal 3.000MHz** The original part is ceramic, but this should work: https://www.aliexpress.com/item/1005002978924496.html

**2 x BC458C** it exists the 2S485 but I am not sure is the same, otherwise someone suggests the KSC1845FTA as alternative.

## Resistors and Capacitors<br>
These components are available everywhere<br>
2 x 22 Ohm<br>
1 x 100 Ohm<br>
1 x 150 Ohm<br>
1 x 10K Ohm<br>
3 x 47K Ohm<br>
1 x 120K Ohm<br>
1 x 1M Ohm<br>

2 x 10pF<br>
2 x 1nF<br>
6 x 100nF<br>

1 x 1uF 16V<br>
1 x 10uF 16V<br>
1 x 22uF 16V<br>

## LED<br>
Only on used market. I will think about a possible replacement with 3d printed plastic and SMD leds.<br>
**PW RED**<br>
**DRV GREEN**<br>

## Connector to membrane<br>
**31pin  Connector** The original is the MOLEX 39532314 (https://www.molex.com/en-us/products/part-detail/0039532314) but it is impossible to find it.<br>
Maybe the Amphenol FCI HLW31R-2C7LF can do the job https://www.mouser.it/ProductDetail/Amphenol-FCI/HLW31R-2C7LF?qs=WBZOdOMIekV2voD%252BzNTD0A%3D%3D
