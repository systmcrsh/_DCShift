# _DCShift

A small Max for Live audio utility that removes DC offset from
incoming audio, with an optional control to deliberately shift it
back off-center.

## What it does

- **DC correction** — centers the waveform around true zero by
  default, removing any DC offset present in the source.
- **Deliberate shift** — the same control can push the signal off-
  center on purpose instead, for creative use (e.g. driving a
  following device differently) rather than just cleanup.
- **Live oscilloscope** — see the actual output waveform in real
  time.
- **DC level readout** — a live numeric reading of the actual,
  measured DC level.

## Installing

Download `_DCShift_1.0.amxd` from this repo and drag it onto an
audio track in Ableton Live.

## Documentation

See [`_DCShift_manual.txt`](./_DCShift_manual.txt) in this repo for
the full parameter reference.

## License

See [`LICENSE`](./LICENSE) for the full text.
