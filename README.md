If you're looking for more complete solution, please use [dataferret/docker-logentries](https://github.com/dataferret/docker-logentries)


### Overview
Log data from docker host through fluent to logentries.

```
docker run -v /var/lib/docker/containers:/var/lib/docker/containers -e TOKEN={TOKEN} gregory90/fluent-logentries
```

##### Environment variables
TOKEN - token from logentries


### Credits
Connector for fluent to send logs to logentries is based on https://github.com/Woorank/fluent-plugin-logentries


### MIT
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
