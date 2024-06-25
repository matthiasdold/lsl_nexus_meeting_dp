<div grid="~ cols-2 gap-4">

<div>

<h1> Project release on GitHub <uiw-github /> </h1>

- Landing page [^1] with modules included as `git submodules`.
- Tutorial for getting started - `Dareplane helloworld`
- Strawmen module as general template to start development
- python library `dareplane-utils` on `pypi`.
  - logging via TCP socket
  - default server
  - `StreamWatch` - ring buffer for LSL [^2] streams

</div>

<div class='images_right'>

![dareplane_landing](images/dareplane_git_landing.png)

![dareplane_utils](images/pypi_dareplane_utils.png)

</div>

</div>

[^1]: [1. https://github.com/bsdlab/Dareplane](https://github.com/bsdlab/Dareplane)
[^2]: [2. https://github.com/sccn/labstreaminglayer](https://github.com/sccn/labstreaminglayer)

<style>
.grid-cols-2, [grid~="cols-2"] {
	grid-template-columns: 1.5fr 1fr;
}
.images_right {
  margin-top: -5%;
  margin-right: -5%;
}
img {
  width: 85%;
  border: 1px solid var(--slidev-theme-primary);
}
</style>


