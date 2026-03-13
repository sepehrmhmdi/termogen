# Termogen

Turn terminal sessions into clean README GIFs.

![demo](demo.gif)

Termogen records terminal sessions and converts them into high-quality animated GIFs.

Perfect for:

• CLI documentation  
• README demos  
• developer tutorials  

---

## Example

```bash
termogen record demo.cast
termogen cut demo.cast --start 1 --end 4 -o short.cast
termogen render short.cast -o demo.gif
