# Batch Connect - OSC SAS

A Batch Connect app designed for OSC OnDemand that launches SAS within an
ASU Agave batch job. Cloned from `github.com/jyalim/bc_osc_stata`.

## Prerequisites

This Batch Connect app requires the following software be installed on the
**compute nodes** that the batch job is intended to run on (**NOT** the
OnDemand node):

- [Sas] 9.4
- [Xfce Desktop] 4+

For VNC server support:

- [TurboVNC] 2.1+
- [websockify] 0.8.0+

**Optional** software:

- [Lmod] 6.0.1+ or any other `module purge` and `module load <modules>` based
  CLI used to load appropriate environments within the batch job

[Stata]: https://www.sas.com/
[Xfce Desktop]: https://xfce.org/
[TurboVNC]: http://www.turbovnc.org/
[websockify]: https://github.com/novnc/websockify
[Lmod]: https://www.tacc.utexas.edu/research-development/tacc-projects/lmod


## Contributing

1. Fork it ( https://github.com/jyalim/bc_sas/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request

## License

* Documentation, website content, and logo is licensed under
  [CC-BY-4.0](https://creativecommons.org/licenses/by/4.0/)
* Code is licensed under MIT (see LICENSE.txt)o
* The pictures, icons, and logos encoded in gif files and other formats are either copyrights and/or trademarks of StataCorp LLC.
