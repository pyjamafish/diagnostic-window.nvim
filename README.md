# Diagnostic Window (no header)

This repo patches [diagnostic-window.nvim](https://github.com/cseickel/diagnostic-window.nvim) to remove the header.
<img width="842" alt="image" src="https://user-images.githubusercontent.com/29507110/182702854-d06b579c-2732-4ee6-9f8a-fef88472675c.png">

Note that I have no idea how to code in Lua, so use at your own risk! As the wonderful [license](./LICENSE) states:
> IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.


## Quickstart

Clone the repository using your favorite plugin manager, including 
[MunifTanjim/nui.vim](https://github.com/MunifTanjim/nui.nvim). For example, with packer:
```lua
  use { 
    "cseickel/diagnostic-window.nvim",
    requires = { "MunifTanjim/nui.nvim" }
  }

```

Then open the window with this command:
```
:DiagWindowShow
```

## License

MIT

## Contributing

Please do!
