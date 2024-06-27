### Use-cases
# Use-cases of the platform - 24 experimental sessions (2 closed-loop)

<div grid="~ cols-2 gap-4" id="freiburg_example_pictures">

<div>
  <img src="/images/setup_with_ao.png" alt="setup_with_ao">
</div>

<div>
  <img src="/images/setup_with_copydraw.png" alt="setup_with_copydraw" style='width:90%;'>
</div>

</div>

---

# Using `dareplane-utils`
```bash
pip install dareplane-utils
```

```python
from dareplane_utils.stream_watcher.lsl_stream_watcher import StreamWatcher

sw = StreamWatcher("my_stream_name")

# connect to stream and initialize buffers
sw.connect_to_stream()

while True:
    # Fetch data into buffers
    sw.update()

    x = sw.unfold_buffer()  # for channel samples, most recent at [-1, :]
    t = sw.unfold_buffer_t()  # for timestamps
```
