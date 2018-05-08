# faucetTutorial

Note: this tutorial is work in progress.

The below section links should display everything correctly.
BUT --->

Eventually this repository will be moved into the faucet docs website where the rst files will be compiled to html.
So some of the yaml code blocks are not rendered while viewing on github.
As a temporary workaround view the rst as a 'raw'.


Start with [Installing faucet for the first time](https://faucet.readthedocs.io/en/latest/tutorials.html)
which brad will be demonstrating in the morning. acls carries directly on from that.

Then:
1. [ACLs](_build/html/ACLs.html)
2. [VLANs](_build/html/vlan_tutorial.html)
3. [Routing](_build/html/routing.html)
4. [NFV services](_build/html/nfv-services-tutorial.html)
5. [Routing 2](_build/html/routing-2.html)


If comfortable with the above topics [Build your own network](byon.rst)



THe VM will need to have already installed:
- ssh
- wireshark /TCPDump
- Iperf3
- Docker?
- Firefox
- Ovs bash completion scripts.
- Bird
- screen/tmux

(user will install faucet & ovs from brad's repo as part of first time tutorial).

Those set up scripts (create_ns, as_ns, clear_ns, cleanup) could be placed in the bashrc.
Basic vim config for spaces not tabs.
