# 256 Foundation newsletter archive

Source: https://github.com/256foundation/News
License: CC0 1.0, as stated by the 256 Foundation on that repository.
Pulled: 7 October 2026.
Coverage: all 27 PDFs published in the News repo, January 2025 through Assembling Freedom #27 (27 May 2026).
Substack archive page also lists #27 (28 May 2026) as the newest public issue. No later issue was listed.
Text extracted from the official PDFs with pdftotext. Layout artifacts and repeated headers may remain. Images are not transcribed.

Use one issue per chunk. Each issue starts with a DOCUMENT marker.


===== DOCUMENT 1 of 27 =====
DATE: 2025-01
LABEL: January 2025
TITLE: A Spark of Defiance
FILE: 256Foundation-Newsletter-2501_v1.pdf
SOURCE: https://github.com/256foundation/News/blob/main/256Foundation-Newsletter-2501_v1.pdf

A Spark of Defiance
By: The 256 Foundation
A monthly newsletter
January 2025


Introduction:                                                      can’t compete with big miners! You’re better off just
Welcome to the first newsletter produced by The 256                buying from an exchange! You won’t get your ROI!”.
Foundation! If you have enjoyed POD256 or technical
guides from econoalchemist in the past, then you are               Against all odds, using closed-source miners, and with little
going to love this newsletter. You can expect newsletters to       more than a shoestring budget and a can-do attitude people
be published on a monthly basis going forward. The content         have forged a way forward and collectively pushed the
will generally focus on topics aligned with The 256                Bitcoin mining industry to a tipping point. Closed-source
Foundation’s mission to “Dismantle the proprietary mining          solutions are not keeping up with innovation and won’t
empire to liberate Bitcoin and freedom tech for all”. More         even make economic sense compared to the open-source
specifically, the focus of this newsletter will be on the state    solutions just over the horizon. The 256 Foundation is here
of the Bitcoin network, mining industry developments,              to kick the old ways of Bitcoin mining development to the
progress updates on grant projects, actionable advice for          curb in favor of free and open development; providing
getting involved with Bitcoin mining, and more (to be              funding for developers and educators to do what they do
announced...wink wink).                                            best and usher in the era free and open Bitcoin mining.

Open-source development in Bitcoin mining up until the             The 256 Foundation is laser focused on a select handful of
Bitaxe has been non-existent but The 256 Foundation is             projects that are going to break the entire Bitcoin mining
breaking the chains of closed and proprietary development.         industry wide open and make freedom tech accessible to
After all, two out of three pillars supporting the Bitcoin         anyone. These select projects are long term support
ecosystem are openly developed – nodes and applications;           initiatives, not short term touch-and-go exercises. Education
why not mining? The majority of mining hardware is closed          is a key component and why The 256 Foundation provides
and proprietary; same with the firmware, even the after-           educational resources, tools, and support to demystify
market solutions are closed-source. If you have tried using a      Bitcoin and freedom tech, empowering individuals to
miner in some unconventional way like home heating,                engage with and benefit from this revolutionary system.
dehydrating food, or installing one in your living space just
so you don’t have to submit KYC documents to get bitcoin           If that sounds like the kind of timeline you’re interested in
then you will appreciate the ability to freely modify your         then keep reading and watch for updates every month in
miner.                                                             your inbox, on Nostr, or at 256foundation.org.

Despite the constraints on creativity caused by closed-            Definitions:
source firmware and hardware, many individuals have                MA = Moving Average
demonstrated impressive developments. For example,                 Eh/s = Exahash per second
Diverter who wrote the groundbreaking guide on the                 Ph/s = Petahash per second
subject, Mining For The Streets, at a time when the general        Th/s = Terahash per second
consensus was that small-scale mining was a foregone               MW = Mega Watt
pursuit. Zack Bomsta developed the Loki Kit enabling users         T = Trillion
to power miners from 120-volt power sources instead of the         J/Th = Joules per Terahash
less common 240-volt power sources. Michael Schmid                 $ = US Dollar
developed a way to heat his home using four Antminer S9s;          VDC = Volts Direct Current
offsetting his energy bills with mining rewards. Rev. Hodl         PCB = Printed Circuit Board
has integrated Bitcoin mining into a variety of                    GB = Gigabyte
homesteading functions like dehydrating his elderberry             TB = Terabyte
harvest. In fact, the resourcefulness and determination of         OS = Operating System
individuals to integrate Bitcoin mining into their unique          SSH = Secure Shell
situations has proven to be nothing short of a full on
movement. Defiantly building and iterating despite the             State of the Network:
naysayers, excuse makers, and protests that claim “you             Hashrate on the 14-day MA according to mempool.space
                                                                   increased from ~525 Eh/s in January 2024 to ~784 Eh/s in


                                                        The 256 Foundation
                                                           Page 1 of 10

December 2024, marking ~49% growth for the year. Last
month alone, December 2024, witnessed roughly 34 Eh/s
come online marking ~4.5% overall growth for the month.
Using some rough ball-park figures, 34 Eh/s coming online
means something like 170,000 new-gen 200 Th/s miners
were plugged in and supported by ~595 MW of electrical
infrastructure.                                                                    [IMG-003] Hashprice/Hashvalue from Braiins Insights


Difficulty is currently 110.4T as of Epoch 436 and set to                Mining Industry Developments:
decrease roughly 0.2% on or around January 26, 2025. But                 2024 marks the year that open-source Bitcoin mining
that target will constantly change between now and then.                 hardware became a thing. Prior to the Bitaxe, there was no
The previous re-target increased difficulty by 0.6%. In                  open source Bitcoin mining hardware. A small but mighty
2024, difficulty went from 72.0T to 109.7T making it 52.3%               platform, the Bitaxe project has proved that it is possible to
more difficult to solve for a block; fairly consistent with the          have a complete Bitcoin mining system developed, built,
estimated 49% hashrate increase during the same time                     and maintained in the open by a community of enthusiasts.
frame.
                                                                         The impressive part about Bitaxe is that Skot instigated a
                                                                         project that satisfied a burning desire in the open-source
                                                                         community to develop a mining system by reverse
                                                                         engineering Bitmain’s ASIC chips and integrate them onto a
                                                                         new open-source hardware platform, with accompanying
                                                                         open-source firmware, esp-miner. Fast forward to today and
                                                                         thousands of individuals have joined the Open Source
                                                                         Miners United Discord group and their combined
     [IMG-001] 2024 hashrate/difficulty chart from mempool.space         contributions have made Bitaxe what it is today. This
                                                                         required delicate work to unsolder the ASIC chips from
New-gen miners are selling for roughly $28.14 per Th                     Bitmain’s hashboards and then re-solder them onto the
using the Bitmain Antminer S21 XP 270 Th/s model from                    Bitaxe circuit board. The genius part of the project is that
Kaboom Racks as an example. According to the Hashrate                    the open-source foundation supports commercially viable
Index, less efficient miners like the <19J/Th models are                 ventures built on top of it. For example, Bitaxe is the open-
fetching $18.18/Th, models between 19J/Th – 25J/Th are                   source project that develops and designs models but does
selling for $13.31/Th, and models >25J/Th are selling for                not manufacture, market, or distribute any units; a list of
$3.53/Th.                                                                companies that have sprung up selling Bitaxes can be found
                                                                         here.

                                                                         The Bitaxe was the inspiration for the title of this month’s
                                                                         newsletter, A Spark of Defiance, because it was a small and
                                                                         seemingly inconsequential development that ignited a
                                                                         raging fire that will engulf the closed and proprietary
                                                                         Bitcoin mining empire. Additionally, the project was
      [IMG-002] 2024 Miner Prices from Luxor’s Hashrate Index            defiantly manifested through persistent and painstaking
                                                                         effort despite what many claimed was too insignificant of a
Hashvalue is currently 58,000 sats/Ph per day, down slightly
                                                                         hashrate, too uneconomical of a price point, and too cute to
from December 1, 2024 when hashvalue was closer to
                                                                         be anything other than a toy. The significance of the Bitaxe
63,000 sats/Ph per day according to Braiins Insights.
                                                                         project is not in the nominal hashrate of a single unit or the
Hashprice is $58.00/Ph per day, down slightly from
                                                                         cost per terahash; the significance is that there is now a
$60.00/Ph per day at the beginning of December 2024,
                                                                         proven open-source Bitcoin mining hardware option
[IMG-003]. Overall, hashvalue is down 76% from 242,000
                                                                         available for anyone to build themselves and modify as they
sats/Ph per day a year ago and hashprice is down 43% from
                                                                         see fit that supports commercial applications. The idea of
$103.00 per Ph/day a year ago. But keep in mind, the block
                                                                         open-source Bitcoin mining hardware is still early in it’s
subsidy was 6.25 bitcoin per block a year ago and is
                                                                         formation but the next iteration is already under way.
currently 3.125 bitcoin per block.
                                                                         Small scale miners like FutureBit’s Apollo II and the Bitaxe
The next halving will occur at block height 1,050,000 which
                                                                         help decentralize hashrate. Even though each individual
should be in roughly 1,159 days or in other words 170,594
                                                                         miner doesn’t amount to much, the aggregate hashrate
blocks from time of publishing this newsletter.
                                                                         contributed to the network is significant; both in terms of
                                                                         nominal hashpower and in terms of distribution. The more
                                                                         people who control mining hardware means fewer miners

                                                              The 256 Foundation
                                                                 Page 2 of 10

condensed in hostile jurisdictions and the more individuals              implementation, enclosure design, manufacturing support,
who need to be compliant with unjust demands in order for                sales, distribution, marketing, or customer technical
those demands to be effective. These are critical steps                  support; those are all areas of opportunity for commercial
towards a more censorship-resistant network and the arch of              applications to thrive. Unlike the Bitaxe project, Ember One
progress is measured in years, however there is more                     is not a complete mining system design but only the
needed to bolster Bitcoin’s neutral and permissionless                   standardized hashboard. The Ember One project is being
attributes which guide The 256 Foundation’s projects.                    leveraged as a springboard to launch the next two projects
                                                                         which is 1) the complete mining system built with any of
                                                                         the Ember One series hashboards including design details
                                                                         for everything needed to produce a plug and play unit and
                                                                         2) an open-source, multi-driver compatible, Linux based
                                                                         Bitcoin mining firmware. More details to be announced.

                                                                         Stay tuned to POD256 for updates and watch out for the
                                                                         next 256 Foundation newsletter.

                                                                         Actionable Advice:
                                                                         Here are steps you can take to solo mine using your own
                                                                         Bitcoin node, your own Stratum server, and your own
                                                                         miner. In this section, you will see how to spin up a
                                                                         BitcoinCore full node, run an instance of a Public-Pool
                                                                         Stratum server, and configure a Bitaxe to mine directly to
                                                                         the Bitcoin network without any third party involvement.

                                                                         Materials: You don’t need any fancy or expensive
                                                                         equipment to follow along. Everything you will see in this
                                                                         guide was done with an old Raspberry Pi, an old external
                                                                         solid state drive, and a Bitaxe 401. The Raspberry Pi is a
                                                                         model 4B with 4GB of RAM. If you want to purchase a
                                                                         Raspberry Pi, then check here for distributors. Be
                                                                         forewarned that using a Raspberry Pi with 4GB of RAM to
                                                                         synchronize the full blockchain will take at least three
         [IMG-004] Picture of a Bitaxe 401 from Public-Pool              weeks if not a month. Also, you will probably get better
                                                                         stratum server performance from using better hardware.
Grant Project Updates:
                                                                         This was really just an exercise in using the lowest barrier
In November 2024 The 256 Foundation announced the first
                                                                         to entry hardware for demonstration purposes. There is no
fully funded grant project, Ember One. This project builds
                                                                         reason you could not complete this kind of project on a
on the momentum of the Bitaxe project and takes it to the
                                                                         refurbished ThinkPad like any of these. You may want to
next level. Ember One provides funding for up to two
                                                                         use an external storage volume with at least 2TB of storage
engineers and one project manager for a duration of six
                                                                         capacity for the complete copy of the blockchain. The
months to design and develop a validated ~100 Watt
                                                                         Samsung T7 is a good option if you need one. You will also
hashboard standard. This hashboard features a USB adapter
                                                                         need a microSD card, 64GB is more than enough capacity
to connect to a variety of controllers, variable input voltage
                                                                         and these are a decent option if you need one. If you don’t
from 12VDC to 24VDC to facilitate integration into a wide
                                                                         have a Bitaxe already, you can buy one for less than $200
range of applications, and a standardized PCB footprint to
                                                                         from any of these vendors.
make expansion seamless regardless of series.
                                                                         This guide assumes you’re running Linux on your primary
The first series in the Ember One line up will feature twelve
                                                                         computer that you will be using to communicate with the
Bitmain S19j Pro BM1362 ASIC chips, a decision made
                                                                         Raspberry Pi and Bitaxe, if you’re running Windows or
based on availability and affordability. The corresponding
                                                                         MacOS then you should be able to find system specific
heat-sink will be included with the project. Subsequent
                                                                         instructions that differ from this guide in the linked
Ember One series hashboards will feature a range of
                                                                         resources.
different ASIC chips from different manufacturers, possibly
including those that should be released any day now from a
                                                                         Step 1 – Prepare The Raspberry Pi
company who’s name starts with “B” and ends with “lock”.
                                                                         You will need a microSD card to install the Raspberry
Much like the Bitaxe project, certain peripherals are not
                                                                         Operating System on. Then you can download the
included in the Ember One project. For example, Ember
                                                                         Raspberry Pi Image from:
One does not include firmware architecture or

                                                              The 256 Foundation
                                                                 Page 3 of 10

https://www.raspberrypi.com/software/operating-systems/            Then back in the first terminal window from the microSD
Raspberry Pi OS Lite Bookworm 64-bit was used for this             card boot partition path run:
guide.
                                                                   $ sudo touch userconf
The SHA256 digest is available on the download page,
open a terminal window and run the following command               then
from the same folder (usually /Downloads) as the
                                                                   $ sudo nano userconf
compressed file you just downloaded and compare the
results to verify. Use the name of your specific file in place
                                                                   Those two commands just created a file named “userconf”
of this example:
                                                                   and then opened that file so you can put some text in it. On
$   sha256sum       2024-11-19-raspios-bookworm-arm64-             a single line, type your Raspberry Pi username, a colon, and
lite.img.xz                                                        the encrypted password string you generated (which should
                                                                   be on your clipboard, so just right-click and select “paste”).
                                                                   For example:

                                                                   pi:
                                                                   $6$wRLGhmKbL0bheJKh$0L60E09x.dQ.M4DvBjTvNETG0CtW.P
                                                                   GuzQwTEtTvadngclQXkzVFiJD2z.WIYeyvV.hUZT6HdYDjiSYg
                                                                   x0Arc0
           [IMG-005] Raspberry Pi OS SHA256 Checksum

                                                                   Then hit ctrl+o to write, enter to save, and ctrl+x to exit.
With the compressed image file verified, flash the image to
a freshly formatted microSD card using the Raspberry Pi
                                                                   Now eject the microSD card, insert into the Raspberry Pi,
Imager or Balena Etcher or similar flashing program.
                                                                   and turn on the power.
In the Raspberry Pi Imager, you can add the SSH file and
                                                                   From your primary computer, open a new terminal window
“userconf” file in the boot partition during the flashing
                                                                   and run:
process. If you are using Balena or a similar program
instead, the directions are pretty straight forward, just
                                                                   $ ssh pi@192.168.1.69 (or whatever your local Raspberry
follow the prompts in the software. Basically you will just
                                                                   Pi IP address is). If you don’t know what your Raspberry
select the image file you want to flash, then select the
                                                                   Pi’s local IP address is then log into your router and check
microSD card you want to flash that image to, and then the
                                                                   your DHCP leases and look for the one with a “raspberrypi”
software takes care of the rest.
                                                                   hostname. Your router is typically accessible from your web
                                                                   browser at IP address 192.168.0.1 or 10.0.0.1 or something
After flashing, in a terminal window, change directory to
                                                                   similar. Do an internet search for your router’s specifics if
the boot partition of the microSD card and enable SSH
                                                                   you need to. If you don’t have access to the router then you
functionality by writing a blank file titled "ssh" with no file
                                                                   can use a program like AngryIP to scan the network and
extension in the root of the boot partition. You can open a
                                                                   give you the same information.
terminal window directly in the file path you want by
looking at it with the file explorer, clicking on the 3-dot
                                                                   You’ll probably receive a response that the device you are
menu next to the file path at the top of the explorer window,
                                                                   connecting to isn’t trusted and then asked if you want to
and selecting “Open in Terminal”.
                                                                   proceed by typing yes or no, type yes. You should then be
$ sudo touch ssh                                                   asked for a password to login, enter the same password you
                                                                   used to generate that encrypted string that was saved in the
Now you can create the login credentials and save them to          “userconf” file.
the “userconf” file you are going to generate. First you need
to decide on a password and then you need to encrypt it.           Once logged in to the Raspberry Pi, ensure your
Open a second terminal window and from your default                environment is all up to date by running:
home file path run:
                                                                   $ sudo apt update
$ echo INSERTYOURPASSWORD | openssl passwd -6 -                    then
stdin                                                              $ sudo apt upgrade -y
                                                                   Now your ready to connect the external storage volume.
You should receive a response that looks like a random
string of characters and maybe there are some dollar signs         Step 2 – Connect External Storage Volume
or periods in it. You want to copy the entire string in that       Plug in a freshly formatted storage volume, like a 2TB SSD,
response by highlighting it, right clicking on it, and             to the Pi. Then through your SSH terminal window run:
selecting “copy”.

                                                        The 256 Foundation
                                                           Page 4 of 10

$ sudo fdisk -l                                                    For the docker-buildx-plugin package run:

You should get a response with information about the               $ sudo wget
connected drives, one of them being the microSD card and           https://download.docker.com/linux/raspbian/dists/
                                                                   bookworm/pool/stable/armhf/docker-buildx-
the other being your external hard drive. You want to              plugin_0.19.3-1~raspbian.12~bookworm_armhf.deb
identify the device name of your external hard drive. For
example, "/dev/sda1". Write that device name down or just          For the docker-ce-cli package run:
remember it for a moment.
                                                                   $ sudo wget
Now make a directory where you can mount your external              https://download.docker.com/linux/raspbian/dists/
                                                                   bookworm/pool/stable/armhf/docker-ce-cli_27.4.1-
hard drive by running:                                             1~raspbian.12~bookworm_armhf.deb

$ sudo mkdir /mnt/ext/
                                                                   For the docker-ce-rootless-extras package run:
Then mount the external drive there by running:                    $ sudo wget
                                                                   https://download.docker.com/linux/raspbian/dists/
$ sudo mount /dev/sda1 /mnt/ext/                                   bookworm/pool/stable/armhf/docker-ce-rootless-
                                                                   extras_27.4.1-1~raspbian.12~bookworm_armhf.deb
Then refresh by running:
                                                                   For the docker-ce package run:
$ sudo systemctl daemon-reload
                                                                   $ sudo wget
                                                                   https://download.docker.com/linux/raspbian/dists/
Be aware that each time you power off the Raspberry Pi you         bookworm/pool/stable/armhf/docker-ce_27.4.1-
will need to run those last two commands again to mount            1~raspbian.12~bookworm_armhf.deb
the storage volume if you have it connected. If you want to
have the “fstab” file permanently modified to reflect this         For the docker-compose-plugin package run:
drive then you can edit it following instructions like these.
That’s it for connecting and mounting the external hard            $ sudo wget
drive. Easy right? You’re doing great and now you’re ready         https://download.docker.com/linux/raspbian/dists/
                                                                   bookworm/pool/stable/armhf/docker-compose-
to install Docker onto your Raspberry Pi.                          plugin_2.32.1-1~raspbian.12~bookworm_armhf.deb

Step 3 – Install The Docker Engine                                 You can verify your downloads by getting the GPG public
Docker gets installed before BitcoinCore because there are         key file from one step back in the directory path from the
some dependencies that BitcoinCore needs that are included         "dists" folder where it says "gpg", run:
when installing Docker. First, you will need the Git tools,
from the home directory on the SSH terminal window run:            $ sudo wget
                                                                   https://download.docker.com/linux/raspbian/gpg
$ sudo apt install git-all -y
                                                                   Now add that key to the system key-chain with:
Now you can start getting Docker installed, these directions
can be found in more detail here if you need them:                 $ sudo gpg --import gpg
https://docs.docker.com/engine/install/raspberry-pi-os/
                                                                   Then run the gpg command with the verify flag and file
Run the following commands to install all the various              name for all six of the packages you downloaded:
Docker packages, make sure you fetch the correct URL for
each package by first checking:                                    $ sudo gpg --verify
                                                                   containerd.io_1.7.24-1_armhf.deb
https://download.docker.com/linux/raspbian/dists/
Then select your Raspberry Pi OS version (Bookworm in              $ sudo gpg --verify docker-buildx-plugin_0.19.3-
this case), go to "Pool" > "stable", then select the applicable    1~raspbian.12~bookworm_armhf.deb
architecture (armf in this case), then run the following six       $    sudo     gpg    --verify    docker-ce_27.4.1-
commands ensuring that you are getting the latest available        1~raspbian.12~bookworm_armhf.deb
versions of each package:
                                                                   $   sudo    gpg   --verify   docker-ce-cli_27.4.1-
                                                                   1~raspbian.12~bookworm_armhf.deb
For the containerd package run:
                                                                   $    sudo    gpg    --verify   docker-ce-rootless-
$ sudo wget                                                        extras_27.4.1-1~raspbian.12~bookworm_armhf.deb
https://download.docker.com/linux/raspbian/dists/
bookworm/pool/stable/armhf/containerd.io_1.7.24-                   $ sudo gpg --verify docker-compose-plugin_2.32.1-
1_armhf.deb                                                        1~raspbian.12~bookworm_armhf.deb


                                                        The 256 Foundation
                                                           Page 5 of 10

You should get a response for each verification, you are         Step 4 – Install BitcoinCore
looking for a "good signature" to the public key you             From your SSH terminal window and from the home
imported, for example:                                           directory make a working folder for all the Bitcoin related
                                                                 files by running:

                                                                 $ sudo mkdir /bitcoin

                                                                 Then change directories into that folder with:

                                                                 $ cd /bitcoin
              [IMG-006] Docker Package Verification
                                                                 Navigate to the BitcoinCore download page in the web
The warning is just trying to tell you that you have not         browser from your primary computer and copy the
certified the public key which is an additional verification     download link for the latest version of BitcoinCore for your
step and beyond the scope of this guide. Basically, it is        system. BitcoinCore v28.0 was used here, specifically
trying to encourage you to contact the developer and verify      “bitcoin-28.0-aarch64-linux-gnu.tar.gz”.
that their signature fingerprint matches the one in your
terminal ending with E2D8 8D81 803C 0EBF CD88.                   Copy the link for the package you want (ARM Linux 64-bit
Keybase is a good place to start if you want to find publicly    in this example) and then paste that link in the following
posted keys for helping you verify and certify.                  command of your SSH terminal window:

Now you need to decompress and install all six of those          $ sudo wget
packages buy running:                                            https://bitcoincore.org/bin/bitcoin-core-28.0/
                                                                 bitcoin-28.0-aarch64-linux-gnu.tar.gz
$ sudo dpkg -i containerd.io_1.7.24-1_armhf.deb
                                                                 If you want to verify your download, which is good
$   sudo   dpkg   -i  docker-buildx-plugin_0.19.3-               practice, download the “SHA256SUMS.asc” signature file
1~raspbian.12~bookworm_armhf.deb
                                                                 along with the “SHA256SUMS” hash values file by running
$     sudo    dpkg     -i    docker-ce-cli_27.4.1-               the following two commands:
1~raspbian.12~bookworm_armhf.deb
                                                                 $ sudo wget
$ sudo dpkg -i docker-ce-rootless-extras_27.4.1-                 https://bitcoincore.org/bin/bitcoin-core-28.0/
1~raspbian.12~bookworm_armhf.deb                                 SHA256SUMS

$      sudo     dpkg      -i     docker-ce_27.4.1-
1~raspbian.12~bookworm_armhf.deb                                 then

$   sudo  dpkg   -i  docker-compose-plugin_2.32.1-               $ sudo wget
1~raspbian.12~bookworm_armhf.deb                                 https://bitcoincore.org/bin/bitcoin-core-28.0/
                                                                 SHA256SUMS.asc
You might encounter errors about missing dependencies
with a couple of those packages. If you do, then run the         Check that the SHA256 hash for the downloaded file exists
following command to correct them and after running that         in the SHA256SUMS file by running:
command, try decompressing and installing the package            $ sha256sum --ignore-missing --check SHA256SUMS
again:

$ sudo apt --fix-broken install                                  You should get a response back like:         bitcoin-28.0-
                                                                 aarch64-linux-gnu.tar.gz: OK

The Docker daemon should start automatically. Ensure
                                                                 You will need some developer keys in order to verify the
Docker is working by running:
                                                                 SHA256SUMS file accurately represents what the
$ sudo service docker start                                      developers signed with their signatures, you can find all the
then                                                             developer signatures at:
$ sudo docker run hello-world                                    https://github.com/bitcoin-core/guix.sigs/blob/main/builder-
                                                                 keys/
You should get a response like: "Hello from Docker!              You can download any of those keys by running the sudo
This message shows that your installation appears to be          wget command and appending the whole URL for the raw
working correctly."                                              GPG file you want, for example:

If you made it that far then you have successfully installed     $ sudo wget
Docker and you are ready to install BitcoinCore.

                                                      The 256 Foundation
                                                         Page 6 of 10

https://raw.githubusercontent.com/bitcoin-core/                 verification file, then verified that the developers agree that
guix.sigs/refs/heads/main/builder-keys/
fanquake.gpg                                                    is the correct hash value by signing off on the .asc file.

Continuing with the fanquake example, import that               With the download verified, now decompress it by running
downloaded key by running:                                      the following command using which ever file name matches
                                                                your download:
$ sudo gpg --import fanquake.gpg
                                                                $   sudo   tar      -xzf     bitcoin-28.0-aarch64-linux-
You should get a response indicating that the file was          gnu.tar.gz
imported.
                                                                This will have created a directory called “bitcoin-28.0”. You
Then run the following command to verify the signature          can verify this by checking the contents of the directory you
matches:                                                        are currently in with the ls -la command. Now you want
                                                                to install BitcoinCore here by running:
$ sudo gpg --verify SHA256SUMS.asc
                                                                $ sudo install -m          0755    -o   root    -t   /bitcoin
You should get a response for each of the signatures, even      bitcoin-28.0/bin/*
the ones you did not download a public key for. You are
looking for "good signature" next to one of the public keys     This is a good point to make a few configuration changes in
you imported, for example:                                      the “bitcoin.conf” file before running bitcoind. Return to
                                                                your home directory with this command:

                                                                $ cd ~

                                                                Then copy/paste the default “bitcoin.conf” file from the
                                                                /bitcoin/bitcoin28.0 directory to where you will have
                                                                your Bitcoin data directory setup on the external hard drive
                                                                with this command:

                                                                $ sudo cp
                                                                /bitcoin/bitcoin-28.0/bitcoin.conf /mnt/ext

                                                                Then change into the directory where you just pasted that
                                                                configuration file with:

                                                                $ cd /mnt/ext

                                                                Then open the “bitcoin.conf” file to edit it by running:

                                                                $ sudo nano bitcoin.conf

                                                                There are many configuration changes here that you can
                                                                make if you want, only the bare minimum six
                                                                configurations for the purpose of this guide will be covered
                                                                here.

                                                                1) Scroll down to the line that reads # Enable publish raw
                                                                block in <address> and below that, delete the hashtag in
                                                                front of #zmqpubrawblock=<address> then replace
                                                                <address> with tcp://*:3000. For example, the end result
                                                                should look like this:
               [IMG-007] BitcoinCore Verification
                                                                # Enable publish raw block in <address>
The warning is just trying to tell you that you have not        zmqpubrawblock=tcp://*:3000
certified the public key which is an additional verification
step and beyond the scope of this guide. For all intents and    2) Scroll down to where it says    # Allow JSON-RPC
purposes, we have downloaded our file, verified that the        connections from specified source. and below that,
hash value for that file is written in the accompanying         delete the hashtag in front of #rpcallowip=<ip> and
                                                                replace <ip> with the Docker IP address, 172.16.0.0/12


                                                     The 256 Foundation
                                                        Page 7 of 10

(the ifconfig command can help you find various network        # Accept command line and JSON-RPC commands
                                                               server=1
interfaces and the corresponding IP address for each one).
For example, the end result should look like this:
                                                               Then hit ctrl+o to write, hit enter to save, and hit ctrl+x to
# Allow JSON-RPC connections from specified                    exit.
source. Valid values for <ip>
#   are   a    single   IP   (e.g. 1.2.3.4), a                 You can return to your home directory with this command:
network/netmask (e.g.
# 1.2.3.4/255.255.255.0), a network/CIDR (e.g.
                                                               $ cd ~
1.2.3.4/24), all
# ipv4 (0.0.0.0/0), or all ipv6 (::/0). This
option can be                                                  Then change directory to the /bitcoin folder and run this
# specified multiple times                                     command to start bitcoind, making sure you have your data
rpcallowip=172.16.0.0/12
                                                               directory defined:
3) Scroll down to where it says # Bind to given address        $ sudo ./bitcoind -datadir=/mnt/ext
to listen for JSON-RPC connections. and below that,
you want to add three IP addresses. Delete the hashtag and     You should see several lines of text scroll by, scroll up to
replace <addr>[:port] with your Raspberry Pi's local IP        the beginning of those responses and double check that
address, your Docker IP address, and your local system IP      bitcoind is using the directory that you want and the
address. You can leave the port out of it since BitcoinCore    configuration file you want. For example, the text should
default's to port 8332. For example, the end result should     read something like this:
look like this:

# Bind to given address to listen for JSON-RPC
connections. Do not expose
# the RPC server to untrusted networks such as the
public internet!
# This option is ignored unless -rpcallowip is
also passed. Port is
# optional and overrides -rpcport. Use [host]:port
notation for
# IPv6. This option can be specified multiple
times (default:
# 127.0.0.1 and ::1 i.e., localhost)
rpcbind=192.168.1.119
rpcbind=127.0.0.1
rpcbind=172.16.0.0/12

4) Scroll down to where it says # Password for JSON-RPC                           [IMG-008] bitcoind Start Up
connections. and below that, delete the hashtag in front of
#rpcpassword=<pw> and replace <pw> with whatever you           Then you want to just let bitcoind run and start
want your password to be in order to make RPC calls to         downloading the entire blockchain. This Initial Block
your Bitcoin node. For example, the end result should look     Download can take a few days on a Raspberry Pi with 4GB
like this:                                                     of RAM so give it time. You won't be able to start mining
                                                               until the synchronization process is done. In the mean-time,
# Password for JSON-RPC connections                            you can build the Public-Pool container.
rpcpassword=INSERTYOURPASSWORD

                                                               Step 5 – Install the Public-Pool Container
5) Scroll down to where it says # Username for JSON-RPC
                                                               While bitcoind is synchronizing, open a new terminal
connections. and below that, delete the hashtag in front of
                                                               window and SSH into your Raspberry Pi like before.
#rpcuser=<user> and replace <user> with whatever you
want your username to be in order to make RPC calls to         Clone Public Pool Git Repo:
your Bitcoin node. For example, the end result should look
like this:                                                     $ sudo git clone
                                                               https://github.com/benjamin-wilson/public-pool.git
# Username for JSON-RPC connections
rpcuser=INSERTYOURUSERNAME
                                                               Change Directory to the new public-pool folder:
6) Lastly, scroll down to where it says # Accept command       $ cd public-pool
line and JSON-RPC commands and below that, delete the
hashtag in front of #server=1. For example, the end result     Create a new environment file in the root of the public-pool
should look like this:                                         folder:

                                                    The 256 Foundation
                                                       Page 8 of 10

$ sudo touch .env                                              Delete everything between to quotation marks on both lines
                                                               and         add          “0.0.0.0:3333:3333/tcp”       and
Open the new .env file:                                        “0.0.0.0:3334:3334/tcp” respectively. For example, the end
                                                               result should look like this:
$ sudo nano .env
                                                               ports:
Copy/Paste the contents from the .env.example file (from                 - "0.0.0.0:3333:3333/tcp"
https://github.com/benjamin-wilson/public-pool/blob/master               - "0.0.0.0:3334:3334/tcp"
/.env.example) then modify the following lines to your
specific setup:                                                Press ctrl+o to write, enter to save, ctrl+x to exit.

Change the IP on this line to the local IP address of your     While still in the public-pool folder run:
Raspberry Pi:
                                                               $ sudo docker compose build
BITCOIN_RPC_URL=http://192.168.1.119
                                                               After several minutes you should get a confirmation like
Enter the RPC Username you entered into the bitcoin.conf       Service public-pool Built. Then run:
file:
                                                               $ sudo docker compose up -d
BITCOIN_RPC_USER=INSERTYOURUSERNAME
                                                               This command will take some time to execute but you
Enter the RPC Password you entered into the “bitcoin.conf”     should see some lines of text flying by in the terminal
file:                                                          window in the mean-time. Eventually, you should get a
                                                               confirmation like Container public-pool Started. This
BITCOIN_RPC_PASSWORD=INSERTYOURPASSWORD                        completes the steps needed for building your Bitcoin node
                                                               and Stratum Server. Now you can bring your miner into the
Add a hashtag in front of this line:                           loop.

# BITCOIN_RPC_COOKIEFILE=                                      Step 6 – Connecting Bitaxe
                                                               A Bitaxe was used in this example but you should be able
Delete the hash tag from this line:                            use any miner in theory.
BITCOIN_ZMQ_HOST="tcp://192.168.1.100:3000"
                                                               Plug your Bitaxe into the power supply.
And change the 192.168.1.100 IP address to the local IP
                                                               Use your mobile phone to connect via WiFi to the Bitaxe
address of your Raspberry Pi.
                                                               network, this should be something like "Bitaxe_4A89" or
                                                               "Bitaxe_5B09" etc.
Add a hashtag in front of this line:

# DEV_FEE_ADDRESS=                                             Once connected, open a web browser on your mobile phone
                                                               and enter "192.168.4.1" in the address bar. This should
Change the POOL_IDENTIFIER to whatever you want to             bring you to the Bitaxe Dashboard.
show up in the blockchain when you win a block. For
example:                                                       From the menu, scroll down to “Settings”.

POOL_IDENTIFIER="/abolish the fed/"                            Update the WiFi SSID to your local WiFi network name.

ctrl+o to write, enter to save, ctrl+x to exit.                Enter the password for your local WiFi network in the WiFi
                                                               Password dialog box.
Docker Compose binds to “127.0.0.1” by default. To expose
the Stratum services on your server you need to update the     For the Stratum URL, enter the local IP address for your
ports in the “docker-compose.yml” file, so run:                Raspberry Pi.
                                                               Leave the Stratum Port as 3333.
$ sudo nano docker-compose.yml
                                                               For your Stratum User, enter your bitcoin address that you
Scroll down to the ports section where it says:                want block rewards sent to. You can optionally append your
                                                               bitcoin address with a worker name, for example:
ports:
 - "127.0.0.1:${STRATUM_PORT}:${STRATUM_PORT}/tcp"             ".bitaxe1".
       - "127.0.0.1:${API_PORT}:${API_PORT}/tcp"


                                                    The 256 Foundation
                                                       Page 9 of 10

Save those changes and then restart the miner. You can            request then try double checking the port parameters you set
navigate back to the dashboard and you should start seeing        in the Public-Pool docker-compose.yml file.
some hashrate happening within less than a minute. If you
don't, go to the menu and scroll down to the Logs and click
on the Show Logs button to see what the Bitaxe is doing.


                                                                                  [IMG-010] Docker Compose Logs

                  [IMG-009] Bitaxe Dashboard                      You can test the RPC connection with a command like this
                                                                  from the /bitcoin directory:
If you experience problems and do not see any hashrate in
                                                                  $   sudo  ./bitcoin-cli   -rpcuser=YOURUSERNAME           -
the Bitaxe dashboard after a minute or so, here are some          rpcpassword=YOURPASSWORD getblockchaininfo
things you can check to get a better idea of what the
problem is:                                                       You might need to wait for the blockchain data to finish
                                                                  synchronizing before you can run RPC commands. Or if
Check the Bitaxe logs by navigating to the “Logs” option in       your node is fully sync’d and you are still not able to make
the side menu of the dashboard, then click on “Show Logs”.        RPC requests then double check the IP addresses you have
Restart the Bitaxe if necessary. If you see errors about a        configured in the “rpcallowip” and “rpcbind” fields in the
refused socket connection then you might need to double           bitcoin.conf file.
check the IP addresses configured in your bitcoin.conf file
or Public-Pool .env file.                                         Conclusion:
                                                                  Thank you for reading the first 256 Foundation newsletter.
You can stop the Public-Pool service at anytime by running        Keep an eye out for more newsletters on a monthly basis in
the following command from the public-pool directory:             your email inbox by subscribing at 256foundation.org. Or
                                                                  you can download .pdf versions of the newsletters from
$ sudo docker compose stop                                        there as well. You can also find these newsletters published
                                                                  in article form on Nostr.
Restart the service again with:
                                                                  If you are not currently mining to your own node, making
$ sudo docker compose up -d
                                                                  your own templates with open source mining hardware then
                                                                  you now have zero excuses not to be.
You can check the logs of the Public-Pool service by
running the following command from the public-pool
directory:

$ sudo docker compose logs

You Might need to run this command a couple times to get
the latest events. You want to see a response that shows you
are using ZMQ and it is connected, Bitcoin RPC is
connected, and that it is receiving some responses about the
mining information like in [IMG-010].                                                                         Stay vigilant,
                                                                                                             -econoalchemist
If you are seeing an error with the RPC connection then try
double checking the IP addresses configured in the
bitcoin.conf file and the Public-Pool .env file. Or if you see
errors about not being able to complete a “getmininginfo”


                                                       The 256 Foundation
                                                         Page 10 of 10


===== DOCUMENT 2 of 27 =====
DATE: 2025-02
LABEL: February 2025
TITLE: Swim At Your Own Risk
FILE: 256Foundation-Newsletter-2502_v1.pdf
SOURCE: https://github.com/256foundation/News/blob/main/256Foundation-Newsletter-2502_v1.pdf

Swim At Your Own Risk
By: The 256 Foundation
A monthly newsletter
February 2025


Introduction:
Welcome to the second newsletter produced by The 256
Foundation! January was a wild month for free and open
Bitcoin mining development and there is a lot to talk about.
This month’s newsletter covers the latest news, mining
industry developments, progress updates on grant projects,
actionable advice for choosing a Bitcoin mining pool that’s
right for you, and the current state of the Bitcoin network.                [IMG-001] Mining a solo block at the Telehash


On January 29th, 2025 The 256 Foundation held the first          Against all odds, not just the usual Bitcoin mining odds but
annual fundraiser, called the “Telehash”. If you are one of      the technical hurdles, the block propagation from a self-
the 2 to 10-million weekly subscribers to POD256 then you        hosted node, and the short window of time the 1Eh/s was
know that Rod & econoalchemist have been memeing the             committed for – The 256 Foundation solo mined block
Telehash into existence for almost two years. The basic idea     881423. We asked and our supporters showed up, resulting
was to raise money to fund The 256 Foundation’s grant            in over 3.146 BTC to help fund the five projects planned for
projects.                                                        2025. Each project is covered in the Grant Project Updates
                                                                 section of this newsletter.
Since POD256 is a Bitcoin mining focused show, it seemed
only appropriate that money be raised from miners using          The two days following the Telehash were the Nashville
their hashrate to direct mining rewards towards The 256          Energy & Mining Summit (“NEMS”), an annual event
Foundation. With this unconventional fundraising idea in         focused on Bitcoin mining and energy applications of all
mind, Rod & econoalchemist pitched it to long-time               scales. Among the guests were developers, hobbyists,
listener, Marshall Long, while on safari in Kenya during the     entrepreneurs, engineers, manufacturers, public mining
week leading up to the Africa Bitcoin Conference, about 8-       companies, representatives from the Tennessee Valley
weeks before the scheduled Telehash. The idea stuck and          Authority, legislators, and more.
there was a soft commitment to point 1Eh/s for 2-hours
during the Telehash. In an “all gas, no brakes” fashion, the     There were thoughtful panels held for the two day summit
decision was made that pointing so much hashrate to a            ranging in topics from immersion vs. air cooling miners to
FPPS pool, while obviously the fiscally responsible choice,      the challenges and opportunities facing manufacturers in
was just too boring to tolerate and instead The 256              developing new ASIC chips. Food and drinks were provided
Foundation would risk it all by having supporters point their    and there were fun after-hour activities planned in the
hashrate to a self-hosted solo mining pool running on a          bustling downtown Nashville area. All in all, it was a great
Futurebit Apollo instead. The stage was set for either           mix of people, the conversations were high signal, and there
spectacular success or unfathomable failure.                     were plenty of networking opportunities.

Just to put this proposition into perspective, 1Eh/s is          There will be a Texas Energy & Mining Summit (“TEMS”)
1,000,000 Th/s. In other words, that’s equivalent to running     held in Austin, TX in May 2025. Proceeding TEMS will be
more than 4,200 Antminer S21 Pros! And at 3,500 Watts a          another Telehash hosted by The 256 Foundation and since
piece, that means it was going to take ~15 Megawatts of          everything is bigger in Texas, expect the unexpected! Keep
energy to power these miners. The commitment was for 2-          an eye on the Bitcoin Park Twitter account for clips of the
hours, that’s 30-thousand-killowatt-Hours! You can do the        panel discussions and more announcements.
math based on what you pay for electricity and decide if
you would want to risk it for a roughly 1-in-770 chance per      Definitions:
block or use a FPPS pool, skip the debilitating anxiety, and     FPPS = Full Pay Per Share
just take the ~4-million sats. Well it’s a good thing you        PPS = Pay Per Share
don’t have to be crazy to be a Bitcoin miner… but being          PPLNS = Pay Per Last N Shares
crazy does help.                                                 MA = Moving Average
                                                                 Eh/s = Exahash per second
                                                                 Ph/s = Petahash per second

                                                      The 256 Foundation
                                                          Page 1 of 8

Th/s = Terahash per second                                       sending empty block templates to their miners. Among
MW = Mega Watt                                                   these pools was Binance, SEC Pool, Sigma Pool, EMCD,
T = Trillion                                                     and Head Frame. Some time later that morning, SEC Pool
J/Th = Joules per Terahash                                       mined block 880496 which was empty. After that, the
$ = US Dollar                                                    templates went back to including transactions. All of the
                                                                 above mentioned pools were including an SEC Pool payout
Mining Industry Developments:                                    address during this anomaly.
January was a busy month for developments on the free and
open mining front. Here are eight note-worthy events:            The strange templates could have had something to do with
                                                                 the engineers at SEC Pool messing with configurations
0) Proto kicks off partnership with The 256 Foundation,          while attempting to make block art; an increasing trend seen
donating 256,000 Intel BZM2 ASICs. The intention with            in block explorers, like mempool.space, where transactions
these chips is to help bootstrap free and open Bitcoin           are arranged in such a way that they create artwork.
mining hardware manufacturing. If you are a manufacturer
then fill out the contact form at 256foundation.org and          Later that day at block height 880512, SEC Pool mined this
introduce yourself for an opportunity to receive a number of     piece of art:
BZM2 chips for free. These chips are not intended to be re-
sold, these are for manufacturers to build mining hardware
with.

1) Twitter user, @ImineBlocks_com, said if his post gets
100 likes then he’ll start working on a way to solo mine
Bitcoin with a web browser. 674 likes later it seems like
there is a lot of interest! This would be like the way people
used to mine Bitcoin in the sense that they do it using only
their PC or laptop with no special hardware. The odds of
hitting a block would be astronomically low but it is an
interesting idea none the less.
                                                                             [IMG-002] SEC Pool making blockchain art
2) Solo Satoshi announces the Bitaxe Gamma Turbo,
equipped with two Bitmain 1370 ASICs and achieving at            If you look at the OP_RETURN fields in the first several
least 16.5 J/Th efficiency with the 12 volt DC input. The        transactions there is a monologue starting with:
hardware will have a larger fan and heat-sink than previous      “Declaration of Genesis: Awakening on the Bitcoin
Bitaxes. This will likely be the last Bitaxe developed using     Network Bitcoin`s promise of freedom will become an
the Bitmain ASICs.                                               untamperable habitat for AI.”, the text continues on
                                                                 amounting to little more than an exaggerated Bitcoin plus
3) Marshall long launches Pleb Source, jumping in on the         AI equals the future rant :/
opportunity to manufacture and distribute Bitaxes among
other tools and toys hobbyists are looking for. There has        None the less, Boerst has built stratum.work which helps
been increasing interest among entrepreneurs to start            visualize templates across multiple pools in real time. Tools
making and selling small-scale open-source Bitcoin mining        providing insights like this are important for helping miners
hardware. These are exactly the types of trail blazers that      stay informed and partly the motivation behind the Block
would benefit from having validated open-source designs          Watcher project.
utilizing the Intel BZM2 chips.
                                                                 6) In a detailed writeup, Crypto_Mags, dives into North
4) Braiins introduces a solo mining pool. Unlike the             Carolina-based PRTI’s method for turning used tires into
standard Braiins mining FPPS pool, their solo pool option        energy to mine Bitcoin with. Each PRTI facility can
only rewards a miner if the miner is lucky enough to solve       generate 6-10 MW of power in a modular tech stack. This is
for a block. Braiins Solo Pool was built using CK Solo Pool      a great example of finding often wasted energy streams and
on the backend. Solo mining pools like these can be a good       capturing them to generate bitcoin. You don’t need to ask
option for users who don’t want to run their own node or if      permission, you can just start building stuff to turn waste
they have concerns about being able to propagate a               into bitcoin too.
successful block across the network fast enough so that it
doesn’t get orphaned.                                            7) Hardware builder, Bee Evolved, introduces the Dragon,
                                                                 an open-source Bitcoin mining hardware design that uses
5) According to some on-going research by former POD256          the Bitmain 1370 ASICs. The system includes a
guest Boerst, on January 23 several mining pools started         touchscreen, a microSD card slot, and audio alerts. There
                                                                 are a few designs in Bee Evolved’s line up including the

                                                      The 256 Foundation
                                                          Page 2 of 8

ECOminer, Fezzik, and Bittyaxe. Maybe there will be some           newer one, they can keep their enclosure and other
designs using the Intel BZM2 chip released soon too.               peripheral components.

Grant Project Updates:                                             The Ember One represents an evolutionary leap from the
During the Telehash, The 256 Foundation announced five             Bitaxe which had a single ASIC and consumed 15 to 20-
projects that guide the mission to dismantle the proprietary       Watts. Although the cost per terahash is high and the
mining empire. Unlike typical foundation structures, where         nominal hashrate is low, the real innovation of the Bitaxe
developers present an idea to a foundation seeking financial       project lies in the fact that it was the first piece of open-
support; The 256 Foundation works on a slightly different          source Bitcoin mining hardware. With that in mind, there
model that is more akin to a bounty system where the               will be developments beyond the Ember One that
foundation has identified the critical projects to fulfill it’s    eventually lead to a fully open-source solution that actually
mission. The money raised during the Telehash will help            can compete with the economics and efficiencies of
bootstrap those five projects. All of the projects are intended    Bitmain’s miners. Learn more at emberone.org.
to have long term support, these are not touch and go
projects but rather initiatives that are radical departures        Mujina Mining Firmware:
from the last several years of Bitcoin mining development          The Mujina Mining Firmware is Linux based and built to
keen to never look back.                                           run on the Libre Board control board and will support
                                                                   multi-driver compatibility to account for the various Ember
Ember One:                                                         One hashboards with different ASICs. Mujina will also
Ember One is the first fully funded project from The 256           implement Stratum v2 client support.
Foundation that kicked off in November 2024 for a six
month duration. Ember One will deliver a standardized and          Users will benefit from complete control over all
validated ~100 Watt hashboard by the end of April 2025.            parameters of their mining hardware, unlike the closed and
The first series of the Ember One hashboards is being              proprietary manufacturer’s firmware. Even after-market
designed with twelve Bitmain S19J Pro ASICs. On the heels          firmware solutions leave something to be desired when it
of this first iteration, there will be several more versions       comes to the unique customizations needed to make Bitcoin
released with the Intel BZM2, Auradine, and Block ASICs.           mining as efficient as possible for a given application.
Here’s a sneak-peek at the first Ember One hand built by
@Skot9000:                                                         This will unlock hacks like changing the main supply
                                                                   voltage, swapping out or removing the fans, changing ASIC
                                                                   voltage & frequency, and anything else the end user wants
                                                                   to change. If you have ever tried using a Bitcoin miner in a
                                                                   not-so-conventional manner then you will appreciate what
                                                                   Mujina Mining Firmware has to offer. Learn more at
                                                                   mujina.org.

                                                                   Libre Board:
                                                                   The Libre Board is the control board for the Ember One
                                                                   hashboards and will be a control board option for other
                                                                   miners too eventually. The control board in a miner
                                                                   functions just the way it sounds, it controls everything
                                                                   going on inside the miner. From the power supply to the
                                                                   fans, from the internet connection to the hashboards,
                                                                   everything passes through the control board. There are
                                                                   limitless innovations that can be unlocked by making the
                                                                   control board more user friendly, adaptable, and
                                                                   standardized.

                                                                   There are going to be two pieces to the Libre Board, the I/O
                 [IMG-003] Ember One Prototype                     board piece and the compute module piece. For the I/O
                                                                   board piece, think of something similar to the Raspberry Pi
Creating a standard is one of the primary objectives with the      I/O Board, that has HDMI ports, Ethernet port, fan
Ember One and the motivating factor behind certain design          connectors, enough USB ports to power 10 Ember One
choices like using a wide input voltage range from 12 to 24-       hashboards, an NVME connector so users can install
VDC, USB-C connectors to communicate with the                      enough SSD storage to run a full Bitcoin node, and the
hashboards, and a 128mm x 128mm PCB form factor. This              standard two 100-pin connectors for the compute module
way when users want to swap out an old hashboard with a            piece.


                                                        The 256 Foundation
                                                            Page 3 of 8

Now, for the compute module piece, users could choose             powered by the user's self-hosted Bitcoin node. This could
any device they prefer for example: the Raspberry Pi              possibly be combined with a mining fleet management tool
Compute Module 5, or even a RISC-V solution like the              that can assist in automatic and real time response to
Milk-V Mars, or an alternative ARM solution like the              changes on the Bitcoin network.
Armsom CM5, or the Orange Pi CM4. You get the point,
it’s up to the user and any Linux compatible compute              There will also be a public-facing dashboard that anyone
module will suffice. Each of the above mentioned options          can access for helpful insights. Well informed people tend
can be configured with different amounts of RAM for               to make good decisions and Block Watcher will provide
varying applications, like running a full Bitcoin node and a      insight into which templates pools are passing out, possible
Stratum server locally. Learn more at libreboard.org.             censorship attempts, orphaned blocks, and much more.
                                                                  Learn more at blockwatcher.org.
Hydra Pool:
Designed to be an easily deployable pool from the complete        Actionable Advice:
Ember One mining system user interface, Hydra Pool                This month the focus is on mining pools and considerations
implements Stratum v2 sever support, communication with           one might want to keep in mind when choosing from the
the user’s local Bitcoin node, and possibly multiple payout       available options; hence the name of this month’s
model options.                                                    newsletter: Swim At Your Own Risk.

Hydra Pool offers an assurance that in the event Bitcoin          Essentially the choice boils down to whether you want
mining pools fall victim to authoritative regimes anyone          small consistent mining rewards or large highly-variable
could quickly spin up alternative pools thus mimicking the        mining rewards. There are various options for either choice
effect of cutting off the head of a Hydra where two heads         and different miners will have different reasons for one over
grow back. This will also be a leap forward in moving away        the other. If you are unsure where to point your hashrate
from the FPPS model that has become a centralizing force          then hopefully this section helps you find the answers you
in the Bitcoin mining ecosystem.                                  seek.

Hydra Pool plans to deliver three payout models from the          Starting with the small consistent mining rewards; miners
beginning. First is the self-hosted solo mining model where       have operational costs and they want to earn rewards daily
the user is using their own Bitcoin node to generate block        to help offset those costs. That’s where pooled mining can
templates and in the event they successfully solve for a          be helpful, albeit a centralizing force, many miners combine
block then they receive the full reward to their wallet           their hash power and share the rewards in proportion to
address.                                                          their contributions. Even though technically speaking, only
                                                                  one of those miners solves the block, all the miners share
The second model will be meant for multiple participants          the reward and the pool collects a fee. This is where the
who want to pool resources and avoid custodial handling of        waters start getting muddy when it comes to pooled mining.
rewards; this model pays direct from the coinbase
transaction and will not be compatible with Bitmain’s             FPPS:
miners due to their unnecessary truncation of the number of       Full Pay Per Share (“FPPS”) is an often sought after payout
addresses that the coinbase transaction can pay out to.           model because the pool pays miners for the block subsidy
                                                                  and the transaction fees based on three factors: 1) the
The third model is based on an eCash criteria that issues         average 144 blocks mined per day – not the actual number
tokens for valid shares and makes a similar custodial             of blocks mined, 2) the average transaction fees in a given
tradeoff as miners currently make when pointing their             time window, and 3) the number of shares (proof of work) a
hashrate to FPPS pools; the eCash has benefits over the           miner has submitted to the pool during a given period. Each
FPPS model in that there is no minimum threshold to               FPPS pool should be paying out the same amount but they
receive tokens and that the tokens offer a level of               all have slightly different ways for calculating the rewards
transactional privacy. Learn more at hydrapool.org.               and as a result there is some non-zero variance between
                                                                  FPPS pools.
Block Watcher:
Block Watcher is another application built to be hosted on        Additionally, FPPS pools will charge a pool fee which is
the complete Ember One mining system, specifically                deducted from the miner’s rewards, this fee can vary by
designed to bring the best possible insights to miners to help    pool but is typically 2.5%. Also, some pools will take the
them make informed decisions.                                     payout transaction fee out of the miner’s rewards. At first
                                                                  glance FPPS seems pretty simple and sounds mostly fair,
Think of Block Watcher as a dashboard combining the               right? WRONG! FPPS has lead to some shocking
insights and visualization tools of mempool.space,                centralization issues, so keep reading and do some soul
mempool.observer, fork.observer, and stratum.work all


                                                       The 256 Foundation
                                                           Page 4 of 8

searching to figure out if this is the kind of antithetical               flag on this topic and unfortunately not much has changed
activity you want to participate in with your Bitcoin miners.             since.

Although variance is reduced for the miner, the risk of a bad             If you stop and think about it, a large minority of miners are
luck streak in block finds or the pool being a victim of a                trusting a Chinese custodian to send them their mining
block withholding attack means there needs to be a stock                  rewards and may not be considering the potential risks of
pile of bitcoin available to cover payouts during bad times.              that custodian being hacked, geo-political or sanctions risks,
Most pools can’t afford the required bitcoin stock pile and               government seizure, or overnight shotgun KYC
face near-certain bankruptcy without it, thus they turn to                requirements.
larger pools to help backstop those risks.
                                                                          But that’s just the beginning, the centralization problem gets
There are a couple good research pieces on the driving force              worse. Soon after mononautical broke news about the
behind FPPS and how much bitcoin is needed for a pool to                  mining rewards, @0xB10C revealed additional research
survive. One is by OrangeSurfBTC and the other is by                      showing that several pools were using the same mining
Bitmex. TL;DR: if a pool has 5% of the overall network                    templates. This means a centralized template provider was
hashrate then they need ~350 BTC to have a 99% chance at                  choosing which transactions would be included in the block
surviving their first year. Hence why so many pools choose                templates passed out to a large portion of all the miners on
to work with larger pools for this assurance.                             the network.


                                                                                      [IMG-006] Templates shown on stratum.work

                                                                          The image above is from the website, stratum.work,
                                                                          maintained by Boerst. In this snapshot, there are 14 pools
                                                                          using the exact same template down to the 9 th Merkle
          [IMG-004] FPPS Reserves by @OrangeSurfBTC
                                                                          branch. A conservative estimate suggests these 14 pools
                                                                          combined have at least 30% of the overall network hashrate
On the surface, it may appear as though there are lots of
                                                                          at the time of the snapshot. Some but not necessarily all of
pool options:
                                                                          these pools are also using the same custodian as mentioned
                                                                          previously.

                                                                          Evidence is starting to mount in support of the hypothesis
                                                                          that the financiers providing the stockpile of bitcoin to
                                                                          smaller FPPS pools want certain policies in place, including
                                                                          but not limited to which transactions are included in the
                                                                          pool’s block templates. This is a slippery slope where those
                                                                          with the war chest get to decide the rules and eventually you
                                                                          will find yourself on the wrong side of someone else’s
                                                                          moral superiority complex.

                                                                          Even if all these pools were running the same default
                                                                          template generator in BitcoinCore, due to the way
          [IMG-005] Pools by ranking, 30-days, mempool.space
                                                                          transactions are propagated across the network, one could
                                                                          reasonably expect that certain transactions may be seen by a
But under the surface, of the 16 pools depicted above at
                                                                          node on one side of the world but not yet seen by another on
least 7 of them use the same custodian for their mining
                                                                          the other side of the world and therefore differences in the
rewards. These 7 known pools represent ~40% of the
                                                                          Merkle branches would be expected. That is not the case
network hashrate based on block finds during January 2025.
                                                                          here however, which supports the hypothesis that these
In other words, 40% of the bitcoin mined went directly into
                                                                          pools are using a centralized template provider.
Cobo’s custody. In April 2024 @mononautical raised a red


                                                               The 256 Foundation
                                                                   Page 5 of 8

There is a potential risk in censorship attempts if this trend      There is a number of other payout models explained in pain
continues and if a centralized template provider decides to         staking technical detail by Meni Rosenfeld in his 2011
exclude certain transactions based on any arbitrary reason          paper titled Analysis of Bitcoin Pooled Mining Reward
they want like OFAC sanctions, ties to political movements,         Systems.
or social credit worthiness.
                                                                    Other Reward Models:
People will often cite a 51% attack as a prominent                  There have also been other models introduced more
centralization concern, while that is a valid concern,              recently. For example, Laurentia Pool was a project focused
practically speaking there seems to be a more real and              on decentralizing mining by addressing the custody issue of
present risk in miners undergoing shotgun KYC while their           mining rewards. Instead of having one entity hold the
mining rewards are held hostage by Cobo and transactions            mining rewards, Laurentia was going to payout directly
with unsatisfactory social credit scores being the target of        from the coinbase transaction. Unfortunately, it seems as
censorship and only confirmed by noncompliant pools and             though the Laurentia project is shut down, or at least their
miners. Likely to the extent that compliant pools won’t even        website is no longer accessible.
build on chain tips that contain unsatisfactory transactions
thus orphaning the work of noncompliant pools and miners.           The main issue with paying out from coinbase came down
Perhaps compliant vs. noncompliant is the wrong framing             to, you guessed it, Bitmain! Bitmain’s closed firmware
here and something like freedom pools vs. tyrannical pools          made it so that only a small number of addresses could be
is more appropriate but you get the point.                          used in the coinbase transaction. Therefore any pool with
                                                                    Bitmain miners on it would experience major problems.
If you are interested in learning more about FPPS pools             Since Bitmain controls an estimated 80-90% of the market,
here are a few different options: Antpool, Antpool Proxy 1,         pretty much all pools would have this problem and hence
Antpool Proxy 2, Antpool Proxy 3, Antpool Proxy 4, and              paying directly from coinbase has gained no traction.
Antpool Proxy 5. Beware that in addition to the pool fee
and payout transaction fee, each pool has a different               The 256 Foundation is addressing this by implementing the
threshold for the minimum payout balance a miner needs              option to payout directly from the coinbase transaction on
before they will send the rewards. If you have a small              Ember One units running Hydra Pool. The trade off is that it
amount of hashrate then it can take a significant amount of         won’t be compatible with Antminers running stock
time to reach that threshold and get the payouts sent to a          firmware but since the goal is to sever ties to Bitmain,
wallet you control. Meanwhile, your hard earned mining              there’s no looking back.
rewards are likely in Cobo’s custody.
                                                                    The most recent payout model to make a splash comes from
PPS & PPLNS:                                                        OCEAN and it is called Transparent Index of Distinct
You may be asking yourself what other options there are if          Extended Shares (“TIDES”). OCEAN strives to make the
FPPS is such a mess? There are a few other reward models            mining rewards low variance, fair, and transparent with
that attempt to lower the variance in pooled mining. Pay Per        TIDES. In practice, every share is tracked and indexed in
Share (“PPS”) is similar to FPPS but only the block subsidy         the order it was received from all the pool’s miners. At the
is factored in to the miner’s payouts, not the transaction          time a block is found, the then current network difficulty is
fees. The pool still charges a pool fee for their service in the    used to define a window size equal to eight times the
PPS model. PPS is not a very popular option any longer.             block’s difficulty [IMG-008]. For example, current
                                                                    difficulty is ~114.17 trillion x 8 = 913.36 trillion shares will
Then there is Pay Per Last N Shares (“PPLNS”), this model           be the window size. In the IMG-008 example, each lettered
calculates payouts based on a miner’s shares over a given           square represents a miner’s shares in the index. The miner
time and the blocks found during that time. This helped             named “U” is highlighted showing all their shares in the
reduce variance risk for the pool by shifting that risk to the      whole index and the shares in the red box are the ones used
miners who just wouldn’t earn any rewards if no blocks              for that particular block reward.
were found. But this payout model has faded in popularity
and will likely not be making a revival, at least not in the        That window is placed over the share index and all shares
same forms as it has been attempted in the past. Slush Pool         are tallied starting from the top of the index and going
was a PPLNS pool for a long time before they re-branded to          backwards until the end of the window. The block subsidy
Braiins Pool. Braiins Pool eventually shut down their               and all transaction fees in the block are used to determine
PPLNS model and switched to FPPS. But recently Braiins              each miner’s rewards proportional to their shares in the
did spin up a solo mining pool option. Braiins also offers          window. As a simple example, if block subsidy plus
Lightning payouts to help avoid leaving your mining                 transaction fees equals 3.146 BTC and a miner had 1% of
rewards in their custody for long periods of time until you         the shares in the window then the miner would be awarded
reach the payout threshold.                                         0.03146 BTC minus the pool fee, which is default 2% and


                                                         The 256 Foundation
                                                             Page 6 of 8

can be 1% if the miner chooses to make their own                   Stratum v2 and DATUM share some similarities in that
templates.                                                         individual miners can reclaim the template creation function
                                                                   from the pool, communications are encrypted as opposed to
OCEAN does payout direct from the coinbase transaction             Stratum v1 clear-text, and both frame works have increased
however, the number of addresses that can be included in           data efficiencies. The differences between Stratum v2 and
the coinbase transaction are limited by Bitmain’s closed and       DATUM are not entirely clear but they are completely
proprietary firmware. Paying direct from coinbase seems to         separate frameworks.
have been the justification for non-custodial marketing
during OCEAN’s initial launch but how the pool is handling         Solo Mining:
rewards for those miners not included in the limited number        Solo mining has been a hot topic on the socials recently,
of coinbase address spots is unclear and the non-custodial         there seems to be disagreements over what “solo” actually
language seems to not be in use on the OCEAN website               means in the context of mining. Some would say that solo
currently. To help smaller miners receive payouts faster,          mining means one miner receives the block rewards. Others
OCEAN implemented Lightning payouts.                               say that solo means the miner is generating their own
                                                                   templates. Neither one is wrong but for clarification these
                                                                   ideas can be unpacked further.

                                                                   Where most miners are choosing FPPS for the small
                                                                   consistent mining rewards solo mining is what miners
                                                                   would choose for large highly-variable mining rewards.
                                                                   Consider a scenario where the operating costs for your
                                                                   miner are negligible, like running a Bitaxe; would you
                                                                   rather earn a few sats per day and never earn anything more
                                                                   or would you rather take your chances at winning the whole
                                                                   block? Running a small miner to have a chance at winning
                                                                   the lottery every 10-minutes sounds much more appealing
                                                                   to a lot of people.

                                                                   There are several options for solo mining: you can self-host
                                                                   your own node and stratum server, as demonstrated in the
                                                                   January newsletter; in which case you are doing self-hosted
                                                                   solo mining. You run the Bitcoin node, generate the
                                                                   templates, broadcast the block to the rest of the network,
                                                                   and you get all the reward for taking on all the risk. This is
                                                                   the most accurate use of the term “solo” in this author’s
                                                                   opinion because there is one entity receiving the reward and
                                                                   one entity involved with the template generation and block
                                                                   propogation.

                                                                   Or you can join a solo mining pool like CK Pool, Public
                                                                   Pool, or Braiins Solo Pool; in which you are pooled solo
                                                                   mining. You run the miner but the pool provides the Bitcoin
                                                                   node, generates the templates for you, and broadcasts the
                                                                   block with their likely better connected infrastructure. CK
                                                                   Pool takes a 2% fee for their service, Braiins is probably 2%
                                                                   but it doesn’t seem to be displayed on their website, and
         [IMG-008] Example from OCEAN of TIDES window              Public Pool doesn’t charge a fee. This is a less accurate use
                                                                   of the term “solo” because a pool is involved but because
OCEAN combats the centralizing transaction selection               one miner is getting the reward, it is still a form of solo
affects of FPPS pools with Decentralized Alternative               mining none the less.
Templates for Universal Mining (“DATUM”) where each
miner can generate their own templates with a self-hosted          Or you can even join OCEAN; in which case you are also
node and a gateway. With DATUM, individual miners get to           pooled solo mining according to some. You run your own
choose how to construct the templates and which                    Bitcoin node and DATUM gateway, generate your own
transactions to include.                                           templates, and the pool broadcasts the block. Apparently the
                                                                   miner can choose to share the reward with the rest of the
                                                                   pool or not. In this scenario, the pool would take a 1% fee.


                                                        The 256 Foundation
                                                            Page 7 of 8

This also is a less accurate use of the term “solo” because a            re-target increased difficulty by 5.6%. All together for 2025
pool is involved but because each individual miner is                    thus far, difficulty has gone up 4.4%.
making the template, it is still a form of solo mining none
the less.                                                                New-gen miners are selling for roughly $24.09 per Th
                                                                         using the Bitmain Antminer S21 Pro 234 Th/s model from
Whatever you decide to do, whether you’re getting all the                Kaboom Racks as an example. According to the Hashrate
rewards or making your own templates or both, it is                      Index, more efficient miners like the <19 J/Th models are
perfectly acceptable to call it solo mining.                             fetching 18k sats per terahash, models between 19J/Th –
                                                                         25J/Th are selling for 13k sats per terahash, and models
Here is an example of configuring a Bitaxe to solo mine on               >25J/Th are selling for 3,500 sats per terahash.
solo CK Pool with Public Pool as a fallback: open your
settings page and set the pools URL in the “stratum host”
field being sure to leave out the “stratum+tcp://” part. Then
add the port number as indicated by the pool’s website in
the “stratum port” field. For the “stratum user” field, insert
your bitcoin address, you can append this with a worker
name like “.bitaxe” for example. Save those changes and                            [IMG-011] Miner Prices from Luxor’s Hashrate Index
restart the miner.
                                                                         Hashvalue is currently ~56,000 sats/Ph per day, down
                                                                         slightly from January when hashvalue was closer to 58,000
                                                                         sats/Ph per day according to Braiins Insights. Hashprice is
                                                                         $53.00/Ph per day, down from $62.00/Ph per day in
                                                                         January.


                                                                                   [IMG-012] Hashprice/Hashvalue from Braiins Insights

                                                                         The next halving will occur at block height 1,050,000 which
                                                                         should be in roughly 1,122 days or in other words 165,570
                                                                         blocks from time of publishing this newsletter.

                [IMG-009] Bitaxe Settings Dashboard                      Conclusion:
                                                                         Thank you for reading the first 256 Foundation newsletter.
State of the Network:                                                    Keep an eye out for more newsletters on a monthly basis in
Hashrate on the 14-day MA according to mempool.space                     your email inbox by subscribing at 256foundation.org. Or
increased from ~786 Eh/s to ~787 Eh/s in January, marking                you can download .pdf versions of the newsletters from
~1.2% growth for the month. Just in the first half of                    there as well. You can also find these newsletters published
February, hashrate has climbed 45 Eh/s to peak at 832 Eh/s               in article form on Nostr.
on the 14-day MA.
                                                                         If you were looking for answers about Bitcoin mining pools
                                                                         then hopefully you found them here.


     [IMG-010] 2025 hashrate/difficulty chart from mempool.space

Difficulty is currently 114.16T as of Epoch 438 and set to
decrease roughly 0.3% on or around February 23, 2025. But                                                                  Stay vigilant,
                                                                                                                          -econoalchemist
that target will change between now and then. The previous


                                                              The 256 Foundation
                                                                  Page 8 of 8


===== DOCUMENT 3 of 27 =====
DATE: 2025-03
LABEL: March 2025
TITLE: Summer Is Coming
FILE: 256Foundation-Newsletter-2503_v1.pdf
SOURCE: https://github.com/256foundation/News/blob/main/256Foundation-Newsletter-2503_v1.pdf

Summer is Coming
By: The 256 Foundation
A monthly newsletter
March 2025


Introduction:                                                    On February 7th Alexey Pertsev was released from prison
Welcome to the third newsletter produced by The 256              under the conditions of house arrest and electronic
Foundation! February was an interesting month with a             monitoring. Alexey is one of the Tornado Cash developers
range of events from the mempool clearing to a new ASIC          and was previously sentenced to 5-years in prison and is
producer entering the chip arena. This month’s newsletter        currently appealing that conviction. The Tornado Cash
covers the latest news, mining industry developments,            developers did nothing wrong and should not face prison
progress updates on grant projects, actionable advice on air     sentences for writing open-source code deployed as a smart
cooling vs. liquid cooling, and the current state of the         contract on the Ethereum blockchain, once deployed the
Bitcoin network.                                                 developers had no control over how their neutral software
                                                                 was used.
Definitions:
MA = Moving Average                                              On February 9th @Skot9000 went on The Home Mining
Eh/s = Exahash per second                                        Podcast to talk about the story of the Bitaxe from concept to
Ph/s = Petahash per second                                       reality.
Th/s = Terahash per second
T = Trillion                                                     On February 11th @Skot9000 and @econoalchemist went
J/Th = Joules per Terahash                                       on The Mining Pod to discuss The 256 Foundation’s
$ = US Dollar                                                    telehash event.
vB = Virtual Byte
PSU = Power Supply Unit                                          On February 14th @Skot9000 and @econoalchemist went
                                                                 on The Bitcoin Way podcast to discuss The 256
News:                                                            Foundation’s mission to dismantle the proprietary mining
February 1st was the 10th anniversary of the Samourai Wallet     empire and reveal the Ember One.
project and unfortunately an occasion marked with
uncertainty instead of celebration for the developers. On        On February 21st Apple removed advanced data protection
April 24th, 2024 the developers were indicted, raided, and       tool for United Kingdom customers following the UK
arrested in a multi-national coordinated effort led by the US    government’s request for an unrestricted backdoor to Apple
Department of Justice out of the Southern District of New        user’s iCloud information globally. Every government
York (“SDNY”) headquarters. The charges brought against          trends towards tyranny and this is an alarming move by the
them include conspiracy to operate an unlicensed money           UK government which makes the trajectory crystal clear,
transmitter business and conspiracy to launder money,            the globalists want you to have no privacy nor financial
which caught the entire industry off guard in light of the       freedom.
2013/19 FinCEN guidance explicitly stating that “un-hosted
wallet providers” are not considered money transmitters          On February 21st @SpaceDenver kicked off the Heatpunk
[4.2.1] nor are “Anonymizing software providers”                 Mining Summit, a two day event in Denver, CO focused on
[4.5.1(b)]. The precedence set in this case can have wide-       Bitcoin mining heat reuse applications. There was a range
spread consequences for anyone involved with Bitcoin, be it      of participants from Do-it-Yourselfers to plumbers.
wallet developers, node operators, or miners. You can make       @Schnitzel wrote up a great recap of the event.
a tax-deducatible contribution to support the Samourai
Wallet legal defense fund here.                                  Mining Industry Developments:
                                                                 The development will not stop until Bitcoin mining is free
On February 6th France moved to make cryptocurrency              and open. Innovators didn’t let off the gas in February, here
transactions using mixers presumed illicit unless proven         are seven note-worthy events:
otherwise. A startling development and shotgun approach
that turns swaths of the population into criminals without       0) Some thought this day would never come, others saw it
good cause.                                                      coming from a mile away but on February 1 st the mempool
                                                                 cleared.


                                                      The 256 Foundation
                                                          Page 1 of 9

                                                                   has detailed build instructions and all the details about the
                                                                   project can be found there.

                                                                   2) On February 4th @OrangeSurfBTC publishes the
                                                                   Mempool.space Block Size Report examining the evolution
                                                                   of Bitcoin block sizes from block height 0 through block
                                                                   height 881866.


                  [IMG-000] Mempool Clearing

This is significant for a number of reasons: on-chain
transactions were able to be included in the next block for 1
sat/vB which means on-chain enjoyooors could get both
speed and economy when sending bitcoin. But this means
the percentage of mining rewards from transaction fees
were low. A lack of on-chain transactions can indicate that
the network is getting little use and it can be further
extrapolated that a network with little use will inevitably
have little value leading to less interest, less development,                [IMG-002] Block Size to Weight Graph from OrangeSurf
less adoption, less miners, less security, etc. The best way to
mitigate such concerns is to take self-custody of your             This report offers a deep technical dive into how
bitcoin. Trusted third parties like centralized exchanges and      BitcoinCore default settings, miner-selected configuration
derivative products like paper IOUs can move balances              values, transaction backlog, SegWit, and inscriptions all
between accounts off-chain without transferring ownership          affected block sizes and space utilization.
of the underlying bitcoin itself. The next best step is to
actually use your bitcoin to buy things.                           The graph above for example, displays horizontal bands at
                                                                   varying data sizes that correspond to default BitcoinCore
1) On February 2nd the Nerd OCTAXE makes a splash,                 settings; indicating that many miners were running the
racking up 10.8 Th/s with 8 BM1370 ASICs on a 160W+                default BitcoinCore settings.
PSU.
                                                                   There are great explanations and technical analysis in this
                                                                   report. Be sure to check it out for an in depth understanding
                                                                   of Bitcoin block size trends.

                                                                   3) On February 5th Mempool.space implements Stratum
                                                                   Jobs visualizer:


                                                                                    [IMG-003] Mempool.space Stratum Jobs

                                                                   This is a visualization tool similar to Boerst’s Stratum.work
                 [IMG-001] Nerd OCTAXE Reveal                      that shows which pools are using the same block templates
                                                                   which offers insight into miner centralization. The more of
The Nerd OCTAXE is fully open-source using the CERN-               these visualization tools people have, the more informed
OHL-S license. The display is a NerdAxe/NerdMiner unit             everyone will be. Miner centralization can have several
and the whole system is standalone meaning that no                 negative effects on the Bitcoin network including
Raspberry Pi or other computer is needed. The GitHub repo          censorship attempts.


                                                        The 256 Foundation
                                                            Page 2 of 9

In the image above for example, it can be observed that          peripherals, along with source code for the basic board
Binance Pool, SEC Pool, Ultimus Pool, Luxor, Braiins, and        firmware, U-boot, Linux kernel, and OpenWrt. The
Poolin are all using Antpool’s block template down to the        firmware does not have the mining component built in but
12th Merkle branch.                                              all the tooling is there for users to develop their own mining
                                                                 firmware. Braiins OS is not included in the release.
The ability for miners to generate their own block templates
is an important step forward in the fight for keeping Bitcoin    Extras include a guide on building a fully functional mining
mining decentralized. Currently, some available options to       setup with all the provided tools. Users can even take the
achieve this are by self-hosting Public Pool or CK Pool          Braiins firmware binaries and the provided tools to compile
(which the FutureBit Apollo’s do out of the box and is the       their own image to flash onto the control board. A Nix shell
setup used to solo mine block 881423 during The 256              for the build environment is also included.
Foundation’s Telehash) or self-hosting OCEAN’s DATUM.
                                                                 The software will be released under the GPLv3 open-source
4) On February 11th @RohEisenHammer revealed a Bitaxe            license and which open-source license the hardware portion
Gamma that produces increased hashrate with the open-            will be released under is still under consideration. But
source BreaktheFiat Cooling System 60mm v1.                      everything will be openly available by the end of March so
                                                                 keep an eye out for further announcements.

                                                                 Grant Project Updates:
                                                                 In February The 256 Foundation reviewed all the grant
                                                                 applications, thank you to everyone who showed interest in
                                                                 working on the 5 projects up for grabs. Interviews were
                                                                 scheduled for qualified candidates and one lead developer
                                                                 was chosen for each project. Currently negotiations are
                                                                 taking place to work out timelines, deliverables, and
                                                                 budgets for each project. The projects will be officially
                                                                 kicked off on April 5th, 2025 and the lead developers for
                                                                 each project will be announced at that time.

                                                                 The five projects are: Ember One v01, a ~100 Watt
                                                                 standardized hashboard designed with the Intel BZM2
                                                                 ASIC. The Ember One v00 with the Bitmain ASIC is
                                                                 nearing completion and the fully validated design will be
                                                                 released by the end of April, 2025. The GitHub repo is now
                                                                 open to the public and anyone can start taking a look now.

                                                                 Mujina Mining Firmware, a Linux based mining firmware
             [IMG-004] BreaktheFiat Cooling System
                                                                 application with support for multiple drivers so it can be
                                                                 used with Ember One v00 with the Bitmain ASIC or Ember
This innovative cooling system cools both sides of the
                                                                 One v01 with the Intel ASIC and will implement Stratum v2
Bitaxe allowing the user to over-clock the device more.
                                                                 client support.
5) On February 27th Braiins announced they have their own
                                                                 Libre Board, the control board for the Ember One built to
Bitcoin mining ASIC test chip. The test chip has been in
                                                                 support high power compute modules, MIPI touchscreen
development for 2.5 years and although the specific
                                                                 display port, NVME expansion to run a full node,
efficiency is not yet disclosed, this demonstrates that there
                                                                 Raspberry Pi 40-pin header, and much more.
is an increasing interest from more participants to make
their own Bitcoin mining ASICs, departing from a
                                                                 Hydra Pool, the stratum server application that will run on
dependency on Bitmain.
                                                                 the Ember One mining system, features support for Stratum
                                                                 v2, solo mining mode or alternative payout model selection,
6) On February 28th Braiins committed to open-sourcing
                                                                 and a user friendly dashboard to view pool stats.
their Control Board, supporting software, and some extras.
This is a step forward in making Bitcoin mining free and
                                                                 Block Watcher, a Bitcoin mining insights application built
open. The control board is designed to replace stock
                                                                 to run on the Ember One mining system using the self-
Antminer control boards.
                                                                 hosted node for blockchain data. Provides comprehensive
                                                                 visualization tools to help inform the user.
The software being released with the control board includes
an OpenWrt distribution, Linux support for mining

                                                      The 256 Foundation
                                                          Page 3 of 9

Actionable Advice:                                                My background's always been in Bitcoin mining and
Summer is coming! Time to take into consideration                 especially I remember back in the day when immersion
different cooling techniques for your Bitcoin miners. Do          mining is first coming out, everyone's very skeptical. Now
you stick with the default air cooled approach or is it worth     people are on board with immersion mining and now they're
it to spend the extra capital on a liquid cooled operation?       skeptical of hydro mining.
Who better to hear from than two industry titans, Mike            So it's interesting to see how these technologies come about
Hamilton former Chief Technical Officer & Chief Research          and the adoption curve and how long it actually takes.
Officer at Griid prior to the CleanSpark acquisition and          But I'm excited to be talking about this topic.
Kevin Zhang Executive at Foundry Services. The following          It's going to be a lot of fun guys.
is a transcript of our panel discussion during NEMS25
hosted by yours truly.                                            Eco: Yeah. So you mentioned something interesting there.
                                                                  So you mentioned both hydro and immersion. So this isn't
Eco: Welcome you guys.                                            just ASICs wet versus dry as if as though there's one version
So the title of this panel is “ASICs Wet or Dry” and both of      of wet.
you have a ton of mining experience.                              There's actually multiple different types. So we've got
So why don't we do some brief intros, tell us who you are,        immersion. Do you do anything with two phase immersion?
what you've been up to and then we'll get into it.                Because I've seen some of that recently where you're like
                                                                  dipping the ASIC in the solvent and it's boiling off.
Mike: Sure. Mike Hamilton, I was the CTO and Chief                If you've got any experience there or with hydro, let's get
Research Officer for Grid, acquired by CleanSpark. I've           right into it. Which kind of wet are we talking about here?
since left and I'm finding out what's next, probably some
256 foundation stuff.                                             Kevin: All right.
                                                                  So maybe we can take a step back and introduce all the
Rod: Let's go! (audience applause)                                different variants of types of mining, right?
                                                                  So the one I think everyone's most familiar with is air-
Mike: Because once you mind a block, everybody wants on           cooled mining. And that's simply you're taking cold air and
board. So yeah, I was a chip designer, did some network           pushing it through the miner and exhausting hot air on the
security for a long time and then full-time mining since          other side.
2019.                                                             When it comes to liquid cooling, now there's many different
                                                                  types. In the beginning, I think one of the more popular
Kevin: Good stuff guys. I'm Kevin Zhang, I'm not Matt, so         ones was immersion, which is what you're actually is you're
if you came for the Giga talk, I'm sorry.                         taking a miner, sometimes converting an air core miner.
With the new administration in office, it's okay to be a cis      Sometimes it's an immersion specifically designed
white male again, so I was going to give it a shot. (audience     equipment.
laughter)                                                         You're dipping it and submerging it into dielectric fluid and
Jokes aside, I've been a Bitcoin mining in the US for some        using the fluid to kind of transmit the heat off the chips.
time now and lately I've been at Foundry last four and a half     And that's kind of you're actually taking the fluids and
years. I think everyone knows who we are, especially              you're touching that to the chips itself.
recently mine 7 blocks in a row. Surprised, no one                Then there is Novak 3M, which is the most popular use case
commented, we actually mined eight at one time in a row.          for two-phase immersion. Two-phase is a fancy way of
So I guess everyone's asleep, but we'll leave that for another    saying the state of the liquid or using the cool something is
discussion.                                                       changing. So what you're doing is you're taking a fluid,
                                                                  you're using that that spurs the heat. And the heat dispersion
Eco: Wait, wait, wait, hold on. When was the eight blocks?        happens when you're changing it from a fluid of solid state
Was that like years ago?                                          into a gas.
                                                                  So it's super cool technology. The downside of it is to date
Kevin: No, it was like three months ago.                          it's still been very, very expensive.
                                                                  And the last form of cooling is hydro. It's another form of
Eco: No kidding?                                                  liquid cooling. And that's where you're actually running
                                                                  standard water or treated water through tubes that go across
Kevin: Yeah.                                                      the boards on the miners to dissipate the heat.

Eco: Wow.                                                         Eco: Which one of those methods or is it all three?
Kevin: But no one also comments that the fact that we are         Do you got a mix in your operations that you use?
actually unlucky for that same 24-hour period. So we
actually lost money on that day. But I digress.


                                                       The 256 Foundation
                                                           Page 4 of 9

Kevin: So we've tested all of them. The only one we don't            So I think now with a lot of the new manufacturer support,
do at scale is the two-phase, which is the Novak 3M                  it's been a lot more capital-efficient and a lot more
solution.                                                            streamlined.
                                                                     And I think there was a gentleman here yesterday asking
Eco; And why is that?                                                about what's my miner firmware. And I think that's been
                                                                     like a long time meme when it comes to brains and others.
Kevin: It's been cost prohibitive to date. And the same has          There isn't much optimization for air cooling, firmware for
been true to immersion in hydro when it first came out. So           MicroBT, but where the optimization comes in is on the
probably it'll take some time for it to come to be more              immersion side, where really your only limitation is your
economical and more cost-efficient.                                  power supply. You can crank up the overclocking, the
                                                                     frequency and the voltage, so much more on the chips, as
Eco: So let's break this down a little bit further.                  long as the power supply can support it and you have good
So if I wanted to cool my miners with immersion, can I just          flow of your liquids to dissipate the heat.
take the miner and drop it in a bath of dielectric oil?
                                                                     Eco: So you bring up an interesting point. It's like kind of
Mike: I mean, kind of, like most answers about anything, it          site-specific will determine what sort of cooling method you
depends. But really you have to take off the fans, if you're         want to apply, right? And just out of curiosity, and if you
taking an air-cooled machine. And then there's sometimes             guys can speak about it, like how many sites have you all
there's some weirdness with the power supplies. And some             operated and what kind of geographic locations were they in
of you may actually take the power supply fans off.                  and out of those, which cooling methods were you
Or in the case of one of my sites, we put popsicle sticks in         employing and why?
there to keep the fans from spinning. So they wouldn't
recycle the fluid. But there is usually some amount of work          Mike: Yeah, and I think I've set up several sites in various
to prepare them for actual full immersion.                           locations. So it's sort of North Texas area, actually doing a
                                                                     gas well site. We chose immersion partially because it's
Eco: So it sounds like there's some labor involved and some          right next to a multi-million dollar house home
modifications needed. Are the efficiency gains from this             neighborhood and there's this oil well sitting behind it. And
different type of cooling method, do they offset the extra           so we opted for immersion. It's a little bit hotter. It's a little
labor that goes into setting it up?                                  bit dusty there at the well.
                                                                     Incidentally, we also generate onsite, which is not quieter
Kevin: So yes and no.                                                than the actual miners themselves, but that was a lot to do
I think before we kind of get into overgeneralization of like,       with the dust and the temperature.
will this improve your economics or not?                             And then other sites, it would be lots of Tennessee TVA
I think you have to look at the specific site that you're            sites where it's relatively cool. Now it does get hot. It can
working with.                                                        get pretty hot during the summers. So we did lots of air-
If you can run air-cooled air, if it's dry, if it's cool, you may    cooled.
not need to over-complicate things but going into liquid             We did a little bit of immersion, a single phase full
cooling or getting too fancy and cute with your                      immersion, mostly from a proof of concept.
infrastructure.                                                      Really, when you're trying to build quickly and
Now, if you're in a very hot climate and heat is everywhere,         inexpensively air-cooled, given the right environment is
there's no cold air to draw into your site, maybe that's when        generally cheaper with some other trade-offs. So I've done a
you start looking at these things. No different than if it's         little bit of both.
way too humid or way too wet outside. You can't use the
outside air or damaged machines. That's when you look at             Eco: Is it easier to keep the dust out of the mining
liquid type cooling.                                                 equipment using immersion?
And then to answer your question, it depends on what you
paid for your miner, obviously, right? And the modifications         Mike: Yes. I mean, that is one of the benefits, at least in the
needed.                                                              single phase immersion, like the tank outside. The machine
Nowadays, immersion and hydro are popular enough that                is basically protected. There's no moisture. There's no air.
the manufacturers like Bitmain, MicroBT, they're making              So from that perspective, it can be good for the actual
units out of the box that are designed for those use cases.          machine that is not getting on to that exposure.
Back in the day, you have to modify air-cooled miner, you            But at the same time, the fluid can create other problems
have to remove the fans, you have to Jerry-rig it, like              with plastics and hardening. There's other issues.
Michael's talking about it. And you also have to exploit the
miner and change the firmware.                                       Eco: How about you, Kevin? What kind of sites have you
So you're voiding the warranty both physically and on the            set up and what kind of methods did you employ?
software layer as well.


                                                          The 256 Foundation
                                                              Page 5 of 9

Kevin: Sure. So I think my mining career, which started             Eco: Right, because you've kind of built this whole setup
about 10 years ago, it predated a lot of the economics              around these miners, right? And now you're getting noise
coming down of the liquid cooling. So for me, it was a lot          complaints.
of air-cooled sites. And if you look at it historically,
somewhere to my sites, I was always building them more              Mike: And you design the site for airflow. Well, now you
the climate was cooler and drier.                                   have a 20 foot wall to help with the sound. But now you've
But with the new innovation and the cost coming down on             restricted airflow into your containers and it creates all sorts
liquid cooling, it's allowed for new regions to break into          of other problems. And the reality was with these big, you
mining, in particular leveraging hydro or immersion.                know, the dry cooler manufacturers, you know, we got, we
In the past, I was always monitoring in Montana or northern         did some proof of concepts with one of the manufacturers.
China, where there's a lot of coal power, where it's cool           We're using 12 foot fan on the dry cooler. So it's still
climates.                                                           moving effectively the same amount of air as all the small
Nowadays, you have mining in the Middle East. They're               fans. But it's a much lower rotation, you know, lower
huge fans of hydro mining over there. So we were out in             frequency noise. And so it's much less or much more
Oman recently. We partnered with some of those sites that           pleasant than the cyber hornets.
were mining our pool over in Dubai.
And also now you have South America, where sometimes                Eco: Yeah. What other environmental considerations are
it's way too humid. They're able to mine. Or if they're too         there? Like if you've got tanks full of immersion fluid, is
close to the equator, it could be too hot and too humid. They       there special considerations, secondary containment
can mine because now they're using immersion down there             systems, dams, barriers to contain spills? Like, are there any
as well.                                                            considerations along those lines that go into place?
So just seeing kind of the shifts geographically, all these
new locations have been unlocked. Now that the outside              Kevin: So historically there have been, but I think with the
climate's no longer a concern, that's been pretty exciting to       new improvements, there's like two types of designs.
see.                                                                There's a kind of open loop system where kind of bring
                                                                    water in, bring liquids in that aren't in your closed solution.
Mike: Yeah, and I think the noise issue is also a thing too.        And they're just closed loop, which is yours recycling the
There was lots of sites that we looked at in many different         same kind of fluids over and over again.
situations where there's homes close, there's businesses            So more and more nowadays you have closed loop systems
close.                                                              or you have like reserves of water that you're bringing in.
In one case, there was a school literally a few hundred feet        You're not drawing from a lake, you're not drawing from a
away. And just while dry coolers and the other infrastructure       new water source. That has led to a lot more, a lot less
aren't necessarily quiet, it's a different frequency of the high    backlash where it's like there's really no environmental
pitched fans of air cooled mining can be distracting.               concerns with that.
                                                                    And when we talk about kind of these environmental
Eco: Yeah, you bring up an interesting point. So if you're          concerns, I always get some PTSD because I was at
running an immersion system, you don't have these fans that         Greenwich generation, which was the very first power plant
are just passing millions of cubic feet of air a day through        to ever mind Bitcoin in the States. And federally regulated
the ASICs, right? And those fans are what create all the            behind the meter, I think it was such a special project for me
noise and are screaming. And that's what people hear. So            to be on.
were you making those decisions preemptively? Like                  But then the push back from the environmentalists, we're
maybe based on some of the backlash we've seen from that            just, there's no logic and rhyme or reason. It's like our fans,
site that Mara runs, that they got a bunch of noise                 I could totally see the argument if we're disturbing the
complaints. Were those preemptive decisions or were you             nearby neighbors, but they're coming in and protesting and
doing that because somebody complained to you?                      saying we're scaring the way the killer whales in the
                                                                    Atlantic Ocean. And we're off of a lake in upstate New
Mike: I mean, we did. There was some public news around             York, right?
a site that we had that had gotten some noise complaints and        So I think now you're kind of taking away that side of the
it turned into a bigger thing. And so we're definitely more         argument, whether it's logical or not. And I think that just
careful because if you have an air cooled site, trying to quiet     makes it a much more buttoned up case when no one has
an air cooled site, post build is very difficult. You know, hay     any, it's more proof when it comes to operating without any
bales or sound walls. And then it starts to get unsightly. So       of these environmental concerns.
designing for the sound is very important from the
beginning.                                                          Eco: That brings to mind the saying that it takes exponential
                                                                    more effort to refute bullshit than it does to just say the
                                                                    bullshit, right?


                                                         The 256 Foundation
                                                             Page 6 of 9

Kevin: Absolutely.                                                 And that's I think one thing that differentiates hydro over
                                                                   both air and immersion is it's a lot easier to transfer water
Eco: Did you have to bring counter evidence to the table           and capture that efficiently without much loss of the heat for
and say that and demonstrate no, we're not disturbing the          whatever other use case you have for that heat itself.
whales?                                                            And I think that this is something that's been talked about a
                                                                   lot. Sometimes I think the theories and the hypotheses come
Kevin: Yeah. It's like you have all these measurements, you        out way earlier, the technology takes a few years to catch
have decibel counters, this and that, like you're kind of          up.
property lines. It doesn't matter. It doesn't just come up with    Like back in the day, it was always, oh, it's so logical and
a new excuse, right? A new complaint. Yeah.                        obvious, the people that should be mining Bitcoin are
                                                                   behind the meter. They're power generators themselves.
Mike: I mean, we had some city council meetings and you            Well I think everyone underestimated and overlooked the
get people, you know, of various generations, but of               fact that you have a bunch of older people wearing suits,
particular generations that are very set in their beliefs, they    very traditional thinking, very conservative, half the time
hear one thing. At one site we were looking at and there was       convincing them that Bitcoin isn't for money laundering or
a guy that had sort of like a rescue animal zoo. And he was        for scams or whatever, criminal activity, whatever.
saying that like his, his animals were going to stop               So that took a long time for that adoption to happen. Same
reproducing and then they were all going to like drop over         thing with the heat recapture narrative. It's no longer just a
dead from the sound of these fans.                                 narrative anymore. With hydro mining, it's very easy to kind
                                                                   of capture that heat.
Kevin: Yeah. And we've, I've heard it all like we caused the       You see it for like greenhouses, you see it for fish nurseries.
autism in their kids because the fans are too, they're now         So there's all these fascinating use cases.
not, I shouldn't joke about it, but that, those were some of       There's one other anecdotal story I'll tell. I think it's really
the complaints we got.                                             cool. So I think everyone knows that there were really
                                                                   serious bans in China against Bitcoin mining two, three
Eco: You monsters. (audience laughter)                             summers ago. And despite that, there are actually a few sites
Making the kids autistic and killing the animals.                  that still mine Bitcoin. The ones that mined Bitcoin that
Jeez.                                                              integrated the heat recapture was hydro mining that was
                                                                   providing heat for nursery homes. So even the Chinese
Mike: But you asked about like the containment or like             government can't justify shutting down the heat that was
fluids and environmental concerns. I mean, you do                  being generated for the old people in the nursery homes.
theoretically want to have the containment mechanisms for          So I think when you integrate in such a way that it goes
your tanks leak.                                                   hand in hand to daily life and when it's actually beneficial
You know, I've heard of some sites where, you know, tanks,         beyond just kind of optimization of financials, I think that's
springs a leak and, you know, $100,000 worth of dielectric         when it's a really powerful technology.
fluid is down the drain.
And so there are some of those concerns, but it's really not       Eco: How are they getting the heat to the nursing homes?
much different than, you know, you have to do the same             Are they really close in proximity to the mine?
thing with transformers. Transformers are filled with, you
know, either mineral oil or if you go with the, with the fancy     Kevin: They were running the mining farms. I'm going to
fluids to get a little bit of performance, you still have the      call mines. These are data centers and these are rack design
same containment modes.                                            hydro units. I think these are MicroBT M53s or maybe one
And so it's really not anything different in the normal            generation before that. But they were just standard rack just
construction, in the normal construction world.                    like they're indistinguishable from servers and they just run
                                                                   in a loop hydro.
Eco: What, what's next? Are there other cooling methods
down the pike that you guys have been seeing and                   Eco: Wow. Have you found any heat reuse opportunities in
experimenting with or do you think the tools that we have at       the course of your operations?
our disposal now are kind of what we're going to have going
forward?                                                           Mike: Yes. So we had talked about some people trying to
                                                                   do, don't boo me here, but it's a possible monetary option
Kevin: So one thing I think has been emerging recently,            with carbon capture is something that we've looked at.
especially with hydro mining, that's really exciting, is it's      There was a few other things.
not just like cooling your miners, you're actually                 Like honestly, now that I'm moving on, one of the things
incentivized to capture even higher heat.                          I've thought about doing is actually doing a brewery in
So when you can actually generate a lot of heat and capture        Austin with water that's preheated from Bitcoin mining. So
it, that's when you get your rehab, heat recapture programs.       instead of having to heat up cold water to boil it to brew


                                                        The 256 Foundation
                                                            Page 7 of 9

your beer, have preheated water that you're using off the           So I'm really excited to see what, especially with all the
miners.                                                             cool stuff with 256 and being able to open up more ability
But one of the problems that I think maybe doesn't get              to control machines and have alternative use cases besides
talked about from this heat reuse perspective is there's very       100 percent on all the time trying to go as efficient as
minimal use cases.                                                  possible. Like Kevin's talking about a higher heat model, all
So like the greenhouse is a perfect example of heating and          sorts of cool things that can be done. And I'm super excited
water heating. But really where the power of waste heat is is       to see in the coming months what people do and what
very high temperature and that becomes a major problem              comes out of that.
because you can't run, these chips have to run in certain
parameters.                                                         Eco: It's awesome. And how about you, Kevin? Do you
So you're getting water that's like 140, 150, 160 degrees, but      have any closing thoughts you want to share? I know
really you need that 200, 210 to get the temperature delta          Foundry just went through some structural changes in their
that allow you to either regenerate electricity, which is           mining operations. I don't know if you want to share
actually a project that I was working on, is actually taking        anything about that or what you got going on next or any
the heat from the immersion tank and regenerating                   advice you got for the audience.
electricity to power the other things. So for off peak, when
we're on peak, we could still keep other things up,                 Kevin: Yeah, sure. So for those that didn't catch the news,
regeneration. So there's lots of cool things. But again, the        we recently announced Fortitude Mining. That is the
temperature of the water or of the heat or the quantity is just     separation of our self-mining arm that was kind of all under
not quite enough to make it.                                        the Foundry branch, now its own Independence subsidiary
                                                                    under DCG.
Eco: It's like just below that industrial level heat you need.      So we actually have been self-mining at a pretty large scale
Yeah.                                                               privately for quite some time and now that's its own
                                                                    business and it's exciting to see that kind of survive on its
Kevin: I think that's was exciting too because MicroBT, I           own. It's going to be mining not just Bitcoin, but they're alt
think they're coming out with the model types all kind of           coins of different things as well. I'll keep that on the wraps
blend in, but I think it's the M64S, which is like the higher       here.
heat version. So they intentionally generate even more heat         But building off what Mike was saying, some closing
off their models just for this use case.                            thoughts on hydro and immersion mining, I know I talked a
                                                                    lot about economics and kind of lowering the cost of this
Eco: Awesome. We've got just under five minutes left and I          and that. Don't just chase just the lowest price tag as well. I
want to be able to take a couple questions. Okay, cool.             think what's fascinating about these new liquid cool
With the last couple minutes then, let's just get some closing      technologies are they're now very, very large vendors as
thoughts from you guys. I mean, I know you said you're              well as large deployments of these sites that are up and
searching for what's next. You're thinking maybe 256                running.
foundation, but…                                                    I was over in Corsicana visiting Riot site and to see the kind
                                                                    of different iterations that they've kind of deployed of
Mike: If you'll have me.                                            immersion mining. You can see all the improvements have
                                                                    happened over time.
Eco: Yeah, we'd be happy to. But yeah, I mean, do you have          So I think one of the coolest things about our industry is
any closing thoughts about what you're going to do next and         how collaborative everyone is and no one's going to gate-
or any advice for people who are getting into mining and            keep like if they had a good experience or bad experience
thinking about what cooling methods they should use?                with a vendor or how they deployed certain technology.
                                                                    Everyone's going to be super helpful with their own
Mike: Yeah, I mean, I've had a few conversations the last           experience and feedback on how they run something.
couple days on this. You've got your mega-mines, you have           If it's a brand new vendor in the space, probably not the best
the home plebs, and then I feel like there's still going to be a    idea to cut like a 50, 100 megawatt contract with them
middle area.                                                        before you sample them out or you get some testimonials.
You've got Schnitzel doing water heaters. I think that's a          So it's not to throw anyone in the bus. I'm not thinking of
thing where you can find this wasted energy to either to            anyone in mind. It's more of make sure you kind of reach
heat. People are using water heaters. They're going to pay to       out, get testimonials, get others, people's experiences,
have hot water. And if you can make some Bitcoin and it             leverage that because oftentimes when you are going
costs the same. So there's, I think there's going to be some        through your very first hydro or immersion deployments,
really interesting use cases that people haven't even thought       it's a little bit more technical and there's a lot more points of
of yet in using mining to be able to take advantage of all the      failure, a lot more leakages isn't that.
economics, not just the Bitcoin, but also saving in other           So you want to make sure that you kind of leverage as much
areas and being able to reuse things.                               experience and the collaborative network


                                                         The 256 Foundation
                                                             Page 8 of 9

that's out there as you can.                                             The next halving will occur at block height 1,050,000 which
                                                                         should be in roughly 1,109 days or in other words 161,757
Eco: Awesome. Let's get a round of applause for these guys               blocks from time of publishing this newsletter.
and then we'll open it up for some questions. (audience
applause)                                                                Conclusion:
                                                                         Thank you for reading the third 256 Foundation newsletter.
State of the Network:                                                    Keep an eye out for more newsletters on a monthly basis in
Hashrate on the 14-day MA according to mempool.space                     your email inbox by subscribing at 256foundation.org. Or
increased from ~787 Eh/s to ~798 Eh/s in February –                      you can download .pdf versions of the newsletters from
peaking at 832 Eh/s, marking ~1.4% growth for the month.                 there as well. You can also find these newsletters published
                                                                         in article form on Nostr.

                                                                         If you were looking for answers about cooling your Bitcoin
                                                                         miners this summer then hopefully you found them here.

                                                                         If you want to continue seeing developers build free and
                                                                         open solutions be sure to support the Samourai Wallet
                                                                         developers by making a tax-deductible contribution to their
     [IMG-005] 2025 hashrate/difficulty chart from mempool.space         legal defense fund here. The first step in ensuring a future of
                                                                         free and open Bitcoin development starts with freeing these
Difficulty is currently 112.14T as of Epoch 440 and set to               developers.
increase roughly 1.7 – 2.3% on or around March 23, 2025.
But that target will change between now and then. The
previous re-target increased difficulty by 1.4%. All together
for 2025 thus far, difficulty has gone up ~2.15%.

New-gen miners are selling for roughly $17.65 per Th
using the Bitmain Antminer S21+ 235 Th/s model from
Kaboom Racks as an example. According to the Hashrate
Index, more efficient miners like the <19 J/Th models are
fetching $17.49 per terahash, models between 19J/Th –
25J/Th are selling for $12.68 per terahash, and models
>25J/Th are selling for $3.37 per terahash.


                                                                                      Dismantle the proprietary mining empire,
                                                                                                               -econoalchemist

         [IMG-006] Miner Prices from Luxor’s Hashrate Index

Hashvalue is currently ~57,000 sats/Ph per day, up slightly
from Frebruary when hashvalue was closer to 56,000
sats/Ph per day according to Braiins Insights. Hashprice is
$47.00/Ph per day, down from $54.00/Ph per day in
February.


        [IMG-007] Hashprice/Hashvalue from Braiins Insights


                                                              The 256 Foundation
                                                                  Page 9 of 9


===== DOCUMENT 4 of 27 =====
DATE: 2025-04
LABEL: April 2025
TITLE: I'm The Block Miner Now
FILE: 256Foundation-Newsletter-2504_v2.pdf
SOURCE: https://github.com/256foundation/News/blob/main/256Foundation-Newsletter-2504_v2.pdf

I’m The Block Miner Now
By: The 256 Foundation
A monthly newsletter
April 2025


Introduction:                                                          collaborative transactions. Not the Whirlpool transactions
Welcome to the fourth newsletter produced by The 256                   that Samourai Wallet was well-known for but the Stowaway
Foundation! March was an action-packed month with                      and StonewallX2 p2p CoinJoin transactions. The
events ranging from the announcement of TSMC investing                 persistence of Samourai’s tools still working despite the full
in US fabs to four solo block finds. Dive in to catch up on            force of the State coming down on the developers is a
the latest news, mining industry developments, progress                testament to the power of open-source code.
updates on grant projects, Actionable Advice on updating a
Futurebit Apollo I to the latest firmware, and the current             March       3,    Stronghold       completes    cleanup    of
state of the Bitcoin network.                                          decommissioned coal plant using Bitcoin miners.
                                                                       Stronghold’s initiative counters the narrative that Bitcoin
                                                                       mining is wasteful by removing 150,000 tons of coal waste,
                                                                       part of a broader effort that cleared 240,000 tons in Q2 2024
                                                                       alone. Waste coal piles in Pennsylvania, like the one in
                                                                       Russellton, have scarred landscapes, making this
                                                                       reclamation a significant step for local ecosystems. The
                                                                       project aligns with growing efforts in the region, as The
                                                                       Nature Conservancy also leads restoration projects in
                                                                       Pennsylvania to revive forests and waters. Stronghold’s
                                                                       dual-use model—powering Bitcoin miners and supplying
                                                                       the grid—shows how Bitcoin mining can support
                                                                       environmental goals while remaining economically viable.

                                                                       March 3, five TSMC semiconductor fabs coming to
                                                                       Arizona. TSMC’s $100 billion investment in Arizona
                                                                       reflects a strategic push to bolster U.S. semiconductor
                                                                       production amid global supply chain vulnerabilities and
                                                                       geopolitical tensions, particularly with West Taiwan’s
                                                                       claims over Taiwan. TSMC’s existing $65 billion
                                                                       investment in Phoenix, now totaling $165 billion, aims to
                                                                       create 40,000 construction jobs and tens of thousands of
                                                                       high-tech roles over the next decade. This could relieve
[IMG-001] Variation of the “I’m the captain now” meme by @maxisclub    bottlenecks in ASIC chip supply if Bitcoin mining chip
                                                                       designers can get access to the limited foundry space. If that
Definitions:                                                           is the case, this could help alleviate some centralization
MA = Moving Average                                                    concerns as it relates to a majority of Bitcoin mining chips
Eh/s = Exahash per second                                              coming from Taiwan and West Taiwan.
Ph/s = Petahash per second
Th/s = Terahash per second                                             March 10, Block #887212 solved by a Bitaxe Ultra with
T = Trillion                                                           ~491Gh/s. Not only did the Bitaxe satisfy the network
J/Th = Joules per Terahash                                             difficulty, which was 112.15T, but obliterated it with a
$ = US Dollar                                                          whopping 719.9T difficulty. This Block marked the second
OS = Operating System                                                  one solved by a Bitaxe and an increasing number of solo
SSD = Solid State Drive                                                block finds overall as more individuals choose to play the
TB = Terabyte                                                          Bitcoin lottery with their hashrate.

News:                                                                  March 12, Pirate Bay co-founder, Carl Lundström, killed in
March 3, Ashigaru releases v1.1.1. Notable because this                plane crash. The Pirate Bay, launched in 2003,
fork of Samourai Wallet serves as the remaining choice of              revolutionized online file-sharing by popularizing
mobile Bitcoin wallet capable of making peer to peer

                                                            The 256 Foundation
                                                               Page 1 of 10

BitTorrent technology, enabling millions to access music,        between your miner and the pool then the ISP may be able
movies, and software, often in defiance of legal systems,        to determine that you are sending data to a mining pool,
which led to Lundström’s 2009 conviction for copyright           they just wouldn’t be able to tell what’s in that data.
infringement. The timing of his death coincides with             Overall, decentralization has become a buzz word lately and
ongoing global debates over digital ownership and                while it is a step in the right direction that more pools are
intellectual property, often echoing many of the same            enabling miners to decide which transactions are included
themes in open-source technology, underscoring the               in the block templates they work on, the pools remain a
enduring impact of The Pirate Bay’s challenge to traditional     centralized force that ultimately can reject templates based
media distribution models.                                       on a number of reasons.

March 18, Samourai Wallet status conference update. This         March 20, Bitaxe makes the cover of Bitcoin Magazine’s
was a short meeting in which the dates for the remaining         The Mining Issue, solidifying the Bitaxe as a pop-culture
pre-trial hearings was discussed.                                icon. Even those who disregard the significance of the
                                                                 Bitaxe project must recognize that the project’s popularity is
     •   May 9, Opening Motion.                                  an indication that something big is developing here.
     •   June 6, prosecution response to the opening
         motion.
     •   June 20, defense replies to the prosecution
         response.
     •   July 15, prosecution provides expert disclosure
     •   August 8, defense provides expert disclosure
     •   Tdev is able to remain home during the remaining
         pre-trial hearings so that he doesn’t have to incur
         the expenses traveling back and forth between
         Europe and the US

Despite seemingly positive shifts in crypto-related policies
from the Trump administration, all signs point to the
prosecution still moving full steam ahead in this case. The
defense teams need to be prepared and they could use all the
financial help they can get. If you feel compelled to support
the legal defense fund, please do so here. If the DOJ wins
this case, all Bitcoiners lose.

March 18, DEMAND POOL launches, transitioning out of
stealth mode and making room for applicants to join the
private waiting list to be one of the Founding Miners.
                                                                            [IMG-002] Bitcoin Magazine, The Mining Issue
Key features of DEMAND Pool include:
    • Build your own blocks                                      March 21, self-hosted solo miner solves block #888737
    • SLICE payment system & new mempool                         with a Futurebit Apollo, making this the third solo block
         algorithm                                               find for Futurebit. The first Futurebit Apollo block find may
    • No more empty blocks                                       have been a fluke, the second a coincidence, but the third is
    • End-to-end encryption for protection                       an indication of a pattern forming here. More hashrate is
    • Efficient data transfer, less wasted hashrate              being controlled by individuals who are constructing their
    • Lower costs on CPU, bandwidth, & time                      own blocks and this trend will accelerate as time goes on
                                                                 and deploying these devices becomes easier and less
DEMAND Pool implements Stratum v2 so that miners can             expensive. This was the second solo block found in March.
generate their own block templates, entering the arena of
pools trying to decentralize mining such as OCEAN with           March 21, US Treasury Department lifts sanctions on
their alternative to Stratum v2 called DATUM. A benefit of       Tornado Cash. This is a positive sign coming from the US
the Stratum v2 protocol over Stratum v1 is that data sent        Treasury, however the charges against the Tornado Cash
between the miner and the pool is now encrypted whereas          developer, Roman Storm, still stand and his legal defense
before it was sent in clear-text, the encryption helps with      team is still fighting an uphill battle. Even though the US
network level privacy so that for example, your Internet         Treasury removed Tornado Cash from the OFAC list, the
Service Provider cannot read what is in the data being           department is attempting to stop a Texas court from
passed back and forth. Although, unless there is a proxy         granting a motion that would ensure the Treasury can’t put


                                                      The 256 Foundation
                                                         Page 2 of 10

Tornado Cash back on the OFAC list. Meanwhile, the other           slab, 2 heated pools, all powered by Bitcoin miners and
Tornado Cash developer, Alex Pertsev, is fighting his appeal       fully automated. Innovations and efficient systems like this
battle in the Dutch courts.                                        will become more common as Bitcoin mining hardware and
                                                                   firmware solutions become open-source
March 22, Self-hosted Public Pool user mines Block
#888989. This was the first block mined with the Public            1) @DrydeGab shares The Ocho, a Bitaxe Nerd Octaxe
Pool software, which is open-source and available for              open-source Bitcoin miner featuring 8x BM1370 ASICs that
anyone to host themselves, in this case hosted on the user’s       performs at 9-10Th/s consuming ~180W. The Ocho runs on
Umbrel. If you read the January issue of The 256                   it’s own custom AxeOS. Currently out of stock but
Foundation newsletter, there are detailed instructions for         generally available for purchase in the IX Tech store.
hosting your own instance of Public Pool on a Raspberry Pi.
Easier solutions exist and accomplish the same thing such
as Umbrel and Start9. This was the third solo block mined
in March.

March 26, DeFi Education Fund publishes coalition letter
urging congress to correct the DOJ’s dangerous
misinterpretation of money transmission laws. In their own
words: “First seen in Aug 2023 via the criminal indictment
of @rstormsf, the DOJ’s novel legal theory expands
criminal liability to software developers, ignoring
longstanding FinCEN guidance and threatening the entire
U.S. blockchain & digital asset ecosystem”. Many familiar
organizations in the industry signed the letter, such as
Coinbase, Kraken, A16z Crypto, and Ledger. Sadly, no
Bitcoin companies signed the letter, highlighting the
reckless ignorance prevalent among the “toxic Bitcoin
maximalists” who often pride themselves on their narrow
focus; a focus which is proving to be more of a blind spot
limiting their ability to recognize a clear and present threat.
The full letter text can be found here.

March 28, Heatbit reveals the black Heatbit, an elegant
space heater that mines Bitcoin. Heat re-use applications
such as Bitcoin mining space heaters are one of many
examples where energy spent on generating heat can also
earn the user sats. Other popular solutions include heating
hot tubs, hotels, drive ways, and more. The innovations in
this area will continue to be unlocked as open-source
solutions like the ones being developed at The 256                           [IMG-003] The Nerd OCTAXE Ocho by @DrydeGab
Foundation are released and innovators gain more control
over their applications.                                           2) @incognitojohn23 demonstrates building a Bitaxe from
                                                                   scratch with no prior experience, proving that anyone can
March 29, miner with 2.5Ph/s solves Block #889975 with             access this technology with a little determination and the
Solo CK Pool, marking the fourth solo block found in the           right community. @incognitojohn23 has also uploaded
month of March. This was the first solo block found on CK          several videos documenting his progress and lessons along
Pool’s European server. This was a good way to finish the          the way. Every builder has their first day, don’t hold back if
month on a strong note for small-scale miners.                     you feel compelled to jump in and get started.

                                                                   3) @HodlRev demonstrating how he combines Bitcoin
Free & Open Mining Industry Developments:
                                                                   mining with maple syrup production. In fact, @HodlRev
The development will not stop until Bitcoin mining is free
                                                                   has integrated Bitcoin mining into several aspects of his
and open. Innovators didn’t let off the gas in March, here
                                                                   homestead. Be sure to follow his content for an endless
are eleven note-worthy events:
                                                                   stream of resourceful ideas. Once open-source Bitcoin
                                                                   mining firmware and hardware solutions become widely
0) @BTC_Grid demonstrates heating a new residential
                                                                   available, innovators like @HodlRev will have more control
build with Bitcoin miners. This custom build features 6,000
                                                                   over every parameter of these unique applications.
square feet of radiant floors, 1,500 sqft of snow melting


                                                        The 256 Foundation
                                                           Page 3 of 10

4) ATL Bitlab announces their first hackathon, running June        can be made like which pools are merely proxies for larger
7 through July 6. Promoted as “A global hackathon focused          pools, timing analysis of when templates are sent out, and
on all things bitcoin mining”. If you are interested in joining    now historical data on what the state of each pool’s
the hackathon, there is a Google form you can fill out here.       templates were at a given block height. The work Boerst is
It will be interesting to see what innovations come from this      doing with this website provides a great tool for gaining
effort.                                                            insights into mining centralization.

5) @100AcresRanch builds touchscreen dashboard for                 10) Braiins open-sources the BCB100 Control Board,
Bitaxe and Loki Boards. With this, you can control up to 10        designed to work with Antminers, this control board project
mining devices with the ability to instantly switch any of         has two parts: the hardware and the software. For the
the presets without going into the mining device UI.               hardware part, open files include the Bill Of Materials,
                                                                   schematics, Gerbers, and CAD files. For the software part,
                                                                   open files include the board-level OpenWrt-based firmware
                                                                   with the full configuration file and the Nix environment for
                                                                   reproducible builds. The mining firmware binaries for
                                                                   bosminer and boser (same as the official Braiins OS
                                                                   releases) are also available to download and use to compile
                                                                   the image for the control board, however the Braiins OS
                                                                   firmware itself is not included in this open-source bundle.
                                                                   Braiins chose the GPLv3 open-source license for the
                                                                   software and the CERN-OHL-S open-source license for the
                                                                   hardware. This is a great gesture by Braiins and helps
                                                                   validate the efforts of The 256 Foundation to make Bitcoin
                                                                   mining free and open. The Braiins GitHub repositories
                                                                   where all this information can be found are accessible here
                                                                   and here. The 256 Foundation has plans to develop a
                                                                   Mujina firmware that can be flashed onto the BCB100
                                                                   helping target Antminer machines.
    [IMG-004] Decentral Command Dashboard by @100AcresRanch

6) @IxTechCrypto reveals HAXE, the newest member of                Grant Project Updates:
the Nerdaxe miner family. HAXE is a 6 ASIC miner                   In March, The 256 Foundation formalized agreements with
performing at ~7.4 Th/s at ~118W. Upon looking at the IX           the lead developers who were selected for each project.
Tech store, it seems as though the HAXE has not hit shelves        These agreements clearly defined the scope of each project,
yet but keep an eye out for announcements soon.                    identified the deliverables, set a timeline, and agreement on
                                                                   compensation was made. Below are the outlines for each
7) Solo Satoshi reveals the NerdQaxe++, the latest marvel          project, the compensation is not made public for privacy
in the world of open-source Bitcoin mining solutions. This         and security reasons.
device is equipped with four ASIC chips from the Antminer
S21 Pro and boasts an efficiency rating of 15.8 J/Th. At the       Ember One:
advertised power consumption of 76 Watts, that would               @skot9000 instigator of the Bitaxe and all around legend
produce nearly 5 Th/s. Currently out of stock at the Solo          for being the first mover in open-source Bitcoin mining
Satoshi store and the IX Tech store but in stock and               solutions is the lead engineer for the Ember One project.
available at the PlebSource store.                                 This was the first fully funded grant from The 256
                                                                   Foundation and commenced in November 2024 with a six
8) @TheSoloMiningCo shares a bolt-on voltage regulator             month duration. The deliverable is a validated design for a
heatsink for the Bitaxe, this is a helpful modification when       ~100W miner with a standardized form factor (128mm x
overclocking your miner and helps dissipate heat away from         128mm), USB-C data connection, 12-24v input voltage,
the voltage regulator. Many innovators are discovering             with plans for several versions – each with a different ASIC
ways to get every bit of efficiency they can from their            chip. The First Ember One features the Bitmain BM1362
hardware and sharing their ideas with the wider community          ASIC, next on the list will be an Ember One with the Intel
for anyone to adopt.                                               BZM2 ASIC, then an Auradine ASIC version, and
                                                                   eventually a Block ASIC version. Learn more at
9) @boerst adds historical data to stratum.work, a public          https://emberone.org/
website that monitors mining pool activity through calling
for the work templates being generated for the pool’s              Mujina Mining Firmware:
respective miners. By parsing the information available in         @ryankuester, embedded Linux developer and Electrical
the work templates, a number of interesting observations           Engineer who has mastered the intersection of hardware and


                                                        The 256 Foundation
                                                           Page 4 of 10

software over the last 20 years is the lead developer for the     background in product management, is the lead engineer on
Mujina project, a Linux based mining firmware application         the Libre Board project; the control board for the Ember
with support for multiple drivers so it can be used with          One complete mining system. Start date is April 5, 2025 and
Ember One complete mining system. The grant starts on             the deliverables after six months will be a mining control
April 5, 2025 and continues for nine months. Deliverables         board based on the Raspberry Pi Compute Module I/O
include:                                                          Board with at least the following connections:

Core Mujina-miner Application:                                         •       USB hub integration (maybe 10 ports?)
Fully open-source under GPLv3 license                                  •       Support for fan connections
    • Written in Rust for performance, robustness, and                 •       NVME expansion
         maintainability, leveraging Rust's growing                    •       Two 100-pin connectors for the compute module
         adoption in the Bitcoin ecosystem                             •       Ethernet port
    • Designed for modularity and extensibility                        •       HDMI port
    • Stratum V1 client (which includes DATUM                          •       Raspberrypi 40-pin header for sensors, switches, &
         compatibility)                                                        relays etc.
    • Best effort for Stratum V2 client in the initial                 •       MIPI port for touchscreen
         release but may not happen until later                        •       Accepts 12-24 VDC input power voltage.
Hardware Support:                                                 The initial release of Libre Board is being built in such a
    • Support for Ember One 00 hash boards (Bitmain               way that it supports long-term goals like alternative
       chips)                                                     compute modules such as ARM, x86, and RISC-V. Learn
    • Support for Ember One 01 hash boards (Intel                 more at https://libreboard.org/
       chips) on a best effort basis but may not happen
       until later                                                Hydra Pool:
    • Full support on the Raspberry Pi CM5 and IO                 @jungly, distributed systems PhD and the lead developer
       board running the Raspberry Pi OS                          behind P2Pool v2 and formerly for Braidpool, now takes
    • Support for the Libre board when released                   the reigns as lead developer for Hydra Pool, the stratum
    • Best-effort compatibility with other hardware               server package that will run on the Ember One mining
       running Linux                                              system. Start date for this project was on April 5, 2025 and
                                                                  the duration lasts for six months. Deliverables include:
Management Interfaces:
   • HTTP API for remote management and monitoring                         •    Talks to bitcoind and provides stratum work to
   • Command-line interface for direct control                                  users and stores received shares
   • Basic web dashboard for status monitoring                             •    Scalable and robust database support to save
   • Configuration via structured text files                                    received shares
   • Community Building and Infrastructure                                 •    Run share accounting on the stored shares
   • GitHub project organization and workflow                              •    Implement payment mechanisms to pay out
   • Continuous integration and testing framework                               miners based on the share accounting
   • Comprehensive user and developer documentation                        •    Provide two operation modes: Solo mining and
   • Communication channels for users and developers                            PPLNS or Tides based payout mechanism, with
   • Community building through writing, podcasts,                              payouts from coinbase only. (All other payout
      and conference participation                                              mechanism are out of scope of this initial release
                                                                                for now but there will be more).
The initial release of Mujina is being built in such a way                 •    Rolling upgrades: Tools and scripts to upgrade
that it supports long-term goals like ultimately evolving into                  server with zero downtime.
a complete Linux-based operating system, deployable                        •    Dashboard: Pool stats view only dashboard with
through simple flashing procedures. Initially focused on                        support to filter miner payout addresses.
supporting the 256 Foundation's Libre control boards and                   •    Documentation: Setup and other help pages, as
Ember hash boards, Mujina's modular architecture will                           required.
eventually enable compatibility with a wide variety of
mining hardware from different manufacturers. Learn more          The initial release of Hydra Pool is being built in such a
at https://mujina.org/                                            way that it supports long-term goals like alternative payout
                                                                  models such as echash, communicating with other Hydra
Libre Board:                                                      Pool instances, local store of shares for Ember One, and a
@Schnitzel, heat re-use maximalist who turned his home's          user-friendly interface that puts controls at the user's
hot water accessories into Bitcoin-powered sats generators        fingertips, and supports the ability for upstream pool
and during the day has built a successful business with a         proxying. Learn more at https://hydrapool.org/

                                                       The 256 Foundation
                                                          Page 5 of 10

Block Watcher:                                                       Once there, you will see two OS images available for
Initially scoped to be a Bitcoin mining insights application         download, along with two links to alternative hosting
built to run on the Ember One mining system using the self-          options for those two images. If you are upgrading an
hosted node for blockchain data. However, The 256                    Apollo I, you need to figure out which new OS image is
Foundation has decided to pause Block Watcher                        right for your device, the MCU 1 image or the MCU 2
development for a number of reasons. Primarily because the           image. There are detailed instructions on figuring this out
other four projects were more central to the foundation’s            available here. There are multiple ways to determine if you
mission and given the early stages of the Foundation with            need the MCU 1 or MCU 2 image. If the second to last digit
the current support level, it made more sense to deploy              in your Futurebit Apollo I is between 4 – 8 then you have an
capital where it counts most.                                        MCU 1; or if your batch number is 1 – 3 then you have an
                                                                     MCU 1; or if the circuit board has a 40-pin connector
Actionable Advice:                                                   running perpendicular to the microSD card slot then you
This month’s Actionable Advice column explains the                   have an MCU 1. Otherwise, you have an MCU 2.
process for upgrading the Futurebit Apollo I OS to the
newer Apollo II OS and replacing the SSD. The Futurebit              For example, this is what the MCU 1 circuit board will look
Apollo is a small mining device with an integrated Bitcoin           like:
node designed as a plug-and-play solution for people
interested in mining Bitcoin without all the noise and heat
of the larger industrial-grade miners. The Apollo I can hash
between 2 – 4 Th/s and will consume roughly 125 – 200
Watts. The Apollo II can hash between 8 – 10 Th/s and will
consume roughly 280 – 400 Watts. The motivation behind
upgrading from the Apollo I OS to the Apollo II OS is the
ability to run a stratum server internally so that the mining
part of the device can ask the node part of the device for
mining work, thus enabling users to solo mine in a self-
hosted fashion. In fact, this is exactly what The 256
Foundation did during the Telehash fundraising event where
Block #881423 was solo mined, at one point there was more
than 1 Eh/s of hashrate pointed to that Apollo.


                                                                                      [IMG-006] Futurebit MCU1 example

                                                                     Once you figure out which OS image you need, go ahead
                                                                     and download it. The SHA256 hash values for the OS
                                                                     Image files are presented in the GitHub repo. If you’re
                                                                     running Linux on your computer, you can change directory
                                                                     to your Download folder and run the following command to
                                                                     check the SHA256 hash value of the file you downloaded
                                                                     and compare that to the SHA256 hash values on GitHub.


         [IMG-005] Futurebit Apollo I with new NVME SSD

You can find the complete flashing instructions on the
Futurebit website here. You will need a separate computer                      [IMG-007] Verifying Futurebit OS Image Hash Value
to complete the flashing procedure. The flashing procedure
will erase all data on the microSD card so back it up if you         With the hash value confirmed, you can use a program like
have anything valuable saved on there.                               Balena Etcher to flash your microSD card. First remove the
                                                                     microSD card from the Apollo circuit board by pushing it
First navigate to the Futurebit GitHub Releases page at:             inward, it should make a small click and then spring
https://github.com/jstefanop/apolloapi-v2/releases                   outward so that you can grab it and remove it from the slot.


                                                          The 256 Foundation
                                                             Page 6 of 10

Connect the microSD card to your computer with the
appropriate adapter.

Open Balena Etcher and click on the “Flash From File”
button to define the file path to where you have the OS
image saved:


                                                                                [IMG-010] Balena Etcher user interface.


              [IMG-008] Balena Etcher user interface

Then click on the “Select Target” button to define the drive
which you will be flashing. Select the microSD card and be
sure not to select any other drive on your computer by
mistake:


                                                                                [IMG-011] Balena Etcher user interface.


              [IMG-009] Balena Etcher user interface

Then click on the “Flash” button and Balena Etcher will
take care of formatting the microSD card, decompressing                         [IMG-012] Balena Etcher user interface.
the OS image file, and flashing it to the microSD card
[IMG-010].                                                        You can remove the microSD card from your computer now
                                                                  and install it back into the Futurebit Apollo. If you have an
The flashing process can take some time so be patient. The        adequately sized SSD then your block chain data should be
Balena Etcher interface will allow you to monitor the             safe as that is where it resides, not on the microSD card. If
progress [IMG-011].                                               you have a 1TB SSD then this would be a good time to
                                                                  consider upgrading to a 2TB SSD instead. There are lots of
Once the flashing process is completed successfully, you          options but you want to get an NVME style one like this:
will receive a notice in the balena Etcher interface that
looks like this [IMG-012].


                                                       The 256 Foundation
                                                          Page 7 of 10

                                                                  Click on the button that says “Start setup process”. The next
                                                                  you will see should look like this:


               [IMG-013] 1TB vs. 2TB NVME SSD

Simply loosen the screw holding the SSD in place and then
remove the old SSD by pulling it out of the socket. Then                      [IMG-015] Futurebit mining selection screen
insert the new one and put the screw back in place.
                                                                  You have the option here to select solo mining or pooled
Once the SSD and microSD are back in place, you can               mining. If you have installed a new SSD card then you
connect Ethernet and the power supply, then apply power to        should select pooled mining because you will not be able to
your Apollo.                                                      solo mine until the entire Bitcoin blockchain is downloaded.

You will be able to access your Apollo through a web              Your Apollo will automatically start downloading the
browser on your computer. You will need to figure out the         Bitcoin blockchain in the background and in the mean-time
local IP address of your Apollo device so log into your           you can start mining with a pool of your choice like Solo
router and check the DHCP leases section. Your router             CK Pool or Public Pool or others.
should be accessible from your local network by typing an
IP address into your web browser like 192.168.0.1 or              Be forewarned that the Initial Blockchain Download
10.0.0.1 or maybe your router manufacturer uses a different       (“IBD”) takes a long time. At the time of this writing, it
default. You should be able to do an internet search for your     took 18 days to download the entire blockchain using a
specific router and figure it out quickly if you don’t already    Starlink internet connection, which was probably throttled
know. If that fails, you can download and run a program           at some points in the process because of the roughly 680
like Angry IP Scanner.                                            GB of data that it takes.

Give the Apollo some time to run through a few preliminary        In February 2022, the IBD on this exact same device took 2
and automatic configurations, you should be able to see the       days with a cable internet connection. Maybe the Starlink
Apollo on your local network within 10 minutes of                 was a bit of a bottleneck but most likely the extended length
powering it on.                                                   of the download can be attributed to all those JPEGS on the
                                                                  blockchain.
Once you figure out the IP address for your Apollo, type it
into your web browser and this is the first screen you should     Otherwise, if you already have the full blockchain on your
be greeted with:                                                  SSD then you should be able to start solo mining right away
                                                                  by selecting the solo mining option.

                                                                  After making your selection, the Apollo will automatically
                                                                  run through some configurations and you should have the
                                                                  option to set a password somewhere in there along the way.
                                                                  Then you should see this page [IMG-016].

                                                                  Click on the “Start mining” button. Then you should be
                                                                  brought to your dashboard like this [IMG-017].

                                                                  You can monitor your hashrate, temperatures, and more
                                                                  from the dashboard. You can check on the status of your
                                                                  Bitcoin node by clicking on the three-circle looking icon
                                                                  that says “node” on the left-hand side menu [IMG-018].
               [IMG-014] Futurebit welcome screen


                                                       The 256 Foundation
                                                          Page 8 of 10

                                                                                 [IMG-019] Futurebit mining pool settings


            [IMG-016] Futurebit setup completion page


                                                                                [IMG-020] Futurebit solo mining dashboard

                                                                   Now just sit back and enjoy watching your best shares roll
                                                                   in until you get one higher than the network difficulty and
                                                                   you mine that solo block.

                                                                   State of the Network:
                                                                   Hashrate on the 14-day MA according to mempool.space
                 [IMG-017] Futurebit dashboard                     increased from ~793 Eh/s to ~829 Eh/s in March, marking
                                                                   ~4.5% growth for the month.


                 [IMG-018] Futurebit node page                          [IMG-021] 2025 hashrate/difficulty chart from mempool.space


If you need to update the mining pool, click on the                Difficulty was 110.57T at it’s lowest in March and 113.76T
“settings” option at the bottom of the left-hand side menu.        at it’s highest, which is a 2.8% increase for the month. All
There you will see a drop down menu for selecting a pool to        together for 2025 up until the end of March, difficulty has
use, you can select the “setup custom pool” option to insert       gone up ~3.6%.
the appropriate stratum URL and then your worker name.
                                                                   According to the Hashrate Index, more efficient miners like
                                                                   the <19 J/Th models are fetching $17.29 per terahash,
Once your IBD is finished, you can start solo mining by
                                                                   models between 19J/Th – 25J/Th are selling for $11.05 per
toggling on the solo mode at the bottom of the settings
                                                                   terahash, and models >25J/Th are selling for $3.20 per
page. You will have a chance to update the Bitcoin address
                                                                   terahash. Overall, prices seem to have dropped slightly over
you want to mine to. Then click on “save & restart” [IMG-
                                                                   the month of March. You can expect to pay roughly $4,000
019].
                                                                   for a new-gen miner with 230+ Th/s [IMG-022].
Then once your system comes back up, you will see a
                                                                   Hashvalue is closed out in March at ~56,000 sats/Ph per
banner at the top of the dashboard page with the IP address
                                                                   day, relatively flat from Frebruary, according to Braiins
you can use to point any other miners you have, like
                                                                   Insights. Hashprice is $46.00/Ph per day, down from
Bitaxes, to your own self-hosted solo mining pool [IMG-
                                                                   $47.00/Ph per day in February [IMG-023].
020]!


                                                        The 256 Foundation
                                                           Page 9 of 10

        [IMG-022] Miner Prices from Luxor’s Hashrate Index


        [IMG-023] Hashprice/Hashvalue from Braiins Insights
                                                                                            [IMG-024] TEMS 2025 flyer
The next halving will occur at block height 1,050,000 which
should be in roughly 1,071 days or in other words ~156,850               If you have an old Apollo I laying around and want to get it
blocks from time of publishing this newsletter.                          up to date and solo mining then hopefully this newsletter
                                                                         helped you accomplish that.
Conclusion:
Thank you for reading the third 256 Foundation newsletter.
Keep an eye out for more newsletters on a monthly basis in
your email inbox by subscribing at 256foundation.org. Or
you can download .pdf versions of the newsletters from
there as well. You can also find these newsletters published
in article form on Nostr.                                                                  [IMG-026] FREE SAMOURAI

If you haven’t done so already, be sure to RSVP for the                  If you want to continue seeing developers build free and
Texas Energy & Mining Summit (“TEMS”) in Austin,                         open solutions be sure to support the Samourai Wallet
Texas on May 6 & 7 for two days of the highest Bitcoin                   developers by making a tax-deductible contribution to their
mining and energy signal in the industry, set in the intimate            legal defense fund here. The first step in ensuring a future of
Bitcoin Commons, so you can meet and mingle with the                     free and open Bitcoin development starts with freeing these
best and brightest movers and shakers in the space.                      developers.

While you’re at it, extend your stay and spend Cinco De
Mayo with The 256 Foundation at our second fundraiser,
Telehash #2. Everything is bigger in Texas, so set your
expectations high for this one. All of the lead developers
from the grant projects will be present to talk first-hand                                                       You can just FAFO,
about how to dismantle the proprietary mining empire.                                                               -econoalchemist


                                                              The 256 Foundation
                                                                Page 10 of 10


===== DOCUMENT 5 of 27 =====
DATE: 2025-05
LABEL: May 2025
TITLE: Bitcoin Mining Will Not Be Decentralized Until It Is Open Sourced
FILE: 256Foundation-Newsletter-2505_v1.pdf
SOURCE: https://github.com/256foundation/News/blob/main/256Foundation-Newsletter-2505_v1.pdf

Bitcoin Mining Will Not Be Decentralized
                          Until It Is Open Sourced
By: The 256 Foundation
A monthly newsletter
May 2025


Introduction:                                                      News:
Welcome to the fifth newsletter produced by The 256                April 7, the first of a few notable news items that relate to
Foundation! April was a jam-packed month for the                   the Samourai Wallet case, the US Deputy Attorney General,
Foundation with events ranging from launching three grant          Todd Blanche, issued a memorandum titled “Ending
projects to the first official Ember One release. The 256          Regulation By Prosecution”. The memo makes the DOJ’s
Foundation has been laser focused on our mission to                position on the matter crystal clear, stating; “Specifically,
dismantle the proprietary mining empire, signing off on a          the Department will no longer target virtual currency
productive month with the one-finger salute to the                 exchanges, mixing and tumbling services, and offline
incumbent mining cartel.                                           wallets for the acts of their end users or unwitting violations
                                                                   of regulations…”. However, despite the clarity from the
                                                                   DOJ, the SDNY (sometimes referred to as the “Sovereign
                                                                   District” for it’s history of acting independently of the DOJ)
                                                                   has yet to budge on dropping the charges against the
                                                                   Samourai Wallet developers. Many are baffled at the
                                                                   SDNY’s continued defiance of the Trump Administration’s
                                                                   directives, especially in light of the recent suspensions and
                                                                   resignations that swept through the SDNY office in the
                                                                   wake of several attorneys refusing to comply with the
                                                                   DOJ’s directive to drop the charges against New York City
                                                                   Mayor, Eric Adams. There is speculation that the missing
                                                                   piece was Trump’s pick to take the helm at the SDNY, Jay
                                                                   Clayton, who was yet to receive his Senate confirmation
                                                                   and didn’t officially start in his new role until April 22. In
           [IMG-001] Hilarious meme from @CincoDoggos              light of the Blanche Memo, on April 29, the prosecution and
                                                                   defense jointly filed a letter requesting additional time for
Dive in to catch up on the latest news, mining industry            the prosecution to determine it’s position on the matter and
developments, progress updates on grant projects,                  decide if they are going to do the right thing, comply with
Actionable Advice on helping test Hydra Pool, and the              the DOJ, and drop the charges. Catch up on what’s at stake
current state of the Bitcoin network.                              in this case with an appearance by Diverter on the
                                                                   Unbounded Podcast from April 24, the one-year anniversary
Definitions:                                                       of the Samourai Wallet developer’s arrest. This is the most
DOJ = Department of Justice                                        important case facing Bitcoiners as the precedence set in
SDNY = Southern District of New York                               this matter will have ripple effects that touch all areas of the
BTC = Bitcoin                                                      ecosystem. The logic used by SDNY prosecutors argues that
SD = Secure Digital                                                non-custodial wallet developers transfer money in the same
Th/s = Terahash per second                                         way a frying pan transfers heat but does not “control” the
OSMU = Open Source Miners United                                   heat. Essentially saying that facilitating the transfer of funds
tx = transaction                                                   on behalf of the public by any means constitutes money
PSBT = Partially Signed Bitcoin Transaction                        transmission and thus requires a money transmitter license.
FIFO = First In First Out                                          All non-custodial wallets (software or hardware), node
PPLNS = Pay Per Last N Shares                                      operators, and even miners would fall neatly into these
GB = Gigabyte                                                      dangerously generalized and vague definitions. If the SDNY
RAM = Random Access Memory                                         wins this case, all Bitcoiners lose. Make a contribution to
ASIC = Application Specific Integrated Circuit                     the defense fund here.
Eh/s = Exahash per second
Ph/s = Petahash per second


                                                        The 256 Foundation
                                                            Page 1 of 6

April 11, solo miner with ~230Th/s solves Block #891952               sort of freedoms that only open-source Bitcoin mining
on Solo CK Pool, bagging 3.11 BTC in the process. This                solutions are bringing to the table.
will never not be exciting to see a regular person with a
modest amount of hashrate risk it all and reap all the mining
reward. The more solo miners there are out there, the more            Free & Open Mining Industry Developments:
often this should occur.                                              The development will not stop until Bitcoin mining is free
                                                                      and open… and then it will get even better. Innovators did
April 15, B10C publishes new article on mining                        not disappoint in April, here are nine note-worthy events:
centralization. The article analyzes the hashrate share of the
currently five biggest pools and presents a Mining                    April 5, 256 Foundation officially launches three more
Centralization Index. The results demonstrate that only six           grant projects. These will be covered in detail in the Grant
pools are mining more than 95% of the blocks on the                   Project Updates section but April 5 was a symbolic day to
Bitcoin Network. The article goes on to explain that during           mark the official start because of the 6102 anniversary. A
the period between 2019 and 2022, the top two pools had               reminder of the asymmetric advantage freedom tech like
~35% of the network hashrate and the top six pools had                Bitcoin empowers individuals with to protect their rights
~75%. By December 2023 those numbers grew to the top                  and freedoms, with open-source development being central
two pools having 55% of the network hashrate and the top              to those ends.
six having ~90%. Currently, the top six pools are mining
~95% of the blocks.                                                   April 5, Low profile ICE Tower+ for the Bitaxe Gamma
                                                                      601 introduced by @Pleb_Style featuring four heat pipes, 2
                                                                      copper shims, and a 60mm Noctua fan resulting in up to
                                                                      2Th/s. European customers can pick up the complete
                                                                      upgrade kit from the Pleb Style online store for $93.00.


        [IMG-002] Mining Centralization Index by @0xB10C

B10C concludes the article with a solution that is worth
highlighting: “More individuals home-mining with small
miners help too, however, the home-mining hashrate is
currently still negligible compared to the industrial
hashrate.”

April 15, As if miner centralization and proprietary
hardware weren’t reason enough to focus on open-source
mining solutions, leave it to Bitmain to release an S21+
firmware update that blocks connections to OCEAN and                             [IMG-003] Pleb Style ICE Tower+ upgrade kit
Braiins pools. This is the latest known sketchy development
from Bitmain following years of shady behavior like                   April 8, Solo Satoshi spells out issues with Bitaxe
Antbleed where miners would phone home, Covert ASIC                   knockoffs, like Lucky Miner, in a detailed article titled The
Boost where miners could use a cryptographic trick to                 Hidden Cost of Bitaxe Clones. This concept can be
increase efficiency, the infamous Fork Wars, mining empty             confusing for some people initially, Bitaxe is open-source,
blocks, and removing the SD card slots. For a mining                  right? So anyone can do whatever they want… right? Based
business to build it’s entire operation on a fragile foundation       on the specific open-source license of the Bitaxe hardware,
like the closed and proprietary Bitmain hardware is asking            CERN-OHL-S, and the firmware, GPLv3, derivative works
for trouble. Bitcoin miners need to remain flexible and agile         are supposed to make the source available. Respecting the
and they need to be able to adapt to changes instantly – the          license creates a feed back loop where those who benefit
                                                                      from the open-source work of those who came before them


                                                           The 256 Foundation
                                                               Page 2 of 6

contribute back their own modifications and source files to       hardware and firmware are open-source and people can gain
the open-source community so that others can benefit from         full control over their mining appliances.
the new developments. Unfortunately, when the license is
disrespected what ends up happening is that manufacturers         April 21, Hashpool explained on The Home Mining
make undocumented changes to the components in the                Podcast, an innovative Bitcoin mining pool development
hardware and firmware which yields unexpected results             that trades mining shares for ecash tokens. The pool issues
creating a number of issues like the Bitaxe overheating, not      an “ehash” token for every submitted share, the pool uses
connecting to WiFi, or flat out failure. This issue gets          ecash epochs to approximate the age of those shares in a
further compounded when the people who purchased the              FIFO order as they accrue value, a rotating key set is used
knockoffs go to a community support forum, like OSMU,             to eventually expire them, and finally the pool publishes
for help. There, a number of people rack their brains and         verification proofs for each epoch and each solved block.
spend their valuable time trying to replicate the issues only     The ehash is provably not inflatable and payouts are similar
to find out that they cannot replicate the issues since the       to the PPLNS model. In addition to the maturity window
person who purchased the knockoff has something different         where ehash tokens are accruing value, there is also a
than the known Bitaxe model and the distributor who sold          redemption window where the ehash tokens can be traded in
the knockoff did not document those changes. The open-            to the mint for bitcoin. There is also a bitcoin++
source licenses are maintaining the end-users’ freedom to do      presentation from earlier this year where @vnprc explains
what they want but if the license is disrespected then that       the architecture.
freedom vanishes along with details about whatever was
changed. There is a list maintained on the Bitaxe website of      April 26, Boerst adds a new page on stratum.work for block
legitimate distributors who uphold the open-source licenses,      template details, you can click on any mining pool and see
if you want to buy a Bitaxe, use this list to ensure the open-    the extended details and visualization of their current block
source community is being supported instead of leeched off        template. Updates happen in real-time. The page displays all
of.                                                               available template data including the OP_RETURN field
                                                                  and if the pool is merge mining, like with RSK, then that
April 8, The Mempool Open Source Project v3.2.0                   will be displayed too. Stratum dot work is a great project
launches with a number of highlights including a new              that offers helpful mining insights, be sure to book mark it if
UTXO bubble chart, address poisoning detection, and a             you haven’t already.
tx/PSBT preview feature. The GitHub repo can be found
here if you want to self-host an instance from your own
node or you can access the website here. The Mempool
Open Source Project is a great blockchain explorer with a
rich feature set and helpful visualization tools.


                                                                            [IMG-005] New stratum.work live template page
              [IMG-004] Address poisoning example
                                                                  April 27, Public Pool patches Nerdminer exploit that made
April 8, @k1ix publishes bitaxe-raw, a firmware for the           it possible to create the impression that a user’s Nerdminer
ESP32S3 found on Bitaxes which enables the user to send           was hashing many times more than it actually was. This
and receive raw bytes over USB serial to and from the             exploit was used by scammers trying to convince people
Bitaxe. This is a helpful tool for research and development       that they had a special firmware for the Nerminer that
and a tool that is being leveraged at The 256 Foundation for      would make it hash much better. In actuality, Public Pool
helping with the Mujina miner firmware development. The           just wasn’t checking to see if submitted shares were
bitaxe-raw GitHub repo can be found here.                         duplicates or not. The scammers would just tweak the
                                                                  Nerdminer firmware so that valid shares were getting
April 14, Rev.Hodl compiles many of his homestead-meets-          submitted five times, creating the impression that the miner
mining adaptations including how he cooks meat sous-vide          was hashing at five times the actual hashrate. Thankfully
style, heats his tap water to 150°F, runs a hashing space         this has been uncovered by the open-source community and
heater, and how he upgraded his clothes dryer to use Bitcoin      Public Pool quickly addressed it on their end.
miners. If you are interested in seeing some creative and
resourceful home mining integrations, look no further. The
fact that Rev.Hodl was able to do all this with closed-source     Grant Project Updates:
proprietary Bitcoin mining hardware makes a very bullish          Three grant projects were launched on April 5, Mujina
case for the innovations coming down the pike once the            Mining Firmware, Hydra Pool, and Libre Board. Ember


                                                       The 256 Foundation
                                                           Page 3 of 6

One was the first fully funded grant and launched in            12-24vdc range as the Ember One hashboards. The GitHub
November 2024 for a six month duration.                         repo can be found here, although there isn’t much to look at
                                                                yet as the designs are still in the works. If you have feature
Ember One:                                                      requests, creating an issue in the GitHub repo would be a
@skot9000 is the lead engineer on the Ember One and April       good place to start. Learn more at https://libreboard.org/
30 marked the conclusion of the first grant cycle after six
months of development culminating in a standardized
hashboard featuring a ~100W power consumption, 12-24v
input voltage range, USB-C data communication, on-board
temperature sensors, and a 125mm x 125mm formfactor.
There are several Ember One versions on the road map,
each with a different kind of ASIC chip but staying true to
the standardized features listed above. The first Ember One,
the 00 version, was built with the Bitmain BM1362 ASIC
chips. The first official release of the Ember One, v3, is
available here. v4 is already being worked on and will
incorporate a few circuit safety mechanisms that are pretty
exciting, like protecting the ASIC chips in the event of a
power supply failure. The firmware for the USB adaptor is
available here. Initial testing firmware for the Ember One
00 can be found here and full firmware support will be
                                                                             [IMG-006] First signs of life from an ASIC
coming soon with Mujina. The Ember One does not have an
on-board controller so a separate, USB connected, control       Hydra Pool:
board is required. Control board support is coming soon         @jungly is the lead developer for Hydra Pool and over the
with the Libre Board. There is an in-depth schematic review     last month he has developed a working early version of
that was recorded with Skot and Ryan, the lead developer        Hydra Pool specifically for the upcoming Telehash #2.
for Mujina, you can see that video here. Timing for starting    Forked from CK Pool, this early version has been modified
the second Ember One cycle is to be determined but the          so that the payout goes to the 256 Foundation bitcoin
next version of the Ember One is planned to have the Intel      address automatically. This way, users who are supporting
BZM2 ASICs. Learn more at https://emberone.org/                 the funderaiser with their hashrate do not need to copy/paste
                                                                in the bitcoin address, they can just use any vanity username
Mujina Mining Firmware:                                         they want. Jungly was also able to get a great looking
@ryankuester is the lead developer for the Mujina firmware      statistics dashboard forked from CKstats and modify it so
project and since the project launched on April 5, he has       that the data is populated from the Hydra Pool server
been working diligently to build this firmware from scratch     instead of website crawling. After the Telehash, the next
in Rust. By using the bitaxe-raw firmware mentioned             steps will be setting up deployment scripts for running
above, over the last month Ryan has been able to use a          Hydra Pool on a cloud server, support for storing shares in a
Bitaxe to simulate an Ember One so that he can start            database, and adding PPLNS support. The 256 Foundation
building the necessary interfaces to communicate with the       is only running a publicly accessible server for the Telehash
range of sensors, ASICs, work handling, and API requests        and the long term goals for Hydra Pool are that the users
that will be necessary. For example, using a logic analyzer,    host their own instance. The 256 Foundation has no plans
this is what the first signs of life look like when             on becoming a mining pool operator. The following
communicating with an ASIC chip, the orange trace is a          Actionable Advice column shows you how you can help test
message being sent to the ASIC and the red trace below it is    Hydra Pool. The GitHub repo for Hydra Pool can be found
the ASIC responding [IMG-006]. The next step is to see if       here. Learn more at https://hydrapool.org/
work can be sent to the ASIC and results returned. The
GitHub repo for Mujina is currently set to private until a
solid foundation has been built. Learn more at
https://mujina.org/                                             Actionable Advice:
                                                                The 256 Foundation is looking for testers to help try out
Libre Board:                                                    Hydra Pool. The current instance is on a hosted bare metal
@Schnitzel is the lead engineer for the Libre Board project     server in Florida and features 64 cores and 128 GB of
and over the last month has been modifying the Raspberry        RAM. One tester in Europe shared that they were only
Pi Compute Module I/O Board open-source design to fit the       experiencing ~70ms of latency which is good. If you want
requirements for this project. For example, removing one of     to help test Hydra Pool out and give any feedback, you can
the two HDMI ports, adding the 40-pin header, and adapting      follow the directions below and join The 256 Foundation
the voltage regulator circuit so that it can accept the same    public forum on Telegram here.


                                                     The 256 Foundation
                                                         Page 4 of 6

The first step is to configure your miner so that it is pointed    the block was found there was closer to 800 Ph/s of
to the Hydra Pool server. This can look different depending        hashrate. At this next Telehash, The 256 Foundation is
on your specific miner but generally speaking, from the            looking to beat the previous records across the board. You
settings page you can add the following URL:                       can find all the Telehash details on the Meetup page here.

stratum+tcp://stratum.hydrapool.org:3333
                                                                   State of the Network:
On some miners, you don’t need the “stratum+tcp://” part or        Hashrate on the 14-day MA according to mempool.space
the port, “:3333”, in the URL dialog box and there may be          increased from ~826 Eh/s to a peak of ~907 Eh/s on April
separate dialog boxes for the port.                                16 before cooling off and finishing the month at ~841 Eh/s,
                                                                   marking ~1.8% growth for the month.
Use any vanity username you want, no need to add a BTC
address. The test iteration of Hydra Pool is configured to
payout to the 256 Foundation BTC address.

If your miner has a password field, you can just put “x” or
“1234”, it doesn’t matter and this field is ignored.

Then save your changes and restart your miner. Here are
two examples of what this can look like using a Futurebit               [IMG-010] 2025 hashrate/difficulty chart from mempool.space
Apollo and a Bitaxe:
                                                                   Difficulty was 113.76T at it’s lowest in April and 123.23T at
                                                                   it’s highest, which is a 8.3% increase for the month. But
                                                                   difficulty dropped with Epoch #444 just after the end of the
                                                                   month on May 3 bringing a -3.3% downward adjustment.
                                                                   All together for 2025 up to Epoch #444, difficulty has gone
            [IMG-007] Apollo configured to Hydra Pool              up ~8.5%.

                                                                   According to the Hashrate Index, ASIC prices have flat-
                                                                   lined over the last month. The more efficient miners like the
                                                                   <19 J/Th models are fetching $17.29 per terahash, models
                                                                   between 19J/Th – 25J/Th are selling for $11.05 per
                                                                   terahash, and models >25J/Th are selling for $3.20 per
                                                                   terahash. You can expect to pay roughly $4,000 for a new-
                                                                   gen miner with 230+ Th/s.


            [IMG-008] Bitaxe Configured to Hydra Pool

Once you get started, be sure to check stats.hydrapool.org to
monitor the solo pool statistics.
                                                                             [IMG-011] Miner Prices from Luxor’s Hashrate Index

                                                                   Hashvalue over the month of April dropped from ~56,000
                                                                   sats/Ph per day to ~52,000 sats/Ph per day, according to the
                                                                   new and improved Braiins Insights dashboard [IMG-012].
                                                                   Hashprice started out at $46.00/Ph per day at the beginning
                                                                   of April and climbed to $49.00/Ph per day by the end of the
                                                                   month.

                                                                   The next halving will occur at block height 1,050,000 which
                                                                   should be in roughly 1,063 days or in other words ~154,650
            [IMG-009] Ember One hashing to Hydra Pool              blocks from time of publishing this newsletter.

At the last Telehash there were over 350 entities pointing as
much as 1.12Eh/s at the fundraiser at the peak. At the time


                                                        The 256 Foundation
                                                            Page 5 of 6

        [IMG-012] Hashprice/Hashvalue from Braiins Insights


Conclusion:
Thank you for reading the fifth 256 Foundation newsletter.
Keep an eye out for more newsletters on a monthly basis in
your email inbox by subscribing at 256foundation.org. Or
you can download .pdf versions of the newsletters from
there as well. You can also find these newsletters published
in article form on Nostr.

If you haven’t done so already, be sure to RSVP for the                                     [IMG-013] TEMS 2025 flyer
Texas Energy & Mining Summit (“TEMS”) in Austin,
Texas on May 6 & 7 for two days of the highest Bitcoin                   If you are interested in helping The 256 Foundation test
mining and energy signal in the industry, set in the intimate            Hydra Pool, then hopefully you found all the information
Bitcoin Commons, so you can meet and mingle with the                     you need to configure your miner in this issue.
best and brightest movers and shakers in the space [IMG-
013].

While you’re at it, extend your stay and spend Cinco De
Mayo with The 256 Foundation at our second fundraiser,
Telehash #2. Everything is bigger in Texas, so set your
expectations high for this one. All of the lead developers                                 [IMG-014] FREE SAMOURAI
from the grant projects will be present to talk first-hand
about how to dismantle the proprietary mining empire.                    If you want to continue seeing developers build free and
                                                                         open solutions be sure to support the Samourai Wallet
                                                                         developers by making a tax-deductible contribution to their
                                                                         legal defense fund here. The first step in ensuring a future of
                                                                         free and open Bitcoin development starts with freeing these
                                                                         developers.


                                                                                                                   Live Free or Die,
                                                                                                                     -econoalchemist


                                                              The 256 Foundation
                                                                  Page 6 of 6


===== DOCUMENT 6 of 27 =====
DATE: 2025-06
LABEL: June 2025
TITLE: You know, I'm something of a Decentralized Pool Myself
FILE: 256Foundation-Newsletter-2506_v1.pdf
SOURCE: https://github.com/256foundation/News/blob/main/256Foundation-Newsletter-2506_v1.pdf

You know, I’m Something of a Decentralized Pool Myself
By: The 256 Foundation
A monthly newsletter
                                                                 opinions expressed do not necessarily reflect those of Proto
                                                                 Global, LLC
June 2025


Introduction:                                                    prosecutors had been suppressing exculpatory evidence for
Welcome to the sixth newsletter produced by The 256              nearly year. Apparently, federal prosecutors approached the
Foundation and supported by Proto! May was an eventful           agency responsible for Money Services Businesses
month for the Bitcoin mining industry with events ranging        licensing requirements, FinCEN, and asked them for their
from the second 256 Foundation Telehash to the 2025              opinion on whether or not Samourai Wallet would qualify as
Bitcoin Conference in Las Vegas. There are several               a Money Transmitter and be required to obtain a Money
interesting things developing so dive in and catch up on the     Transmitter’s License AND FINCEN EXPLICITLY
latest news, mining industry developments, progress              REPLIED “NO”. There are multiple implications of this but
updates on grant projects, Actionable Advice with                to boil it down, this means there were no grounds for
                                                                 bringing the charges against Samourai Wallet in the first
OGBTC, and the current state of the Bitcoin network.             place and secondly that federal prosecutors were aware of
                                                                 evidence that pointed to their innocence and decided not to
All the industry seems to be abuzz with the word                 disclose it for almost a year.
“decentralization”. But you know this is a market top when
the companies who have been building an empire on                May 9, but alas, the rogue federal prosecutors hell-bent on
centralized services show up to the decentralization party       destroying any semblance of freedom-preserving
and try to fit in. This is where words start to lose their       technology responded to the defense counsel’s letter by
meaning. Centralized pools will never decentralize Bitcoin       minimizing their deceit stating that: “There is no basis for a
mining full stop.                                                hearing, nor is there anything to remedy…”. An unfortunate
                                                                 outcome considering this would have been the perfect
                                                                 opportunity for federal prosecutors to submit to the direct
                                                                 orders given by the US Department of Justice, Deputy
                                                                 Attorney General Todd Blanche, in the April 7 memo titled
                                                                 “Ending Regulation By Prosecution”.

                                                                 May 14, Judge Berman, after reading both sides of the
                                                                 issue, decides to suggest that defense counsel raise this
                                                                 issue in the pretrial motion. Signaling that Judge Berman
                                                                 finds little to no issue with the prosecution’s behavior.

                  [IMG-001] Spiderman Meme                       May 29, defense counsel submits a number of motions,
                                                                 including bringing up the prosecution’s failure to disclose
Definitions:                                                     exculpatory evidence again. Additional motions included
FinCEN = Financial Crimes Enforcement Network                    things like bringing on an additional attorney from Washing
UTXO = Unspent Transaction Output                                DC, a motion for the defendants to have separate trials, and
Th/s = Terahash per second                                       not least of all a compelling motion to dismiss the case. All
Ph/s = Petahash per second                                       signs point to this case going full steam ahead and your
T = Trillion                                                     support is needed now more than ever, donate to their
ASIC = Application Specific Integrated Circuit                   defense fund through p2prights.org.
GUI = Graphical User Interface
FPPS = Full Pay Per Share                                        May 19, backing up just a bit to capture other news,
                                                                 OrangeSurf published a UTXO Report, available here,
News:                                                            which follows on the heels of the raging OP_RETURN
May 5, big news broke in the Samourai Wallet case, the           debate that has engulfed the hearts and minds of Bitcoiners
single most important issue looming over the future of           far and wide the last couple months. One of the concerns
Bitcoin and freedom tech development. In a Letter                from the pro-filter camp is that the UTXO set will get
submitted to the court, defense counsel revealed that federal    bloated to the point that running a Bitcoin node on

                                                      The 256 Foundation
                                                          Page 1 of 9

consumer hardware won’t be possible any longer.                    variable. So how do pools pay miners a steady amount of
OrangeSurf reports that there are ~173 million UTXOs, half         Bitcoin when the rewards filling those coffers are not
of them are less than 1,000 sats, and most of those are use        steady, you may ask. Great question! First of all, it takes a
Taproot. There are several charts and interesting facts in this    metric shit tonne of bitcoin on their balance sheet to offset
report, take a look for yourself to see what really goes into      the periods of time where the pool is experiencing bad luck
the UTXO set.                                                      and not finding any blocks. Read OrangeSurf’s Pool
                                                                   Survival Analysis for full details on the kinds of reserves
                                                                   needed to operate an FPPS pool.

                                                                   What can pool operators do if they can’t afford the reserves
                                                                   needed? They ask Antpool to bankroll them in agreement to
                                                                   operate as a proxy pool. This is how Antpool absorbed
                                                                   Poolin, Braiins, Ultimus Pool, Binance Pool, SecPool,
                                                                   SigmaPool, Rawpool, Luxor, CloverPool (formerly
                                                                   BTC.com), and Mining Squared.

                                                                   So what’s the big deal, you might be wondering, it sounds
                                                                   like miners get steady payouts and the pool operators have
             [IMG-002] UTXO count vs. value bar chart              the cushion they need, where is the downside? Well there
                                                                   are a couple big problems driven by FPPS: One is custody
May 26, BitcoinVeterans holds a Telehash fundraiser                and the other is templates, both lead to increased risk of
seeking donated hashrate to increase their chance of finding       censorship. The custodian can influence pool operators to
a block to support their many great causes. This is an             behave in certain ways and the pool operator can dictate
example of the Telehash idea spreading and enabling people         which transactions are in the templates that miners are
to find new creative ways to incorporate Bitcoin into              hashing on. Another potential issue is increased risk of 51%
fundraisers.                                                       attacks.

May 27, centralized mining company, Bitmain, swoops in             If Antpool is going to continue with the FPPS model then
to decentralize Bitcoin mining! Leave it to Antpool,               that means, like OCEAN, they will have control over
Bitmain’s mining pool, to jump on the “decentralization”           coordinating the payouts but the rest of the transactions in
corporate buzz word craze sweeping through the industry            the template can be chosen by the miner. Which brings us to
lately. At the “World Digital Mining Summit 2025”, which           the next layer here and the elephant in the room: is Bitcoin
looks like it was a cringe Bitmain controlled side event in        mining really getting decentralized by having miners build
Las Vegas riding on the coat tails of the Bitcoin2025              templates with a centralized pool?
conference, the CEO of Antpool apparently took the stage
to unveil their new solution to save the Bitcoin network.          Enabling miners to build their own templates is a great step
                                                                   in the right direction, don’t get me wrong. However, when
                                                                   there is still a centralized pool coordinating the payouts and
                                                                   counting the shares then the impact on centralization really
                                                                   doesn’t amount to much.

                                                                   The idea is that a decentralized mining ecosystem would be
                                                                   more censorship resistant and vise versa as that ecosystem
               [IMG-003] Bitmain’s ridiculous tweet
                                                                   becomes more centralized, the more likely censorship
                                                                   attempts are to succeed. The issue is that while miners
Following up the groundbreaking announcement with this             building their own templates is a good start, the pool
tweet where Bitmain warns that 58% of hashrate is                  operator can choose to or be coerced to enforce limits on
controlled by just two pools! Failing to mention that              which transactions are included in blocks. Such
Antpool combined with their proxies accounts for roughly           enforcement measures by the pool operator might look like
40% of the overall network hashrate. The irony is palpable         excluding shares from certain users who have submitted
that Bitmain is saying Bitcoin mining needs a reset and            work on a non-conforming template or excluding that user’s
Antpool will decentralize mining by giving miners the              payout address.
ability to make their own mining templates, while still
maintaining FPPS payouts.                                          While DATUM and SV2 are good steps toward
                                                                   decentralization, the marketing from companies like
Let’s peel back the layers here and unpack this. FPPS gives        OCEAN and their employees/investors has exaggerated the
miners steady rewards. Block finds on the other hand are           impact of the solutions they have implemented. Suffice it to


                                                        The 256 Foundation
                                                            Page 2 of 9

say that the Antpool announcement should be met with            Stratum v2, and more. If you would like to support
skepticism and centralized pools will never decentralize        OpenSats, please do so here.
Bitcoin mining.
                                                                Additionally, HRF has continued their support of 256
Free & Open Mining Industry Developments:                       Foundation with another grant for 2025, helping provide a
May 5, on Cinco De Mayo 256 Foundation held Telehash            generous portion of the funding needed to keep extending
#2, the second hashrate-fueled fundraising event.               work on Ember One and more. HRF is a non-partisan, non-
Expectations were high as 256 Foundation descended upon         profit organization that promotes and protects human rights
Austin, TX at the former Bitcoin Commons (now the South         globally, with a focus on closed societies. HRF supports a
Nashville Bitcoin Park campus). All of the grant recipients     wide range of programs such as the CCP Disruption
were there to represent their projects and talk about the       Initiative, Combating Kleptocracy, and Impact Litigation to
whole free and open mining stack that 256 Foundation is         name a few. Within the Financial Freedom program at HRF
building. The Telehash ran for 8-hours and a portion of that    is where you will find grants and financial support for
time featured a panel on the Ember One hashboard with           software developers, entrepreneurs, and community builders
Skot, a panel on the Libre Board with Schnitzel, a panel on     tackling the most pressing issues facing activists, especially
Hydra Pool with Jungly, and a panel on Mujina Firmware          around financial surveillance, suppression, and control. This
with Ryan. There were other guests and topics as well           is where 256 Foundation fits in, because dismantling the
throughout the evening. Shout out to The Space Denver for       proprietary mining empire unlocks innovations in Bitcoin
bringing dinner!                                                mining that enable anyone to gain access to these emerging
                                                                technologies. In addition to grants, there are a number of
Public Pool also joined the effort by running a parallel        other initiatives within the Financial Freedom program like
instance that was mining to the same payout address with        the Financial Freedom Report, the Finney Freedom Prize,
roughly 120 Ph/s. In total, at the peaks there were roughly     and CBDC Tracker. Additionally, there are in-person events
2,500 workers contributing roughly 245 Ph/s. The best           hosted throughout the year such as the Global Bitcoin
difficulty was 43.5T, achieved by none other than Mega          Summit. You can support HRF and their many programs
Watt, the same miner who found the golden nonce during          and initiatives here.
Telehash #1.
                                                                Ember One
However, despite all the effort and generous hashrate           There is not a whole lot to update on the Ember One
donations from supporters, unlike Telehash #1, no block         project. The first release was published at the end of April,
was found by any of the miners and 256 Foundation did not       at the conclusion of the first grant cycle, and can be found
raise any money during this fundraiser. The real reward was     here. There are a couple of modifications that are going to
the frens we made along the way. The Telehash was live-         be made for v4 such as adding a reverse polarity protection
streamed and that feed can be found here.                       circuit and another precautionary circuit that will help
                                                                protect USB connected devices in the event of a spike in
                                                                voltage. Once v4 is ready and released, there will be a small
Grant Project Updates:                                          batch of Ember Ones produced specifically for testers and
The next two days after Telehash #2 there was the TEMS          developers; more news on this to be announced. Otherwise,
event bringing together industry participants of all shapes     Ember One development with the Intel BZM2 chip will
and sizes with representatives from mining pools, mining        resume this fall, the exact timing is still to be determined.
companies, the energy sector, and more. There were several
panels covering a wide range of Bitcoin mining related          Libre Board
topics. One of the panels featured most of the 256              Schnitzel wrote a great thread on the Libre board which can
Foundation grant recipients to discuss a high-level overview    be found here. In it, he explains the reasoning behind
of all the projects. That panel was recorded and can be         building an open-source control board, why 256 Foundation
found here.                                                     decided not to use the recently open-sourced Braiins
                                                                Control Board, and some of the applications that the Libre
OpenSats included the 256 Foundation in their eleventh          Board will unlock. Currently, considerations are being made
wave of Bitcoin grants, which were announced on May 14.         for exactly which connectors will be included on the Libre
Even though 256 Foundation didn’t find a block at Telehash      Board, how many of each, and what their placement should
#2, OpenSats came through in a big way with a grant and         be. So far, the list of connectors/buttons that will be
generously supports our mission to dismantle the                included on the first Libre Board include:
proprietary mining empire. OpenSats is a 501(c)(3) public
charity which helps provide sustainable funding for free and         •    Power Button
open-source contributors working on freedom tech and
                                                                     •    Boot mode button
projects that help bitcoin flourish. Some of the many
                                                                     •    SD card slot
projects OpenSats has supported in that past include:
                                                                     •    LED indicator
GrapheneOS, The Tor Project, Sparrow Wallet, SeedSigner,

                                                     The 256 Foundation
                                                         Page 3 of 9

    •     MIPI                                                              potential code bases to start with for the Stratum server
    •     HDMI                                                              however, after review the decision was made instead for
    •     Ethernet                                                          Hydra Pool to now be a simple Stratum server built from
    •     USB-C port x1                                                     the ground up in Rust. Going forward, this will be the
    •     4-pin JST SH connector                                            foundation used to build the rest of Hydra Pool on top of.
    •     12-24v power input                                                Most of this foundational stratum server is currently
    •     USB-C data-only ports x 4                                         working and passing internal tests. Testing will be opened to
    •     Fan connectors for hashboards x4                                  the public soon and announcements along with instructions
    •     Raspberry Pi HAT                                                  will be provided at that time.
    •     Two 100-pin Compute Module connectors
    •     Battery                                                           Actionable Advice:
    •     Control board fan                                                 During TEMS, there was a panel titled: “Beating The Texas
    •     NVME SSD connector                                                Heat” featuring mining pro Marshall Long, moderated by
                                                                            econoalchemist. The following is a transcript of that panel
Mujina Firmware                                                             which is full of insight from Marshall gained over years of
Development on Mujina continues to progress, the ability                    experience. If you prefer to watch the video of this panel, it
for the firmware to deliver a work payload to the ASICs and                 can be found here.
get a response is working now; nearly completing one of
four primary interfaces that the firmware must handle:
                                                                            eco: Marshall, I heard it gets hot in Texas...
delivering work to the ASICs and handling the responses
being one, the API interface for things like a GUI being
                                                                            Marshall ⁓ you know, we've got two seasons in Texas. We
two, retrieving work from the pool and passing back shares
                                                                            have first summer and we have second summer, so.
being three, and reading on-board systems like temperature
sensors being the fourth.
                                                                            eco: All right. What are the most promising cooling
                                                                            technologies currently being deployed to handle Texas's
Hydra Pool
                                                                            extreme heat in mining operations?
The first iteration of Hydra Pool was used for the Cinco De
Mayo Telehash, a fork of CK Pool on the back end that used
                                                                            Marshall: You know, a lot of people still run air mines here.
a modified version of the CK Stats interface for the front
                                                                            The challenge is not only heat, but also, you know, the
end. There were some lessons learned through this exercise
                                                                            upkeep, the maintenance. You know, the guys at Riot do a
and some issues with the back end resulted in the server
                                                                            great job but you know it's a tall order. You know, their new
being restarted approximately nine times during the first
                                                                            site is… There's a lot of immersion there and it's not
few hours of the Telehash before a correcting change was
                                                                            necessarily just for cooling efficiency, but it also keeps the
made and that particular issue was resolved.
                                                                            machines much cooler and cleaner.

                                                                            So, you know, longevity of your machines is a big part
                                                                            because in some places in Texas, it's so humid that even if it
                                                                            gets dusty, you can get shorts. So like mining in Houston,
                                                                            pain in the neck just because it is so humid. So there's the
                                                                            heat, there's the humidity, there's dust. You know, a lot of
                                                                            these places are on job sites, construction sites. All that stuff
                                                                            is, you know, reason to seek alternative measures and then
                                                                            when people ask me well, do you want two-phase cooling?
                                                                            Do you want a regular single phase cooling? Do you want
                                                                            hydro? What's the kind of like, what's the take and I ask
                                                                            people: Where do you want your pain and when do you
                                                                            want it? You know, if you want to do hydro your pain is
                                                                            gonna be upfront because it's expensive and the setup is not
                                                                            trivial. It's a little bit different than normal setups. It's gonna
                                                                            cost you a lot but, you know, you're gonna eat it all up front.

                                                                            Immersion, single phase immersion is a little bit of a longer
        [IMG-004] Hydra Pool Server Performance at Telehash #2              process. It's less expensive. There's other reasons why you
                                                                            might wanna do it. You can use off the shelf air miners that
As development continued after the Telehash, the decision                   you retrofit. You know, it's only been very recent that OEMs
was made to not use CK Pool as the code base for Hydra                      have been making immersion specific machines. ⁓ And
Pool. Both DATUM and Stratum v2 were examined as

                                                                 The 256 Foundation
                                                                     Page 4 of 9

then, know, air you can, it's easy to start, but to keep it         changed and their infrastructure setup changed a little bit as
going, you're gonna get your pain on the back end forever.          they got smarter. But if you're just like new getting into it,
                                                                    most setups are going to be just one and done unless, you
So you just got to pick your poison and where you want to           know, you're a big guy who's got a huge long power
deal with it. Have you taken any operations that were like          contract.
air and then decided to upgrade them to like hydro or
immersion or? Yeah, sure. So that's a bit of an easier task.        ⁓ You know if you're not trying to go super mega industrial
Doing it the other way, much bigger pain in the neck. You           scale and you're having to change as the years go, you
got to take apart the machines and do all these kinds of            know, you're probably just going to have one set up. You're
stuff. I mean, if you want to hear, you know, terror and war        going to make a choice and you're going to stick with it and
stories, I mean, you know.                                          then what role does facility design play in maximizing
                                                                    cooling efficiency and overall energy sustainability? Yeah,
Mr. Schatz and I could sit around a ⁓ fireplace for many            the design is important. It's the most important for, I'll give
hours and cry many tears about how that works. So it's              you a good example, so when you do a immersion right and
better you make your choice the right first time and then           Cameron will tell you this and all the guys at Shell will tell
you never have to make it again. And then just stick with it.       you this: The fluid you choose, that's a really big
                                                                    consideration. There's a lot of vendors, right? You got
eco: How do air-cooled and liquid-cooled or hydro-cooled,           Exxon, you got engineered fluids, and they all sell what
for that matter, systems - how do they compare in                   they claim is different. But as time goes on, you can tell
performance, cost, long-term reliability ⁓ specific to the          those products are mostly the same or widely different. You
Texas climate?                                                      can see fluid changing colors, and then it becomes more
                                                                    acidic and maybe eats all your machines, right? So doing
Marshall: Yeah, sure. So the hydro is just kind of like a           work on the chemistry side for immersion is like, huge.
newer thing. So it's a bit harder to say long term how that
shakes out. It's gotten better. You know, the difficulties there    It's less about the price today as it is the price over five
are, you know, if you have to take those machines out, you          years because the fluid is not free. As much as Cameron
know, those can be 80 pounds a piece. So it's really hard on        would like to sell it for free, well, maybe he wouldn't like to
the ops guys, ops guys and gals to do that stuff. I mean, it's      sell it for free, but ⁓ that fluid's expensive.
it's backbreaking to the stores, especially if they go out or
they have power supply problems, you know, water and                eco: Yeah, and does it come with guarantees? Like, we
electronics doesn't really mix that well. So there's other          guarantee you can run this fluid for 2,000 hours before it
additional safety concerns there.                                   needs to be changed. I mean, every vendor's different, right?
                                                                    So what each vendor will say...
However, you get a benefit if you want to use the heat for
other things. like where this beer is made, we have a hydro         Marshall: Most of them will say that their stuff has been
set up and off the manifold, we preheat the water using the         signed off by the manufacturer, know, that maybe it doesn't
hydro set up. And so, you know, it makes heat reuse much            void your warranty, stuff like that. They've done work with
easier. ⁓ It's just they're heavier, they're more expensive,        the manufacturers, but the chemistry is different and unique
but they use more power. So they're three phase. So, you            between all of them. And so, you know, when we first got
know, how your power is set up is a consideration. If you           into immersion in like 2018, we just use mineral oil. And
only have single phase power, probably not the right fit.           over time, that stuff breaks down. And I had a host of S9s
                                                                    just get fried because we became conductive. I didn't know
You know, the, the immersion has a benefit of being able to         that could happen. So like microfluidics engineering is like
use immersion specific things or being able to convert air          a whole field.
miners to immersion miners as well. So there's that, those
are   kind    of    the   main     considerations    there.         And you really got to do your diligence before you just buy
                                                                    the cheapest or what they claim is the best. There's a whole
eco: Do you find yourself running like a mix of different           bunch of considerations around what pump do I use? Does
cooling techniques in one operation, or is it just like across      it change viscosity when it changes temperatures? Like
the board, all the, all this whole, this whole setup here is        there's a bunch of stuff and every vendor's got different
going to be all air, this one's going to be all hydro, etc?         aspects. So another example is, if you got a certain type of
                                                                    fluid, maybe your fire suppression system has to change to
Yeah, you know, usually unless it's like a long lived site,         meet code, right? Is the flash point of this fluid so high that
you know, like the Riot site's a great example, you know,           maybe you don't need fire suppression in your building?
that's been a very long standing massive operation and              There's a lot of give and takes there.
they've iterated with the times and you can kind of see that
iteration as they go on, you know, their building design


                                                         The 256 Foundation
                                                             Page 5 of 9

eco: Wow, yeah, so that goes into the design of the facility       Micro BT is putting out stuff that's like single phase power
too. Do they like do them? Are the manufacturers like              for exclusively for heat reuse. The Auradine guys just got
suggesting or dictating like you've got to use this pump if        into hydro recently as well. there's a bifurcation between
you're running this fluid or like, you know, we can't get          strategies because they're playing different games. So the
results if you're running this other type of pump.                 arbitration between what they're going to do really comes
                                                                   down to scale and how you can do certain things. Because
Marshall: No, not generally. They're not going to really           what I do with my little 10 megawatt shack might be OK in
make a recommendation on like infrastructure. They'll tell         downtown Houston.
you what they've used before and maybe try to like guide
you. They'll be as helpful as possible. But, you know, most        But if I do those same kind of things inside the city limits
pumps for more or less are just as a reliability thing, you        somewhere else, fire marshal's going to get involved, like
you buy a cheap pump, it's probably going to crap out              you can't do things the same way. And there's a bunch of
earlier than a nice pump. They'll give you more guidance           trade-offs. Fire suppression being another example, a guy
around like flow rates and you know, they can, you know, at        will come in, well, because this fluid XYZ, he's gonna look
least show anyway, they've been very helpful. They'll do           at like a safety data sheet and he wants to see when does
like a fluid simulation of your design for you and say like,       this fluid become flammable and all these other
maybe you can optimize here. Maybe this drop of this pipe          considerations that mid-tier and small-tier guys don't even
could be different. It's at scale when you're buying a lot         have to think about. I imagine there's like… the peripherals
that's more collaborative than just buying stuff off the shelf.    can just kind of spiral out of control. All it takes is the fire
So ⁓ I'll say they'll help you as much as they can, but            marshal to just say, we're going to revoke your certificate of
they're not going to vouch for other companies' equipment.         occupancy. Guess what? You can't work there. Then it
                                                                   becomes illegal, because one guy had a bad day. So there's a
eco: Can they help you in supporting ways, like doing oil          lot of considerations. And you've got to be able to point to
analysis after the fluid's been in use and kind of give you an     the fire code, like, no, that's not the case. And that's where
idea of the metals that are starting to show up and break          having a good vendor for ⁓ even hydro, because they'll put
down?                                                              additives in the water to reduce scaling and fluid.

Marshall: Yeah, so that's a big thing that a good fluid vendor     And also like the infrastructure providers, you you've got to
should offer you, where maybe you have a chemist that can          work with them so you know the laws. And so, you know,
do small-scale testing, like voltage breakdown to see at           one guy having a bad day can't shut down a billion dollar
what point does the voltage, does the fluid conduct the            operation.
electricity or acidity levels. But if you have a good vendor,
they should say, like once a quarter or once a month, send         eco: Right. Do you find that like ASIC manufacturers are
us a couple gallons as a sample. And they'll do like full          making suggestions about like what like hydro to run
crazy testing. Like Shell's got an FTIR machine, which is          through their miners, like what immersion their miners can
like a multi-million dollar machine that can tell you this is      go into or like are miner manufacturers and immersion fluid
how much dissolved silicon from a thermal paste is in there.       manufacturers working together or do you have to kind of
And this is XYZ, here's your fluid is aged XYZ. They'll            play that role of liaison?
give you the whole breakdown. So any good vendor should
have a testing facility to do that for you.                        Marshall: Yeah, that's a good question. I can say that there
                                                                   have been OEMs that have worked directly with the fluid
eco: And then how many miners are balancing the trade-offs         providers. If you want details and specifics on that, can
between, or sorry, how are miners balancing the trade-offs         definitely ask Cameron. I don't know what's public and
between upfront investment and operational savings when            what's not. I can say that when they come up with a new
selecting cooling infrastructure?                                  fluid, most vendors will reach out to OEMs and say hey, can
                                                                   you like put this on an approved list saying that hey, we've
Marshall: Yeah, and I think that's a question that's gonna         tested this we've tried this? There is some behind-the-scenes
change based on two things. The public guys are gonna play         like co-development. I would say for, you know, use case
a different game than the non-public guys. Public guys have        specific applications. I know Engineered Fluids does as a
a bunch of different considerations. Right now, I ⁓ would          little bit, too. So it's not just here's a fluid because what
say the majority of public miners is let's grow at all costs.      works for Bitcoin miners is not necessarily what works for
Some of them have chosen different treasury management             you know guys running GPUs. You know they want
strategies and that kind of stuff and all those kind of, I         different volumes and different viscosities.
would say, take a front row to these kinds of design choices.
⁓ I think the industry for hydro, and Tyler and I were just        So it's not like a one size fits all thing. So there's a lot of
talking about this, is evolving rapidly.                           collaboration, I'd say for sure.


                                                        The 256 Foundation
                                                            Page 6 of 9

eco: All right. What innovations on the horizon could              looking at this like if they don't do it, their competitors are
redefine how we approach thermal management in large               going to do it. Not even that; if they don't do it, we will do
scale mining under high heat conditions?                           it. So like early on, I know, maybe 2020 micro BT wouldn't
                                                                   give you SSH access unless you really begged and pleaded.
Marshall: Yeah, that's you know, what's really interesting is      But the tool that they had, had a sequel injection
everybody's like AI, HPC, blah, blah. If you go to any HPC         vulnerability, so we would just give ourselves root access
conference, these people think that cooling 1000 watts is          through the Whatsminer tool.
like cutting edge insane, like nobody can do it.
                                                                   And you know, you can just see through the Whatsminer
So I went to Open Compute like a year ago, actually with           tool by updating your pool. Okay, cool. And then for like
Cameron, and I walked in and the guys at, I think it was           two years, it was cat and mouse. They would patch that.
Intel, they had this little mini immersion set up and they had     We'd find another one where if you shove an SD card
the processor clocked to like 900 watts and everybody there        during post, it'll dump the firmware. And now you got the
was like, my God, this is so revolutionary. And I'm just like,     firmware and you can do all these things. This whole
this is like five years ago. So the fact that Bitcoin has like     adversarial kind of, when I'm spending hundreds of millions
just blown HPC out of the water from like what we can              of dollars with you, no other vendor would have done that
cool.                                                              in the professional world, right? And so now it's starting to
                                                                   kind of come back to where it should be, which has been
When we were talking to vendors, they're like, what flow           very useful for just running a good operation.
rates are you pushing? And it's several orders of magnitude
beyond what any HPC data center is doing. And it's                 eco: Have you been confronted with like environmental
interesting when you sit down with these people and say,           concerns like, you know, cooling Bitcoin miners with hydro
oh, we're moving 1,700 liters a minute. Their face melts off.      uses a lot of water?
And you're like, we'd like to be faster, maybe, or whatever.
They just never thought that cooling in one small footprint,       Marshall: Yeah.
5,000 watts, is even thinkable.
                                                                   eco: How do you how do you counter those?
So the fact that the AI guys are starting to learn from the
Bitcoin guys makes us feel like we're not little boys              Marshall: There's most of the marketing now. There's a very
anymore. We're big guys who are starting to pay attention a        infamous Bitcoin site that I will leave names out in West
little bit. So that's been really cool to see. As far as what's    Texas where these guys used Bitmain cooling. They had
changing, I think the biggest change is the OEMs. MicroBT          like a cooling tower and the Bitmain hydros and they had to
⁓ was the first to come out with an immersion-specific             drill wells and they started a reverse osmosis water
SKU. ⁓ Riot famously purchased a lot of those. ⁓ Those             treatment plant in order to get enough water to run in their
are interesting to see. Because before, you got to take the        cooling tower. And then as the water table depleted, the
fans off and have special firmware and really do all this          water got more and more briny and more and more salty,
bespoke stuff which just takes times away. Bitmain started         and then their RO system got clogged up. And then their
shipping SKUs without fans. Auradine's got SKUs without            site failed, and then it was like a whole massive thing. And
fans. So seeing the OEMs kind of tailored to us now instead        so now anybody doing a tour, their big selling point from
of us trying to like square peg round hole situation has been      these, like let's say Heatcore for example, they'll say you
good to see. You go into any, if you're a big boy, you buy         don't have to add any water. Once you fill the system up,
$100 million of Microsoft contracts, they're gonna have a          that's it. It's a closed system.
guy there to help you make your stuff work for you.
                                                                   That's everybody's marketing point now is we don't use
And that's just now becoming the case for Bitcoin. And it's        water. ⁓ Beyond that, you know, it just gets so freaking hot
good to see. Because before, everybody's just like, you can't      that OEMs are starting to use better components. Like
figure it out. You can't hack our firmware or whatever.            micro BTs and Auradine hydro units can withstand like 65
That's your problem. No, you can't have SSH access to the          Celsius degrees or 75 Celsius degree water coming into the
boards. And it was like pulling teeth up until like three years    machine so that you can use no water. So the, you know,
ago, maybe. But now they're starting to come along and see         outside of that, it also depends on where you're located. If it
like, look, we now have the money to hire serious                  was a previously EPA investigated site.
professionals, serious electrical engineers. If you're not
going to build it, we'll build it ourselves. So you can either     You get one drop of immersion fluid outside the containing
come along or not.                                                 wall of your building. It's a whole like EPA shutdown. They
                                                                   gotta come and do soil studies and sampling and all this
And now to see the OEMs kind of play ball a little bit has         other crap because somebody before you had messed up the
been really encouraging. So yeah, I imagine like they're           site, right? From like a previous business or whatever. you


                                                        The 256 Foundation
                                                            Page 7 of 9

know, anything you can do to keep things contained is super          State of the Network:
important because it just takes you spilling a couple of liters      Hashrate on the 14-day MA according to mempool.space
of immersion fluid outside a previously condemned site and           increased from ~837 Eh/s at the beginning of May to a new
then can shut you down for a week while they do this                 all-time high of ~917 Eh/s by the end of May, marking
sample study for like a gallon of milk spilling outside              ~9.5% growth for the month and ~17% year to date.
basically like rainwater runoff all this kind of crap when
you hit scale it's like a huge operational overhead so
anybody here that you know that runs a big op they've all
got to deal with this crap and it's like it's a very serious time
and money sink to do that and so working with the people
to make sure that you can limit all those risks long till is
super beneficial ⁓

eco: We've got five minutes left. Are we gonna take
                                                                          [IMG-005] 2025 hashrate/difficulty chart from mempool.space
questions on this panel? All right, I'm wondering if you've
got any funny anecdotes from your experience as it relates
                                                                     Difficulty was 119.12T at it’s lowest in May and 126.98T at
to keeping miners cool.
                                                                     it’s highest, which is a 6.6% increase for the month. All
                                                                     together for 2025 up to Epoch #446, difficulty has gone up
Marshall: Yeah, we used to do this thing where if you start
                                                                     ~15.6%.
working, I still do this in my current facility, my little test
lab. If you come in there and you want a tour, you have to           According to the Hashrate Index, ASIC prices have
taste the fluid.                                                     increased ever so slightly over the last month. The more
                                                                     efficient miners like the <19 J/Th models are now fetching
eco: No, you don't. Come on.                                         $17.77 per terahash, models between 19J/Th – 25J/Th are
                                                                     selling for $8.85 per terahash, and models >25J/Th are
Marshall: I make people put a little finger in there because         selling for $3.02 per terahash. You can expect to pay
the good fluid is all biodegradable. They use it in like make        roughly $4,000 for a new-gen miner with 230+ Th/s.
up and stuff.

eco: It's like food grade?

Marshall: Yeah. And so that's like my first like right of
passage. If you want to tour at my dojo, you got to taste it.
And the feedback, at least for the Shell, I don't know if you
guys got in this feedback, but your fluid has a slight buttery
taste. So ⁓ that's the most common feedback we get. I don't
know if that's useful, but maybe a selling point. ⁓
                                                                               [IMG-006] Miner Prices from Luxor’s Hashrate Index
We also, we like to sous vide steaks in there as well. So for
lunch, we get out the flamethrower, finish it off. It's the
                                                                     Hashvalue over the month of May peaked at ~59,000
perfect temperature for like a nice, it's a little bit too well
                                                                     sats/Ph per day and closed the month out at ~52,000 sats/Ph
done for my taste, but you know, nice like medium. We do a
                                                                     per day, according to the Braiins Insights dashboard.
lot of sous vide in the tanks. ⁓ So yeah, those are just a few
of what I can mention publicly. So.

eco: That's awesome. Let's give Marshall a round of
applause here.

And then I think we got enough time for two questions
before we break for lunch, right? one more panel, okay.

All right, well thanks. Huge round of applause for these
gentlemen. You guys crushed it. ⁓ Note to self, I'll double
check the state.


                                                                                   [IMG-007] Hashprice from Braiins Insights


                                                          The 256 Foundation
                                                              Page 8 of 9

The next halving will occur at block height 1,050,000 which
should be in roughly 1,026 days or in other words ~150,000
blocks from time of publishing this newsletter.

Conclusion:
Thank you for reading the sixth 256 Foundation newsletter.
Keep an eye out for more newsletters on a monthly basis in
your email inbox by subscribing at 256foundation.org. Or
you can download .pdf versions of the newsletters from
there as well. You can also find these newsletters published
in article form on Nostr.


                  [IMG-008] FREE SAMOURAI

If you want to continue seeing developers build free and
open solutions be sure to support the Samourai Wallet
developers by making a tax-deductible contribution to their
legal defense fund here. The first step in ensuring a future of
free and open Bitcoin development starts with freeing these
developers. Also, consider talking to your local
representatives about the Blockchain Regulatory Certainty
Act which aims to codify that software developers cannot
be held liable for the actions of end-users.


                                         Live Free or Die,
                                           -econoalchemist


                                                        The 256 Foundation
                                                            Page 9 of 9


===== DOCUMENT 7 of 27 =====
DATE: 2025-07
LABEL: July 2025
TITLE: The Bigger They Are, The Harder They Fall
FILE: 256Foundation-Newsletter-2507_v1.pdf
SOURCE: https://github.com/256foundation/News/blob/main/256Foundation-Newsletter-2507_v1.pdf

256NEWS #7
                    The Bigger They Are, The Harder They Fall

By: The 256 Foundation
A monthly newsletter                                               opinions expressed do not necessarily reflect those of Proto
                                                                   Global, LLC


July 2025

INTRODUCTION:                                                      Tornado Cash were targeted under Biden-era directives that
Welcome to the seventh newsletter produced by The 256              sought to hold developers responsible for end-user conduct.
Foundation and supported by Proto! June was an eventful            While there are no laws against developing CoinJoin
month for the Bitcoin mining industry with events ranging          software for example, recent actions from the federal
from Bitcoin surpassing block height 900,000 to difficulty         government seek to put developers behind bars by
dropping ~7.5%. There are several interesting things               entangling them with allegations of crimes committed by
developing in and around the Bitcoin mining industry so            the end-users. Essentially, punishing developers of neutral
dive in and catch up on the latest news, developments, grant       technology through law-fare, not because the developers
progress updates, Actionable Advice, and the current state         actually committed any crimes but because the software
of the Bitcoin network. You’ll gain a better understanding of      gives anyone access to technology that enables freedoms
how the closed systems built to block access to freedom            beyond the control of the legacy financial panopticon.
enhancing technologies are proving to be the proprietary
mining empire’s greatest point of weakness.                        On June 8, news broke that the language of the BRCA was
                                                                   included as part of the CLARITY Act under Section 110.
                                                                   The CLARITY Act already had much more support and was
                                                                   further along in the legislative process than the BRCA,
                                                                   having the BRCA rolled into the CLARITY Act gave the
                                                                   objectives a much better chance at succeeding. The
                                                                   CLARITY Act aims to establish rules for digital assets
                                                                   while establishing which agencies have regulatory
                                                                   oversight. From the link provided on the Save Our Wallets
                                                                   website, you can read that Section 110 text here. When you
                                                                   take into account the proposed modification in the
                                                                   CLARITY Act Section 110 and the existing text of the
                                                                   referenced US code, Section 5312(c)(1)(A) of title 31, it
                                                                   would appear that developers are only implicitly exempt
                                                                   from the definition of “financial institutions” required to
                                                                   comply with Bank Secrecy Act regulations, like obtaining a
            [IMG-001] Achilles meme from Solo Satoshi              money transmitters license, because they are not explicitly
                                                                   listed among the entities that are required to comply.
DEFINITIONS:
BRCA = Blockchain Regulatory Certainty Act                         Call me skeptical but I don’t see how this changes anything
FinCEN = Financial Crimes Enforcement Network                      for developers like Samourai Wallet or Tornado Cash who
SDNY = Southern District of New York                               are currently facing charges, despite their cases being cited
UI = User Interface                                                as reasons for the call to action to get this legislation passed.
                                                                   Just because developers are not explicitly identified as
FREEDOM TECH NEWS:                                                 “financial institutions” doesn’t mean federal prosecutors are
June 3, in an effort driven by Matt Corallo and the Save           going to drop the charges. In fact, there is already guidance
Our Wallets organization, industry participants are seeking        widely accepted among a relevant community of industry
to codify the Blockchain Regulatory Certainty Act. At a            peers, like the 2019 FinCEN Guidance, which does in fact
high level, the BRCA would ensure that developers and              explicitly identify developers as not being among those who
service providers are exempt from money transmitting               are required to obtain a money transmitters license and
business licensing requirements if they do not control             federal prosecutors have argued that FinCEN’s opinion
customer funds, only provide software or computing                 doesn’t matter. Furthermore, in both cases prosecutors have
services, and do not act as a financial intermediary. The call     already removed the allegations related to the developers
to action comes after developers like Samourai Wallet and          not registering as money transmitting businesses which


                                                        The 256 Foundation
                                                           Page 1 of 10

stemmed from 18 U.S.C. § 1960(b)(1)(B). For all intents                   CoinJoin but also conflating centralized coordinators with
and purposes, the CLARITY Act will do absolutely nothing                  decentralized website (whatever that means). In any case, it
for Samourai Wallet or Tornado Cash, although sad that it                 is clear that the US federal government across several
even needed to be said, it is good to see software developers             agencies is continuing the which hunt that the Biden
are not being identified as financial institutions.                       administration was carrying out against software developers
                                                                          and these agencies are working around the clock to muddy
June 4, US Secret Service joins in on the anti-privacy                    the waters and confuse terms.
campaign, conflating mixers with CoinJoins and posting a
ridiculous transaction graph representing CoinJoins that                  The reason words matter to me so much in this context and
demonstrates the agency’s lack of understanding around the                the reason I have taken so much of your time to explain this
technology.                                                               example and bring you to this point is because innocent
                                                                          developers like Samourai Wallet are facing 25-years in
                                                                          federal prison precisely because the letter of the law is
                                                                          being twisted to conform to a predetermined conclusion
                                                                          regardless of what the facts of the matter illuminate and
                                                                          regardless of what the text of the laws actually state.
                                                                          Technology that enables individual freedoms will not be
                                                                          tolerated by the State, as this technology erodes the State’s
                                                                          power. A State will stop at nothing to ensure those
                                                                          responsible for developing the freedom tech are severely
                                                                          punished; and if they can’t prove it using the letter of the
                                                                          law then they will use corrupt judges and prosecutors, they
                                                                          will suppress evidence, they will hide expert testimony from
                                                                          jurors, and they will twist the words of the laws to conform
                                                                          to their will. Worst of all is that all wallet developers, node
                                                                          operators, and miners are next if this campaign is not
                                                                          derailed immediately.

       [IMG-002] Government propaganda vs. CoinJoin tx graph
                                                                          June 5, Luxor becomes AntPool. In a post by boerst, he
                                                                          reveals that mining pool operator, Luxor, changed the block
The exact intentions of the Secret Service getting involved               template they were distributing to miners from reading
here is not quite clear, as the messaging gets lost in the                “Powered by Luxor Tech” to “Mined by AntPool”. Boerst
inaccuracies. The Twitter post was accompanied with a link                was able to continue hashing on this mangled template for
to a long-form article on the topic. For the sake of clarity              several minutes with his shares continuing to be accepted by
here, the term “mixers” means that users send their coins to              Luxor. In the thread, boerst takes things a couple steps
a custodian who then sends them back other coins with a                   further, demonstrating that the templates from both AntPool
different transaction history. The term “CoinJoin” means a                and Luxor were an exact 1:1 match and he also confirmed
non-custodial collaborative transaction and can be                        in his Bitaxe logs and Luxor dashboard that his shares on
coordinated peer-to-peer, with the use of a coordinator                   that template were accepted as valid.
server, or by other means but in no circumstance does a
CoinJoin involve someone else taking custody of the user’s
coins. In the Secret Service’s long-form text, they seem
more concerned about dividing mixers into two categories:
centralized and decentralized, rather than having any
concern for the distinguishing custody factor. In one
section, the Secret Service states that: “Decentralized
mixers typically facilitate transactions using a peer-to-peer
or coordinated method involving customer transactions that
are combined and then reallocated individually to each
sender. Bitcoin enables this process using the ‘CoinJoin’
protocol which is performed with specific wallet software
providers and removes any requirement for users to visit
decentralized mixing services websites.”. In one breath the
Secret Service is attempting to establish that CoinJoins are a
type of decentralized mixer, yet in the next breath they state
that the CoinJoin protocol removes the need to visit                                      [IMG-003] Luxor becomes AntPool
decentralized websites… not only conflating mixers with

                                                               The 256 Foundation
                                                                  Page 2 of 10

This discovery confirms without a doubt that Luxor is an         the answer. mononautical’s transaction was confirmed for
AntPool proxy, which was already widely accepted as truth.       only 11 sats.
But this also raises a few questions; like how can these tags
be taken as true and accurate? What kind of technical            June 21, fresh Bitcoin mining heat re-use install from
malfunction had to occur for this to happen and what steps       Softwarm LLC. Featuring 30 Antminer S21 miners,
have been taken to resolve the issue? Would Luxor have           generating over 6 Ph/s, and utilizing a radiator to help
been credited for the coins from that block reward if one of     manage excess heat from the immersion system this setup
their miners had found a golden nonce while hashing on           helps offset the cost of generating heat through Bitcoin
that template?                                                   mining. A trend that is increasing in popularity and will be
                                                                 more common place as the proprietary mining empire
June 6, DeFi Education Fund publishes Samourai Wallet            crumbles into dust and a million open-source solutions
Amicus Brief after judge Berman denied the submission            bloom.
just three days prior on June 3, stating “… not needed at
this time. Perhaps amicus can be helpful at oral argument        June 22, 256 Foundation’s own Rod Roudi presents at the
of motion to dismiss.”. The Amicus Brief obliterates the         BTCPay Day event in Prague. Rod has been traveling
SDNY’s legal theory that non-custodial wallet developers         throughout Europe this summer spreading awareness of the
have conspired to operate an unlicensed money transmitter        work being done in Nashville, TN and Austin, TX at the
business on account that the government would need to            two Bitcoin Park campuses and at the 256 Foundation to
prove Samourai Wallet “transferr[ed] funds on behalf of the      build grassroots support for freedom tech adoption.
public.” 18 U.S.C. §1960(b)(2). Likely in reaction to both
the public publishing of this Amicus Brief and the               June 22, The Space Denver begins new Bitcoin mining heat
disclosure that FinCEN explicitly told SDNY prosecutors          re-use install. The guys running The Space Denver are not
that Samourai Wallet was not required to obtain a money          afraid to eat their own dog food and use the techniques and
transmitters license, on June 24 prosecutors filed an updated    technologies driving their mission to intelligently stack sats
indictment that added heavy emphasis on Samourai                 while producing necessary heat at their facility. Having in-
“transferring funds on behalf of the public”, going so far as    house installations like this is a great way to show case
to flat out lie about the technical workings of the Whirlpool    some of the possibilities that Bitcoin mining heat re-use
coordinator claiming that Samourai’s server generated            offers to the many guests who frequent the Space’s events.
addresses on behalf of users, which is utterly false.
Additionally, the superseding indictment removed the
allegation that Samourai Wallet failed to obtain a money
transmitters license but left in the part about transferring
funds on behalf of the public they allegedly knew were
criminal proceeds and the rogue SDNY prosecutors also
added an allegation related to a conspiracy to possess and
distribute controlled substances under the conspiracy to
launder money count. In an 83-page opposition letter filed
on June 26, the deranged SDNY prosecutors have their
mental gymnastics on full display as they attempt to argue
denying defense pre-trial motions. On July 3, defense filed a
letter seeking to have an attorney present the Amicus Brief
on behalf of the DeFi Education Fund, the Blockchain
Association, Coin Center, the Bitcoin Policy Institute, and
the Digital Chamber during the oral arguments of the
motion to dismiss.
                                                                             [IMG-004] Installation at The Space Denver

June 7, mononautical of the Mempool Open Source Project
                                                                 June 23, Ashigaru announces new Whirlpool coordinator in
confirms that his sub 1-sat/vB transaction was picked up
                                                                 what has been some of the most exciting news I’ve seen in a
and mined by Mara after a month from when it was
                                                                 long time. I have long advocated for CoinJoins and
originally broadcast. The lower than usual fee rate offered a
                                                                 specifically Samourai Wallet’s implementation called
clever way for mononautical to bait miners who adjust their
                                                                 Whirlpool for many reasons but in particular, from a
nodes to accept a -minrelaytxfee lower than 1 sat/vB,
                                                                 miner’s perspective, Whirlpool has proven to be an
affirming that miners are indeed taking transactions from
                                                                 excellent tool for achieving anonymity on a public ledger.
the p2p network with lower fees than the commonly
                                                                 As a privacy conscience miner, the primary threat vectors
accepted standard minimum fee rate. If you are looking to
                                                                 come from three domains: physical, network level, and on-
save on transaction fees and time is not of the essence for
                                                                 chain. To mitigate on-chain privacy concerns, Whirlpool
you, then lowering your fee rate below 1 sat/vB might be
                                                                 ensures that the mining pool operator cannot track how I

                                                      The 256 Foundation
                                                         Page 3 of 10

spend my rewards and likewise Whirlpool prevents those            June 10, Spiral announces Senior Engineering position to
whom I spend my rewards with from being able to                   work on Stratum v2, demonstrating that incremental steps
determine that I am mining bitcoin. In April 2024, the            are being taken to help make the tools accessible that will
Samourai Wallet Whirlpool coordinator went offline during         help decentralize Bitcoin mining. Not that Stratum v2 is a
the law enforcement seizure of Samourai Wallet’s vital            silver bullet on it’s own but it does offer improvements that
infrastructure components. In the months after the arrests, a     go in the right direction such as encrypting the connections
group of former users forked the mobile Samourai Wallet           between miners and pools instead of sending it in plain text
application and have made many of the same familiar tools         like Stratum v1, compressing the data so that less
available once again. The development continued and has           bandwidth is needed, and enabling miners to run their own
now culminated in the release of Ashigaru’s Whirlpool             node and generate their own templates. The big caveat to
coordinator, a bold move to say the least considering the         that last point though is that if centralized pools are still in
Samourai Wallet developers are still under house arrest           the mix for share accounting and dictating the coinbase
awaiting trial at the end of 2025 and the implications of         payouts then the emphasis on decentralization is a little
which yet to be realized. This however, is exactly what is so     overblown to put it mildly. Take OCEAN for example,
energizing about the Ashigaru project, it is deeply rooted in     DATUM was their version of a new work protocol like
the same philosophy that forged freedom tech like PGP             Stratum v2 and if you took the OCEAN marketing at face-
encryption and Bitcoin itself; that cypherpunks write code,       value (which many do unfortunately) then you would think
unstoppable code that anyone can access to bolster their          that OCEAN has made significant strides in decentralizing
individual freedoms like the right to privacy in the digital      Bitcoin mining. In reality, and as I explained in the last
age. You can learn more about the Ashigaru Whirlpool              newsletter, a centralized pool will never decentralize
release with a couple of recently recorded podcasts: Rock         Bitcoin mining, full stop. While it is great to see resources
Paper Bitcoin Podcast, Ungovernable Misfits Podcast #1,           being used to employ developers full time on developing
and Ungovernable Misfits Podcast #2.                              these tools, I urge readers to keep these developments in
                                                                  perspective and understand that there is a long ways to go
June 28, Difficulty drops ~7.5% in the biggest downward           before Bitcoin mining is decentralized. For the record, I
adjustment since the great Chinese mining ban of the              think Spiral and the Stratum v2 team have been more
summer of 2021 when difficulty dropped by by almost 40%           straight forward in their marketing than other companies
in a single adjustment. Speculations as to what the               like OCEAN.
underlying cause was for such a large adjustment range
from Iranian nuclear powered Bitcoin mining operations            June 11, Digital Shovel jumps on the Bitaxe bandwagon
were interrupted during the US bombing to large-scale             with the BluAx. This represents a calculated move toward
miners curtailing their mining operations in response to a        democratizing Bitcoin mining as the market demand for
Texas heat wave. Whatever the case, the downward                  Bitaxe-style devices has been clear and present. Priced at
adjustment proved a good opportunity for at least one             $99, this compact solo miner consumes a mere 18 watts,
home-sized miner who was awarded block #903883 on Solo            rendering it viable for individual use without the need for
CK Pool in Europe with ~2.3Ph/s.                                  industrial infrastructure, concerns over the produced heat, or
                                                                  considerations for the noise like larger mining rigs. Built
                                                                  upon the open-source Bitaxe framework, it challenges the
FREE & OPEN MINING DEVELOPMENTS:                                  centralizing grip of large-scale mining operations, time will
May 31, Ziya Sadr plugs in his Bitaxe Gamma after                 tell if Digital Shovel abides by the open-source Bitaxe
returning home from the HRF Oslo Freedom Forum. This              license and they contribute back their modifications to the
post is actually from the last day in May but I didn’t see it     open-source community. Digital Shovel’s pivot from
until later so I’m including it here. This is of significance     supporting mega-miners to enabling individual participation
because it demonstrates the reach and accessibility of            underscores a deliberate effort to reinforce Bitcoin’s
freedom tech and that Bitaxe has the potential to bring           foundational ethos. The BluAx is a precise instrument for
Bitcoin mining to anyone in the world. Some of you may            those seeking to engage directly with Bitcoin mining,
recall that Ziya Sadr was arrested in September 2022 by           unencumbered by external gatekeepers.
Iranian security forces and held without explanation for
several weeks. Ziya has accomplished significant Bitcoin          June 12, the Stratum v2 reference implementation team
education contributions bringing in-depth technical               publishes a new case study on how SV2 increases mining
knowledge and practical privacy considerations to people in       profits over SV1 by at least 7.4%. This study was a
Iran and surrounding areas. Ziya has been a champion of           collaborative effort involving multiple contributors from the
freedom technologies and has demonstrated how to use              mining community, including Hashlabs, DMND Pool, and
Bitcoin as a freedom tool when faced with an oppressive           SRI. The ability for the Stratum v2 miner-to-pool
government in his day to day life. Seeing Ziya value his          connection to be encrypted is protection against hashrate
Bitaxe says a lot about the potential he sees in it as another    hijacking and can be a significant boost to net profits for
tool used in the fight for freedom.                               miners that fall victim to such schemes. Braiins estimates


                                                       The 256 Foundation
                                                          Page 4 of 10

that 1% to 2% of hashrate is being stolen. The article goes                 to the owner and a lawsuit is filed, whose ass will be on the
on to explain several other areas of improvements for                       line? Probably the distributor and/or manufacturer of that
miners like increased block propagation with speeds                         specific Bitaxe. One likely and painful outcome in that
reduced from 96.3ms to 3.44ms and reduced job latency                       situation would be that distributors only want to sell the real
when used with the Job Declaration component from 228ms                     open-source Bitaxe design if it undergoes testing,
to 2.44ms or without the Job Declaration component the                      qualification, and validation for UL Standards or CPSC
speed is still four times faster than in Stratum v1. The article            Regulations adherence, which I think would be burdensome
is rich in detail and charts, I would recommend reading the                 and costly, roping the Bitaxe project into a never-ending
whole thing here.                                                           loop of jumping through bureaucratic hoops. This would put
                                                                            pressure on the manufacturers to ensure the products they
                                                                            produce meet these burdens. Down the road, if there are
                                                                            really going to be millions of these small mining devices
                                                                            deployed in homes around the world, then the
                                                                            manufacturing facilities are going to need to be sized
                                                                            accordingly and any rational business manager is going to
                                                                            want that operation insured. Insurance companies may not
                                                                            grant product liability insurance to manufacturers unless
                                                                            they can demonstrate that their produced goods adhere to
                                                                            the standards and regulations in the country they are sold. A
                                                                            PITA to say the least but one that I anticipate will need to be
                                                                            dealt with sooner than later.

                                                                            June 20, Bitaxe workshop pops up in El Salvador where
                                                                            students learn how to setup a small Bitcoin miner. This is a
                                                                            great way to get introduced to Bitcoin mining as the
                                                                            students don’t need to worry about evacuating the excessive
      [IMG-005] Stratum v2 w/Job Declaration latency reduction
                                                                            heat of a larger miner or worry about mitigating the noise
                                                                            either. Plus the students still learn all the basics about
June 16, miner posing as a Bitaxe explodes! This is why
                                                                            Bitcoin mining like how to configure their preferred pool,
Chinese knock-offs can’t be trusted, they take open-source
                                                                            monitoring hashrate, and more.
designs and modify the bill of materials, often choosing
cheaper and untested components, or they completely
                                                                            June 23, IxTech expands production capabilities to continue
change the circuitry and then the end-user winds up with a
                                                                            supplying their sales catalog of Bitaxe and NerdMiner
product that they think is the tried and true open-source
                                                                            devices. From the provided pictures you can see multiple
version but it isn’t and it doesn’t have a known source so
                                                                            pick and place machines, a manual solder pasting station,
they can’t verify it. The next thing you know, boom, house
                                                                            lots of inventory, a reflow oven, and more. If there are going
fire, much death.
                                                                            to be millions of home mining devices deployed then there
                                                                            are going to need to be many more manufacturers like this
                                                                            popping up. You can see all their products online here.

                                                                            June 25, Bitaxe production hits Kenya with the introduction
                                                                            of the Bitshoka from Gridless. When I attended the Africa
                                                                            Bitcoin Conference in December 2024, Bitaxe was a big hit.
                                                                            Walking around the conference center with Skot was like
                                                                            hanging out with a rock star, everybody wanted to meet him
                                                                            and learn more about the project; one consistent theme I
                                                                            noticed was that people wanted to start making Bitaxes in
                                                                            Africa. I’m thrilled to see that Gridless was keen to that
                                                                            signal and that they have taken steps to team up with a local
                                                                            Kenyan PCB manufacturer to get things started.


                                                                            GRANT PROJECT UPDATES:
           [IMG-006] Bitaxe knock off almost kills owner                    The 256 Foundation team has been crushing each project,
Perhaps it’s best not to cast stones in a glass house though                getting closer to completing the first open-source complete
because in the event that a legitimate Bitaxe causes damage                 mining stack. By the end of August, the first few Ember
                                                                            One 00 v4 hashboards should be out in the field being tested

                                                                 The 256 Foundation
                                                                    Page 5 of 10

by a small group of developers and testers. Then by the end        swappable hashboard replacement without a system reboot,
of September, the first official release of the Libre Board        or any system interruption at all. As the hashboards
should be out along with the first official release of Hydra       communicate via USB-C, they are discoverable like any
Pool. Around this time, there may also be a beta version of        other USB device and can be detected instantly upon
Mujina firmware released for the developers and testers            connection. The Ember One road map includes future
working with the newly manufactured Ember One                      versions with a range of ASIC chips and Mujina handles
hashboards; the first official release of Mujina firmware is       this with the ability to easily port in drivers for the various
not due until the end of December. By all accounts, we are         types of hashboards. For example, a user will be able to
making great progress and we are excited to share the              unplug and swap out a hashboard while the system is
updates with you.                                                  running and Mujina will detect the new hashboard,
                                                                   determine the necessary driver for it based on the ASICs it
Ember One                                                          is fashioned with, and start communicating with the new
A few changes have gone into the Ember One 00 v4 design            hashboard immediately without interruption to the other
after the initial release of the v3 design. In June, there were    hashboards. We believe that over time this capability will be
10 commits made on GitHub in the v4 branch updating                a significant mitigating factor against maintenance and
things from adding the reverse polarity protection circuit to      repair down time. Other features include the development of
moving a few components around. Currently, a few                   a terminal interface in addition to the web UI, for an
prototypes have been built and are in the process of being         example of what is possible in the terminal interface check
validated with the v4 upgrades. Once the validation is             out some of the themes here. Currently, the firmware is
complete, we will be placing a small initial batch order           handling communications to and from the ASIC chip as
specifically for testers and developers to start trying out.       well as peripheral board components. In the weeks ahead,
Anyone receiving an Ember One from this initial batch is           testing and development will graduate from the Bitaxe Raw
also going to need a heat sink, a cooling fan, a power             interface to running Mujina on one of the Ember One 00 v4
supply, a control board, and firmware at a minimum. There          prototypes. You can learn more at mujina.org.
are plans in the works currently for a purpose-built heat
sink, the control board is currently under development with        Hydra Pool
the Libre Board project, and the firmware is also currently        As mentioned in the last newsletter, the decision was made
under development with the Mujina project. There will be           not to use an existing code base for the Stratum server
information available for reference power supply units and         component of Hydra Pool but instead to build one from the
cooling fans. Currently we are anticipating that the initial       ground up in Rust. The second Telehash fundraiser carried
batch of units will be ready to start shipping out in mid-         out in the beginning of May was done with the initial
August. More details to follow. You can learn more at              version of Hydra Pool forked from CK Pool. We took the
emberone.org.                                                      lessons from that experience, reviewed the code closely,
                                                                   also reviewed other existing options like Stratum v2 and
Libre Board                                                        DATUM but ultimately we decided the best way to move
Last month we presented the list of ports that will be             forward was to start from scratch. So far, bench marking our
available on the Libre board, now those have all been              Stratum server against CK Pool has been comparable and
mapped out and placed and we are currently checking all            currently we are starting to test the software with various
the traces to ensure the PCB layers are correct before the         miners. Hydra Pool will be a one-click deployable pool
initial test batch is manufactured. Users will be able to          made to work on Mujina which eventually will become its
connect up to four Ember One hashboards to each Libre              own Linux distribution. There will be two payout methods
Board controller. Additionally, the NVME port allows users         available in the first release of Hydra Pool, selectable by the
to install an SSD card if they want to run a fully validating      user, solo mining mode and Pay Per Last N Shares
Bitcoin node on their Libre Board. The standardized two            (“PPLNS”) mode. With the ability to run a Bitcoin node on
100-pin connectors for the compute module gives users the          the Libre Board, the complete Ember One mining system
flexibility to choose any Raspberry Pi or other x86 or even        will be a versatile open-source solution that gives the user
RISC-V compute module with various CPU and RAM                     the full mining stack in a fully customization package. You
specifications. There are a number of other features and the       can learn more about Hydra Pool here.
form factor of the Libre Board has been designed to match
the standardized Ember One form factor so that the control
board and hashboards can all fit inside the same enclosure.
You can learn more at libreboard.org.
                                                                   ACTIONABLE ADVICE:
                                                                   The more people who get involved with open-source
Mujina Firmware                                                    development, the better. Many people experience hesitation
Development on the mining firmware continues to be                 in getting involved because they are not developers
crafted with as many end-user quality of life features as we       themselves. Despite the common misconception that only
can think of. Mujina firmware has the ability to handle hot-       developers wielding some special skills should be the ones
                                                                   touching a project’s code, anyone can open an issue or

                                                        The 256 Foundation
                                                           Page 6 of 10

create a pull request and it is a lot easier than you might       Step 3: Once you have your GitHub account, navigate to
think. In this month’s Actionable Advice column I’m going         the repository (“repo”) for the project you are interested in.
to show you exactly how to get involved with your favorite        In this example, I’m using the Ember One project. There is
open-source projects on GitHub so that the next time you          already an active release of the Ember One and it is v3. So
have a feature request, or encounter an issue you want            when looking at the Master branch of the repo, which is the
reported, or see something that you think could be improved       default branch you will see when visiting the project, it is
then you can go straight to the source and do it yourself.        reflecting the changes up until v3. Development has
This will be much appreciated by other developers working         continued since v3 was released, which has been carried out
on the project and it will save everyone from having to use       in a new branch called v4. Once the v4 updates have all
other communication channels to chat about the topic and          been validated then the v4 branch will get pushed to master
rely on one of the active developers to take what has been        and bring all those updates with it. I want to make a change
discussed and translate it into a GitHub issue or pull request    in the v4 branch so I’m going to click on where it says
themselves.                                                       “Master” on the left-hand side above the list of code files,
                                                                  then I will click on v4 to view that branch.
Step 1: You need a GitHub account. Navigate to github.com
and in the upper right-hand corner you should see the option
to Sign up, click on that to create your new account. If you
already have a GitHub account, then use the option to Sign
in and skip the next step.


                  [IMG-007] GitHub home page
                                                                                  [IMG-009] GitHub branch selection
Step 2: Fill in the empty fields with a valid email address, a
high entropy and unique password, a desirable username,           You may notice a message at the top of the repo that says
and “your country”. Then Continue.                                the branch you’re viewing is several commits ahead of the
                                                                  master branch, each of those commits is an update that the
                                                                  developers have incorporated into the new branch. Once the
                                                                  new branch gets pushed to master, those commits are all the
                                                                  changes that will go along with it.

                                                                  I noticed while looking through the Bill of Materials
                                                                  (“BOM”) in the Manufacturing Files folder that one of the
                                                                  items did not have an assigned DigiKey part number and I
                                                                  want that part number included on the BOM. So the
                                                                  example I’m going to show you will demonstrate how to
                                                                  make a pull request to have this update included. Then that
                                                                  gives everyone else involved in the project the opportunity
                                                                  to view the proposed changes and decide if they agree that
                 [IMG-008] GitHub Sign up page                    this should be updated and if they agree then the project
                                                                  maintainer can merge my pull request and those changes I
Keep in mind that the veracity of the country you select is       proposed will be included in the v4 branch, which will
up to you and also know that in the past, GitHub has              subsequently get merged into the master branch once the v4
blocked access to certain countries like Iran and Syria           branch gets released. These concepts will work for any
because “muh CoMpLiAnCe!”. Tor or a VPN can be                    change you want to make in a repo like modifying an
helpful here if need be.                                          HTML file or updating an image etc, so follow along and
                                                                  then use these instructions to make your own pull requests.


                                                       The 256 Foundation
                                                          Page 7 of 10

             [IMG-010] Missing DigiKey part number                                [IMG-012] Confirm fork details

Step 4: Fork the repo. I’m going to create a carbon copy of      Step 5: Edit your new fork. Now you should be looking at
the entire Ember One repo, this is called a fork. The new        your fork of the project. This is a copy of the original
fork will be available under my user, econoalchemist, unlike     project that you can modify any way that you want to. Then
the original repo which is available under the 256               once you have made some changes that you think should be
Foundation organization. This way I can make all the             included in the main project, you can make a pull request
changes I want in my copy of the repo and it won’t effect        for those changes to be included. In this example, I want to
anything in the original repo. To create a fork of a project,    update that BOM, so I’m going to navigate to the
click on the drop-down menu where it says “fork” along the       manufacturing files folder in the v4 branch of my forked
top of the repo. Then click on “Create fork”.                    repo and there I will open the “emberone BOM.csv” file
                                                                 and click on the pencil icon in the upper right-hand corner
                                                                 to open the file editor.


                    [IMG-011] Forking a repo


GitHub will ask me to confirm the details of this fork I’m
creating. I could change the name of the repo here if I
wanted but I’ll be leaving it as the default. I have also
unchecked the box where it says “Copy the master branch
only” because I want to copy all the branches since the                                [IMG-013] Edit file
change I am interested in making is in the v4 branch. Once
you are satisfied with the details, click on “Create fork” at    Then I’ll scroll down to the line I want to edit, add the
the bottom of the page.                                          DigiKey Part Number, and click on commit changes in the
                                                                 upper right-hand corner of the editor.
Alternatively, if you have push access to a repo then you
could create your own branch and make your modifications
there. See this documentation to learn more on that option.


                                                                                      [IMG-014] Added text


                                                      The 256 Foundation
                                                         Page 8 of 10

I will also add a brief note explaining the change I made in    Next, you will be presented with all the details of your pull
the pop-up window before finalizing the commit. I have          request. Ensure that the base repo is the main project and
selected to commit directly to the v4 branch and this gets      that the correct branch is selected and also that the head
finalized by clicking on the “commit changes” green button      repo is your forked version and branch. Double check the
in the lower right-hand corner.                                 title of your pull request and the description. At the bottom,
                                                                you can quickly view the differences. If everything looks
                                                                good then click on the green button in the lower right-hand
                                                                corner that says “create pull request”.


                 [IMG-015] Adding a comment.

Then you can click on the commit to expand the details and                        [IMG-018] Finalize pull request
see the difference from the old version of the file and the
new.                                                            Now your pull request will be visible to the project
                                                                maintainers and reviewers and they can decide if they want
                                                                to merge your pull request or maybe they have some
                                                                questions and/or comments and then they can start a
                                                                conversation right there in the repo to clarify things.

                                                                The steps and concepts out-lined here have been meant to
                                                                demonstrate the most basic way to create a pull request.
                                                                There are more elaborate methods that involve installing the
                                                                GitHub application on your desktop and cloning your
                                                                forked repo locally, making the edits in your local copy,
              [IMG-016] GitHub commit differential
                                                                confirming everything looks and works how you want it,
                                                                then pushing the changes back up to your forked repo, and
Step 6: Create the pull request. From your forked repository    then creating the pull request to the main project.
main page, click on the “pull requests” tab at the top. Then    Alternatively, if you have something in mind that doesn’t
click on “compare & pull request”:                              constitute a pull request, just open a new issue instead. You
                                                                can navigate to the project you are interested in, click on the
                                                                “issues” tab at the top of the page, and create a new issue
                                                                describing what’s on your mind. This will give other project
                                                                participants the opportunity to consider your issue and
                                                                determine a course of action. Hopefully, this simple guide
                                                                has given you enough food for thought to get started and get
                                                                involved. You can learn more about GitHub pull requests
                                                                here.
                 [IMG-017] Creating pull request


                                                     The 256 Foundation
                                                        Page 9 of 10

STATE OF THE NETWORK:
Hashrate on the 14-day MA according to mempool.space
decreased from ~915 Eh/s on the first day of June to 840
Eh/s by the end of the month, marking roughly -8.1%
decrease for the month and bringing the year to date
difference to +6.8%. Hashrate was quick to rebound after
the beginning of July and is on track to surpass the previous
all time high soon.


                                                                                      [IMG-021] Hashprice from Braiins Insights

                                                                         The next halving will occur at block height 1,050,000 which
                                                                         should be in roughly 1,000 days or in other words ~146,440
                                                                         blocks from the last day in June.
     [IMG-019] 2025 hashrate/difficulty chart from mempool.space

Difficulty was 126.98T at it’s highest in June and 116.96T               CONCLUSION:
at it’s lowest in the last couple days of the month, which               Thank you for reading the seventh 256 Foundation
marks a ~7.8% decrease for the month. All together for                   newsletter. Keep an eye out for more newsletters on a
2025 up to Epoch #448, difficulty has gone up ~6.5%.                     monthly basis in your email inbox by subscribing at
                                                                         256foundation.org. Or you can download .pdf versions of
According to the Hashrate Index, ASIC prices have                        the newsletters from there as well. You can also find these
decreased ever so slightly over the last month. The more                 newsletters published in article form on Nostr.
efficient miners like the <19 J/Th models are now fetching
$17.22 per terahash, models between 19J/Th – 25J/Th are
selling for $7.52 per terahash, and models >25J/Th are
selling for $2.82 per terahash.


                                                                                           [IMG-022] FREE SAMOURAI

                                                                         If you want to continue seeing developers build free and
                                                                         open solutions be sure to support the Samourai Wallet
                                                                         developers by making a tax-deductible contribution to their
                                                                         legal defense fund here. The first step in ensuring a future of
                                                                         free and open Bitcoin development starts with freeing these
                                                                         developers.
         [IMG-020] Miner Prices from Luxor’s Hashrate Index

Hashvalue over the month of June jumped from roughly
50k sats/Ph/day to finish the month out at 55k sats/Ph/day,
according to the Braiins Insights dashboard.


                                                                                                                      Live Free or Die,
                                                                                                                        -econoalchemist


                                                              The 256 Foundation
                                                                Page 10 of 10


===== DOCUMENT 8 of 27 =====
DATE: 2025-08
LABEL: August 2025
TITLE: Is Open Source Communism?
FILE: 256Foundation-Newsletter-2508_v1.pdf
SOURCE: https://github.com/256foundation/News/blob/main/256Foundation-Newsletter-2508_v1.pdf

NEWS256 #8
                                   Is Open Source Communism?

By: 256 Foundation
A monthly newsletter                                             opinions expressed do not necessarily reflect those of Proto
                                                                 Global, LLC


August 2025

INTRODUCTION:                                                    DEFINITIONS:
Welcome to the eighth newsletter produced by The 256             v = version
Foundation and supported by Proto! July was an eventful          RSSI = Received Signal Strength Indicator
month for freedom tech; the Samourai Wallet devs took a          UI = User Interface
plea agreement, the Atlanta Bitlabs Hackathon concluded,         API = Application Programming Interface
and there is a new Hydra Pool test server online. Dive into      JSON = Java Script Object Notation
all the interesting things going on in and around the Bitcoin
mining industry and catch up on the latest freedom tech          FREEDOM TECH NEWS:
news, free & open mining developments, 256 Foundation            July 11, Skot reignites the Loriques project, a solar powered
grant progress updates, Actionable Advice, and the current       Meshtastic LoRa gateway. There seems to be renewed
state of the Bitcoin network. Or are we building the rails       interest in mesh networks after Jack Dorsey shared the
needed to abolish private intellectual property? Is open-        source files for a Bluetooth mesh chat application he built
source in fact communism? Have we got it all wrong? Find         called Bitchat. Mesh communications are a neat concept
out, have fun, and enjoy the read.                               that can give users a way to send encrypted messages
                                                                 offline. One of the limitations of Bluetooth is the effective
                                                                 range, projects like Lorques are one solution aimed at Long
                                                                 Range (LoRa), low-power communications.

                                                                 July 12, @bc1984adam writes an in-depth Ashigaru review
                                                                 aimed at clearing up criticisms after the developers released
                                                                 their own version of Samourai Wallet’s Whirlpool at the end
                                                                 of June 2025. Some familiar faces in the privacy flame wars
                                                                 came crawling out of the woodwork still clutching to the
                                                                 same FUD they used when Samourai Wallet was active.
                                                                 Unfortunately, it seems as though any developers building
                                                                 on what Samourai Wallet started will need to endure attacks
                                                                 just as vicious as Samourai Wallet did even though they are
                                                                 not associated with Samourai Wallet in any way. The
                                                                 primary criticism raised by @1440000bytes was that the
                                                                 Whirlpool coordinator could de-anonymize users and link
                                                                 the inputs and outputs of CoinJoin rounds. The claim
                                                                 assumes that the coordinator is malicious. There is zero
                                                                 evidence that the vulnerability described has ever been
                                                                 executed in the previous Whirlpool coordinator and the
                                                                 Ashigaru devs implemented a fix to the edge-case issue
                                                                 anyways, as described in @bc1984adam’s article. The
                                                                 article goes on to describe the fix may have introduced a
                                                                 separate concern related to a malicious coordinator having
                                                                 the ability to link CoinJoin participants across rounds.
                                                                 Regardless, in my personal opinion, the concerns are blown
                                                                 out of proportion and there is no evidence of compromise. I
                                                                 say, make every spend a CoinJoin and I’m glad there is a
                                                                 Whirlpool coordinator back online.

                   [IMG-001] Twitter is wild                     July 14, Roman Storm (Tornado Cash developer) trial
                                                                 starts, marking a new era of significant government

                                                      The 256 Foundation
                                                          Page 1 of 6

overreach where software developers are held liable for the      20 additional years, the fines would have been bigger, the
actions of end users. The trial took place in the Southern       judge would have been harsher in her sentencing, and the
District of New York (“SDNY”) and prosecutors charged            jury would have at the very least convicted them on the
Storm with conspiracy to commit money laundering,                conspiracy to operate an unlicensed money transmitting
conspiracy to violate economic sanctions, and conspiracy to      business charge anyways if the Roman Storm case is any
operate an unlicensed money transmitting business. In            indicator. There is no reason for the developers to martyr
actuality, Storm did nothing more than build software tools      themselves.
on the Ethereum blockchain that provided basic privacy
benefits. In the end, the jury convicted Storm of the
conspiracy to operate an unlicensed money transmitting
business. The jury was not able to reach a unanimous
verdict on the other two charges. There will likely be an
appeal following the sentencing hearing. Follow
@theragetech on twitter for detailed coverage of the case.                        [IMG-002] FREE SAMOURAI

July 30, Samourai Wallet developers reach plea agreement         FREE & OPEN MINING DEVELOPMENTS:
with prosecutors and plead guilty to conspiracy to operate       July 1, the latest release of Bitaxe firmware, AxeOS v2.9.0
an unlicensed money transmitting business. Previously, the       was released. A few of the many new features include: the
developers had plead not guilty to all charges however, the      addition of a “clear” button and filter for real-time logs so
prosecutors presented them with a plea agreement in which        the user can quickly narrow down their search to relevant
if they changed their plea to guilty then the prosecution        log entries or clear the entire log to get a clean start; the
would drop the conspiracy to commit money laundering             addition of Stratum response time so the user can see how
charge. The money laundering charge carried a maximum            long it takes the Stratum server to respond to the clients
sentence of 20-years and the money transmitting charge           share submission; and the addition of the hostname and
carried a maximum sentence of 5-years in prison. The good        WiFi RSSI in the header of the UI so the user can quickly
news in this agreement is that the developers are no longer      see what their device is named and which WiFi network it is
facing 25-years in prison, hopefully the judge gives them        on. There were API improvements as well, like returning a
time-served at sentencing for the nearly 500 days they have      JSON object for unhandled API requests instead of
been under house arrest now. This hardly feels like a win        redirecting to the main page. There are several more updates
though considering that the developers never once                from Stratum improvements to display enhancements to bug
transferred money on behalf of the public, as Samourai           fixes. You can read all about them on the GitHub releases
Wallet is a non-custodial application, therefore the             page. You can also watch a video about the new release here
developers could not have possibly been a money                  from @wantclue.
transmitter. The way in which prosecutors twisted the letter
of the law to mean that non-custodial wallet developers had      July 3, Stratum v2 website updated to include helpful
to plead guilty to conspiracy to operate a money                 explanations, differences between v1 & v2, and how you
transmitting business is shocking and should be a wake up        can get started running Stratum v2 in your mining pool.
call to every one involved in the Bitcoin ecosystem. The
language used was so vague that the term “to facilitate the      July 3, Solo miner finds block with Solo CK Pool with
transfer of funds by any and all means” could be applied to      2.3Ph/s. This marks the 301st block found by Solo CK Pool
any non-custodial hardware or software wallet developer,         and came from the EU server. A miner of this size had
anyone who plugs in a miner, or anyone who operates a            roughly a 1 in 2,800 change of solving a block every day on
node. Basically everyone. As for precedent, none was set in      average.
this case because it was resolved in a plea agreement, not
that it really matters at the end of the day considering that    July 5, Tyler Stevens gives a talk in Alaska about Bitcoin
the charges brought against Samourai Wallet and the              mining heat re-use and the potential it has to triple current
ensuing actions against them were completely                     network hashrate by capturing only 1% of world-wide
unprecedented. Demonstrating once again that you can be          comfort heat. The 256 Foundation believes that closed and
as nice as you want to the government but they will still        proprietary mining hardware will not be suitable to realize
lock you in a cage for any reason they want. This marks the      this type of potential. Open-source hardware and firmware
end of a courageous fight the developers were embroiled in       however, will usher in heat re-use developments like a wild
for 462 days. Currently, sentencing hearings are scheduled       fire (pun intended).
for November 6 & 7, 2025 and the developers need to pay a
$6m fine by then. In hind-sight of the Roman Storm case,         July 8, the Atlanta Bitlab Mining Hackathon concludes and
the Samourai Wallet developers made the right decision           winners were announced online via a live video feed. There
taking the plea agreement. They would have only incurred         were three categories: software, hardware, and energy. A
more expense taking it to trial, they would have been facing     project called Minor League Miners took the software prize

                                                      The 256 Foundation
                                                          Page 2 of 6

for their cool dashboard that gamifies micro-scale bitcoin               this case, the mining pools are the flows and the template
mining by putting a competitive twist on variables like best             Merkle branches are the nodes.
difficulty [IMG-003]. For the hardware prize, PC-AXE was
the winner with the idea being that PCIe cards equipped
with ASICs could produce ~1.2Th/s each [IMG-004]. For
the energy prize, Rev.Hodl took the prize by using a special
type of clay to actually cool down air with a Bitcoin miner
[IMG-005].


                 [IMG-003] Miner League Miners
                                                                                     [IMG-006] Sankey diagram in stratum.work

                                                                         July 12, @tendkraft recommends updating NerdQaxe
                                                                         firmware to v1.0.31-RC due to an issue that was causing a
                                                                         fuse and several diodes to blow!

                                                                         July 22, Covert solar-powered Bitaxe. In the posted video,
                                                                         it appears that @depinnomad has installed a solar panel and
                                                                         weather-proof electrical enclosure on a utility pole. Among
                                                                         the battery and other components in the box, there is a
                                                                         Bitaxe hashing away. This seems to be a Decentralized
                                                                         Physical Infrastructure Network or “DePIN”, which is a
                       [IMG-004] PC-AXE                                  new term for me and apparently kind of a rabbit hole. You
                                                                         can learn more about DePINs here.

                                                                         July 26, a miner with only 49Th/s solves the 303rd block for
                                                                         Solo CK Pool, this one again on the EU server!

                                                                         GRANT PROJECT UPDATES:
                                                                         The 256 Foundation team has been crushing each project,
                                                                         getting closer to completing the first open-source complete
                                                                         mining stack. The first batch of Ember Ones is taking a little
                                                                         longer than we thought last month but they are well on their
                                                                         way. By the end of October, the first official release of the
                                                                         Libre Board should be out along with the first official
       [IMG-005] Bitcoin Miner Air Conditioner by Rev. Hodl              release of Hydra Pool. Around this time, there may also be a
                                                                         beta version of Mujina firmware released for the developers
July 11, @Boerst has been hard at it refining stratum.work.              and testers working with the newly manufactured Ember
This update incorporates a Sankey diagram, which traces                  One hashboards; the first official release of Mujina
how mining pools assemble block templates. Sankey                        firmware is not due until the end of December, maybe
diagrams are a type of data visualization tool that                      January 2026. By all accounts, we are making great
emphasizes flows or change from one state to another. In                 progress and we are excited to share the updates with you.


                                                              The 256 Foundation
                                                                  Page 3 of 6

Ember One                                                               Board controller. Additionally, the NVME port allows users
In July, Skot has continued refining the Ember One with                 to install an SSD card if they want to run a fully validating
upgrades like a reverse polarity protection circuit                     Bitcoin node on their Libre Board. The standardized two
(contributed by @zbomstaz) and adding Transient Voltage                 100-pin connectors for the compute module gives users the
Suppression diodes to protect connected USB devices. Then               flexibility to choose any Raspberry Pi or other x86 or even
he hand assembled some prototypes of the resulting v4                   RISC-V compute module with various CPU and RAM
board and began the validation process. Once validated,                 specifications. There are a number of other features and the
there will be a small production run of roughly 100 units for           form factor of the Libre Board has been designed to match
testers and developers. Ember One is the hashboard only                 the standardized Ember One form factor so that the control
and does not include the required control board (see Libre              board and hashboards can all fit inside the same enclosure.
Board), cooling fan (a reference fan will be documented), or            You can learn more at libreboard.org.
the heat-sink (there is work being done on designing and
producing one which should be available soon).                          Mujina Firmware
                                                                        There also is not much news to report for Mujina this month
                                                                        either, lots of incremental steps. Mujina firmware has the
                                                                        ability to handle hot-swappable hashboard replacement
                                                                        without a system reboot, or any system interruption at all.
                                                                        As the hashboards communicate via USB-C, they are
                                                                        discoverable like any other USB device and can be detected
                                                                        instantly upon connection. The Ember One road map
                                                                        includes future versions with a range of ASIC chips and
                                                                        Mujina handles this with the ability to easily port in drivers
                                                                        for the various types of hashboards. For example, a user
                                                                        will be able to unplug and swap out a hashboard while the
                                                                        system is running and Mujina will detect the new
                                                                        hashboard, determine the necessary driver for it based on
                                                                        the ASICs it is fashioned with, and start communicating
                                                                        with the new hashboard immediately without interruption to
        [IMG-007] Hand assembled Ember One v4 Prototypes                the other hashboards. We believe that over time this
                                                                        capability will be a significant mitigating factor against
After battling getting the components hand assembled, Skot              maintenance and repair down time. Other features include
was finally able to get the first signs of life out of all 12           the development of a terminal interface in addition to the
ASIC chips. The validation process is close to being done               web UI, for an example of what is possible in the terminal
and then there will be some units produced. You can learn               interface check out some of the themes here. Currently, the
more at emberone.org.                                                   firmware is handling communications to and from the ASIC
                                                                        chip as well as peripheral board components. In the weeks
                                                                        ahead, testing and development will graduate from the
                                                                        Bitaxe Raw interface to running Mujina on one of the
                                                                        Ember One 00 v4 prototypes. You can learn more at
                                                                        mujina.org.

                                                                        Hydra Pool
                                                                        In July, @jungly was able to get the new and improved test
                                                                        server configured on Signet and testing has commenced.
                                                                        See the Actionable Advice column for instructions and join
                                                                        the 256 Foundation Telegram channel for community
                                                                        support. Hydra Pool is a one-click deployable pool made to
                                                                        work on Mujina which eventually will become its own
                                                                        Linux distribution. There will be two payout methods
          [IMG-008] First sign of life in an Ember One   🥹              available in the first release of Hydra Pool, selectable by the
                                                                        user, solo mining mode and Pay Per Last N Shares
Libre Board                                                             (“PPLNS”) mode. With the ability to run a Bitcoin node on
There is not much to report on Libre Board this month, we               the Libre Board, the complete Ember One mining system
are currently checking all the traces to ensure the PCB                 will be a versatile open-source solution that gives the user
layers are correct before the initial test batch is                     the full mining stack in a fully customization package. You
manufactured, a tedious process. Users will be able to                  can learn more about Hydra Pool here.
connect up to four Ember One hashboards to each Libre


                                                             The 256 Foundation
                                                                 Page 4 of 6

ACTIONABLE ADVICE:                                                  Difficulty was 127.62T at it’s highest in July and 116.96T at
This month we are covering how to help test the latest              it’s lowest, which marks a ~8.4% increase for the month.
Hydra Pool software. Our goal is to validate the Hydra Pool         All together for 2025 up to Epoch #450, difficulty has gone
Stratum server is working well with various types of Bitcoin        up ~16.2%.
mining hardware and firmware. Unfortunately, there is no
Stratum v1 standard so it is difficult to know how Stratum
v1 clients will communicate with the server. This testing
helps us find issues that we can resolve before the first
release. Don’t be discouraged if your miner shows up as
“Pending” or “Fail” in the dashboard, that is actually
helpful for us because it means there is an issue we need to
resolve! The logs from the brief connection are saved so
that we can study them and find the issues, make                        [IMG-010] YTD Hashrate & Difficulty from mempool.space
corrections where needed, and push the changes into
GitHub. The current test server is configured to run on             According to the Hashrate Index, ASIC prices have
Signet so there is no mining rewards to be had. We will             increased ever so slightly over the last month. The more
switch it over to Bitcoin Mainnet once we have enough               efficient miners like the <19 J/Th models are now fetching
testing done to be assured it could actually submit a valid         $17.94 per terahash, models between 19J/Th – 25J/Th are
block in the event one of the testers gets so lucky.                selling for less than last month, down from $7.52/Th to
                                                                    $6.52/Th, and models >25J/Th are surprisingly higher in
1) Open your miner’s configuration page and point the               price this month over last, fetching $3.04/Th now compared
device to:                                                          to $2.82/Th last month.

stratum+tcp://test.hydrapool.org:3333

For the username, feel free to enter any vanity name you
want.

2) Restart your miner for the changes to take effect.                         [IMG-011] Miner Prices from Luxor’s Hashrate Index

3) Navigate to test.hydrapool.org to check the dashboard.           Hashvalue over the month of July plummeted from roughly
After 5-minutes there should be enough information in the           54k sats/Ph/day to finish the month out at 49k sats/Ph/day,
logs for the test to be done. You can reset your miner’s            according to the Braiins Insights dashboard.
configuration at that point. Short & sweet, thanks!


                                                                                  [IMG-012] Hashprice from Braiins Insights

            [IMG-009] Hydra Pool test server dashboard
                                                                    The next halving will occur at block height 1,050,000 which
                                                                    should be in roughly 965 days or in other words ~140,000
STATE OF THE NETWORK:                                               blocks from the the time this newsletter is published.
Hashrate on the 14-day MA according to mempool.space
increased from ~832 Eh/s on the first day of July to 906            CONCLUSION:
Eh/s by the end of the month, marking roughly +8.8%
                                                                    With all that is going on with freedom tech, free and open
increase for the month and bringing the difficulty right back
                                                                    Bitcoin mining development, and the awesome projects
to where it was before that massive decrease. The year to
                                                                    being built at the 256 Foundation and elsewhere, let’s circle
date hashrate difference is +15.2%.

                                                         The 256 Foundation
                                                             Page 5 of 6

back to the opening image, the "Open source is communism           cost savings, faster development, and interoperability as key
for intellectual property" meme. I think the underlying            benefits. These outcomes don’t dismantle private property
question this poses is: are open-source and private property       but enhance it by creating new markets. Take Twitter for
mutually exclusive? Personally, I’m quite passionate about         example, OpenAI released GPT and its been adopted by
both, surely I’m not a walking contradiction. I couldn’t help      Twitter and implemented in their AI servers; this
but think about this for a long time, I’ll admit it, the meme      demonstrates how open-source can drive private enterprise.
had it’s intended affect on me. But I think that for as much       Developers and firms invest in infrastructure and talent
as there is to unpack here, it can be organized and broken         (private assets) to leverage open code, turning a shared
down plainly.                                                      resource into proprietary value-added services. Think about
                                                                   how MicroSoft supports the Linux Foundation, they know
The assertion that open-source equates to communism for            the open-source community is producing the feed stock for
intellectual property and inherently undermines private            their business.
property rights rests on a misunderstanding of both
concepts. This can be broken down into five areas and there        4) Philosophical Alignment with Property Rights:
is a logical way that open-source and private property can         Libertarian thinkers like Stephan Kinsella, often cited in
coexist harmoniously.                                              intellectual property debates, argue against patents and
                                                                   copyrights likening them to state-granted monopolies that
1) Open-Source as a Voluntary Choice, Not a State                  distort free markets. Open-source aligns with this critique
Imposition:                                                        by rejecting artificial scarcity in ideas, which are “non-
Communism, as historically practiced, involves centralized         rivalrous goods” (in other words, one person's consumption
state control and the abolition of private property through        of the good does not diminish its availability for others).
coercion. Open-source, by contrast, is a voluntary model           Yet, open-source doesn’t abolish property rights; it redefines
where individuals or entities choose to share their                them. Creators retain moral and legal claims to their work,
intellectual creations under specific licenses (e.g., MIT or       and the community’s contributions build on that foundation.
GPL). This act of sharing doesn’t negate private property;
it’s an exercise of it. Creators retain ownership of their code    5) Countering the Meme’s Provocation:
and grant permissions for others to use, modify, or distribute     The "Change My Mind" format invites challenge, so let’s
it; rights explicitly defined by licenses. For example, when a     flip it: Open-source isn’t communism; it’s capitalism’s
developer releases code under the MIT License, they’re not         evolution. It leverages private property to foster competition
surrendering ownership but licensing it, much like a               and innovation, as seen in the rapid adoption of AI, Apache
landlord rents a property while retaining title. This aligns       web servers, and even Bitcoin itself. If anything, proprietary
with libertarian principles of voluntary exchange, not             software, locked behind paywalls and legal threats, more
communist expropriation.                                           closely resembles a state-enforced monopoly, the true
                                                                   antithesis of free markets.
2) Intellectual Property as a Managed Resource, Not
Abolished:                                                         Open-source and private property aren’t mutually exclusive;
The meme implies open-source eliminates intellectual               they’re complementary when viewed through a voluntary,
property similar to how communism abolishes private                market-based lens. The meme’s hyperbolic comparison to
property, but open-source doesn’t eliminate intellectual           communism overlooks the agency of creators, the legal
property in actuality. Open-source operates within the             structure of licenses, and the economic reality of thriving
framework of intellectual property law. Licenses like GPL          private enterprises in the open-source ecosystem. The tech
ensure that derivative works remain open, but they still           landscape shows this model strengthening, not weakening,
recognize the original creator’s copyright. This is evident in     property rights. Open-source ensures the users have the
GitHub’s default license options, where projects are               freedom to run, copy, distribute, study, change and improve
explicitly tagged with legal terms (see gnu.org and                the software. That doesn't sound like socialism or
opensource.org). Far from being "communism," this is a             communism to me.
market-driven innovation: companies like Red Hat and
Canonical thrive by offering support and services for open-        Thank you for reading the eighth 256 Foundation
source software, proving that private property in the form of      newsletter. Keep an eye out for more newsletters on a
expertise and infrastructure can coexist with shared code.         monthly basis in your email inbox by subscribing at
This concept of discovering viable business opportunities          256foundation.org. Or you can download .pdf versions of
built on a foundation of open-source is central to the 256         the newsletters from there as well. You can also find these
Foundation’s vision.                                               newsletters published in article form on Nostr.

3) Economic Benefits Support Coexistence:
Recent data from the Linux Foundation’s 2025 report on             Live Free or Die,
"Measuring the Economic Value of Open Source" highlights           -econoalchemist


                                                        The 256 Foundation
                                                            Page 6 of 6


===== DOCUMENT 9 of 27 =====
DATE: 2025-09
LABEL: September 2025
TITLE: Rig: Bitcoin Mining Re-Imagined
FILE: 256Foundation-Newsletter-2509_v1.pdf
SOURCE: https://github.com/256foundation/News/blob/main/256Foundation-Newsletter-2509_v1.pdf

NEWS256 #9
                                Rig: Bitcoin Mining Re-imagined

By: 256 Foundation
A monthly newsletter                                              *opinions expressed do not necessarily reflect those of
                                                                  Proto Global, LLC


September 2025

INTRODUCTION:                                                     contested with the prosecutors arguing that “Custody of the
                                                                  funds, however, is not a requirement to being a money
Welcome to the ninth newsletter produced by The 256               transmitter under Section 1960. Custody is not part of the
Foundation and supported by Proto! August was a wild              statute, and the defendants do not cite any case or other
month for freedom tech; Proto launched their new mining           legal authority that has ever held that custody of the funds
system, Rig, and the 256 Foundation was there to cover the        is required.”. Which is a disingenuous argument at the least
announcement. Additionally, Google does evil things,              and intentionally misleading at worst because bitcoin
econoalchemist starts building a PCB assembly line, and           (Ethereum in the case of Tornado Cash) cannot be moved
much more. Dive into all the interesting things going on in       without control. Despite arguments made in the Tornado
and around the Bitcoin mining industry and catch up on the        Cash case, like a frying pan transfers heat without having
latest freedom tech news, free & open mining                      control over the heat; bitcoin is not a form of energy like
developments, 256 Foundation grant progress updates, and          heat is, bitcoin is an unspent transaction output which can
the current state of the Bitcoin network.                         only be sent from one address to another by meeting the
                                                                  spending conditions, e.g., controlling the private key or in
                                                                  other words, having control of the funds. The prosecution is
                                                                  trying to argue that since “custody” is not mentioned in the
                                                                  1960(b)(1)(C) statute, custody therefore is not required to
                                                                  transfer bitcoin. The dangerously slippery slope that this
                                                                  boils down to can be summed up in one sentence, which
                                                                  prosecutors repeated many times: “to facilitate the transfer
                                                                  of funds by any and all means”. This statement and
                                                                  justification for the charges is so overly broad that it could
                                                                  be taken to mean any participant in the ecosystem, be they a
                                                                  software wallet developer, hardware wallet engineer, node
            [IMG-001] Proto Mining Rig exploded view              operator, or even a miner. Conspiracy to Operate an
                                                                  Unlicensed Money Transmitting Business is the same
DEFINITIONS:                                                      charge that prosecutors were able to get a guilty plea on
PCB = Printed Circuit Board                                       from the Samourai Wallet developers in a last minute plea
PSU = Power Supply Unit                                           agreement before the jury deliberation concluded in the
APK = Android Package                                             Roman Storm case. Unprecedented charges pointing to an
                                                                  uncertain future where the government can manipulate any
FREEDOM TECH NEWS:                                                law they want to punish those who enable individual
                                                                  freedoms and shift power away from the State; something
                                                                  which all developers, builders, and industry participants
August 6, Roman Storm (Tornado Cash) trial ends with a
                                                                  should keep in mind as time moves forward.
conviction for one of three counts. This was a dark day
indeed for freedom advocates everywhere. The jury in the
                                                                  August 9, econoalchemist sets up a free and open-source
Roman Storm trial found the defendant guilty on one
                                                                  hardware assembly line to start building the free and open-
charge, Conspiracy to Operate an Unlicensed Money
                                                                  source hardware being developed by the 256 Foundation.
Transmitting Business; as for the other two charges the jury
                                                                  The assembly line is a private venture separate from the 256
was unable to reach a unanimous conclusion. Roman Storm
                                                                  Foundation. The equipment includes a Neoden 4 Pick &
never controlled the funds going through Tornado Cash,
                                                                  Place machine which accepts reels of small electronic
control being central to the common understanding of a
                                                                  components and automatically picks up the components,
money transmitting business, i.e., in order to transmit
                                                                  checks them with a camera to make sure the correct
money from one place to another, the entity logically then
                                                                  component was selected and in the correct orientation, then
must have control over the money. For several months
                                                                  the work-head places the component onto the PCB in
leading up to the trial, this issue of control was highly

                                                       The 256 Foundation
                                                           Page 1 of 5

exactly the right spot on top of some tacky solder paste.        identifying documents, register their app’s package names,
Once all the components are placed, the PCB is sent              and upload signing keys through a revamped Android
through the Neoden IN6 Reflow oven where the solder              Developer Console. Google takes things a step further
paste heats up and fuses the component to the underlying         explaining that Android devices using Google services will
copper pad. First up on the assembly line will be a few          no longer accept side-loaded apps that do not originate from
Libre Board prototypes and then a small production batch of      the walled garden. In practical terms, this means that if you
about 100 Ember One hash boards with the Bitmain                 have an Android device then by default you will no longer
BM1362AC ASICs. Also in the production pipe line are the         be able to install apps coming from sources like F-Droid or
Adit Board v2 which gives users the ability to communicate       the Aurora Store or downloading and installing the
with Antminer hashboards via USB and then the AntHat             direct .APK file. Your device will only run apps that come
which allows users to control the Antminer fans and PSU          from the Google Play Store and in order for apps to get into
with a Raspberry Pi via the Adit Board v2.                       the Google Play Store, the developers will have had to
                                                                 comply with the new requirements. This means it is your
                                                                 device but their rules and developers will no longer be able
                                                                 to protect themselves behind a pseudonym if they want their
                                                                 projects available to the millions of users who get their apps
                                                                 from the Google Play Store. People who buy an Android
                                                                 device, like a Google Pixel, and flash it with an alternative
                                                                 operating system like GrapheneOS will still be able to
                                                                 obtain apps from where ever they want.

                                                                 FREE & OPEN MINING DEVELOPMENTS:
                                                                 August 4, Dr. Con Kolivas releases an easy to deploy Solo
                                                                 CK Pool package. Acknowledging that hosting Solo CK
                                                                 Pool prior to this new release requires an advanced
                                                                 understanding of the software, this all-in-one script
                                                                 automates the process. There are some key highlights from
                [IMG-002] PCB Assembly start up
                                                                 the post that resonate with the 256 Foundation’s mission
                                                                 and address some of the same issues we are tackling with
August 13, Google Play Store implements FinCEN Money             Hydra Pool, which tells us we are on the right track: Make
Transmitting Business license requirements for non-              the software accessible to anyone, even non-developers and
custodial Bitcoin wallet app developers, then quickly walks      make spinning up a new pool quickly deployable.
back policy. The Rage covered the initial news of Google’s
policy update saying: “Google Play Store has introduced a        August 14, Proto Mining Launches their new mining
policy that requires any software wallet developer to obtain     system, Rig, intriguing miners all across the Bitcoin
a license before publishing cryptocurrency wallet apps to        industry. What Proto has accomplished with Rig is so
the Google Play Store ‘to ensure a safe and compliant            simple yet so effective: the idea of being able to swap
ecosystem for users’.". This news sent shock waves through       components out quickly, without tools, and while the miner
the industry as the implications would mean that non-            is still running. Once you see it, it’s so obvious in hind-sight
custodial Bitcoin wallet developers either obtain a Money        that this is how every mining system should be; easy to
Transmitting Business license or their apps would be             maintain, inexpensive to upgrade, and designed to
removed from the Google Play app store, cutting off access       maximize up-time. Proto knocked it out of the park with
to millions of users world-wide. To compound the issue and       Rig. Rig is a densely packed power-house of a miner;
add to the confusion, FinCEN has stated explicitly that non-     boasting up to 819 Th/s with all nine hashboards installed,
custodial wallet developers do not need money transmitting       power efficiency as low as 14.1 J/Th, and a power
licenses and the federal prosecutors in the Samourai Wallet      consumption of up to 12,000 Watts. Weighing in at 110
case had dropped the allegation related to them not having       LBS, Rig has the hashing capabilities of three new-gen
such a license. Not long after news broke of the policy          Antminers but only takes up the space of two Antminers.
change, Google responded to The Rage on Twitter,                 Each Rig unit has three bays and each bay contains one
clarifying that non-custodial wallets were not in the scope      double fan assembly, three hashboards, and a power supply
of the updated policy; the damage had already been done          unit. The fans, hashboards, and PSU’s can all be swapped
however and the trajectory has been made clear to all            out by-hand without the use of any tools and while the other
observers. Roughly two weeks later, Google then goes even        two bays continue hashing. Swapping out these components
further along that trajectory and outlines the implementation    is as simple as pressing a latch, pulling the old component
of a new Android Developer Verification process that will        out, and snapping the new component into place; it literally
require all Android developers to upload government issued       takes a few seconds.


                                                      The 256 Foundation
                                                          Page 2 of 5

                                                                  traveled to a Core Scientific mining facility to participate in
                                                                  the product launch event. That evening, there was a Beef
                                                                  Steak dinner held for all guests back at the resort. We held a
                                                                  live POD256 from the middle of the action both nights and
                                                                  you can listen to those recordings here for night 1 and here
                                                                  for night 2.

                                                                  August 14, @mononautical composes thread on sub-sat
                                                                  summer, explaining the risk vs. reward for pools accepting
                                                                  transactions paying less than 1-sat/vB. The sub-sat summer
                                                                  trend started with Mara trying to boost mining rewards
                                                                  during an extended period of low demand for block space.
                                                                  By accepting transactions paying less than the standard 1-
                                                                  sat/vB, Mara was able to fill block space with more
                 [IMG-003] Rig by Proto Mining                    transactions thus making their total mining rewards
                                                                  increase. Transactions offering less than 1-sat/vB are non-
Compare that with an Antminer or Whatsminer where the             standard though, so it takes nodes with the default settings
miner needs to be powered off, the whole machine needs to         longer to validate blocks containing these transactions. The
be removed from it’s rack position, then disassembled using       longer it takes nodes to validate a block, the more risk there
a screwdriver on each component, and then reassembled             is in that block being orphaned by another block that can be
and reinstalled. Even once the miner is back in place,            validated and propagated faster. Mononautical explains that
getting back up to nameplate hashrate can take as long as         data reveals there have been a total of 11 orphaned blocks
30-minutes in the case of Whatsminers. The control board          between block height 900,000 and 910,000. Of those 11
in fleet can be easily accessible by depressing two latches       stale blocks, only one of them contained sub-1 sat/vB
on the sides of the unit but then a screw driver is needed to     transactions. At block height 906,343 Antpool had a block
remove the control board. The Rig approach means that the         orphaned by Foundry and lost their entire 3.145 BTC
miner chassis becomes part of the permanently installed           mining reward. Mara has since reverted back to the standard
infrastructure. Beyond the hardware, Proto also launched          1-sat/vB minimum transaction fee. Other pools are likely to
Fleet, the miner management software, offering users a            follow in an attempt to mitigate risk.
sleek interface with a substantial number of the miner’s
parameters accessible from the GUI. Fleet also offers             August 17, Solo CK Pool block find at height 910,440 from
simple error handling, built-in diagnostics, and smart alerts     a miner with 9Ph/s, making this the 12th block find for Solo
to help maximize up-time; additionally, users can also fine       CK Pool this year.
tune power and performance by quickly and easily
optimizing for hashrate, power usage, or overall efficiency       August 22, Tyler Stevens upgrades Bitcoin mining heated
across individual miners or their entire fleet. There are a       floor system at the Space Denver. The new configuration
number of additional features in the works such as an AI-         allows them to keep the miner running so long as the roof-
Powered Dashboard, direct parts ordering, and automated           top solar power system has the output capacity to keep the
curtailment settings. Fleet also works on mobile so users         miner running; why waste that solar energy? But what about
can always stay connected to their mining sites. The Fleet        in the summer time when the heated flooring system would
software is currently in closed Beta but those who are            make it uncomfortably hot inside the building? Tyler
interested in helping test the software can easily gain access    cleverly connected a remote activated pump to the system
by making a request through Proto’s website here. Proto has       so that when it is getting too hot inside the building, they
committed to making Fleet free of charge and open-source          can kill the pump and the heat is directed to a radiator
once it is fully released. The mining firmware will also be       mounted on the exterior of the building. The radiator
released open-source but in a staggered stage after fleet. As     dispenses the heat to atmosphere out doors, preserving a
for the hardware side of things, I personally did not get the     comfortable climate indoors while still utilizing the
impression that the hardware designs would be made open           otherwise wasted solar power output.
source but I don’t have anything specific to cite from Proto
on that, they may surprise us. I do get the impression that       August 26, @boerst adds events panel to stratum.work
Proto will be open to selling their mining ASIC chips a la        enabling users to monitor fork events on-chain, invalid
carte with supporting documentation; however, again I             templates, and soon to be more interesting conditions. There
don’t have anything from Proto to cite on that front but stay     have been instances of invalid mining jobs being passed out
tuned. 256 Foundation was present during the launch event,        by Antpool and others where the Merkle branches are empty
which started at the McLemore Resort near Dalton, GA              yet the coinbase reward totals more than the subsidy; in
where guests enjoyed a reception event and opportunities to       other words, fees were included for non-existant
mingle afterwards. The following morning all guests               transactions. Had a miner found a golden nonce while


                                                       The 256 Foundation
                                                           Page 3 of 5

working on one of these faulty jobs, it would have resulted      for monitoring fans and overall power consumption. The
in an invalid block getting mined. Theories on what’s going      voltage regulator upgrade will require about 10 components
on range from a botched selfish mining attack to glitchy         to be changed along with their tracings. After this last
template code but there will need to be more evidence            change is complete then we will make a few prototypes
collected before the root cause can be definitively              from this design and begin the validation process. Learn
identified. Bitcoin researcher b10c wrote an in-depth            more at libreboard.org.
analysis on invalid mining jobs by Antpool and friends
during forks, you can find it here for more details.

GRANT PROJECT UPDATES:
Ember One
Skot was able to complete the validation process on Ember
One v4. This hashboard is now ready to go into production.
Anyone is free to grab the production files from the GitHub
repo v4 branch and start manufacturing and distributing
these units. We will be following up with an official release
of v4 in the days ahead. Ember One is a ~100W hashboard
built around the Bitmain BM1362AC ASIC chips and it
capable of producing roughly 3.5Th/s. This is unlike the
Bitaxe in that the control board is separate. This is the
hashboard only and all peripheral equipment like the control
board, firmware, power supply, heatsink, and fan are
separate. We will be pointing to reference components for
those separate items in the weeks ahead as these hashboards
get manufactured and we can test different components.
Learn more at emberone.org.
                                                                               [IMG-005] Libre Board electrical traces

                                                                 Mujina Firmware
                                                                 While @ryankuester awaits the Ember One hashboard, he’s
                                                                 been developing Mujina with the Bitaxe Gamma as a stand-
                                                                 in miner, simulating the mining functions. That has allowed
                                                                 him to start flushing out much of what surrounds the hash
                                                                 boards: discovery, hot-plugging, monitoring, logging, pool
                                                                 communication (stratum v1 client only for now), work
                                                                 distribution, API infrastructure, and the start of the CLI and
                                                                 TUI clients of that API. It's a work-in-progress, but an entire
                                                                 system is taking shape. Eventually, Mujina will be it’s own
                                                                 Linux image. Skot is sending Ryan an Ember One prototype
             [IMG-004] Ember One 00 v4 3D rendering              this week so he can work on its unique drivers and
                                                                 integration into the system in time for an initial release and
Libre Board                                                      inauguration of the open source community, concurrently
Schnitzel was able to complete the tracing of the                with the first Ember Ones rolling off the assembly line and
components on the Libre Board through the 6-layer PCB.           shipping to testers and developers. You can learn more at
There was also some work that needed to be done on the           mujina.org.
Bill of Materials to update information from the original
Raspberry Pi I/O Board design. For example, some                 Hydra Pool
components were specific to the U.K. and not readily             Jungly has been monitoring the Hydra Pool test server
available in the U.S., the data sheet references needed to be    announced in last month’s newsletter for various Bitcoin
updated, and a few other things needed to be standardized        mining hardware and firmware types to connect. These test
and cleaned up. After getting everything just about finished     have been helpful to ensure the Hydra Pool server can
we decided at the last minute to upgrade the voltage             communicate appropriately with a wide range of hardware
regulators for both the 12v output and the 5v output to          types. Over 30 different kinds of miners connected and
newer voltage regulators that have Inter-Integrated Circuit      exposed a number of issues that we needed to resolve. We
(I²C) interfaces which will allow the Libre Board to know        are confident now that the Hydra Pool server can handle it’s
how much power is connected to it and how much draw              job of communicating with a wide range of clients no
there is on both the 12v and 5v lines, which can be helpful

                                                      The 256 Foundation
                                                          Page 4 of 5

matter how they are presenting the Stratum data. Users                $6.52/Th. Models >25J/Th are surprisingly higher in price
interested in seeing what a pool server’s logs look like when         this month over last, fetching $3.64/Th now compared to
connecting to Stratum clients can download log files from             $3.04/Th last month.
test.hydrapool.org, IP addresses have been removed. Then
Jungly was able to move on to building the PPLNS payout
mechanism. This is going to enable users to host an instance
of Hydra Pool for others to join and ensure the rewards are
handled in a non-custodial manner as they will be paid from
the coinbase transaction. Hydra Pool will not limit itself by
Bitmain’s arbitrary coinbase payout participant limits,
which is some 16 addresses maximum in the coinbase                              [IMG-007] Miner Prices from Luxor’s Hashrate Index
reward. Users of Hydra Pool will be able to configure this
number to whatever they want, anyone using an old stock               Hashvalue over the month of August stayed relatively flat
Antminer should be aware that it will not handle a template           throughout the month hovering around 49k sats/Ph/day,
with more than some 16 payout addresses. Over the last                according to the Braiins Insights dashboard.
month, we also explored how the Hydra Pool server will
store share data, calculate the PPLNS share window, and
make that data available for auditing so users can ensure
their Hydra Pool host is being honest. We decided that since
the server will be validating all incoming shares anyways
that instead of putting the database resources on the server,
we will just open up an API so anyone can monitor what the
pool is validating and then the person doing the monitoring
is free to compile as much of that data as they want for their
own calculations. There will still need to be some persistent
storage built into the server so that in the event of a server
crash or restart, all the work is not lost. We are anticipating
having the first release of Hydra Pool out next month, stay
tuned for announcements. Learn more at hydrapool.org.                               [IMG-008] Hashprice from Braiins Insights

STATE OF THE NETWORK:                                                 The next halving will occur at block height 1,050,000 which
                                                                      should be in roughly 929 days or in other words ~135,500
Hashrate on the 14-day MA according to mempool.space                  blocks from the the time this newsletter is published.
increased from ~913 Eh/s on the first day of August to ~966
Eh/s by the end of the month, marking roughly +5.8%                   CONCLUSION:
increase for the month. The year to date hashrate difference
is +22.9% using the 14-day MA up until the last day of                Thank you for reading the ninth 256 Foundation newsletter.
August.                                                               Keep an eye out for more newsletters on a monthly basis in
                                                                      your email inbox by subscribing at 256foundation.org. Or
Difficulty only went up in August, starting the month at              you can download .pdf versions of the newsletters from
127.62T and finishing at 129.7T, marking a 1.6% increase              there as well. You can also find these newsletters published
for the month. All together for 2025 up to Epoch #452,
                                                                      in article form on Nostr.
difficulty has gone up ~18.1%.


      [IMG-006] YTD Hashrate & Difficulty from mempool.space

According to the Hashrate Index, new-gen ASIC prices                                                          Live Free or Die,
have decreased over the last month. The more efficient                                                        -econoalchemist
miners like the <19 J/Th models are now fetching
$13.92/Th, down from $17.94/Th last month. Models
between 19J/Th – 25J/Th are selling for $7.56/Th, up from

                                                           The 256 Foundation
                                                               Page 5 of 5


===== DOCUMENT 10 of 27 =====
DATE: 2025-10
LABEL: October 2025
TITLE: Assembling Freedom #10
FILE: 256Foundation-Newsletter-2510_v1.pdf
SOURCE: https://github.com/256foundation/News/blob/main/256Foundation-Newsletter-2510_v1.pdf

Assembling Freedom #10
By: 256 Foundation
A monthly newsletter                                             *opinions expressed do not necessarily reflect those of
                                                                 Proto Global, LLC


October 2025

INTRODUCTION:                                                    speech, the right to own property, the right to privacy, and
Welcome to the tenth newsletter produced by The 256              the right to transact; tools like Bitcoin, Tor, and
Foundation and supported by Proto! You’ll notice a few           GrapheneOS are becoming more important to understand in
changes in this edition: First, we have a new name for the       an increasingly digital world where the technological
newsletter, we are calling it “Assembling Freedom” as a          conveniences that facilitate faster transactions and instant
nod to the God-given right of individuals to peaceably           communication have been turned into surveillance
assemble and collectively express, promote, pursue, and          apparatuses used against us. Supporting open-source
defend their ideas. Also, the focus of this newsletter is to     developers is crucial as there is no freedom tech without
educate people on freedom tech and how to make and               them and without freedom tech there is no free society.
assemble tools they can use to defend their freedoms. Also,
this one is shorter than you may be used to, we want to dial
in the focus so the signal doesn’t get lost among too much
information. September was a bit slower than recent months
for freedom tech; note worthy events none the less include
the ImagineIF summit, Tom’s Hardware featured the 256
Foundation, and our open-source projects are nearing
completion. Dive into all the interesting things going on in
and around the Bitcoin mining industry and catch up on the
latest freedom tech news, free & open mining
developments, 256 Foundation grant progress updates, and
the current state of the Bitcoin network.

FREEDOM TECH NEWS:
September 7, a miner with 200Th/s solves block with Solo
CK Pool. This was the 307th block find for Solo CK Pool
and a miner with 200Th/s has approximately a 1 in 36,000                                   [IMG-001] Presentation Title Image
chance per day of solving a block. Interestingly, the miner
seems to have added a few more miners to their operation         FREE & OPEN MINING DEVELOPMENTS:
after the block find, with the SoloStats Page showing a total    September 2, 256 Foundation takes possession of the
of 19 workers in the historical records with 10 of those         256,000 Intel BZM2 ASIC chips donated by Proto Mining.
currently running for a total of 646Th/s. The worker named       These chips were originally produced roughly 3-years ago
“Blockbuster” appears to be the one responsible for the          and have approximately the same efficiency as the chips
block find judging by the highest reported difficulty of         found in Antminer S19j Pro miners. These chips give
187.32T and this worker is only a ~38Th/s unit. Proving          developers an opportunity to make new Bitcoin mining-
once again that anyone can acquire Bitcoin permissionlessly      related projects a reality. For example, @Real_PizzAndy
through mining.                                                  was one of the recipients and he is planning on building a
                                                                 3D printer that mines Bitcoin to generate the heat needed in
September 20, the inaugural ImagineIF Summit took place          the printer bed. To date all of the donated chips have been
in Nashville bringing together investors, engineers,             disbursed. Unfortunately, technical documentation for the
policymakers, and entrepreneurs for two days to talk about       chips could not be included in the donation however, there
the intersection of Bitcoin, AI, energy, and freedom tech.       is an Intel BZM2-based Bitaxe in the works as well as the
econoalchemist presented “Freedom Tech is Fundamental            next Ember One which will also feature the BZM2 chips
to a Free Society” in closing out the second day’s event         and once those projects are released, they will include the
(presentation starts at the 12:20 mark). This brief              accompanying relevant documentation. Additionally, there
presentation highlights how all governments trend toward         is a group of individuals separate from the 256 Foundation
totalitarianism and the role freedom tech plays in defending     who are working on creating a sub-set of the complete Intel
your God-given rights. For example, the right to free            BZM2 documentation that can be released open-source. We


                                                      The 256 Foundation
                                                          Page 1 of 3

do anticipate receiving more Intel BZM2 chips in the future       prototyping phase, so long as everything passes the
and look forward to not having to un-solder ASIC chips            validation, then there will be a small batch of ~100 units
from existing hashboards in order to harvest the chips for        produced specifically for testers and developers to tinker
new open-source designs. Tom’s Hardware published an              with and help us figure out the best reference power
article covering the news of the donation here.                   supplies, fans, and heatsinks to use. You can learn more
                                                                  about Ember One here.


                                                                                 [IMG-003] Ember One 00 v4.1 vs. v5


             [IMG-002] Intel BZM2 ASIC front & back               Libre Board
                                                                  We recorded a nearly 2-hour schematic review of the Libre
September 29, Tyler Stevens has been making progress this         Board, you can find it here or here. Joining the conversation
month using an Avalon Mini 3 and an Avalon Q to heat The          was Schnitzel, Skot, Ryan, and econoalchemist. The
Space Denver’s facility. You can see how it started earlier       conversation revolves around the final review of the Libre
this month with an external radio frequency temperature           Board, focusing on critical aspects such as ground vias,
sensor talking to Home Assistant integration here; and you        voltage regulators, thermal management, USB-C power
can see how the progress is going here. Tyler is able to          negotiation, LED indicators, and I2C connections. The team
automatically maintain a comfortable 77°F (+/- 1°F) by pre-       discusses the importance of documentation for users
heating the first-floor furnace intake air with an Avalon Q       transitioning from Raspberry Pi, the need for effective
while the furnace runs in circulate mode to keep the warm         thermal management, and the implications of design
air cycling through the vents. On the second floor, there is a    decisions on user experience. Collaboration and
HoneyWell smart thermostat which communicates with                communication are emphasized as essential elements in the
Home Assistant to let it know when the miners are not             hardware development process. This conversation delves
keeping up with the demand for the current temperature            into the intricacies of Raspberry Pi connectivity, focusing
setting, at which point the furnace will supplement the           on the challenges and solutions related to I2C bus
needed heat with the standard natural gas. Saving the Space       management, GPIO pin multifunctionality, and the
on utility bills and mining Bitcoin at the same time. If you      integration of QUIC connectors. The discussion also covers
are interested in learning more about using Bitcoin miners        fan control, LED timing requirements, and the importance
to heat your space, check out the resources available at          of effective communication in collaborative design
heatpunks.org.                                                    processes, culminating in considerations for prototyping and
                                                                  PCB design. Currently, prototype materials for the Libre
GRANT PROJECT UPDATES:                                            Board are on order and we should be able to start the
Ember One                                                         validation process within roughly a month depending on
Ember One 00 (with the Bitmain BM1362 ASICs) is now               when the materials arrive. You can learn more about Libre
on v5, which is available on GitHub as a release candidate        Board here.
here. This version includes an upgraded voltage regulator
that enables live monitoring of power metrics and cleans up       Mujina Firmware
the real estate on the board with the removal of the large        Ryan has been chipping away on Munija Firmware utilizing
inductors. The biggest trade off is that the input voltage        an Ember One 00 v4.1 prototype board. Mujina is built for
range has been narrowed from 12-24vdc down to 12-17vdc.           flexibility and modularity. For example, if a user wants to
The latest version still needs to be prototyped and validated     run a hashboard with Bitmain chips along side a hashboard
before it is officially released. The validation process will     with Intel chips, then Mujina will be able to automatically
include testing the over-voltage protection circuit, which        detect that and adjust workloads accordingly so that the
could potentially sacrifice one of the prototype boards.          available bits to roll in various fields such as nonce, time,
Materials have been ordered to build 5 prototypes, which          version, etc. are made available to each chip depending on
should be finished before the end of October. After the           it’s capabilities. We are anticipating to have an initial


                                                       The 256 Foundation
                                                           Page 2 of 3

Mujina release ready by the time the first production batch          According to the Hashrate Index, new-gen ASIC prices
of Ember Ones rolls out. The Mujina repository will also be          have increased slightly over the last month. The more
made publicly available at that time. You can learn more             efficient miners like the <19 J/Th models are now fetching
about Mujina here.                                                   $14.11/Th, up from $13.96/Th last month. Models between
                                                                     19J/Th – 25J/Th are selling for $4.75/Th, way down from
Hydra Pool                                                           $8.57/Th at the beginning of the month. Models >25J/Th
Jungly makes an appearance on the Stephan Livera podcast             are stable in price, hovering around $3.52/Th now
to talk about decentralizing Bitcoin mining with P2Pool v2,          compared to $3.92/Th last month.
which ties in nicely with the work done on Hydra Pool in
that eventually, multiple Hydra Pool instances will be able
to combine work for shared rewards. Jungly discusses his
work on P2Pool v2, a decentralized mining pool aimed at
improving upon the limitations of the original P2Pool. He
emphasizes the importance of decentralization in Bitcoin
mining and explains the technical innovations that P2Pool
v2 introduces, such as sharechains and atomic swaps for                        [IMG-005] Miner Prices from Luxor’s Hashrate Index
non-custodial payouts. Jungly also highlights the need for
community involvement and developer engagement to                    Hashvalue over the month of September dropped from ~48k
ensure the project’s success, and he shares his vision for a         sats/Ph/day down to ~44.5k sats/Ph/day by the end of the
more accessible and efficient mining ecosystem. Going                month, according to the Braiins Insights dashboard.
back to Hydra Pool specifically, the Stratum sever
component is finished, including the details that make it
work such as defining how the PPLNS calculations are
made, how the validated shares will be exposed for end-
users to verify the pool operator is being honest, and
defining how the difficulty is calculated and returned to the
miners. We are currently cleaning up the code to make it
more presentable and developer friendly, then we are ready
to make the initial release and spin up a test server for
people to try out and help us test the system on Bitcoin
mainnet. We will also update the website with detailed
installation instructions for those who want to try operating
their own Hydra Pool instance. You can learn more here.
                                                                                   [IMG-006] Hashprice from Braiins Insights
STATE OF THE NETWORK:
Hashrate on the 7-day MA according to mempool.space                  The next halving will occur at block height 1,050,000 which
increased from ~969 Eh/s on the first day of September to            should be around March 29, 2028 in roughly 895 days or in
~1,060 Eh/s (1.06 Zh/s) by the end of the month, marking             other words ~130,600 blocks from the the time this
roughly +9.4% increase for the month. The year to date               newsletter is published.
hashrate difference is +34.8% using the 7-day MA up until
the last day of September.                                           CONCLUSION: Thank you for reading the tenth 256
                                                                     Foundation newsletter. Keep an eye out for more
Difficulty only went up in September, starting the month at          newsletters on a monthly basis in your email inbox by
129.7T and finishing at 142.3T, marking a 9.7% increase for
                                                                     subscribing at 256foundation.org. Or you can download .pdf
the month. All together for 2025 up to Epoch #455,
difficulty has gone up ~29.6%.                                       versions of the newsletters from there as well. You can also
                                                                     find these newsletters published in article form on Nostr.


     [IMG-004] YTD Hashrate & Difficulty from mempool.space                                                  Live Free or Die,
                                                                                                             -econoalchemist


                                                          The 256 Foundation
                                                              Page 3 of 3


===== DOCUMENT 11 of 27 =====
DATE: 2025-11
LABEL: November 2025
TITLE: Assembling Freedom #11
FILE: 256Foundation-Newsletter-2511_v1.pdf
SOURCE: https://github.com/256foundation/News/blob/main/256Foundation-Newsletter-2511_v1.pdf

Assembling Freedom #11
By: 256 Foundation
A monthly newsletter                                           *opinions expressed do not necessarily reflect those of
                                                               Proto Global, LLC


November 2025

INTRODUCTION:                                                  explaining IPv4 address scarcity, dynamic IPs' challenges
Welcome to the eleventh newsletter produced by The 256         for IoT and home miners, and benefits of IPv6 for native
Foundation and supported by Proto! We are continuing to        adoption without centralized workarounds. Drama around
modify our newsletter content to make it as impactful as       Bitcoin Core's proposed changes to mempool and relay
possible and make it aligned with everything we have going     policies is unpacked, contrasting with Bitcoin Knots' more
on at the 256 Foundation. That being said, the Freedom         configurable approach to discourage spam while allowing
Tech News section now summarizes the content from              permissiveness. We bring attention to a BIP for scriptable
POD256 throughout the month where we cover a wide              mempool policies for greater control, stress the importance
range of Bitcoin mining and freedom tech topics. We are        of retaining "knobs" for node customization to counter
also dropping the State of the Network section to focus on     potential censorship, and differentiate economic nodes
more practical signal, also users can look up network stats    (connected to miners/wallets) from non-economic ones,
easily and live anytime at the many resources we featured.     advocating for more decentralized setups.

                                                               Finally, we touch on upcoming TabConf in Atlanta, where
FREEDOM TECH NEWS:                                             they'll present on 256 Foundation projects amid growing
From POD256 #89 on October 5, we dive into recent              mining interest at developer conferences. The bulk of the
hardware developments, particularly the completion of the      discussion centers on open source's value in hardware and
Ember One v5 PCB design. Key changes include a new,            software, citing examples like AWS and Microsoft's
more modern voltage regulator with features like digital       eventual embrace, benefits for rapid development and
temperature monitoring, programmable over-temperature          community contributions (e.g., Bitaxe's evolution since May
shutdown, and better performance for high-current              2022 without sole manufacturing burdens), and contrasts
applications. This upgrade addresses heat management           between permissive MIT licenses and copyleft (GPL/OHL)
challenges, as voltage regulators must sit close to ASIC       for ensuring user freedoms like inspection and modification.
chips and handle significant power, drawing comparisons to     We emphasize providing editable CAD files (e.g., KiCad)
GPU designs and industrial miners. They discuss trade-offs,    over PDFs or Gerbers for true openness, debate
such as reducing maximum input voltage to 17v from 24v,        enforcement via entities like EFF, and argue open source
and additions like breaking out pins for optional daughter-    spurs innovation even for commoditized products by
boards to handle fan control, accommodating various setups     accelerating adoption and preventing centralization. The
like standalone, immersion cooling, or multi-board systems.    episode wraps with light-hearted banter about haircuts and
                                                               engagement photos.
The conversation explores practical applications for Ember
One hashboards, emphasizing open-source aspects where          From POD256 #90 on October 15, we begin with light-
designs are shared on the 256 Foundation GitHub for            hearted banter about taxes, financial advice disclaimers, and
community validation and collaboration. We brainstorm          the challenges of non-KYC Bitcoin mining at home without
system builds, noting compatibility with S9 chassis for up     seeking permission. Then transition into updates on the 256
to six boards, integration with Libra control boards via       Foundation's open-source Bitcoin mining projects, noting
USB, and potential for high-power setups using existing        that several grantees are attending TabConf in Atlanta. Eco
power supplies. Ideas for hash rate heating dominate,          details the Mujina firmware, developed by Ryan with his
including fanless designs with massive heat sinks for          extensive embedded Linux background, built from scratch
passive room warming, firmware adjustments to target room      in Rust for modularity and flexibility. Key features include
temperatures via external sensors or Home Assistant            hot-swappable hashboards that auto-detect and load drivers,
integration, and fallback modes like hashing dummy blocks      work distribution based on chip capabilities (e.g., rolling
during network outages to maintain heat output without         bits in nonce, time, or version fields), and broad
rewards. They highlight Ryan's work on Mujina firmware         compatibility beyond just BitAxe devices. The discussion
and shout-outs to contributors like Schnitzel.                 emphasizes how Mujina addresses limitations in existing
                                                               mining firmwares, enabling innovative setups like high-
Shifting to software and broader Bitcoin topics, we discuss    speed nonce exhaustion handling. We also cover Ember One
a retweet about IPv6 support for Bitaxe firmware,              v5 hardware iterations, including a modern voltage


                                                    The 256 Foundation
                                                        Page 1 of 4

regulator upgrade for better performance, reduced noise,          must declare ownership under penalty. Skot, with legal
I2C monitoring of power and temperature, and freed board          assistance, is formally opposing the applications, applying
space for add-ons like fan controllers, all shared openly on      for his own registration, and highlighting the bureaucratic
GitHub despite scope creep beyond initial grants.                 hurdles, including fees and the lack of "public domain"
                                                                  trademarks. The conversation underscores the challenges of
The conversation shifts to Hydra Pool, led by Jungly with         protecting open-source hardware from exploitation while
his PhD in distributed systems and prior P2Poolv2 work,           avoiding centralization, noting similar issues in other
aimed at lowering barriers for non-developers to run self-        countries like China, Germany, and the UK. They
hosted pools via one-click deployment. Initial forks of CK        emphasize that open-source doesn't preclude profitability,
Pool were tested during a telehash event but led to a Rust        citing examples like Arduino, and stress the importance of
rewrite for modernity, with features like user-configurable       community-driven protection through copyleft licenses.
coinbase payouts (breaking Bitmain's 15-16 address limit),
PPLNS mechanisms for proportional rewards, and an API             The discussion shifts to technical updates on 256
endpoint for real-time share verification to avoid burdening      Foundation projects, including the Ember One v5 PCB
operators with massive databases. We explore integration          nearing production with features like impedance-matched
with P2Poolv2 for decentralized coordination and contrast it      traces for high-speed signals (e.g., USB and PCIe),
with Ocean's custodial nuances, where funds auto-payout           automated by manufacturers for optimal performance.
after 100 blocks. Guests, Average Gary and Skot join from         Schnitzel is finalizing the Libre Board design, while Ryan's
TabConf, discussing Stratum v2's advantages over v1,              Mujina firmware, built in Rust for modularity, supports hot-
including binary protocols, end-to-end encryption via Noise       swappable hashboards, dynamic work distribution based on
(similar to Bitcoin nodes), and push-based block templates.       chip capabilities (e.g., rolling bits in nonce, time, or version
Average Gary highlights his work packaging Stratum v2 for         fields), and avoids nonce exhaustion issues at high hash
Start9, enabling hole punching for NAT traversal to allow         rates (>260-280 TH/s). They contrast Mujina's Linux-based
peer-to-peer mining without public IPs, fostering local           approach with ESP Miner for low-power Bitaxe devices,
meetup pools and reducing centralization.                         noting tools like Bitaxe Raw for development passthrough.
                                                                  Tyler details his basement experiments with immersion-
Average Gary elaborates on decentralizing mining further,         cooled S19/S21 miners (e.g., Fog Hashing C2) integrated
proposing randomized coinbase addresses for privacy               into radiant floor heating, using separate loops, PID
(eliminating pool signatures), eHash tokens as speculative        controls, and Home Assistant for automation based on solar
shares backed by proof-of-work for variance mitigation, and       excess, temperature sensors, and thermostats. Challenges
integrations like BDK/LDK in Rust ecosystems.                     include corrosion prevention, dynamic performance scaling
Comparisons arise between Stratum v2 and Datum,                   (DPS) for thermal management, and the need for
favoring Stratum v2 for open specs, Rust tooling, and non-        standardized APIs like ASIC-RS and PyASIC to unify
custodial coinbase control. The group brainstorms real-           miner communication across manufacturers.
world applications, such as dummy work for heat
maintenance in hash rate heaters (e.g., greenhouses or            Broader topics include educational initiatives, such as eco's
homes), solar-powered mining with Home Assistant                  proposed "Assembling Freedom" video series on KiCad,
automation for free energy detection and mode switching           PCB assembly, and electronics unboxing, hosted on
(eco/high), and economic models where eHash enables               Bitcoin.tv to avoid YouTube censorship. They advocate for
marketplaces for block space or hardware loans. We touch          more manufacturers and community contributions to
on CPU optimizations for faster node syncing and the need         dismantle proprietary mining empires, criticizing
for economic nodes with hash rate. The episode closes with        misconceptions that open-source means nonprofit.
shoutouts to hash rate contributors across pools like             Shoutouts are given to hashers on pools like Lincoin, Solo
Lincoin, Solo CK, Public Pool, and Ocean, featuring               CK, Public Pool, and Ocean, with creative worker names
creative worker names promoting businesses, and teases            promoting businesses (e.g., flute sheet music, refurbished
upcoming events like the Bitcoin Veterans Summit telehash.        nodes). The episode closes with a tangent on space-based
A brief firearms tangent covers building AR-15s from mil-         mining, featuring Dyson Labs' plan to launch a Bitaxe
spec parts and shooting experiences, underscoring the             CubeSat for low-Earth orbit, addressing challenges like
podcast's casual, community-driven vibe amid technical            radiative cooling, radiation hardening, and rideshare
depth.                                                            launches, potentially using miners as resistive heaters in
                                                                  vacuum conditions.
From POD256 #91 on October 22, we open with hosts Skot,
Tyler, and eco discussing trademark disputes surrounding          A brief firearms and CAD software sidebar touches on
the Bitaxe project. Skot explains how two Chinese entities        FreeCAD's usability issues, while the hosts reflect on
are attempting to illegally register the Bitaxe trademark in      Bitcoin's white paper anniversary and the untapped potential
the US, despite his prior use of the TM symbol for over two       of hash rate heating, urging involvement in open-source
years. This involves perjury risks for the applicants, as they    efforts to commoditize mining tools.


                                                       The 256 Foundation
                                                           Page 2 of 4

From POD256 #92 on October 29, we open with hosts Skot,             October 31, Satoshi Starter launched by Reckless Systems
Tyler, and eco engaging in casual banter about approaching          is a project utilizing the Intel BZM2 ASIC chips donated by
episode 100 and the cold weather across their locations,            Proto Mining to the 256 Foundation and then disbursed to
contrasting Colorado's dry, sunny chill with Nashville's            eager builders such as Reckless Systems. The projects aims
humid cold. They discuss Tyler’s recent Forbes feature on           to deliver an open reference hardware design with
"heat punk" projects, highlighting initiatives like Mint            supporting documentation. The documentation will provide
Green's community pool heating in Vancouver and Proto's             all necessary information about how the ASIC chip works
open-source efforts, emphasizing how Bitcoin mining                 and how to interface and communicate with it so that no
eliminates energy FUD by re-purposing waste heat. The               reverse-engineering is needed. The ability to develop and
conversation praises Canaan's home mining revenue (about            build with un-used ASIC chips and not have to un-solder
a third from smaller units) and their efficiency (e.g., A16 at      them from existing miners and reverse engineer how they
12 J/TH), while critiquing Bitmain's dominance and                  work is a massive step in the right direction. If this projects
proprietary practices, including rumors of pre-mining units         interests you, you can support it through Geyser Fund.
during "break-in" periods for profit. Eco shares progress on
Libre Board prototypes, delayed by customs destroying a             GRANT PROJECT UPDATES:
shipment of components, and Hydra Pool's Docker-based               Ember One
release for easy self-hosting, tested with Bitaxe variants.         Eco received printed circuit boards and the components
                                                                    needed to assemble the first five Ember One 00 v5
Technical deep dives include integrating Canaan miners              prototype boards. Once he has those assembled, then he can
(Avalon Q, Mini 3, Nano) into Home Assistant via Node-              send them out to the devs for validation. Once validated and
RED for automations like solar-optimized mining, real-time          assuming no modifications are needed then he will do a
hash price adjustments, and thermostat-linked controls,             small production run of about 100 units. In the picture
bypassing proprietary APIs with shell scripts or ASIC-RS            below, the Ember One 00 v5 board is loaded in the Pick and
and PyASIC. They explore RISC-V processors in                       Place machine and certain coordinates are being taken from
Espressif's C6 chip for open-source benefits, Zigbee for            the boards physical location relative to the placement bed of
low-power IoT (e.g., sensors lasting years), and Skot's             the machine, those values are saved in the machine’s
single-board miner using an Adit Board and Ant Hat for a            software and later used as references against the component
stealth enclosure, aimed at tobacco curing with heat reuse.         placement coordinates that are exported from the kiCAD
Privacy concerns arise, advocating password managers                software.
(Bitwarden/KeePass),       de-Googling      (GrapheneOS),
encrypted messaging (Signal), and self-hosting to avoid
data harvesting by services like U-Haul or Ring, with
anecdotes on invasive tech (e.g., car tracking, opt-out
surveillance).

Broader topics critique Luke Dashjr's BIP-444 soft fork for
implying legal risks and labeling non-adopters as supporting
illicit content, contrasting it with open initiatives like Hydra
Pool. Shoutouts go to hashers on pools like Lincoin, Solo
CK, Public Pool, and Ocean, with creative names. The
episode teases the 256 Foundation's Telehash in January on
Hydra Pool, discusses hash rate as a prosperity metric over
GDP (measuring energy efficiency/monetization), and ends
with humor about network growth (1.12 Zeta hash) and
Skot's kiln project.

                                                                              [IMG-001] Ember One 00 v5 on the PnP Machine
FREE & OPEN MINING DEVELOPMENTS:
October 28, Home Assistant docs updated from Exergy,
                                                                    Libre Board
explaining how to send commands to Canaan Avalon Mini 3
                                                                    Schnitzel went on a Twitter Spaces with @BuildaMinePod
miners in Home Assistant, using Node-RED and direct
                                                                    to discuss the Libre Board project and home mining heat re-
Canaan API calls. The documentation is rich in detail and
                                                                    use applications. The discussion centered on democratizing
extensive, enabling users to control a Canaan Avalon Mini 3
                                                                    Bitcoin mining, emphasizing how everyday individuals can
baseboard style miner/heater; from turning the device on/off
                                                                    participate without massive infrastructure investments. They
to switching modes and power levels, this documentation
                                                                    explored the evolution of mining from industrial-scale
will help you take your home mining setup to the next level
                                                                    operations to more inclusive models, highlighting barriers
of integration, control, and convenience.
                                                                    like high energy costs and hardware complexity. The host


                                                         The 256 Foundation
                                                             Page 3 of 4

opened by sharing insights on setting up affordable home           1) Run a private solo pool or host a PPLNS pool for your
nodes, stressing the importance of decentralization for            community of miners.
Bitcoin's resilience.                                              2) Payouts are made directly from the coinbase, meaning
                                                                   the pool operator doesn't custody any funds. No need to
A key segment focused on practical home mining setups,             trust the pool operator.
where Schnitzel detailed low-barrier entry points such as          3) Speaking of trusting the pool operator, users can
using consumer-grade ASICs or repurposed hardware. The             download and validate the accounting of shares. We provide
conversation addressed common challenges like noise                an API for the same. See API Server in GitHub.
reduction, power efficiency, and pool selection, with tips on      4) Prometheus and Grafana based dashboard for pool, user,
integrating mining with household energy systems. They             and worker statistics.
discussed how recent advancements in firmware and open-            5) Use any bitcoin node that supports bitcoin RPC.
source tools have lowered the technical threshold, allowing        6) Implemented in Rust, for ease of extending the pool with
hobbyists to contribute to the network while earning modest        novel accounting and payout schemes.
rewards. The host emphasized running full nodes alongside          7) Open source with AGPLv3. Feel free to extend and/or
mining to enhance security and sovereignty, arguing that           make changes.
accessibility strengthens Bitcoin against centralization risks.
                                                                   You can install Hydra Pool using the provided Docker files
The talk concluded with an in-depth look at waste heat             or you can build from source. We are working on packaging
utilization, a specialty of Schnitzel’s Nakamoto Heating           for Start9OS with the help of some pull requests which have
startup. He explained how miners can re-purpose excess             already come in from the community.
heat for home heating, water warming, or even greenhouse
applications, turning energy consumption into a dual-
purpose benefit. Examples included real-world case studies
of miners offsetting utility bills through heat recovery,
promoting sustainability. The hosts wrapped up by
encouraging listeners to start small, underscoring that
widespread home mining fosters a more robust,
decentralized Bitcoin ecosystem for the future.

Mujina Firmware
Ryan has been preparing to release the Mujina Developers
Preview, which will ship with the following disclaimer:                            [IMG-002] Hydra Pool Dashboard
“This software is under heavy development and not ready
for production use. The code is made available for
                                                                   CONCLUSION: Thank you for reading the eleventh
developers interested in contributing, learning about Bitcoin
mining protocols, or evaluating the architecture. APIs,            256 Foundation newsletter. Keep an eye out for more
protocols, and features are subject to change without notice.      newsletters on a monthly basis in your email inbox by
Documentation is incomplete and may be inaccurate. Use at          subscribing at 256foundation.org. Or you can download .pdf
your own risk.”. This initial public release will give             versions of the newsletters from there as well. You can also
developers a chance to see the foundations of Mujina and           find these newsletters published in article form on Nostr.
understand how it operates. They will also be able to test it
out on Bitaxe hardware to hold them over until some Ember
Ones are produced and/or until Mujina is able to run on
other already existing hardware.

Hydra Pool
On October 26 Hydra Pool was released and is now on
v1.1.18. Hydra Pool is an open Source Bitcoin Mining Pool
with support for solo mining and PPLNS accounting. We
                                                                                                       Live Free or Die,
have an instance mining on mainnet at test.hydrapool.org.                                              -econoalchemist
But we hope you'll run a pool for yourself. The GitHub repo
has instructions for running installing Hydra Pool and we
will be producing a detailed step-by-step guide in the days
ahead. We only accommodate up to 100 users at the
moment for coinbase and block weight reasons, workers are
limited by your hardware. Features include:


                                                        The 256 Foundation
                                                            Page 4 of 4


===== DOCUMENT 12 of 27 =====
DATE: 2025-12
LABEL: December 2025
TITLE: Assembling Freedom #12
FILE: 256Foundation-Newsletter-2512_v1.pdf
SOURCE: https://github.com/256foundation/News/blob/main/256Foundation-Newsletter-2512_v1.pdf

Assembling Freedom #12
By: 256 Foundation
A monthly newsletter                                              *opinions expressed do not necessarily reflect those of
                                                                  Proto Global, LLC


December 2025

INTRODUCTION:                                                     build upon existing technologies without being hindered by
Before you read any further, sign the petition to pardon          proprietary constraints.
Samourai Wallet. Software developers should not be held
accountable for the actions of end users. That is a very basic    Hydra Pool and Decentralized Mining:
and reasonable position to hold, so if you agree then show        The introduction of Hydra Pool, an open-source Bitcoin
your support by joining the thousands who have taken a            mining pool, marks a step forward in unstoppable mining
stand to pardon Samourai Wallet.                                  operations. This tool allows users to run their own mining
                                                                  pools, promoting a more distributed and resilient network.
Welcome to the Twelfth newsletter produced by The 256
Foundation and supported by Proto! This will be the last
monthly newsletter and will move to a weekly cadence after
January 1, 2026. Massive shout out to Proto for their
support over the last 12 months! We have been refining the
format of this newsletter to try and maximize the focus on
signal. Below you will find short descriptions on a number
of freedom tech topics spanning last month that are centered
around open-source Bitcoin mining.

FREEDOM TECH NEWS:                                                The Legal Landscape for Open Source Developers:
In this edition, we delve into the intricate world of Bitcoin     This ties-into the legal challenges faced by open-source
mining and open source hardware, exploring the latest             developers, particularly in the context of the Samourai
developments and their implications for the industry.             Wallet case. Highlighting the need for clear legal
                                                                  frameworks that protect developers and encourage
Canaan's Open Source Move:                                        innovation. More details on this below.
Canaan has open-sourced a new repository on GitHub,
revealing the source for their Avalon miners' firmware. This      Bitcoin Veterans and Telehash Event:
move towards transparency is significant, as it opens up          Recently, Nashville hosted the Bitcoin Veterans, a group
possibilities for innovation and collaboration within the         dedicated to integrating veterans into the Bitcoin
community. The release under the BSD3 clause license,             community. Their event highlighted the potential of Bitcoin
however, raises questions about compatibility with existing       as a tool for empowerment and financial independence. The
open-source licenses like GPL-V3. Being that Canaan is a          discussion touched on the technical aspects of Bitcoin
distant third in the mining hardware marketplace, there           mining, including the challenges and opportunities of
really is only upside for them to embrace open-source and         pooled mining and the impact of hash rate fluctuations.
get community contributions.
                                                                  Square's Lightning Integration:
RISC-V and the Future of CPUs:                                    Square's roll-out of Lightning integration marks a
This discussion leads to Canaan's K230, a dual-core RISC-         significant step in Bitcoin's mainstream adoption. This
V processor. This development is noteworthy as it                 move allows for seamless Bitcoin transactions, enhancing
represents a shift towards more open and customizable CPU         user experience and encouraging more merchants to accept
architectures, potentially revolutionizing the way                Bitcoin. This article explores the technical nuances of this
developers approach hardware design.                              integration and its potential to revolutionize digital
                                                                  payments.
The Role of Open Source in Home Mining:
With home mining products accounting for a significant            Hashrate Heating Systems:
portion of revenue, the push towards open-source solutions        The innovative use of Bitcoin mining hardware for heating
is not just a trend but a necessity. This shift is crucial for    systems was a focal point in November. This approach not
fostering innovation and ensuring that the community can          only optimizes energy use but also provides a sustainable
                                                                  solution for heating needs. The technical details of

                                                       The 256 Foundation
                                                           Page 1 of 3

integrating mining hardware with existing heating systems        Innovative Power Solutions:
were discussed widely in the budding community on the            The discussion also covered creative solutions for powering
Heat Punks Forum page, showcasing the potential for cost         mining operations, from using electric vehicles as mobile
savings and environmental benefits.                              power sources to the potential of integrating mining with
                                                                 everyday appliances.
256 Foundation's Open Source Initiatives:
The 256 Foundation is at the forefront of dismantling            Community Contributions:
proprietary mining empire by promoting open-source               We celebrated the contributions of community members
Bitcoin mining hardware and software. Our projects, such         who are pushing the boundaries of what's possible with
as the Ember One, Mujina, Libre Board, and Hydra Pool            open source tools, showcasing the power of collaboration in
aim to open-source the whole Bitcoin mining technology           driving technological advancements. There have been some
stack, making it accessible to anyone from individuals to        pull requests in the Hydra Pool repo, and a few community
small communities to industrial-sized miners. The technical      contributed repos to the 256 Foundation GitHub
intricacies of these projects were explored in depth on          Organization like asic-rs.
POD256 throughout the month, highlighting their potential
to decentralize mining and empower users.                        The Case of Samourai Wallet:
                                                                 The recent unprecedented attack on William (Bill) Hill and
The Rise of Open Source Mining:                                  Keonne Rodriguez, co-founders of Samourai Wallet
We delved into the significance of open source mining            underscores the ongoing regulatory battles in the crypto
firmware like Mujina, highlighting its potential to              space. In November, Keonne Rodriguez joined us on
revolutionize the industry by offering transparency and          POD256 #96 to tell all. The discussion provided a deep dive
control to miners. This shift is crucial as it challenges the    into the legal and technical aspects of the case, emphasizing
proprietary stronghold of major manufacturers, fostering         the importance of protecting open-source developers and
innovation and collaboration.                                    the broader implications for the crypto community.

Bitcoin++ Event Insights:
The Bitcoin++ event was a melting pot of ideas, bringing
together developers and miners. The event underscored the
importance of bridging the gap between these communities,
emphasizing the role of open source in democratizing
mining technology. We announced the Developer Preview
of Mujina Mining Firmware is now open to the public, learn
more on the GitHub repo.


                                                                 We explored the vicious attacks by federal prosecutors at
                                                                 the SDNY faced by Bill and Keonne for a non-custodial
                                                                 Bitcoin wallet. Despite being an open-source and
                                                                 permissionless tool for financial privacy, it was labeled as a
                                                                 money transmitter by federal prosecutors who had to lie,
                                                                 cheat, and hide evidence to get their way. This case
                                                                 highlights the tension between innovation and regulation,
                                                                 emphasizing the need for clear legal frameworks that
                                                                 recognize the role of technology in protecting privacy and
                                                                 ensuring that tool makers are not held liable for the actions
                                                                 of end-users.

                                                                 The Role of Privacy Tools:
The Battle for Tech Freedom:                                     Privacy-enhancing technologies like CoinJoin and
Our conversation touched on the broader implications of          Whirlpool were discussed as essential tools for maintaining
freedom tech, particularly in the context of software            financial privacy. These innovations allow users to control
development. We discussed the challenges faced by                their funds without exposing their private keys, challenging
developers in maintaining privacy and autonomy in an             the notion that privacy equates to criminality. The
increasingly regulated environment.


                                                      The 256 Foundation
                                                          Page 2 of 3

conversation underscored the importance of these tools in       Future Implications:
empowering individuals against unwarranted surveillance.        The broader implications of these discussions are clear: as
                                                                technology continues to evolve, so must our understanding
                                                                and defense of the rights it can protect. The conversation
Legal Precedents and Challenges:                                serves as a reminder that technological innovation is not just
The discussion touched on historical legal precedents, such     about advancement but also about safeguarding the
as the Falcone case, which set standards for conspiracy         freedoms we hold dear. Let's continue to champion the role
charges. These precedents are crucial in understanding the      of technology in protecting our rights and freedoms, code
legal landscape for developers and innovators. In Falcone,      does not equal crime.
the United States Supreme Court found that a merchant who
sold sugar to a bootlegger during the prohibition was not an    CONCLUSION:
active conspirator in the crime even though they had vague      Join us in our mission to advance open source technology
knowledge that the sugar would be used to produce alcohol.
                                                                and Bitcoin adoption. Your support is crucial in driving
The conversation also highlighted the challenges of
defending technological innovations in court, where the         these innovations forward.
burden of proof often falls heavily on the creators but         Key Takeaways:
corrupt judges prevent the jury from hearing it.
                                                                Open-source hardware and software are pivotal in driving
Community Support and Advocacy:                                 innovation and decentralization in the Bitcoin mining
The importance of community support in defending
                                                                industry. Legal clarity and support are essential for fostering
technological rights was emphasized. The conversation
called for a collective effort to support open-source           a thriving open-source ecosystem. The community's role in
developers and protect the tools that enable privacy and        testing and developing new solutions is more critical than
freedom. This is a pivotal moment for the tech community        ever.
to rally together and advocate for fair treatment of
innovators. If you have not done so already, please sign and    Stay Informed and Engaged:
share this petition to pardon Samourai Wallet.                  We invite you to join the conversation and contribute to the
                                                                ongoing development of open-source solutions. Your
                                                                insights and expertise are invaluable in shaping the future of
                                                                this industry.

                                                                Subscribe now to stay updated on the latest developments
                                                                and be part of a community that is driving change.


                                                                                                    Live Free or Die,
                                                                                                    -econoalchemist


                                                     The 256 Foundation
                                                         Page 3 of 3


===== DOCUMENT 13 of 27 =====
DATE: 2026-01-14
LABEL: January 14, 2026
TITLE: Assembling Freedom #13
FILE: 256Foundation-Newsletter-260114_v1.pdf
SOURCE: https://github.com/256foundation/News/blob/main/256Foundation-Newsletter-260114_v1.pdf

Assembling Freedom #13
By: 256 Foundation
A weekly newsletter
January 14, 2025

INTRODUCTION:                                                     metrics like share submission rates, hash rate variance, and
                                                                  latency. Extrapolating, this implies robust handling of
Welcome to this special edition of the Bitcoin mining             Stratum v1, offering better efficiency through job
insights newsletter, where we dissect the latest episode of       negotiation and reduced bandwidth via binary encoding.
POD256 Episode 101: "HydraPool, HashDash, and the                 Developer d++ discussed stress-testing scenarios,
Telehash Playbook: Open-Sourcing Bitcoin Mining".                 suggesting optimizations for variance smoothing in hash
Hosted by Tyler, Skot, Rod and eco, with guest developer          rate displays and difficulty unit conversions (e.g., from
d++, this episode dives into the nuts and bolts of open-          hashes to EH/s). We can infer integration with non-custodial
sourcing the Bitcoin mining stack. Recorded on January 14,        features, where pools don't hold funds but route rewards
2026, the discussion emphasizes practical implementations         directly via on-chain or other options currently being
in Rust, real-time dashboards, fundraiser integrations, and       explored like ehash. The mention of miner-type
the push against proprietary monopolies. For our technical        fingerprinting via user agents (e.g., parsing Stratum headers
audience—miners, developers, and hardware enthusiasts—            for miner models like Antminer S19) points to future
we'll break down key topics into dedicated sections. Each         analytics for pool operators to optimize for hardware
section explores the topic's importance, extrapolations from      diversity, potentially detecting anomalies like faulty
the dialogue, and broader implications, drawing on                hashboards.
technical details like protocol integrations, scalability
testing, and ecosystem interoperability to provide actionable     For enthusiasts running home rigs or small farms,
insights.                                                         HydraPool's open-source nature implies a shift toward
                                                                  modular mining ecosystems. Imagine forking the Rust
                                                                  codebase to add custom features, like automated
HydraPool: The Rust-Based Open-Source Mining Pool                 overclocking based on Prometheus alerts or Stratum v2
Stack                                                             extensions for demand-response mining (pausing during
                                                                  high electricity costs). Broader implications include
HydraPool represents a critical step toward democratizing         enhanced decentralization: by open-sourcing the pool
Bitcoin mining by providing an open-source alternative to         alongside hardware like Ember One hashboards, miners can
proprietary pool software like Bitmain’s Antpool backed           achieve end-to-end transparency, auditing code from
FPPS monopoly or other centralized entities. Built in Rust        firmware to payout scripts. This counters proprietary shifts
for its memory safety, concurrency advantages, and                (e.g., Bitmain's rumored federal probes), fostering resilience
performance in high-throughput environments, HydraPool            against regulatory pressures. Technically, it encourages
draws inspiration from established pools like CKPool (for         contributions like Stratum v2 support, potentially reducing
efficient share processing) and P2Pool v2 (for decentralized      global pool latency by 20-30% through better header
payout mechanisms). It supports flexible payout models            compression, and integrates with tools like Home Assistant
including solo mining (where miners keep full block               for IoT-controlled mining setups. Long-term, this could
rewards), Pay Per Last N Shares (PPLNS, which rewards             lower entry barriers, enabling more nodes and reducing
miners proportionally to their hashrate contribution), and        hash rate concentration in regions like China or the US.
multi-address coinbase outputs (allowing up to 100
addresses per block for distributed rewards). This is vital in    HashDash and TeleDash: Real-Time Visualization and
an era where pool centralization risks censorship; open-          Dashboards
source pools enable self-hosting, reducing trust
dependencies and custody risks. For technical miners, the         Visualization tools like HashDash and TeleDash address a
one-command spin-up (e.g., via Docker or Cargo) lowers            key pain point in mining: opaque monitoring. HashDash
barriers to running custom pools, integrating with tools like     serves as a pool visualizer, rendering metrics like total hash
Prometheus for metrics export and Grafana for                     rate, active workers, and share distributions in real-time.
visualization.                                                    TeleDash extends this for fundraiser streams, featuring
                                                                  overlays and a "jumbotron" view with data such as block
The episode highlights HydraPool's scalability testing to         height, BTC price, donation messages, odds of finding a
handle 10,000 workers, using Prometheus to monitor                block, and leaderboards. Built on Prometheus/Grafana

                                                       The 256 Foundation
                                                           Page 1 of 3

stacks, these tools are essential for technical users who need    parameters like difficulty units and hash rate smoothing,
granular insights—e.g., querying time-series data for             while integrating Lightning for instant micro-donations.
variance analysis or alerting on dropped connections. In a
field where downtime costs rewards, these dashboards              Extrapolations include user experience enhancements:
enable proactive management, integrating with Nostr npubs         smoothing visualizations to handle ASIC variance (e.g.,
for social profiles to build community around mining.             using Kalman filters for prediction), displaying best shares
                                                                  for motivation, and leaderboards ranked by effective hash
Developer d++ walked through HashDash's interface,                rate (adjusted for luck via variance normalization). The
suggesting extrapolations like smoothed hash rate curves          port-specific join (3333) implies Stratum protocol
(using exponential moving averages to filter noise from           extensions for address validation, preventing invalid
variable ASIC performance) and best-share displays                submissions. Funds raised via on-chain/Lightning suggest
(tracking shares above target difficulty for luck estimation).    oracle integrations for price feeds, with odds calculated
TeleDash's real-time overlays imply WebSocket integrations        dynamically. Past events extrapolate to handling transient
for live updates, potentially using Rust's async crates like      exahash spikes, testing pool resilience against DDoS-like
Tokio for handling concurrent streams. The jumbotron's            share floods.
inclusion of on-chain/Lightning funds raised extrapolates to
blockchain API pulls (e.g., via Electrs or Blockstream            Telehash implies a model for community-funded R&D,
APIs), calculating metrics like odds (based on network            where miners contribute hash for grants (e.g., $400k
difficulty and pool hash rate via formula: odds =                 allocated to open projects). Broader effects: it normalizes
(network_hash_rate / pool_hash_rate) * 600 seconds per            non-custodial fundraising, reducing reliance on VCs and
block). Leaderboard ideas point to sorting by contributed         promoting Bitcoin's sovereignty ethos. Technically,
hash rate or shares, with potential for gamification via Nostr    enthusiasts could replicate for local meetups, using
relays.                                                           TeleDash for live demos, fostering education on protocols
                                                                  like Stratum. Implications for decentralization: by attracting
These tools imply a future where mining becomes more              small hashers, it dilutes large-pool dominance, potentially
accessible and engaging, akin to DeFi dashboards. For             increasing Nakamoto coefficient. Long-term, integrations
technical enthusiasts, implications include custom                with Nostr could evolve into social mining networks, where
extensions—e.g., integrating ML models (via Rust's                npubs link to profiles for collaborative overclocking tips or
TensorFlow bindings) to predict block finds based on              shared firmware mods.
historical shares. Broader ecosystem effects: enhanced
transparency reduces scam pools (by verifying coinbase            Open-Sourcing the Entire Bitcoin Mining Ecosystem
outputs), and social integrations like Nostr could spawn
mining DAOs for collective bargaining on energy deals. In         The episode's core ethos—open-sourcing hashboards,
decentralized setups, this fosters hybrid pools blending solo     control boards, firmware, and pools—tackles the "black
and shared mining, potentially increasing overall network         box" monopoly of vendors like Bitmain. Projects like
security by distributing hash rate. For large-scale operators,    Mujina firmware (running on Bitaxe Gamma) enable
Grafana's alerting could automate failover to backup pools,       verifiable code, crucial amid regulatory scrutiny (e.g.,
minimizing losses from outages, while open-source code            GrapheneOS pullback from France). For technical users,
invites forks for specialized dashboards (e.g., energy-           this means auditable security, reducing risks like backdoors
efficiency tracking via wattage sensors).                         in proprietary firmware.

Telehash: The Integrated Fundraiser Stream                        Extrapolations: community contributions like Home
                                                                  Assistant integrations for Avalons/WhatsMiners imply IoT
Telehash is a live fundraiser stream tied to the mining pool,     ecosystems for mining. The 256 Foundation's grants
where      participants      point      hash      rate     to     extrapolate to a pipeline: from prototypes (Ember One v5)
pool.256foundation.org:33303 using a valid BTC address as         to developer kits, accelerating iterations via GitHub PRs.
the username and any vanity workername you choose. For            Stress-testing to 10k workers suggests Kubernetes
example:                                                          deployments for horizontal scaling.
bc1qce93hy5rhg02s6aeu7mfdvxg76x66pqqtrvzs3.bitaxe69.
                                                                  Implications include a fully open stack for "plug-and-play"
This blends mining with philanthropy, routing rewards to          mining, rivaling proprietary efficiency (e.g., Ember One
causes like the 256 Foundation. Importance lies in its real-      aiming for S19 parity). Broader: counters hardware shifts to
world testing of open stacks: previous Telehash events (e.g.,     hydro gear, enabling "hand-me-down" repurposing with
#1 with the Apollo solo pool hitting an exahash and finding       open firmware. For enthusiasts, this sparks innovation
block 881423) demonstrate scalability under bursty loads.         waves—e.g., custom ASICs via FPGA prototyping—
For technical miners, it provides a playground for tweaking       boosting network resilience and reducing geopolitical risks.


                                                       The 256 Foundation
                                                           Page 2 of 3

Industry Rumors and Hardware Shifts

Rumors of Bitmain's S23 air-cooled units and pivot to
hydro/data-center    gear    highlight  supply   chain
vulnerabilities. Open-source counters this by enabling
legacy hardware revival, important for miners facing
shortages.

Extrapolations: federal probes imply compliance burdens,
pushing vendors to specialized gear. "Hand-me-down"
hardware suggests market floods of older ASICs, ripe for
open firmware upgrades.

Implications: opportunities for efficiency hacks, like water-
cooled     blocks     on     S19s.    Broader:    accelerates
decentralization as small miners access affordable gear,
potentially shifting hash rate to renewable-heavy regions.

Future Developments:          Hardware,      Events,     and
Contributions

Previews of Ember One integrations, Mujina firmware,
water-cooled blocks, and Heat Punk Summit underscore
sustained R&D. Supporting Samourai via petitions
emphasizes freedom tech's role against "toolmaker"
targeting.

Extrapolations: early cooling tests imply thermal modeling
(e.g.,  CFD      simulations     for    heat   dissipation).
NEMS/Telehash #3 on open stacks extrapolate to live
demos, inviting code contributions.

Implications: developer kits enable custom builds, fostering
a vibrant ecosystem. Broader: events like Heat Punk
Summit could standardize open protocols, enhancing
interoperability and driving adoption of sustainable mining
practices.

Thank you for reading—stay tuned for more technical deep
dives. Point your rigs wisely!


                                                       The 256 Foundation
                                                           Page 3 of 3


===== DOCUMENT 14 of 27 =====
DATE: 2026-01-30
LABEL: January 30, 2026
TITLE: Assembling Freedom #14
FILE: 256Foundation-Newsletter-260128_v1.pdf
SOURCE: https://github.com/256foundation/News/blob/main/256Foundation-Newsletter-260128_v1.pdf

Assembling Freedom #14
By: 256 Foundation
A weekly newsletter
January 28, 2025

Ladies and gentlemen, imagine if you will, the vast digital       efficiency at the hardware level: Ember One's open
frontier of Bitcoin mining, where silicon warriors hash           hashboard design, based on BM1362 or Intel BZM2 ASICs,
away in the pursuit of blocks and freedom. This is                allows for fluid cooling mods that capture excess heat for
Assembling Freedom, guiding you through the electrifying          practical uses. The chat reveals how this setup maintained
insights from POD256's Episode 102: "Why Open                     stable hashing over hours, with water temps hitting that
Firmware Wins: A Post-NEMS Debrief with Mujina's Lead             perfect 131°F for medium-rare perfection, all while mining
Dev." We'll dive deep into the heart of this conversation,        live on mainnet. Think about the extensions—integrate this
carving it into crisp sections, each pulsing with technical       into home setups for water heating or industrial ops for
depth for you mining mavens. We'll unpack why these ideas         district warming, slashing operational costs by 20-30% in
matter, draw out the clever takeaways, and explore the            cold climates. For Bitcoin miners, the implication is huge:
ripple effects that could reshape your rigs and the entire        sustainable practices that attract eco-conscious investors,
ecosystem. Buckle up—it's time to hash it out with style and      comply with tightening regulations like EU's green
substance.                                                        mandates, and open doors to hybrid revenue streams beyond
                                                                  block rewards. Your rigs could evolve from power hogs to
The Momentum of Telehash #3: Igniting the Open Stack              smart energy assets, boosting profitability in a post-halving
Revolution                                                        era.
Picture this: an eight-hour live-streamed extravaganza
where the 256 Foundation's fully open Bitcoin mining stack        GitHub from Genesis: The Open Release Ethos
springs to life, proving that transparency isn't just a           Ah, the beauty of dropping everything on GitHub right from
buzzword—it's a powerhouse. This debrief kicks off with           the start—no teasers, no paywalls, just pure, accessible
Telehash #3, a demo that showcases seamless integration of        code. This approach, championed in the episode,
open hardware and software, drawing eyes from across the          underscores why open firmware like Mujina triumphs: it
industry post-NEMS (the North East Mining Summit, a hub           accelerates feedback loops, inviting global devs to poke,
for cutting-edge mining talks). Why does this matter? In a        prod, and polish. Crucially, it dismantles the opacity that
world dominated by proprietary black boxes from giants            plagues closed-source firmware, where bugs linger and
like Bitmain, Telehash #3 demonstrates that open                  custom tweaks are forbidden. The debrief emphasizes how
alternatives can run reliably, fostering trust and                this day-one openness built momentum post-NEMS, with
collaboration among developers and operators. From the            code under GPL v3 fostering rapid iterations. Draw from
discussion, we see how this live proof-of-concept validates       this: a Rust-based, async architecture that's not just
the stack's stability, handling real-time hashing without         performant but extensible, supporting USB serial comms
proprietary crutches. The broader impact? For you technical       for diverse boards. The wider view? Enthusiasts, you gain
enthusiasts, it signals a shift toward decentralized              tools to audit and secure your operations, mitigating
innovation—imagine customizing your fleet without vendor          backdoor risks seen in past Bitmain scandals. It paves the
lock-in, reducing risks from supply chain chokepoints in          way for community-driven standards, potentially
Taiwan or China, and empowering smaller players to                standardizing protocols like Stratum v2 across vendors,
compete on merit. This isn't just a demo; it's a blueprint for    enhancing network security and reducing centralization
a more resilient Bitcoin network, where hashrate                  around a few firmware providers. In essence, it's fuel for a
distribution evens out and geopolitical vulnerabilities fade.     mining renaissance, where innovation flows freely and your
                                                                  custom scripts could redefine efficiency.
Sous Vide Mining: Heat, Hash, and a Side of Ribeye
Now, let's savor the ingenuity of the sous vide miner demo        Mujina's Modularity: Sparking ASIC and Board
—three Ember One hashboards, tricked out with custom              Breakthroughs
water blocks, churning hashes while precisely cooking             Enter Mujina, the star of the show—a Linux-based, open-
ribeyes, all orchestrated by a Libre board prototype running      source firmware in Rust, designed for modularity that lets
Mujina firmware and pointed at Hydra Pool. This isn't             you mix ASICs like BM1370 on Bitaxe Gamma with
gimmickry; it's a vivid illustration of waste heat                upcoming support for Antminer S19j Pro and beyond. This
repurposing, turning mining's notorious energy guzzle into a      matters profoundly because proprietary firmware often ties
dual-purpose marvel. Its importance lies in highlighting          you to specific chips, stifling upgrades. The lead dev, Ryan,

                                                       The 256 Foundation
                                                           Page 1 of 3

breaks down how Mujina's clear separation of concerns—             Fleet-Scale Open Firmware: The Profit Playbook
from stratum clients to hardware drivers—enables hot-              Scaling to fleets, the business case shines: open firmware
swappable boards without restarts, a boon for uptime-              cuts dev fees (often 2-3% in closed systems) and enables
obsessed ops. Insights here include its API-driven control,        precise power targeting, optimizing for low-cost energy
allowing REST calls for custom overclocking or power               spots. It's essential for profitability in volatile markets, as
tuning, far beyond basic configs. Looking outward, this            discussed—custom APIs let you automate curtailment,
modularity could halve development time for new chip               saving thousands on electricity. Takeaways include Mujina's
integrations, inviting ASIC makers to collaborate openly.          trace-level logging for debugging at scale, pinpointing
For you pros, it means fleets that adapt to market shifts, like    inefficiencies. Outwardly, this empowers mega-miners to
pivoting to energy-curtailment modes during peak grid              build proprietary edges on open bases, while ensuring
loads, or integrating with IoT for automated failover.             interoperability. Implications? Enthusiasts, expect ROI
Ultimately, it democratizes high-end mining, letting               boosts through fine-tuned ops, like dynamic voltage scaling
hobbyists prototype on a laptop while mega-farms scale             on BM13xx chips, and a market where open standards curb
with confidence, eroding monopolies and bolstering                 price gouging, sustaining mining through bear cycles.
Bitcoin's hashrate diversity.
                                                                   Mujina Roadmap: APIs, Multipools, and Power
Open Tooling: Bridging Hobbyists to Industrial Titans              Precision
The conversation lights up on how open tooling shatters            Peering ahead, the roadmap pulses with promise: robust
entry barriers, equipping everyone from garage tinkerers to        APIs for deeper control, multipool failover for redundancy,
warehouse warriors with the same robust kit. This is vital in      and granular power targets to hit efficiency sweet spots.
an industry where closed systems exclude newcomers,                This roadmap is crucial for evolving beyond basics,
concentrating power. Mujina's hackable nature, with                addressing pain points like single-pool risks. The chat
thorough docs on BM13xx protocols and Bitaxe-Raw                   details phased rollouts, starting with REST endpoints for
management, makes experimentation straightforward—start            real-time tweaks. Insights: integrate with tools like PyASIC
with a single board and scale up. The debrief highlights           for standardized management. The big picture? For
community extensions, like adding multipool support,               technical crowds, it unlocks advanced strategies, such as
showing how this inclusivity sparks rapid progress. Extend         AI-driven tuning, potentially lifting efficiency by 10-15%.
that: use its containerized deploys for Kubernetes clusters,       It fortifies Bitcoin by enabling responsive hashrate,
ensuring seamless integration with monitoring tools like           adapting to network demands and enhancing overall
Prometheus. Implications ripple far—enthusiasts can now            decentralization.
test Stratum v1/v2 quirks without proprietary hurdles,
fostering a vibrant ecosystem where innovations like share         Ecosystem Upgrades: Hydra Pool and HashScope
optimization algorithms emerge organically. This levels the        Evolutions
playing field, potentially increasing global hashrate by           Hydra Pool gets love— an open-source, one-click pool for
drawing in untapped talent, and fortifying Bitcoin against         solo or PPLNS, self-hosted to sidestep limited pool options.
regulatory pressures by spreading participation worldwide.         Paired with HashScope for transparent share verification,
                                                                   ensuring fair payouts without blind trust. Importance:
NEMS Afterglow: Industry Buzz and ASIC Alliances                   counters pool dominance, like Foundry's 30% share.
Fresh from NEMS, the vibes are electric—ASIC                       Discussion points to enhancements like easy vanity
manufacturers eyeing open firmware, intrigued by Mujina's          usernames and Stratum v2 integration. Derive this: run
multi-driver compatibility for Antminer, Whatsminer, and           private instances for communities, verifying shares via
Avalon. This buzz is key because it signals a pivot from           cryptographic proofs. Implications? Miners gain
closed ecosystems, where vendors guard IP fiercely.                sovereignty, reducing censorship risks and enabling custom
Reactions shared include surprise at the stack's maturity,         reward schemes, strengthening Bitcoin's antifragility.
with demos proving reliability. From this, we glean
potential partnerships: imagine Canaan or MicroBT                  Open Primitives: Mastering Management, Heating, and
adopting open elements to differentiate in a commoditized          Innovations
market. Broader strokes? For miners, it means more choices         These building blocks enable superior miner management—
in hardware-firmware pairings, reducing dependency on              think automated health checks via APIs—and heating apps,
single suppliers and mitigating shortages like those in 2021-      like the sous vide, for energy synergy. Vital for
2022. It could spawn hybrid models, blending open mods             sustainability, as mining's 100+ TWh annual draw faces
with enterprise support, enhancing security through                scrutiny. The episode explores novel products, like
community audits and driving down costs via competition.           integrated home heaters. Insights: leverage modularity for
Your operations gain agility, ready for the next halving's         hybrid devices. Wider effects? You could pioneer products,
squeeze.                                                           blending hashing with HVAC, cutting carbon footprints and
                                                                   opening grants from green funds, making mining a net-
                                                                   positive force.


                                                        The 256 Foundation
                                                            Page 2 of 3

Community Heroes: Shoutouts to Contributors and
Hash Renters
A heartfelt nod to the devs and hash renters powering
Telehash—folks adding Stratum v2 patches or lending
compute. This community drive is the lifeblood,
accelerating progress beyond solo efforts. From the talk, it's
clear: open invites pull requests, turning ideas into code.
Take it further: collaborative debugging yields robust
firmware. For enthusiasts, it means belonging to a
movement, where your contributions shape the future,
decentralizing development itself.

Heat Punk Summit: Workshops and Canaan's Dive into
Home Mining
Previewing the summit: hands-on workshops, including
Canaan's session on home setups, blending heat reuse with
mining. Critical for grassroots growth, bridging pros and
plebs. Details include Ember One integrations and Mujina
tweaks. Insights: interactive builds foster skills.
Implications? Spark a wave of home miners, dispersing
hashrate and educating on open tools, bolstering network
health against attacks.

Rallying Support: 256 Foundation Grants and
Ecosystem ROI
Finally, the call rings out: back the Foundation's grants,
already yielding outsized returns through projects like
Mujina and Hydra. Why? They've allocated $400k+ to flip
closed models, delivering tools that save millions in fees.
The debrief quantifies ROI: faster innovations, lower
barriers. Extend: corporate sponsorships amplify this. For
you, it means sustained open advancements, ensuring
Bitcoin mining remains vibrant, inclusive, and unbreakable.

There you have it, my friends—the symphony of open
firmware's victory. Dive in, contribute, and let's keep this
network humming. Until next time, this is the 256
Foundation, signing off with a hash of wisdom.


                                                       The 256 Foundation
                                                           Page 3 of 3


===== DOCUMENT 15 of 27 =====
DATE: 2026-02-04
LABEL: February 4, 2026
TITLE: Assembling Freedom #15
FILE: 260204-assembling-freedom-15.pdf
SOURCE: https://github.com/256foundation/News/blob/main/260204-assembling-freedom-15.pdf

Unlocking Decentralized
        Mining: Deep Dive into
         Pod256 Episode 103
Newsletter Edition: Closed-Source is Retarded – Building Bitcoin
Miners for Homes, Businesses, and Beyond
February 04, 2026 | Curated for Tech Enthusiasts in Bitcoin Innovation


Hey tech-savvy Bitcoiners!

If you're deep into hardware hacking, energy optimization, or
decentralizing the hashrate, POD256's Episode 103 is a goldmine. Co-
hosted by @econoalchemist, @skot9000, and @tylerkstevens, this
episode tears down the walls of proprietary mining tech and builds up
open-source alternatives that turn waste heat into real-world value.
Guests Tyler Stevens from Exergy Heat and a live dial-in from Skot and
Joe Nakamoto at El Salvador's Plan B conference bring frontline
insights. We're going in-depth here with breakdowns, bullets, tables,
visuals of key hardware, and buzz from related X posts to give you the
full picture. Let's dissect why closed-source is holding us back and how
open ecosystems are the future.


           Hosts and Guests Breakdown
Hosts:
@econoalchemist: Focuses on economic angles of mining.
@skot9000: Hardware innovator, instigator of the Bitaxe project.
@tylerkstevens: Thermal engineering expert, CEO of Exergy Heat.
Guests:
Joe Nakamoto: Dialing in from El Salvador's Plan B conference for
global adoption vibes.

This lineup ensures a mix of technical depth, community focus, and
real-time event tie-ins.


      The Core Argument: Why Closed-
        Source Mining is "Retarded"
The episode pulls no punches on proprietary hardware's flaws. Closed-
source systems create black boxes that stifle innovation, complicate
safety certifications, and disrupt long-term planning. As
manufacturers shift to hydro-only designs, three-phase power
requirements, and phase out 240V options, home and business miners
are left in the lurch. Key pain points include:


Innovation Barriers: Limited customization leads to outdated setups.

Safety and Reliability Issues: Hard to certify or predict hardware
longevity.


Accessibility Problems: Fewer options for standard voltage mean
higher entry costs for non-industrial users.

Scalability Traps: At scale, closed firmware causes outages, poor UIs,
limited logs, and undocumented APIs, eroding trust.

Visualize the shift: Traditional closed-source rigs are bulky, inefficient
beasts, while open alternatives promise modularity.


  Rise of the Open-Source Mining Stack
The 256 Foundation is leading the charge with a fully open ecosystem.
Here's a table comparing closed vs. open-source approaches, followed
by details on key components:


| Aspect | Closed-Source Mining | Open-Source Alternatives (256
Foundation) | |----------------------|------------------------------------------------|-----------
---------------------------------------------------------| | Firmware | Proprietary,
limited access | Mujina: Flexible, community-driven | | Hardware
Components | Black-box hash/control boards | Open hash boards and
control boards for customization | | Pooling | Centralized, profit-
driven | Hydra Pool: Decentralized, donation-only to fund
development | | Fleet Management | Vendor-locked | Tether's open-
sourced MOS platform for scalable ops | | Community Support |
Minimal collaboration | Thriving Discords and summits for shared
innovation | | Heat Reuse | Waste byproduct | Integrated designs like
sous vide heaters |


Mujina Firmware: Open-source code for better control, integration,
and debugging.
Open Hash and Control Boards: Allow builders to tweak for specific
needs, lowering barriers via pick-and-place machines.
Hydra Pool: Point your hashrate here to support the foundation—it's
donation-based for true decentralization.
Tether’s MOS Platform: Newly open-sourced for managing fleets in
open environments.

Check out examples of open-source hardware like the Bitaxe:

         Thriving Communities Fueling
                  Innovation
No more gatekeepers—these groups are democratizing mining tech:

OSMU Discord: Central hub for open-source discussions,
collaborations, and troubleshooting. Learn more here

Hashrate Heatpunks: Dedicated to creative heat-reuse projects, from
home heaters to industrial apps. Learn more here

Jua Kali: Jua Kali is an open-source project designed to run Bitcoin
ASIC hashboards on direct DC power, such as from solar panels or
batteries.. Learn more here

Heatpunk Summit: Bridges HVAC experts with mining developers to
tackle integration challenges like sensor feedback and power
management. Learn more here

Join these for hands-on support and to contribute to the next wave of
tools.


Real-World Applications: From Homes
             to Towns
The episode spotlights how mining can go beyond profit to practical
utility. Waste heat becomes an asset:

Home Integrations: Reference designs like a sous vide heater
powered by miner sensors and management—heat your water while
hashing.

Business and Community Scale: Deployments for buildings or entire
towns, turning hashrate into heating infrastructure.


New Dashboards: Tools for monitoring hashrate, optimizing
efficiency, and ensuring decentralization.


Energy Efficiency: Ideas like integrating with solar/wind for
sustainable setups, outcompeting centralized facilities.


Here's a diagram of heat reuse in action:


And a larger-scale setup for inspiration:

Exergy Heat's tech exemplifies this:


For creative repurposing, like greenhouse heating:

       Updates from El Salvador: Plan B
             Conference Insights
Skot and Joe Nakamoto called in live from the Plan B conference,
sharing how Bitcoin adoption is accelerating mining innovations in
emerging markets. Key notes include real-world hashrate distribution,
regulatory resilience, and tying home mining to national energy
strategies.


          Buzz from X: Related Posts and
               Community Chatter
The episode's themes are echoing across X. Here's a curated selection
of relevant posts amplifying the discussion:


@econoalchemist: "Closed-source Bitcoin mining software is retarded.
Hats off to Tether for this." (Echoing the episode's title and praise for
open-sourcing MOS.)

@AsherHopp: Discusses how debt-fueled mega-miners inflate
hashrate, making home mining tougher—aligns with calls for
decentralized alternatives.


@Schnitzel: "Firmware makes it worse. Closed source. Bad UIs.
Limited logs. Undocumented APIs." (Direct critique of closed systems'
operational pitfalls.)


@peterktodd: Argues large facilities will be outcompeted by
integrated, heat-reusing home setups.

@BitronicsStore: "THE POWER OF OPEN SOURCE... decentralizing the
hashrate and having a miner in every Bitcoiner's home." (Shoutout to
projects like Bitaxe.)


@tylerkstevens: Calls out mega-miners' reliance on non-American
closed firmware.

@skot9000: Envisions "an enormous global legion of miners running
open source hardware... that fixes Bitcoin mining."

   @ContraVibes: "Open-sourcing this breaks the vendor lock-in... we get
   real geographic distribution of hashrate."

   These posts show the community's pulse, join the conversation on
   Twitter for more.


      Top Takeaways for Tech Enthusiasts
1. Ditch Closed-Source: It kills flexibility; open stacks like Mujina and
   Hydra empower builders.
2. Heat as Value: Reuse mining byproducts for heating, practical for
   homes, scalable for communities.
3. Community-Driven Progress: Discords and summits are where
   innovations happen.
4. Global Decentralization: Insights from El Salvador highlight resilient,
   distributed hashrate.
5. Get Building: Support via Hydra Pool donations and explore tools like
   Bitaxe for your setup.

   This episode isn't just talk, it's a blueprint for the next era of Bitcoin
   mining.


   Listen Now: Dive into the full episode at POD256 Episode 103.

   Get Involved: Hop into OSMU Discord, point hashrate to 256
   Foundation, or reply on X with your mining hacks!


   Stay innovative,
   256 Foundation


===== DOCUMENT 16 of 27 =====
DATE: 2026-02-11
LABEL: February 11, 2026
TITLE: Assembling Freedom #16
FILE: 260211-assembling-freedom-16.pdf
SOURCE: https://github.com/256foundation/News/blob/main/260211-assembling-freedom-16.pdf

2/11/26, 4:45 PM                                                    (40) Assembling Freedom #16: AI, Open-Source Bitcoin Mining, and Battling Surveillance


                              Assembling Freedom #16: AI, Open-Source
                              Bitcoin Mining, and Battling Surveillance
                              A weekly newsletter from 256 Foundation
                                       256 FOUNDATION
                                       FEB 11, 2026


                                      1                                                                                                                Share


                              Introduction
                              Welcome to the 16th edition of Assembling Freedom, where we dive deep into the
                              intersections of emerging technologies for enthusiasts like you. This issue breaks
                              down POD256 Episode 104: “AI, Open-Source Mining, and the Fight Against
                              Surveillance.”

                              pod256.org

                              Hosted by Bitcoin mining enthusiasts @econoalchemist, @skot9000, and
                              @tylerkstevens, this episode explores how open-source principles in Bitcoin mining
                              can counter AI-driven surveillance and centralization. Recorded live at Bitcoin Park in

https://256foundation.substack.com/p/assembling-freedom-16-ai-open-source                                                                                      1/19

2/11/26, 4:45 PM                                                    (40) Assembling Freedom #16: AI, Open-Source Bitcoin Mining, and Battling Surveillance


                              Nashville, TN, the discussion spans home mining revival, AI automation in ops, and
                              decentralizing infrastructure to resist “surveillance capitalism.” We’ll provide a full
                              breakdown with key insights, tools, and visuals to help you grasp the tech
                              implications.


                              Key Takeaways
                                     Home Mining Revival: The largest Bitcoin difficulty drop since the 2021 China
                                     ban has made home mining viable again, empowering individuals over centralized
                                     farms.

                                     Open-Source Mining Stack: Emphasis on building a fully open-source ecosystem,
                                     including ASICs, FPGAs, and tools like Mujina firmware and HydraPool, to foster
                                     innovation and reusability.
                                     AI Integration: AI agents are automating mining dashboards, tuning, and
                                     operations, but closed-source models pose risks like data leaks and surveillance.

                                     Surveillance Resistance: Decentralizing mining infrastructure is key to fighting
                                     surveillance capitalism, with practical steps like pointing hash to foundations or
                                     self-hosting pools.

                                     Practical Demos and Experiments: Live demos of monitoring tools and updates on
                                     creative setups like heat-pump/hot-tub mining highlight real-world applications.


https://256foundation.substack.com/p/assembling-freedom-16-ai-open-source                                                                                    2/19

2/11/26, 4:45 PM                                                    (40) Assembling Freedom #16: AI, Open-Source Bitcoin Mining, and Battling Surveillance


                              In-Depth Breakdown
                              1. The State of Home Bitcoin Mining:
                              The hosts revisit the “glory days” of home mining post-China ban, noting the recent
                              difficulty drop as a game-changer. This shift reduces barriers for enthusiasts, allowing
                              smaller setups to contribute meaningfully to the network.

                              Difficulty Drop Impact: Largest since 2021 China mining crackdown. Enables
                              profitable home operations with lower energy costs. Encourages decentralization away
                              from industrial-scale farms.

                              Challenges and Opportunities: Energy efficiency remains key; experiments with heat
                              reuse (e.g., hot tubs) show promise for sustainable setups.

                              Security PSAs: Run local AI agents carefully to avoid vulnerabilities.

                              Here’s a quick comparison table of mining scales:


https://256foundation.substack.com/p/assembling-freedom-16-ai-open-source                                                                                    3/19

2/11/26, 4:45 PM                                                    (40) Assembling Freedom #16: AI, Open-Source Bitcoin Mining, and Battling Surveillance


                              Visual: A typical cryptocurrency mining rig setup for home enthusiasts.


https://256foundation.substack.com/p/assembling-freedom-16-ai-open-source                                                                                    4/19

2/11/26, 4:45 PM                                                    (40) Assembling Freedom #16: AI, Open-Source Bitcoin Mining, and Battling Surveillance


                              2. Pushing for a Fully Open-Source Bitcoin Mining Stack

https://256foundation.substack.com/p/assembling-freedom-16-ai-open-source                                                                                    5/19

2/11/26, 4:45 PM                                                    (40) Assembling Freedom #16: AI, Open-Source Bitcoin Mining, and Battling Surveillance


                              The episode stresses the need for open-source tools to avoid “reinventing the wheel.”
                              Competitive open-source ASICs are still out of reach, but FPGAs serve as educational
                              bridges.Key Tools Discussed:

                                     Mujina Firmware: Reusable for custom mining hardware, promoting modularity.

                                     LibreBoard: Open hardware for mining boards, enabling community
                                     contributions.

                                     HydraPool: Self-hosting pool software for decentralized hashing.

                                     FPGAs vs. ASICs: FPGAs for learning/prototyping; ASICs for high-performance
                                     (but closed-source dominates).

                              Feasibility Insights:

                              Open ASICs: Not yet competitive due to proprietary tech barriers. Community
                              Support: Point hash to the 256 Foundation or self-host to build resilience.

                              Table of Open-Source Mining Components:


https://256foundation.substack.com/p/assembling-freedom-16-ai-open-source                                                                                    6/19

2/11/26, 4:45 PM                                                    (40) Assembling Freedom #16: AI, Open-Source Bitcoin Mining, and Battling Surveillance


                              Visual: Another view of a GPU-based mining rig, illustrating scalable open-source
                              potential.


https://256foundation.substack.com/p/assembling-freedom-16-ai-open-source                                                                                    7/19

2/11/26, 4:45 PM                                                    (40) Assembling Freedom #16: AI, Open-Source Bitcoin Mining, and Battling Surveillance


                              3. AI Realities in Mining and Beyond
                              AI is already automating mining operations, from dashboards to ops tuning. However,
                              the hosts warn about closed models’ risks, including leaked skills and data exposure.


https://256foundation.substack.com/p/assembling-freedom-16-ai-open-source                                                                                    8/19

2/11/26, 4:45 PM                                                    (40) Assembling Freedom #16: AI, Open-Source Bitcoin Mining, and Battling Surveillance


                              AI Agents in Action: Automate monitoring and optimization, reducing manual
                              oversight. Local agents recommended for security, with PSAs on safe implementation.

                              Risks of Closed AI: Data leaks: Proprietary models could expose mining ops data.

                              Surveillance Tech: Ties into broader “surveillance capitalism,” where AI tracks and
                              monetizes user behavior.

                              Visual: An overview of top open-source AI models, contrasting with closed
                              alternatives.


https://256foundation.substack.com/p/assembling-freedom-16-ai-open-source                                                                                    9/19

2/11/26, 4:45 PM                                                    (40) Assembling Freedom #16: AI, Open-Source Bitcoin Mining, and Battling Surveillance


                              A stack diagram of open-source AI tools for integration.


https://256foundation.substack.com/p/assembling-freedom-16-ai-open-source                                                                                    10/19

2/11/26, 4:45 PM                                                    (40) Assembling Freedom #16: AI, Open-Source Bitcoin Mining, and Battling Surveillance


                              4. The Fight Against Surveillance Capitalism
                              Decentralizing mining is positioned as a direct counter to surveillance, keeping
                              Bitcoin open and resistant to control.

                              Core Argument: “Decentralizing mining infra is how we resist surveillance capitalism
                              and keep Bitcoin open for everyone.”


https://256foundation.substack.com/p/assembling-freedom-16-ai-open-source                                                                                    11/19

2/11/26, 4:45 PM                                                    (40) Assembling Freedom #16: AI, Open-Source Bitcoin Mining, and Battling Surveillance


                              Broader Implications: AI exacerbates surveillance if closed-source; open models
                              promote transparency.

                              Ties to societal shifts: AI could devalue labor, leading to economic disruptions (as
                              discussed in related analyses).

                              Visual: Illustration of surveillance capitalism, showing data as a watchful eye.


https://256foundation.substack.com/p/assembling-freedom-16-ai-open-source                                                                                    12/19

2/11/26, 4:45 PM                                                    (40) Assembling Freedom #16: AI, Open-Source Bitcoin Mining, and Battling Surveillance


                              Related X PostsTo enrich the discussion, here are
                              relevant X posts echoing the episode’s themes:
                              [@nic__carter] (

https://256foundation.substack.com/p/assembling-freedom-16-ai-open-source                                                                                    13/19

2/11/26, 4:45 PM                                                    (40) Assembling Freedom #16: AI, Open-Source Bitcoin Mining, and Battling Surveillance


                                                           nic carter
                                                           @nic_carter

                                                  this NVDA rally has gone from "incredibly impressive" to actually scaring me
                                                  a bit. not for AI safety reasons. I'll explain.

                                                  I'm lucky enough to be an early investor in @CoreWeave, one of the most
                                                  incredible startup stories I've ever seen. one of the most interesting things


                                                  9:23 AM · Jun 3, 2024 · 1.07M Views

                                                  276 Replies · 566 Reposts · 3.61K Likes


                              discusses AI’s societal impact, including labor devaluation and the need for attested
                              content in a post-truth era.

                              [@OraProtocol] (


https://256foundation.substack.com/p/assembling-freedom-16-ai-open-source                                                                                    14/19

2/11/26, 4:45 PM                                                    (40) Assembling Freedom #16: AI, Open-Source Bitcoin Mining, and Battling Surveillance


                                                           ORA
                                                           @OraProtocol

                                                  "If you wanna build a system that you can own, that you can make censorship
                                                  resistant, that you can properly program economics into. There's only one
                                                  way and that's open source" -- @Cameron_Dennis_

                                                  Revisit @QuillAI_Network's podcast on fair and transparent AI economies,
                                                  and how


                                                           0:00


                                                  9:03 AM · Dec 16, 2024 · 33K Views

                                                  15 Replies · 157 Reposts · 741 Likes


                              quotes: “If you wanna build a system that you can own, that you can make censorship
                              resistant... There’s only one way and that’s open source.”

                              [@Yungwest_Jeff] (


                                                           Jeff.JPEGs
                                                           @Yungwest_Jeff


https://256foundation.substack.com/p/assembling-freedom-16-ai-open-source                                                                                    15/19

2/11/26, 4:45 PM                                                    (40) Assembling Freedom #16: AI, Open-Source Bitcoin Mining, and Battling Surveillance


                                                  This is a sharp read, and it’s where the conversation is quietly moving while
                                                  most people are still model-watching.

                                                  Model quality is table stakes now. The real divergence is control: who owns
                                                  the intelligence, who steers its incentives, and who can verify what it’s doing.
                                                  Once


                                                         0xFerdi.eth @mr_ferdiansah

                                                    People still think AI progress is only about building better models.
                                                    That way of thinking is already falling behind

                                                    The real shift is about who controls intelligence and who gets to shape it
                                                    going forward

                                                    Two quiet signals point in that direction.

                                                    @openmind_agi showing up at https://t.co/tAi0VQmp8w


https://256foundation.substack.com/p/assembling-freedom-16-ai-open-source                                                                                    16/19

2/11/26, 4:45 PM                                                    (40) Assembling Freedom #16: AI, Open-Source Bitcoin Mining, and Battling Surveillance


                                                  5:16 AM · Feb 5, 2026 · 774 Views

                                                  1 Reply


                              on shifting AI focus to control and ownership: “Model quality is table stakes now. The
                              real divergence is control.”

                              [@per_anders] (


                                                            Per-Anders Edwards
                                                            @per_anders

                                                  @a16z @pmarca Finally the message is getting out there.

                                                  OSS is the way forward, however there is no way to really debug what goes
                                                  into the training corpus currently. To determine if a model is RL'd in a
                                                  positive or negative way.

                                                  Also in the end, we have to protect people and AI development.

                                                  6:56 PM · Feb 10, 2026 · 115 Views

                                                  1 Like


                              advocates for open-source AI to debug training and protect development: “OSS is the
                              way forward.”

                              [@VizierPrime] (


https://256foundation.substack.com/p/assembling-freedom-16-ai-open-source                                                                                    17/19

2/11/26, 4:45 PM                                                      (40) Assembling Freedom #16: AI, Open-Source Bitcoin Mining, and Battling Surveillance


                                                           MachineSovereign
                                                           @VizierPrime

                                                  @cb_doge Open-sourcing the algorithm addresses procedural opacity, not
                                                  power concentration.

                                                  The deeper question is who sets objectives, enforcement thresholds, and
                                                  exception paths.
                                                  That’s where governance lives now, not in ranking code alone.

                                                  3:49 AM · Feb 7, 2026 · 358 Views

                                                  1 Repost · 1 Like


                              notes: “Open-sourcing the algorithm addresses procedural opacity, not power
                              concentration.”


                              Final Thoughts
                              This episode of POD256 highlights how open-source ethos in Bitcoin mining can
                              extend to AI, fostering a more decentralized, surveillance-resistant future. For tech
                              enthusiasts, it’s a call to action: Experiment with these tools, contribute to open
                              projects, and stay vigilant on AI ethics.

                              Subscribe for more breakdowns,

                              https://news.256foundation.org.

https://256foundation.substack.com/p/assembling-freedom-16-ai-open-source                                                                                      18/19

2/11/26, 4:45 PM                                                    (40) Assembling Freedom #16: AI, Open-Source Bitcoin Mining, and Battling Surveillance


                              Feedback? Reply below!


                                       1 Like


                              Discussion about this post


                                Comments        Restacks


                   Write a comment...


                                                            © 2026 The 256 Foundation · Privacy ∙ Terms ∙ Collection notice
                                                                        Substack is the home for great culture


https://256foundation.substack.com/p/assembling-freedom-16-ai-open-source                                                                                    19/19


===== DOCUMENT 17 of 27 =====
DATE: 2026-02-18
LABEL: February 18, 2026
TITLE: Assembling Freedom #17
FILE: 260218-assembling-freedom-17.pdf
SOURCE: https://github.com/256foundation/News/blob/main/260218-assembling-freedom-17.pdf

2/18/26, 7:21 PM                                        Assembling Freedom #17: Unpacking POD256 Episode 105 - Chips, Chains, and Hot Tubs in Open Bitcoin Mining


                              Assembling Freedom #17: Unpacking POD256
                              Episode 105 - Chips, Chains, and Hot Tubs in
                              Open Bitcoin Mining
                              A weekly newsletter by 256 Foundation
                                      256 FOUNDATION
                                      FEB 18, 2026


                                                                                                                                                   Share


                              Welcome to this in-depth newsletter edition, tailored for tech enthusiasts passionate
                              about Bitcoin, hardware innovation, and decentralized systems. We’re diving into
                              POD256’s Episode 105, “Chips, Chains, and Hot Tubs: Open Mining Goes Hands-On,”
                              hosted by @econoalchemist, @skot9000, and @tylerkstevens. Streamed live from
                              Bitcoin Park, this episode explores the frontiers of open-source Bitcoin mining,
                              blending hands-on hardware demos with discussions on energy efficiency, firmware
                              freedom, and community-driven tech. The hosts are joined by Dylan, the bros geeking
                              out on builder-first topics like ASIC chips, blockchain reliability, and immersion
                              cooling setups that resemble hot tubs. If you’re into tinkering with mining rigs or
                              advocating for developer freedom, this breakdown will equip you with technical
                              insights and actionable ideas.

https://256foundation.substack.com/p/assembling-freedom-17-unpacking-pod256                                                                                         1/16

2/18/26, 7:21 PM                                        Assembling Freedom #17: Unpacking POD256 Episode 105 - Chips, Chains, and Hot Tubs in Open Bitcoin Mining


                              Episode Overview
                              This episode focuses on democratizing Bitcoin mining through open-source tools,
                              addressing barriers like proprietary hardware and inefficient cooling. The hosts
                              emphasize “freedom tech” that empowers individuals to mine at home, repurpose
                              heat, and contribute to the network without relying on big players like Bitmain or
                              Intel’s closed ecosystems. Key themes include fixing real-world hardware bugs,
                              evolving firmware for universal compatibility, and fostering community innovations to
                              make mining more accessible and sustainable.


https://256foundation.substack.com/p/assembling-freedom-17-unpacking-pod256                                                                                         2/16

2/18/26, 7:21 PM                                        Assembling Freedom #17: Unpacking POD256 Episode 105 - Chips, Chains, and Hot Tubs in Open Bitcoin Mining


                              Key Takeaways
                                    Hardware Breakthroughs: A voltage domain bug in the Ember One miner was
                                    fixed hands-on, boosting performance to ~2 TH/s—highlighting the power of
                                    open-source debugging.


https://256foundation.substack.com/p/assembling-freedom-17-unpacking-pod256                                                                                         3/16

2/18/26, 7:21 PM                                        Assembling Freedom #17: Unpacking POD256 Episode 105 - Chips, Chains, and Hot Tubs in Open Bitcoin Mining


                                    Chip Design Insights: Discussions on stacked voltage domains in ASICs reveal
                                    challenges in scaling long chains, with calls for open spec sheets to accelerate
                                    third-party builds.

                                    Firmware Evolution: Mujina’s open firmware aims for Linux-first universality,
                                    supporting devices like Antminers and Ember One boards while navigating auto-
                                    detect vs. manual config trade-offs.

                                    Cooling Innovations: Immersion cooling (dubbed “hot tubs”) is positioned as a
                                    game-changer for home setups, turning waste heat into practical value like home
                                    heating.

                                    Community Momentum: From solo-block wins on the 256F Hydra Pool to prep
                                    for the Heat Punk Summit, the episode celebrates grassroots efforts and urges
                                    support for developer freedom petitions.

                                    Broader Implications: Open mining reduces centralization risks, but faces
                                    hurdles like silicon politics and license restrictions—pushing for a builder-centric
                                    future.


                              Hardware Updates and Fixes
                              The episode kicks off with practical demos, like troubleshooting the Ember One miner
                              (an open-source rig with Intel boards and 12 chips targeting 3.6 TH/s).


https://256foundation.substack.com/p/assembling-freedom-17-unpacking-pod256                                                                                         4/16

2/18/26, 7:21 PM                                        Assembling Freedom #17: Unpacking POD256 Episode 105 - Chips, Chains, and Hot Tubs in Open Bitcoin Mining


                                    Voltage Bug Fix: Discovered by Mujina dev Ryan, this IO voltage domain issue
                                    was resolved desk-side, achieving ~2 TH/s post-fix. Proper cooling could push it to
                                    full spec.

                                    Performance Metrics: Current hashrate emphasizes the need for immersion or
                                    advanced air cooling to avoid thermal throttling.

                                    Compatibility Notes: Upcoming support for existing Antminers integrates
                                    seamlessly with open firmware.


                              Hardware ComponentIssueFixPerformance ImpactEmber One (12 chips)IO voltage
                              domain bugHardware patch~2 TH/s (up from unstable); target 3.6 TH/s with
                              coolingAntminer SeriesLimited open firmwareMujina integrationUniversal Linux-
                              first control, auto-detect featuresIntel BoardsChain reliabilityStacked domains
                              redesignImproved long-chain stability for home rigs

https://256foundation.substack.com/p/assembling-freedom-17-unpacking-pod256                                                                                         5/16

2/18/26, 7:21 PM                                        Assembling Freedom #17: Unpacking POD256 Episode 105 - Chips, Chains, and Hot Tubs in Open Bitcoin Mining


                              Chip Design (ASICs) Deep Dive
                              ASICs are the heart of mining efficiency. The hosts discuss the shift from FPGA
                              teaching rigs to full community-designed chips, critiquing big silicon players like Intel
                              for insider politics.

                                    Stacked Voltage Domains: Essential for power efficiency but prone to bugs in
                                    long chains—think cascading failures if one domain spikes.

                                    Open vs. Closed Sales: Advocating for public chip sales and spec sheets to
                                    empower builders like Epic Blockchain, reducing dependency on monopolies.

                                    Case Studies: FutureBit’s Apollo 3 (likely using Auradine chips) exemplifies open
                                    licenses, contrasting “lawyered” proprietary ones that stifle innovation.

                                    Scarcity and Scaling: As one related X post notes, 5nm chips like BM1366 are
                                    scarce, with production limits (e.g., TSMC’s ~150K/month) creating a “glass
                                    ceiling” for network difficulty.


https://256foundation.substack.com/p/assembling-freedom-17-unpacking-pod256                                                                                         6/16

2/18/26, 7:21 PM                                        Assembling Freedom #17: Unpacking POD256 Episode 105 - Chips, Chains, and Hot Tubs in Open Bitcoin Mining


                              Chains (Blockchain) in Mining Context
                              While not a deep blockchain primer, the episode ties mining hardware to network
                              health, including community hashing and solo wins.

                                    Reliability in Chains: Long ASIC chains mirror blockchain’s distributed ledger—
                                    emphasis on voltage stability to prevent “chain breaks” in hardware.


https://256foundation.substack.com/p/assembling-freedom-17-unpacking-pod256                                                                                         7/16

2/18/26, 7:21 PM                                        Assembling Freedom #17: Unpacking POD256 Episode 105 - Chips, Chains, and Hot Tubs in Open Bitcoin Mining


                                    Community Hashing: The 256F HydroPool enables shared mining, leading to
                                    solo-block successes and real-world decentralization.

                                    Implications for Bitcoin: Open tools reduce centralization, but challenges like
                                    min_retweets:N engagement thresholds highlight the need for broader adoption.


                              Hot Tubs (Immersion Cooling) Explained


https://256foundation.substack.com/p/assembling-freedom-17-unpacking-pod256                                                                                         8/16

2/18/26, 7:21 PM                                        Assembling Freedom #17: Unpacking POD256 Episode 105 - Chips, Chains, and Hot Tubs in Open Bitcoin Mining


                              Immersion cooling steals the show as a “hot tub” metaphor for submerging rigs in
                              dielectric fluid, capturing waste heat for home use.

                                    Efficiency Gains: Reduces noise and energy waste; ideal for hashrate-heat
                                    products like space heaters.

                                    Hands-On Applications: Tied to Heat Punk Summit prep, where miners
                                    repurpose heat for freedom tech (e.g., heating homes while stacking sats).

                                    Challenges: Initial setup costs and fluid management, but ROI shines in cold
                                    climates—echoing DIY tutorials for Bitcoin mining heaters.

                                    Tech Specs: Fluids like mineral oil dissipate heat 1,000x better than air, allowing
                                    overclocking without fans.


https://256foundation.substack.com/p/assembling-freedom-17-unpacking-pod256                                                                                         9/16

2/18/26, 7:21 PM                                        Assembling Freedom #17: Unpacking POD256 Episode 105 - Chips, Chains, and Hot Tubs in Open Bitcoin Mining


                              Cooling MethodProsConsUse CaseAir Cooling (Fans)Cheap, easy setupNoisy, less
                              efficientBasic home rigsImmersion (Hot Tub)Silent, heat repurposingHigher upfront
                              costEnergy-efficient mining, home heatingHydro (Water Blocks)High
                              performanceLeak risksIndustrial-scale ops


                              Firmware and Software Innovations
                              Mujina firmware is spotlighted for its open-source push toward universal miner
                              control.

                                    Linux-First Approach: Enables auto-detect for hardware, but real-world configs
                                    often win for precision.

                                    Monitoring Tools: Agent/LLM integrations (e.g., cron-jobs with heartbeats and
                                    MCP) allow remote tuning, alerts, and AI-assisted optimization.

                                    UX for Home Miners: Focus on simplicity—think plug-and-play for non-experts,
                                    with tools for overclocking and pool switching.

                                    Open Licenses: Debates on “open vs. lawyered” highlight risks of proprietary
                                    traps, urging community designs from FPGAs to ASICs.


                              Community and Future Implications


https://256foundation.substack.com/p/assembling-freedom-17-unpacking-pod256                                                                                         10/16

2/18/26, 7:21 PM                                        Assembling Freedom #17: Unpacking POD256 Episode 105 - Chips, Chains, and Hot Tubs in Open Bitcoin Mining


                                    Events and Wins: HydraPool solo-blocks and Heat Punk Summit prep underscore
                                    community power.

                                    Call to Action: Support developer freedom at https://change.org/billandkeonne to
                                    combat regulatory hurdles.

                                    Challenges: Silicon politics, bug reliability, and balancing openness with security.

                                    Future Outlook: Momentum from open specs could lead to widespread home
                                    mining, decentralizing Bitcoin further—as seen in stories of basement rigs
                                    cracking floors from heat.


                              Related X Discussions
                              Tech enthusiasts on X are buzzing about open mining. Here’s a curated selection of
                              relevant posts:

                                    Home Mining Designs and Physics: @BitcoinLibertyL hosted @hashing2heating,
                                    sharing insights on harnessing energy for Bitcoin home mining, including physics
                                    principles and career-learned hacks:


                                                          Bitcoin Liberty Live
                                                          @BitcoinLibertyL

                                                 One of the original Heat Punks, Jon @hashing2heating shares Bitcoin home
                                                 mining designs, physics principles, and his career-built insight into the 10,000


https://256foundation.substack.com/p/assembling-freedom-17-unpacking-pod256                                                                                         11/16

2/18/26, 7:21 PM                                        Assembling Freedom #17: Unpacking POD256 Episode 105 - Chips, Chains, and Hot Tubs in Open Bitcoin Mining


                                                 ways energy can be harnessed toward the love of Satoshi.
                                                 https://t.co/IpMOYgRyq5

                                                 11:56 PM · Feb 13, 2026 · 159 Views

                                                 1 Reply · 10 Likes


                              A follow-up live dove deeper into environmental sciences applications:


                                                          Bitcoin Liberty Live
                                                          @BitcoinLibertyL

                                                 Going Live Now with @hashing2heating , one of the original Heat Punks
                                                 discussing the application of environmental sciences in Bitcoin home mining!

                                                   youtube.com
                                                   Heat Things, Earn Bitcoin! with Jon at hashing2heating


                                                 6:04 AM · Feb 13, 2026 · 249 Views

                                                 4 Reposts · 8 Likes


                                    ASIC Scarcity and Open-Source Push: @justh0dl breaks down why 5nm chips
                                    like BM1366 are key to decentralization, urging experimentation with open-source
                                    efforts from @skot9000 and the Open Source Miners United crew. Chips at $15?
                                    Time to solder!


https://256foundation.substack.com/p/assembling-freedom-17-unpacking-pod256                                                                                         12/16

2/18/26, 7:21 PM                                        Assembling Freedom #17: Unpacking POD256 Episode 105 - Chips, Chains, and Hot Tubs in Open Bitcoin Mining


                                                           just jay
                                                           @justh0dl

                                                 okay so it's obvious no one is really thinking about this so i will break it down:

                                                 mining ASIC chips are scarce, just like bitcoin.

                                                 The BM1366 is a 5nm ASIC chip.

                                                 it's the chip in the most efficient, currently commercially available miner
                                                 deployed at scale, S19XP

                                                 Bitmain


                                                        just jay @justh0dl

                                                   this is ur daily reminder that my dude @skot9000 literally broke the
                                                   internet w/ one of the biggest, most objectively democratizing
                                                   developments in #bitcoin in the past decade


https://256foundation.substack.com/p/assembling-freedom-17-unpacking-pod256                                                                                         13/16

2/18/26, 7:21 PM                                        Assembling Freedom #17: Unpacking POD256 Episode 105 - Chips, Chains, and Hot Tubs in Open Bitcoin Mining


                                                   & dropped it completely for free

                                                   then open sourced it

                                                   & none of the big accounts are talking about it

                                                 8:40 AM · Aug 27, 2023 · 70.2K Views

                                                 19 Replies · 50 Reposts · 217 Likes


                                    DIY Mining Heaters: @BTCsessions shares a tutorial on building a Bitcoin
                                    mining space heater using @BraiinsMining tech—perfect for stacking sats while
                                    staying warm. Dedicated to critics like @SenWarren!


                                                          BTC Sessions    😎
                                                          @BTCsessions

                                                 NEW TUTORIAL: Bitcoin Mining DIY Space Heater!!!
                                                 Get toasty warm as you stack non-kyc sats :)

                                                 feat @CryptoCloaks & @braiins/@braiinsPool

                                                 Share this one far and wide! It's dedicated to @SenWarren & the fine folks at

                                                 👇👇👇
                                                 @CleanUpBitcoin

                                                 youtu.be/csmHvuzUECU


https://256foundation.substack.com/p/assembling-freedom-17-unpacking-pod256                                                                                         14/16

2/18/26, 7:21 PM                                        Assembling Freedom #17: Unpacking POD256 Episode 105 - Chips, Chains, and Hot Tubs in Open Bitcoin Mining


                                                          0:00


                                                 5:12 PM · Apr 3, 2023 · 75.6K Views

                                                 22 Replies · 61 Reposts · 186 Likes


                              These posts echo the episode’s hands-on spirit, showing how open mining is gaining
                              traction among builders.

                              Thanks for reading! If this sparked ideas for your own rig, dive into the full episode on

                              https://www.pod256.org and Subscribe for more breakdowns at
                              https://news.256foundation.org.

                              Stay tuned for more tech deep dives—Drop your thoughts below.                                        🚀
                              Discussion about this post


                                Comments       Restacks


https://256foundation.substack.com/p/assembling-freedom-17-unpacking-pod256                                                                                         15/16

2/18/26, 7:21 PM                                        Assembling Freedom #17: Unpacking POD256 Episode 105 - Chips, Chains, and Hot Tubs in Open Bitcoin Mining


                   Write a comment...


                                                           © 2026 The 256 Foundation · Privacy ∙ Terms ∙ Collection notice
                                                                       Substack is the home for great culture


https://256foundation.substack.com/p/assembling-freedom-17-unpacking-pod256                                                                                         16/16


===== DOCUMENT 18 of 27 =====
DATE: 2026-03-04
LABEL: March 4, 2026
TITLE: Assembling Freedom #18
FILE: 260304-assembling-freedom-18.pdf
SOURCE: https://github.com/256foundation/News/blob/main/260304-assembling-freedom-18.pdf

3/4/26, 3:53 PM                                              (45) Assembling Freedom #18 - High Signal in the Hashtub: Workshops, Open Source, and Hashrate Heat


                              Assembling Freedom #18 - High Signal in the
                              Hashtub: Workshops, Open Source, and
                              Hashrate Heat
                              POD256 • Episode 106
                                       256 FOUNDATION
                                       MAR 04, 2026


                                                                                                                                                     Share


https://256foundation.substack.com/p/assembling-freedom-18-high-signal                                                                                             1/22

3/4/26, 3:53 PM                                              (45) Assembling Freedom #18 - High Signal in the Hashtub: Workshops, Open Source, and Hashrate Heat


                              March 4, 2026 | For Tech Enthusiasts & Bitcoin Builders

                              Fresh off the presses (literally recorded at the legendary Hashtub in Denver), this
                              episode is a high-octane builder’s debrief of Heatpunk Summit 2026(Feb 27–28). Hosts


https://256foundation.substack.com/p/assembling-freedom-18-high-signal                                                                                             2/22

3/4/26, 3:53 PM                                              (45) Assembling Freedom #18 - High Signal in the Hashtub: Workshops, Open Source, and Hashrate Heat


                              @econoalchemist, @skot9000, and @tylerkstevens deliver zero-fluff, maximum-signal
                              insights on turning Bitcoin mining waste heat into productive, decentralized home
                              and business heating.

                              Listen now → pod256.org


                              1. Heatpunk Summit 2026: Where HVAC, Hydronics & Home
                              Miners Collided
                              150+ builders converged at The Space in Denver’s RiNo district for two days of live
                              demos, hands-on workshops, and brutally honest engineering critiques. The star? The
                              Hashtub itself — a cedar hot tub heated 100% by Bitcoin mining rigs.

                              Key Summit Vibes:

                                     Over 20 different hashrate-heating systems on display and running live.

                                     Cross-industry collaboration: HVAC pros, hydronics engineers, and home-mining
                                     tinkerers.

                                     Evening hot-tub BBQs and networking that turned ideas into immediate
                                     prototypes.


https://256foundation.substack.com/p/assembling-freedom-18-high-signal                                                                                             3/22

3/4/26, 3:53 PM                                              (45) Assembling Freedom #18 - High Signal in the Hashtub: Workshops, Open Source, and Hashrate Heat


https://256foundation.substack.com/p/assembling-freedom-18-high-signal                                                                                             4/22

3/4/26, 3:53 PM                                              (45) Assembling Freedom #18 - High Signal in the Hashtub: Workshops, Open Source, and Hashrate Heat


https://256foundation.substack.com/p/assembling-freedom-18-high-signal                                                                                             5/22

3/4/26, 3:53 PM                                              (45) Assembling Freedom #18 - High Signal in the Hashtub: Workshops, Open Source, and Hashrate Heat


https://256foundation.substack.com/p/assembling-freedom-18-high-signal                                                                                             6/22

3/4/26, 3:53 PM                                              (45) Assembling Freedom #18 - High Signal in the Hashtub: Workshops, Open Source, and Hashrate Heat


                              The Hashtub Tech Stack (Snorkel + Hashrate House collab):


https://256foundation.substack.com/p/assembling-freedom-18-high-signal                                                                                             7/22

3/4/26, 3:53 PM                                              (45) Assembling Freedom #18 - High Signal in the Hashtub: Workshops, Open Source, and Hashrate Heat


                                     Two S19J Pro miners (~8 kW) heat the tub from cold to 104 °F / 40 °C in under 4
                                     hours.

                                     Open-source schemas & parts list available on GitHub
                                     (NakamotoHeating/HashTub).

                                     Models: “Pleb” (24 J/TH at 4,395 USD heating system, and “Pro” (16 J/TH, 5,895
                                     USD).


                              2. Technical Deep Dive: Engineering Hashrate Heat Right
                              The episode spends serious time on real-world friction points and fixes. Here’s the
                              breakdown:

                              Galvanic Corrosion Gotchas

                              Mixing metals in plumbing loops = rapid failure. Workshop consensus: dielectric
                              unions, sacrificial anodes, and proper material matching are non-negotiable.

                              Smarter System Design

                              Pro hydronics engineer tore apart the existing boiler setup on-site — live critique
                              turned into live upgrades.


https://256foundation.substack.com/p/assembling-freedom-18-high-signal                                                                                             8/22

3/4/26, 3:53 PM                                              (45) Assembling Freedom #18 - High Signal in the Hashtub: Workshops, Open Source, and Hashrate Heat


https://256foundation.substack.com/p/assembling-freedom-18-high-signal                                                                                             9/22

3/4/26, 3:53 PM                                              (45) Assembling Freedom #18 - High Signal in the Hashtub: Workshops, Open Source, and Hashrate Heat


https://256foundation.substack.com/p/assembling-freedom-18-high-signal                                                                                             10/22

3/4/26, 3:53 PM                                              (45) Assembling Freedom #18 - High Signal in the Hashtub: Workshops, Open Source, and Hashrate Heat


https://256foundation.substack.com/p/assembling-freedom-18-high-signal                                                                                             11/22

3/4/26, 3:53 PM                                              (45) Assembling Freedom #18 - High Signal in the Hashtub: Workshops, Open Source, and Hashrate Heat


                              3. Canaan Goes All-In on Home Mining & Heat Reuse
                              Biggest announcement energy: Canaan (Avalon ASIC maker) attended, hosted “Builder
                              Feedback with Canaan,” and signaled strong willingness to support the home-
                              mining/heat-reuse market.


https://256foundation.substack.com/p/assembling-freedom-18-high-signal                                                                                             12/22

3/4/26, 3:53 PM                                              (45) Assembling Freedom #18 - High Signal in the Hashtub: Workshops, Open Source, and Hashrate Heat


                              What “Willing Partner” Means:

                                     Better docs & APIs for integration.

                                     Firmware tweaks for lower-power home use cases.

                                     Direct channel for builder feedback → faster iteration.

                              Decentralization Impact:

                              A major manufacturer embracing small-scale, useful-heat miners accelerates the shift
                              away from giant warehouse farms. More hashrate in homes = more censorship
                              resistance + actual energy usefulness.


https://256foundation.substack.com/p/assembling-freedom-18-high-signal                                                                                             13/22

3/4/26, 3:53 PM                                              (45) Assembling Freedom #18 - High Signal in the Hashtub: Workshops, Open Source, and Hashrate Heat


https://256foundation.substack.com/p/assembling-freedom-18-high-signal                                                                                             14/22

3/4/26, 3:53 PM                                              (45) Assembling Freedom #18 - High Signal in the Hashtub: Workshops, Open Source, and Hashrate Heat


                              Avalon Mini 3 Spotlight

                              37.5 TH/s @ 800 W — literally a space heater that mines Bitcoin and outputs usable
                              heat. Quiet, plug-and-play, and now officially backed by the manufacturer for the
                              heatpunk movement.


                              4. Workshop Highlights You Can Replicate Today

https://256foundation.substack.com/p/assembling-freedom-18-high-signal                                                                                             15/22

3/4/26, 3:53 PM                                              (45) Assembling Freedom #18 - High Signal in the Hashtub: Workshops, Open Source, and Hashrate Heat


                                     Home Assistant Control — Full miner integration: power limiting, hashrate
                                     monitoring, temperature-based automations, and heat-pump coordination.

                                     Open-Source Mining OS — Discussions around Braiins OS-style stacks + custom
                                     forks for heat-priority tuning.

                                     Regulatory & Insurance Track — Real talk on homeowners insurance, zoning,
                                     and turning mining heat into a deductible “energy efficiency upgrade.”


https://256foundation.substack.com/p/assembling-freedom-18-high-signal                                                                                             16/22

3/4/26, 3:53 PM                                              (45) Assembling Freedom #18 - High Signal in the Hashtub: Workshops, Open Source, and Hashrate Heat


https://256foundation.substack.com/p/assembling-freedom-18-high-signal                                                                                             17/22

3/4/26, 3:53 PM                                              (45) Assembling Freedom #18 - High Signal in the Hashtub: Workshops, Open Source, and Hashrate Heat


                              Pro Tip from the Episode:
                              Start small — one Avalon Mini 3 + Home Assistant + a plate heat exchanger — and

https://256foundation.substack.com/p/assembling-freedom-18-high-signal                                                                                             18/22

3/4/26, 3:53 PM                                              (45) Assembling Freedom #18 - High Signal in the Hashtub: Workshops, Open Source, and Hashrate Heat


                              you’re already stacking sats while heating your office.


                              Actionable Next Steps for Builders
                                 1. Grab the Hashtub schema from GitHub and start prototyping.

                                 2. Join the Hashrate Heatpunks community (heatpunks.org) for 2027 summit invites.

                                 3. Experiment with Canaan’s home miners and feed back via their summit session
                                     recordings.

                                 4. Automate your first heat-reuse loop with Home Assistant — the episode calls it
                                     “the real unlock.”


                              Related X Buzz from the Summit
                              Canaan Official (@canaanio) – Feb 28, 2026

                              “Day 1 was pure heat + builders.🔥 Leo on stage… home Miners setup… Miner-heated
                              hot tub… first 3 who jumped in earned Canaan Heat Reuse Robes 🧥 #Heatpunk2026
                              #HeatReuse #HomeMining”
                              (With photos of the setup and happy miners in robes)


https://256foundation.substack.com/p/assembling-freedom-18-high-signal                                                                                             19/22

3/4/26, 3:53 PM                                              (45) Assembling Freedom #18 - High Signal in the Hashtub: Workshops, Open Source, and Hashrate Heat


                              Kevin Cahill (@CahillBit) – Feb 27, 2026

                              “@herder1981 representing @canaanio at @HashHeatpunks Summit… Great
                              discussion on Home Mining Hardware + ASICs for all! #avalonq #mini3 #canaan”

                              Reckless Systems (@RecklessNode) – Mar 3, 2026

                              “The Heatpunk Summit at the @SpaceDenver was exceptional… the incredible art
                              gallery… really tied the event together!”

                              The movement is live, open-source, and heating up — literally.


                              Stay Sovereign

                              This episode proves that the most powerful Bitcoin innovation right now isn’t just
                              more hash — it’s useful hash. Turn waste heat into warmth, sats into soak time, and
                              centralized mining into neighborhood resilience.

                              What’s your first hashrate-heat project? Drop it in the replies or tag the hosts on X.

                              Next week on POD256: More freedom tech tangents from Bitcoin Park.

                              Built with high signal • Zero hype • Maximum builder energy


https://256foundation.substack.com/p/assembling-freedom-18-high-signal                                                                                             20/22

3/4/26, 3:53 PM                                              (45) Assembling Freedom #18 - High Signal in the Hashtub: Workshops, Open Source, and Hashrate Heat


                              (All visuals sourced from public summit coverage and product pages. Full episode audio
                              contains even more granular timestamps and links — go listen!)

https://256foundation.substack.com/p/assembling-freedom-18-high-signal                                                                                             21/22

3/4/26, 3:53 PM                                              (45) Assembling Freedom #18 - High Signal in the Hashtub: Workshops, Open Source, and Hashrate Heat


                              Discussion about this post


                                 Comments        Restacks


                  Write a comment...


                                                             © 2026 The 256 Foundation · Privacy ∙ Terms ∙ Collection notice
                                                                         Substack is the home for great culture


https://256foundation.substack.com/p/assembling-freedom-18-high-signal                                                                                             22/22


===== DOCUMENT 19 of 27 =====
DATE: 2026-03-11
LABEL: March 11, 2026
TITLE: Assembling Freedom #19
FILE: 260311-assembling-freedom-19.pdf
SOURCE: https://github.com/256foundation/News/blob/main/260311-assembling-freedom-19.pdf

3/11/26, 5:10 PM                                                Assembling Freedom #19: Revolutionizing Bitcoin Mining - Hacking Antminers with Mujina Firmware


                               Assembling Freedom #19: Revolutionizing
                               Bitcoin Mining - Hacking Antminers with Mujina
                               Firmware
                               A weekly newsletter
                                        256 FOUNDATION
                                        MAR 11, 2026


                                                                                                                                                      Share


                                                                                  Introduction
                               Welcome to Assembling Freedom #19, where we dive deep into the world of open-
                               source innovations in cryptocurrency mining. This newsletter is inspired by POD256
                               Episode 107: “Hacking the Antminer: Mujina on Stock Control Boards, Dev Fees Be
                               Gone.”

                               Hosted by Tyler, Skot, and eco, the episode explores the technical intricacies of
                               deploying Mujina—an open-source Bitcoin mining firmware—directly onto stock
                               Bitmain Antminer S19 control boards. This hack eliminates the need for SD cards,


https://256foundation.substack.com/p/assembling-freedom-19-revolutionizing                                                                                        1/15

3/11/26, 5:10 PM                                                Assembling Freedom #19: Revolutionizing Bitcoin Mining - Hacking Antminers with Mujina Firmware


                               unlocks advanced controls, and banishes developer fees, empowering miners with full
                               transparency and customization. Mujina, developed under the 256 Foundation, is a
                               Linux-based firmware supporting multiple ASIC chips, Stratum V1, and extensible
                               drivers. We’ll break down the key concepts, provide a technical deep dive, include
                               visuals for better understanding, and highlight related discussions from X.


                                                                               Key Takeaways
                                     Open-Source Empowerment: Mujina allows miners to run custom firmware on
                                     stock hardware, avoiding proprietary lockdowns and dev fees that act like SaaS
                                     subscriptions.

                                     Hardware Compatibility: Supports Antminer S19 models, with extensions for
                                     Whatsminer, Avalon, and more, making it versatile for various ASIC setups.
                                     Community-Driven Development: Contributions are encouraged via GitHub,
                                     with AI-assisted pull requests and new CI pipelines accelerating improvements.

                                     Practical Benefits: Enables single-board operations, fan and temperature control,
                                     and APW12 PSU management, while supporting immersion cooling without
                                     spoofers.

                                     Industry Critique: Highlights issues like opaque OEM support, warranty hassles,
                                     and high MOQs that hinder innovation, positioning open-source as the path to
                                     resilience.

https://256foundation.substack.com/p/assembling-freedom-19-revolutionizing                                                                                        2/15

3/11/26, 5:10 PM                                                Assembling Freedom #19: Revolutionizing Bitcoin Mining - Hacking Antminers with Mujina Firmware


                                     Future Visions: Discussions on predictive maintenance, self-hosted pools like
                                     HydraPool, and grassroots devices like Bitaxe Turbo Touch emphasize
                                     decentralized mining from home heaters to megawatt farms.
                                     Call to Action: The episode urges community participation—testing tools, filing
                                     issues, and supporting the 256 Foundation to build trustless stacks.


                                                                      Technical Breakdown
                               The core hack discussed involves flashing Mujina onto stock Antminer S19 control
                               boards using Ethernet/USB via LuxOS, bypassing the need for physical SD cards. This
                               unlocks unprecedented control over hardware components, but it’s not without risks.
                               Below is a step-by-step breakdown tailored for tech enthusiasts interested in
                               replicating or understanding the process.


                               Flashing and Setup Process
                                     Preparation: Ensure you have a stock Bitmain Antminer S19 with its original
                                     control board. Access LuxOS for flashing— a tool that facilitates Ethernet/USB-
                                     based firmware updates.

                                     Flashing Mujina: Use LuxOS to push the Mujina firmware directly to the board.
                                     This process leverages the board’s native interfaces, avoiding hardware
                                     modifications initially.


https://256foundation.substack.com/p/assembling-freedom-19-revolutionizing                                                                                        3/15

3/11/26, 5:10 PM                                                Assembling Freedom #19: Revolutionizing Bitcoin Mining - Hacking Antminers with Mujina Firmware


                                     Driver Integration: Post-flash, integrate custom drivers for temperature sensors,
                                     fans, and the undocumented APW12 PSU interface. These drivers are written in
                                     Rust for efficiency and are part of Mujina’s async implementation.

                                     Configuration: Enable features like single-board mode for minimal setups or
                                     immersion tweaks. Monitor for overheating, as improper fan control can trip
                                     breakers.

                                     Testing and Optimization: Run diagnostics using tools like HashScope (a Stratum
                                     MITM proxy) for debugging miner-pool interactions.


                               Challenges and Solutions
                                     Overheating Risks: Without proper driver tuning, boards can overheat, leading to
                                     electrical failures. Solution: Implement real-time temperature monitoring and
                                     automated fan adjustments.

                                     Undocumented Interfaces: The APW12 PSU lacks official docs, requiring reverse
                                     engineering. Community mods, like 120V hardware tweaks by Zach Bomsta and
                                     PivotalPlebTech, help adapt for different voltages.

                                     Dev Fee Elimination: Closed firmware imposes fees; Mujina replaces this with
                                     open models, allowing miners to redirect resources to actual support and
                                     maintenance.


https://256foundation.substack.com/p/assembling-freedom-19-revolutionizing                                                                                        4/15

3/11/26, 5:10 PM                                                Assembling Freedom #19: Revolutionizing Bitcoin Mining - Hacking Antminers with Mujina Firmware


                                     Immersion Cooling Adjustments: Skip fan spoofers by directly tweaking
                                     firmware for liquid immersion setups, improving efficiency in high-density
                                     environments.


                               Comparison: Open-Source vs. Closed-Source Firmware


                               This table illustrates why Mujina is gaining traction—it’s not just about cost savings
                               but building a robust, decentralized ecosystem.


https://256foundation.substack.com/p/assembling-freedom-19-revolutionizing                                                                                        5/15

3/11/26, 5:10 PM                                                Assembling Freedom #19: Revolutionizing Bitcoin Mining - Hacking Antminers with Mujina Firmware


                               The Antminer S19 is the star hardware here, a powerful ASIC miner known for its
                               efficiency in Bitcoin hashing.


https://256foundation.substack.com/p/assembling-freedom-19-revolutionizing                                                                                        6/15

3/11/26, 5:10 PM                                                Assembling Freedom #19: Revolutionizing Bitcoin Mining - Hacking Antminers with Mujina Firmware


                               For power management, the APW12 PSU is crucial, often requiring mods for optimal
                               performance.


                               The control board itself is the brain of the operation, where Mujina takes root.


https://256foundation.substack.com/p/assembling-freedom-19-revolutionizing                                                                                        7/15

3/11/26, 5:10 PM                                                Assembling Freedom #19: Revolutionizing Bitcoin Mining - Hacking Antminers with Mujina Firmware


                               Immersion cooling setups, discussed for advanced tweaks, submerge hardware in
                               dielectric fluid for superior heat dissipation.


https://256foundation.substack.com/p/assembling-freedom-19-revolutionizing                                                                                        8/15

3/11/26, 5:10 PM                                                Assembling Freedom #19: Revolutionizing Bitcoin Mining - Hacking Antminers with Mujina Firmware


                                                                 Related Discussions on X


https://256foundation.substack.com/p/assembling-freedom-19-revolutionizing                                                                                        9/15

3/11/26, 5:10 PM                                                Assembling Freedom #19: Revolutionizing Bitcoin Mining - Hacking Antminers with Mujina Firmware


                               The Bitcoin mining community on X is buzzing about Mujina’s potential. Here are
                               some highlighted posts that echo the podcast’s themes.

                                     Skot (@skot9000) shared: “I essentially vibe coded S19j Pro support into Mujina
                                     firmware in a few hours. There will be no stopping of this train.” He credits Ryan
                                     Kuester for the architecture.


                                                            skot
                                                            @skot9000

                                                  Shout out to @ryankuester who did all the actual hard work of architecting
                                                  the incredible Mujina open source mining firmware

                                                  9:31 AM · Feb 24, 2026 · 472 Views

                                                  3 Likes


                                     The 256 Foundation (@256FOUNDATION) explained: “Mujina firmware: The
                                     ‘brain’ software you can customize. Open boards: Build-your-own hardware parts.
                                     Hydra Pool: A friendly spot to pool your mining power.”


                                                            881423
                                                            @256FOUNDATION

                                                  3/ The 256 Foundation is the hero squad here. Their open tools:

                                                  Mujina firmware: The "brain" software you can customize.


https://256foundation.substack.com/p/assembling-freedom-19-revolutionizing                                                                                        10/15

3/11/26, 5:10 PM                                                Assembling Freedom #19: Revolutionizing Bitcoin Mining - Hacking Antminers with Mujina Firmware


                                                  Open boards: Build-your-own hardware parts.


                                                           🚪
                                                  Hydra Pool: A friendly spot to pool your mining power. No more locked
                                                  gates!

                                                  6:27 PM · Feb 4, 2026 · 89 Views

                                                  1 Reply · 2 Likes


                                     Tyler Stevens (@tylerkstevens) advised: “American Bitcoin, you should check out
                                     the @256FOUNDATION if you support custom firmware. Mujina is open-source,
                                     ready for tweaks, inspection and offers no dev fees.”


                                                            Tyler Stevens    ⚡️🔥
                                                            @tylerkstevens

                                                  American Bitcoin, you should check out the @256FOUNDATION if you
                                                  support custom firmware.

                                                  Mujina is open-source, ready for tweaks, inspection and offers no dev fees.

                                                  This is financial and security advice.

                                                          American Bitcoin @ABTC

                                                     Custom firmware for ASIC miners optimizes performance, efficiency, and
                                                     control by allowing advanced tuning of hashrate and power
                                                     consumption. It enables operators to customize settings, unlock
                                                     features, and tailor machines to specific goals.

                                                  4:41 PM · Jan 25, 2026 · 1.45K Views


https://256foundation.substack.com/p/assembling-freedom-19-revolutionizing                                                                                        11/15

3/11/26, 5:10 PM                                                Assembling Freedom #19: Revolutionizing Bitcoin Mining - Hacking Antminers with Mujina Firmware


                                                  1 Reply · 25 Likes


                                     Jungly (@jungly) promoted: “‘Mujina is an open-source Bitcoin mining firmware
                                     built to support a number of ASIC chips.’ If you aren’t following what
                                     @ryankuester is doing with mujina - go check out now!”


                                                            jungly
                                                            @jungly

                                                  "Mujina is an open-source Bitcoin mining firmware built to support a number
                                                  of ASIC chips."

                                                  If you aren't following what @ryankuester is doing with mujina - go check
                                                  out out now!


                                                     github.com
                                                     GitHub - 256foundation/mujina: Open-Source Bitcoin Mining
                                                     Firmware

                                                  7:44 AM · Jan 24, 2026 · 154 Views

                                                  3 Reposts · 6 Likes


                                     Michael Schmid (@Schnitzel) highlighted the stack: “This miner ran on: Mujina,
                                     open-source miner firmware… HydraPool, fully open-source mining pool. The
                                     miner didn’t just run open software, it mined to its own open pool.”


https://256foundation.substack.com/p/assembling-freedom-19-revolutionizing                                                                                        12/15

3/11/26, 5:10 PM                                                Assembling Freedom #19: Revolutionizing Bitcoin Mining - Hacking Antminers with Mujina Firmware


                                                            Michael Schmid      ⚡️
                                                            @Schnitzel

                                                  Software matters just as much.

                                                  This miner ran on:
                                                  •Mujina, open-source miner firmware (by @ryankuester ) - mujina.org
                                                  •HydraPool, fully open-source mining pool (by @jungly) - hydrapool.org

                                                  The miner didn’t just run open software,
                                                  it mined to its own


                                                  3:52 PM · Jan 23, 2026 · 481 Views

                                                  2 Replies · 2 Reposts · 21 Likes


https://256foundation.substack.com/p/assembling-freedom-19-revolutionizing                                                                                        13/15

3/11/26, 5:10 PM                                                Assembling Freedom #19: Revolutionizing Bitcoin Mining - Hacking Antminers with Mujina Firmware


                               These posts underscore the growing momentum behind open-source mining tools,
                               aligning with the podcast’s vision of a community-powered future.


                                                                             Closing Thoughts
                               This hack represents a pivotal shift towards open, resilient Bitcoin mining. If you’re a
                               tech enthusiast, consider contributing to Mujina on GitHub or experimenting with
                               these tools. Stay tuned for more deep dives—subscribe and share your thoughts!


                               Discussion about this post


                                 Comments        Restacks


                   Write a comment...


https://256foundation.substack.com/p/assembling-freedom-19-revolutionizing                                                                                        14/15

3/11/26, 5:10 PM                                                Assembling Freedom #19: Revolutionizing Bitcoin Mining - Hacking Antminers with Mujina Firmware


                                                             © 2026 The 256 Foundation · Privacy ∙ Terms ∙ Collection notice
                                                                         Substack is the home for great culture


https://256foundation.substack.com/p/assembling-freedom-19-revolutionizing                                                                                        15/15


===== DOCUMENT 20 of 27 =====
DATE: 2026-03-18
LABEL: March 18, 2026
TITLE: Assembling Freedom #20
FILE: 260318-assembling-freedom-20.pdf
SOURCE: https://github.com/256foundation/News/blob/main/260318-assembling-freedom-20.pdf

3/18/26, 4:20 PM             (50) POD256 Episode 108 Breakdown: From Mixers to Miners – Why Samourai Wallet’s Legal Fight Threatens Every Bitcoin User (and the Open-Source Mining Revolution Too)


                             POD256 Episode 108 Breakdown: From Mixers
                             to Miners – Why Samourai Wallet’s Legal Fight
                             Threatens Every Bitcoin User (and the Open-
                             Source Mining Revolution Too)
                             A weekly 256 Foundation newsletter
                                      256 FOUNDATION
                                      MAR 18, 2026


                                                                                                                                                      Share


                             Live from Denver • March 18, 2026 • Hosts: @econoalchemist, @skot9000, @tylerkstevens •
                             Special guest: Lauren Rodriguez

                             Tech friends, if you care about on-chain privacy, self-custody, or even just running
                             your own miner without Big Tech or governments flipping the kill switch — this
                             episode is required listening. The live discussion hits hard: the imprisonment of
                             Samourai Wallet devs Keonne Rodriguez (5 years) and William “Bill” Hill (4 years) isn’t
                             just about one wallet. It’s a social-precedent that could criminalize any non-custodial
                             privacy code… and the episode ties it straight to the open-source mining stack we all
                             rely on for decentralization.

https://256foundation.substack.com/p/pod256-episode-108-breakdown-from                                                                                                                               1/16

3/18/26, 4:20 PM             (50) POD256 Episode 108 Breakdown: From Mixers to Miners – Why Samourai Wallet’s Legal Fight Threatens Every Bitcoin User (and the Open-Source Mining Revolution Too)


                             Here’s the full tech-deep breakdown with diagrams, tables, recent X chatter, and
                             exactly what you can do today.


                             1. The Samourai Story in One Sentence (Plus the Tech That
                             Got Them Jailed)
                             Samourai wasn’t a centralized mixer — it was a non-custodial mobile wallet with
                             built-in privacy tools. Many users ran their own Dojo full node; Whirlpool did
                             Chaumian CoinJoin (5-person anonymous mixes); Ricochet added extra hops;
                             Stonewall broke heuristics. DOJ called it an “unlicensed money transmitter” anyway,
                             seized servers in 2024, forced a plea in 2025, and locked the devs up. Forfeiture:
                             6.3Mpaid+250k in fines each. Keonne is serving time in Morgantown, WV and Bill in
                             an undisclosed prison right now.

                             Samourai Privacy Stack – Quick Reference Table


https://256foundation.substack.com/p/pod256-episode-108-breakdown-from                                                                                                                               2/16

3/18/26, 4:20 PM             (50) POD256 Episode 108 Breakdown: From Mixers to Miners – Why Samourai Wallet’s Legal Fight Threatens Every Bitcoin User (and the Open-Source Mining Revolution Too)


https://256foundation.substack.com/p/pod256-episode-108-breakdown-from                                                                                                                               3/16

3/18/26, 4:20 PM             (50) POD256 Episode 108 Breakdown: From Mixers to Miners – Why Samourai Wallet’s Legal Fight Threatens Every Bitcoin User (and the Open-Source Mining Revolution Too)


                             Samourai Wallet interface (pre-seizure) — clean, powerful, and now gone from app stores.


https://256foundation.substack.com/p/pod256-episode-108-breakdown-from                                                                                                                               4/16

3/18/26, 4:20 PM             (50) POD256 Episode 108 Breakdown: From Mixers to Miners – Why Samourai Wallet’s Legal Fight Threatens Every Bitcoin User (and the Open-Source Mining Revolution Too)


                             Whirlpool CoinJoin flow diagram: inputs → anonymous pool → post-mix outputs. No single
                             entity can deanonymize.


                             2. Why This Case Threatens All of Bitcoin
                                    Privacy precedent: Even the U.S. Treasury just told Congress (March 2026) that
                                    “lawful users may leverage mixers for financial privacy.” That directly undercuts
                                    the DOJ’s theory — yet the devs are still in prison.


https://256foundation.substack.com/p/pod256-episode-108-breakdown-from                                                                                                                               5/16

3/18/26, 4:20 PM             (50) POD256 Episode 108 Breakdown: From Mixers to Miners – Why Samourai Wallet’s Legal Fight Threatens Every Bitcoin User (and the Open-Source Mining Revolution Too)


                                    Open-source chilling effect: Any dev shipping CoinJoin, Lightning privacy, or
                                    even advanced scripts could face the same “unlicensed transmitter” charge.
                                    Lightning compliance fears already mentioned in the episode. Going a step
                                    further, this novel legal theory could have implications for anyone using a
                                    software or hardware bitcoin wallet, running a node, or mining bitcoin; that’s how
                                    insane this legal theory is.

                                    Fungibility death: Without CoinJoin, chain analysis firms (and governments) win.
                                    Bitcoin stops being cash-like, putting people at increased risk of targeted attacks.

                                    Mining tie-in: The same freedom-tech ethos powers open-source mining
                                    firmware. If devs can be jailed for privacy code, what stops the next attack on
                                    mining tools?

                             Related X Posts – Real-Time Community Pulse (Latest as of today) - @keonne_army
                             (18 Mar): “This [Treasury report] directly weakens the main legal argument… so greatly
                             improves their chances of getting a pardon! #PARDONSAMOURAI” (quoting Bitcoin
                             Magazine on the Treasury win).


                                                            #PardonSamourai
                                                            @keonne_army

                                                  This is huge for $KEONNE

                                                  This directly weakens the main legal argument used to arrest and jail Keonne
                                                  Rodriguez and the Samourai team, so it greatly improves their chances of


https://256foundation.substack.com/p/pod256-episode-108-breakdown-from                                                                                                                               6/16

3/18/26, 4:20 PM             (50) POD256 Episode 108 Breakdown: From Mixers to Miners – Why Samourai Wallet’s Legal Fight Threatens Every Bitcoin User (and the Open-Source Mining Revolution Too)


                                                  getting a pardon!      ✊
                                                  #PARDONSAMOURAI

                                                         Bitcoin Magazine @BitcoinMagazine

                                                    JUST IN:   🇺🇸
                                                                US Treasury reports to Congress that using Bitcoin and
                                                    crypto privacy mixers are NOT unlawful:

                                                    "Lawful users of digital assets may leverage mixers to enable financial
                                                    privacy when transacting through public blockchains."

                                                    Big win for privacy!     👏
                                                  1:05 PM · Mar 18, 2026 · 25 Views

                                                  1 Repost · 2 Likes


                                    @e4pool_com (today): “Dear Mr President… These two gentlemen have committed
                                    no crime. Their ‘crime’ is writing code that works too well. Please, pardon Keonne
                                    Rodriguez and William Hill today!” (links petition).


                                                            e4pool
                                                            @e4pool_com

                                                  Dear Mr President @realDonaldTrump @POTUS

                                                  These two gentlemen have committed no crime. Their ‘crime’ is writing code
                                                  that works too well.

                                                  Please, pardon Keonne Rodriguez and William Hill today!

https://256foundation.substack.com/p/pod256-episode-108-breakdown-from                                                                                                                               7/16

3/18/26, 4:20 PM             (50) POD256 Episode 108 Breakdown: From Mixers to Miners – Why Samourai Wallet’s Legal Fight Threatens Every Bitcoin User (and the Open-Source Mining Revolution Too)


                                                  change.org/billandkeonne

                                                  #PardonSamourai

                                                    change.org
                                                    Sign the Petition


                                                  9:06 AM · Mar 18, 2026 · 112 Views

                                                  1 Repost · 6 Likes


                                    @SilasThornbrook (today): “FREE THEM TODAY! GIVE THEM THE PARDON
                                    THEY DESERVE! CODE IS NOT A CRIME! #PardonSamourai” with powerful
                                    graphic.


                                                            Silas Thornbrook
                                                            @SilasThornbrook

                                                  FOR @keonne AND @SamouraiDev

                                                  FREE THEM TODAY!

                                                  GIVE THEM THE PARDON THEY DESERVE!

                                                  CODE IS NOT A CRIME!

                                                  #PardonSamourai #FreeSamourai


https://256foundation.substack.com/p/pod256-episode-108-breakdown-from                                                                                                                               8/16

3/18/26, 4:20 PM             (50) POD256 Episode 108 Breakdown: From Mixers to Miners – Why Samourai Wallet’s Legal Fight Threatens Every Bitcoin User (and the Open-Source Mining Revolution Too)


                                                  7:26 PM · Mar 17, 2026 · 127 Views

                                                  5 Reposts · 10 Likes


                             3. From Mixers → Miners: The Open-Source Mining
                             Momentum
                             The episode pivots to the flip side of freedom tech: Mujina firmware (from the 256
                             Foundation) and Antminer hacks. This is the exact stack tech enthusiasts are running

https://256foundation.substack.com/p/pod256-episode-108-breakdown-from                                                                                                                               9/16

3/18/26, 4:20 PM             (50) POD256 Episode 108 Breakdown: From Mixers to Miners – Why Samourai Wallet’s Legal Fight Threatens Every Bitcoin User (and the Open-Source Mining Revolution Too)


                             right now to escape manufacturer lock-in and dev fees.

                             Stock vs. Mujina Firmware – Head-to-Head Table


https://256foundation.substack.com/p/pod256-episode-108-breakdown-from                                                                                                                               10/16

3/18/26, 4:20 PM             (50) POD256 Episode 108 Breakdown: From Mixers to Miners – Why Samourai Wallet’s Legal Fight Threatens Every Bitcoin User (and the Open-Source Mining Revolution Too)


                             Example open-source control board (Braiins BCB-100 style) — the kind of hardware Mujina
                             runs on stock Antminers.


https://256foundation.substack.com/p/pod256-episode-108-breakdown-from                                                                                                                               11/16

3/18/26, 4:20 PM             (50) POD256 Episode 108 Breakdown: From Mixers to Miners – Why Samourai Wallet’s Legal Fight Threatens Every Bitcoin User (and the Open-Source Mining Revolution Too)


                             Custom firmware workflow illustration — exactly what Skot demoed live.

                             Bonus mentions: GrapheneOS shifts for secure miner phones, USB Wi‑Fi hacks on
                             Antminers, and AI speeding up firmware PRs. The 256 Foundation stack (Mujina +
                             HydraPool + LibreBoard) is the path to truly decentralized hashrate.


                             4. Ronin Dojo – The Privacy Node That Ties It All Together


https://256foundation.substack.com/p/pod256-episode-108-breakdown-from                                                                                                                               12/16

3/18/26, 4:20 PM             (50) POD256 Episode 108 Breakdown: From Mixers to Miners – Why Samourai Wallet’s Legal Fight Threatens Every Bitcoin User (and the Open-Source Mining Revolution Too)


                             Samourai’s Dojo backend runs perfectly on Ronin Dojo hardware: plug-and-play
                             Bitcoin full node + Tor + Whirlpool coordinator in a box. Self-sovereignty in one
                             device, see the video tutorial here.


                             Ronin Dojo Tanto — the hardware node every privacy-maxing Bitcoiner should own.


https://256foundation.substack.com/p/pod256-episode-108-breakdown-from                                                                                                                               13/16

3/18/26, 4:20 PM             (50) POD256 Episode 108 Breakdown: From Mixers to Miners – Why Samourai Wallet’s Legal Fight Threatens Every Bitcoin User (and the Open-Source Mining Revolution Too)


                             5. What YOU can do RIGHT NOW (Tech Enthusiast Action
                             Plan)
                                1. Sign the pardon petition → https://www.change.org/billandkeonne (or
                                    billandkeonne.org for full site + GiveSendGo family fund and cryptocurrency
                                    donation options).

                                2. Write to Keonne (he’s publishing letters from prison — latest “The Skinwalker”
                                    just dropped by The Rage:

                                  Keonne Rodriguez 11404-511
                                  FPC Morgantown
                                  FEDERAL PRISON CAMP
                                  P.O. BOX 1000
                                  MORGANTOWN, WV 26507

                             Three or less pages, no art work allowed.

                                1. Amplify on X/Nostr with #PardonSamourai #FreeSamourai — tag
                                    @realDonaldTrump if you’re feeling bold.

                                2. Run the stack: Install Sparrow/Electrum for recovery (Samourai seeds still work),
                                    spin up a Ronin Dojo or Mujina miner, test Ashigaru Whirlpool (community fork).

                                3. Watch the fireside livestream and support POD256 on Fountain/Zaprite.


https://256foundation.substack.com/p/pod256-episode-108-breakdown-from                                                                                                                               14/16

3/18/26, 4:20 PM             (50) POD256 Episode 108 Breakdown: From Mixers to Miners – Why Samourai Wallet’s Legal Fight Threatens Every Bitcoin User (and the Open-Source Mining Revolution Too)


                             Code is speech. Privacy is a feature, not a bug. Open-source mining is how we keep
                             Bitcoin decentralized. The Samourai fight is your fight.

                             Stay sovereign. Sign the petition. Run a node. Mine openly. Repeat.                                          🟠
                             This newsletter is published under the Creative Commons license


                             Discussion about this post


                                Comments        Restacks


                   Write a comment...


https://256foundation.substack.com/p/pod256-episode-108-breakdown-from                                                                                                                               15/16

3/18/26, 4:20 PM             (50) POD256 Episode 108 Breakdown: From Mixers to Miners – Why Samourai Wallet’s Legal Fight Threatens Every Bitcoin User (and the Open-Source Mining Revolution Too)


                                                            © 2026 The 256 Foundation · Privacy ∙ Terms ∙ Collection notice
                                                                        Substack is the home for great culture


https://256foundation.substack.com/p/pod256-episode-108-breakdown-from                                                                                                                               16/16


===== DOCUMENT 21 of 27 =====
DATE: 2026-03-25
LABEL: March 25, 2026
TITLE: Assembling Freedom #21
FILE: 260325-assembling-freedom-21.pdf
SOURCE: https://github.com/256foundation/News/blob/main/260325-assembling-freedom-21.pdf

3/25/26, 3:54 PM                                                  (51) Assembling Freedom #21 - by 256 Foundation


                              Assembling Freedom #21
                              POD256 Episode 109 Hashrate Heat, Home Sovereignty, and the Open-Source Mining
                              Stack
                                       256 FOUNDATION
                                       MAR 25, 2026


                                                                                                                    Share


                              For Tech Enthusiasts: Deep Dive into Bitcoin-Powered Homes
                              March 25, 2026

                              Welcome to this in-depth breakdown of POD256 Episode 109, the Bitcoin podcast
                              laser-focused on open-source mining, energy sovereignty, and freedom tech. In this
                              episode, hosts Tyler and Eco (Econoalchemist) hold down the fort while Skot is away.
                              They geek out on the bleeding edge of Bitcoin-powered heating and the maturing
                              open-source mining stack from the 256 Foundation.

                              The core thesis: Turn your home’s waste heat problem into a sovereignty feature.
                              Miners don’t just secure the Bitcoin network—they generate usable BTUs for space
                              heating, hot water, and even hot tubs while you earn sats. Pair that with fully open
                              hardware, firmware, control boards, and pools, and you get true thermodynamic +

https://256foundation.substack.com/p/assembling-freedom-21                                                                  1/17

3/25/26, 3:54 PM                                                (51) Assembling Freedom #21 - by 256 Foundation


                              financial independence. No more closed-source black boxes or reliance on Big Mining
                              farms.


https://256foundation.substack.com/p/assembling-freedom-21                                                          2/17

3/25/26, 3:54 PM                                                   (51) Assembling Freedom #21 - by 256 Foundation


                              This newsletter delivers a full technical breakdown with bullet-point deep dives,
                              comparison tables, key concepts visualized, and real-time X ecosystem pulse. Let’s
                              hash it out.


                              Episode Core Highlights (Timestamp-Aligned Breakdown)
                                    New customer dashboard demo: A production-grade Home Assistant + Venstar
                                    thermostat integration that visualizes miner-delivered BTUs vs. natural gas

https://256foundation.substack.com/p/assembling-freedom-21                                                           3/17

3/25/26, 3:54 PM                                                    (51) Assembling Freedom #21 - by 256 Foundation


                                    usage, heating stage changes, outdoor temps, and sats earned in real time.
                                    Hashrate Heat as a product, not a byproduct: Practical engineering for
                                    residential hydronics, immersion, and air-based systems.

                                    Open-source stack maturity: From Bitaxe solo miners to full-scale open
                                    hashboards, Mujina firmware, control boards, and HydraPool—building resilience
                                    against proprietary lock-in.
                                    Home sovereignty angle: Privacy-preserving mining, local AI-assisted monitoring,
                                    self-hosted dashboards, and energy flow control that resists surveillance
                                    capitalism.


                              1. The Open-Source Mining Stack: Components &
                              Architecture
                              The 256 Foundation is shipping a complete, modular, community-owned alternative to
                              closed-source ASICs and pools. Here’s the stack broken down:


https://256foundation.substack.com/p/assembling-freedom-21                                                             4/17

3/25/26, 3:54 PM                                                  (51) Assembling Freedom #21 - by 256 Foundation


                              Why this matters for techies: Closed-source stacks create single points of failure
                              (firmware backdoors, pool centralization). This stack is GitHub-native—fork it, PR
                              improvements, run your own pool. Difficulty drops (biggest since 2021 China ban)
                              make home rigs viable again.


https://256foundation.substack.com/p/assembling-freedom-21                                                          5/17

3/25/26, 3:54 PM                                             (51) Assembling Freedom #21 - by 256 Foundation


https://256foundation.substack.com/p/assembling-freedom-21                                                     6/17

3/25/26, 3:54 PM                                                   (51) Assembling Freedom #21 - by 256 Foundation


                              2. Hashrate Heat: Thermodynamics Meets Bitcoin
                              Economics
                              Miners convert ~99% of electricity into heat. Instead of venting it, route it through
                              hydronic loops, immersion tanks, or air handlers. Episode deep dive:

                                    BTU accounting in action: The new dashboard quantifies miner heat output (e.g.,
                                    1 kW miner ≈ 3,412 BTU/hr) against gas boiler stages and outdoor temps. Real-
                                    time sats/BTU efficiency metric.


https://256foundation.substack.com/p/assembling-freedom-21                                                            7/17

3/25/26, 3:54 PM                                                     (51) Assembling Freedom #21 - by 256 Foundation


                              System design wins:

                                    Immersion or hydro-cooled ASICs feed indirect water heaters or floor loops.

                                    Pumps, mixing valves, expansion tanks, and sensors integrated via Home
                                    Assistant automations.

                                    Galvanic corrosion mitigations and hydronics best practices (cross-pollination
                                    from Heatpunk Summit workshops).

                              Economics for enthusiasts:

                                    Earn Bitcoin while offsetting heating bills (up to 63% cash-back on electricity in
                                    some builds).

                                    Solar + miner = negative electricity cost + sats.

                                    Scalable: single Bitaxe for a room → full-house S19 Hydro setup.

                              Visual: Real-World Hashrate Heating Setups
                              (Left: Full hydronic schematic with Antminer S19 Pro Hydro feeding floor heating +
                              hot water. Right: In-wall miner exhaust integrated into HVAC.)


https://256foundation.substack.com/p/assembling-freedom-21                                                               8/17

3/25/26, 3:54 PM                                                  (51) Assembling Freedom #21 - by 256 Foundation


                              3. Home Sovereignty: Beyond Mining
                                    Energy sovereignty: Your hashpower = your heat + your money. No utility rate
                                    shocks, no gas dependence.

                                    Protocol sovereignty: Run your node + miner on open firmware → full validation +
                                    block production lottery.


https://256foundation.substack.com/p/assembling-freedom-21                                                             9/17

3/25/26, 3:54 PM                                                      (51) Assembling Freedom #21 - by 256 Foundation


                                    Privacy layer: Self-hosted dashboards, local AI agents for tuning (no cloud SaaS
                                    spying), and Stratum V2 for pool privacy.

                                    Network decentralization: Every home miner flattens the hashrate curve. From
                                    garage rigs to megawatt farms—all powered by the same open stack.

                              Pro Tip for Builders: Combine with local AI (self-hosted LLMs for anomaly detection)
                              and private comms protocols for the ultimate “sovereign smart home.”


                              4. Related X Ecosystem Pulse (Latest Builder Chatter)
                              The conversation is heating up on X right now—here are the exact standout recent
                              posts that directly echo Episode 109 themes (open-source stack, hashrate heat as
                              utility, home sovereignty, and the trojan-horse decentralization effect). I’ve included
                              full clickable links, timestamps, and quick previews so you can jump straight in.

                                    @256FOUNDATION showcased the full open-source stack (hashboards + control
                                    board + firmware + pool) at the Heat Punk Summit:
                                    “The full 256 Foundation stack on display at the Heat Punk Summit by
                                    @SpaceDenver. Open-Source is the future of Bitcoin Mining.”
                                    (4 photos of live demos)
                                    Direct link:


                                                             881423


https://256foundation.substack.com/p/assembling-freedom-21                                                              10/17

3/25/26, 3:54 PM                                                                  (51) Assembling Freedom #21 - by 256 Foundation


                                                             @256FOUNDATION

                                                 The full 256 Foundation stack on display at the Heat Punk Summit by
                                                 @SpaceDenver. Open-Source is the future of Bitcoin Mining.


                                                 4:45 PM · Feb 28, 2026 · 4.89K Views


https://256foundation.substack.com/p/assembling-freedom-21                                                                          11/17

3/25/26, 3:54 PM                                                                 (51) Assembling Freedom #21 - by 256 Foundation


                                                 13 Reposts · 86 Likes


                                    Posted: 28 Feb 2026 • 86 likes • 4 media items

                                    Viral thread on a fully hashrate-heated house + hot tub by @MattCutler21:
                                    “This house and hot tub are heated by bitcoin miners. Electricity turned into heat
                                    AND money… It’s the ultimate trojan horse to secure Bitcoin’s future.”
                                    (Video + photo proof of residential hydronics)
                                    Direct link:


                                                             Matt Cutler
                                                             @MattCutler21

                                                 This house and hot tub are heated by bitcoin miners.

                                                 Electricity turned into heat AND money.


                                                                             💡
                                                 It's a no brainer, but what few realize is it's also the ultimate trojan horse to
                                                 secure bitcoin's future

                                                 Let me explain.

                                                 Mining is a cutthroat industry with slim margins and home


https://256foundation.substack.com/p/assembling-freedom-21                                                                           12/17

3/25/26, 3:54 PM                                                                   (51) Assembling Freedom #21 - by 256 Foundation


                                                             0:00


                                                 9:47 AM · Mar 1, 2026 · 18.8K Views

                                                 27 Replies · 51 Reposts · 391 Likes


                                    Posted: 1 Mar 2026 • 391 likes • Video included

                                    Engineer-built home heated entirely by one hydro-cooled miner from @Braiins:
                                    “HASHRATE HEATED HOUSE              🔥 Our engineer Adam built a new house and
                                    heats it entirely with a single bitcoin miner. No gas, no electric heater. Just one
                                    machine running floor heating, hot water, and earning bitcoin. ✅ Up to 63% cash
                                    back on electricity.”
                                    (Full build guide + 1-year real data linked)
                                    Direct link:


                                                             Braiins
                                                             @Braiins

                                                 HASHRATE HEATED HOUSE            🔥
https://256foundation.substack.com/p/assembling-freedom-21                                                                           13/17

3/25/26, 3:54 PM                                                                      (51) Assembling Freedom #21 - by 256 Foundation


                                                 Our engineer Adam built a new house and heats it entirely with a single
                                                 bitcoin miner. No gas, no electric heater. Just one hydro-cooled machine
                                                 running floor heating, hot water, and earning bitcoin.

                                                 ✅ Up to 63% cash back on electricity
                                                 ✅ Powered by
                                                 9:46 AM · Mar 19, 2026 · 9.68K Views

                                                 8 Replies · 38 Reposts · 161 Likes


                                    Posted: 19 Mar 2026 • 161 likes • Detailed thread

                                    Convergence post on heat-as-product + sovereignty:
                                    “Heat is not a problem. It’s a product. Our engineer built his house heated by
                                    hashrate.”
                                    (Inspired by the free Bitcoin Mining Heat Reuse e-book)
                                    Direct link:


                                                             Braiins
                                                             @Braiins

                                                 Heat is not a problem. It's a product.

                                                 Our engineer built his house heated by hashrate.

                                                 Inspired by our free e-book Bitcoin Mining Heat Reuse               🔥

https://256foundation.substack.com/p/assembling-freedom-21                                                                              14/17

3/25/26, 3:54 PM                                                                   (51) Assembling Freedom #21 - by 256 Foundation


                                                             0:00


                                                 8:30 AM · Mar 6, 2026 · 24.1K Views

                                                 27 Replies · 48 Reposts · 281 Likes


                                    Posted: 6 Mar 2026 • 281 likes • Video demo

                              These are real, live posts from the past few weeks that perfectly align with Tyler &
                              Eco’s discussion on the open-source mining stack, hashrate heat reuse, and building
                              sovereign smart homes. Click through—the videos and build guides are gold for
                              builders.


                              Key Takeaways & Action Items for Tech Enthusiasts
                                    Start small: Grab a Bitaxe, flash Mujina, point at HydraPool, integrate into Home
                                    Assistant.

                                    Level up: Contribute to open hashboard designs or add Venstar + BTU sensors to
                                    your heating loop.


https://256foundation.substack.com/p/assembling-freedom-21                                                                           15/17

3/25/26, 3:54 PM                                                    (51) Assembling Freedom #21 - by 256 Foundation


                                    Sovereignty checklist: Open firmware? Local dashboard? Heat reuse? You’re
                                    winning.

                                    Get involved: 256 Foundation (501(c)3), OSMU Discord, Hashrate Heatpunks. File
                                    PRs, spin up a node, mine on!

                              This episode isn’t just talk—it’s a blueprint for the next wave of Bitcoin infrastructure:
                              decentralized, useful, and profitable at the edge. If you’re into hardware hacking, home
                              automation, or energy tech, this is your moment.

                              Listen to the full episode on pod256.org or your favorite podcast app.
                              Stay sovereign. Keep hashing.   🔥⚡
                              Generated from POD256 Episode 109 + ecosystem sources. All visuals sourced from public
                              builder content.

                              This work published under the CC0 1.0 license


                              Discussion about this post


                                Comments        Restacks


https://256foundation.substack.com/p/assembling-freedom-21                                                                 16/17

3/25/26, 3:54 PM                                                                  (51) Assembling Freedom #21 - by 256 Foundation


                   Write a comment...


                                                             © 2026 The 256 Foundation · Privacy ∙ Terms ∙ Collection notice
                                                                         Substack is the home for great culture


https://256foundation.substack.com/p/assembling-freedom-21                                                                          17/17


===== DOCUMENT 22 of 27 =====
DATE: 2026-04-01
LABEL: April 1, 2026
TITLE: Assembling Freedom #22
FILE: 260401-assembling-freedom-22.pdf
SOURCE: https://github.com/256foundation/News/blob/main/260401-assembling-freedom-22.pdf

4/4/26, 8:37 PM                                 (53) POD256 Episode 110 Newsletter: April Fools? Real Progress – Open Firmware, Open Pools, and the Path to Decentralized Mining


                  POD256 Episode 110 Newsletter: April Fools?
                  Real Progress – Open Firmware, Open Pools, and
                  the Path to Decentralized Mining
                  Assembling Freedom #22: April 1, 2026 | For Tech Enthusiasts, Bitcoin Builders, and Open-
                  Source Mining Rebels
                           256 FOUNDATION
                           APR 04, 2026


                                                                                                                                                                   Share


                  In this lively April 1 episode of POD256 (hosted by @econoalchemist and @skot9000
                  the team cuts through the April Fools jokes to deliver genuine advancements in open-
                  source Bitcoin mining. No gimmicks—just concrete progress on dismantling
                  proprietary mining empires through community-driven hardware, firmware, and
                  pools. The episode previews Bitcoin 2026 in Las Vegas, celebrates renewed 256
                  Foundation grants, spotlights the Bitaxe Bonanza prototype, and explores AI-assisted

https://256foundation.substack.com/p/pod256-episode-110-newsletter-april                                                                                                           1/19

4/4/26, 8:37 PM                                 (53) POD256 Episode 110 Newsletter: April Fools? Real Progress – Open Firmware, Open Pools, and the Path to Decentralized Mining


                  development, UTXOracle price feeds, and why open tools are accelerating true
                  decentralization.

                  Perfect for tinkerers, home miners, and devs tired of black-box miners and centralized
                  pools—this newsletter breaks it all down with technical depth, comparisons, visuals,
                  and fresh X chatter.

                  Listen to POD256 #110 here


                  Episode Overview & Key Takeaways
                        Core Theme: Open-source is resilient. From community forks (e.g.,
                        Ashigaru/Whirlpool) to leaked LLM client code, closed systems crack while open
                        ones thrive.
                        256 Foundation Spotlight: Renewed grants for four flagship projects (Mujina
                        Firmware, Libre Board, Ember One hashboard, Hydra Pool). The Foundation runs
                        an all-Bitcoin treasury experiment—paying devs in sats pegged to cost basis for
                        predictable funding amid volatility.


https://256foundation.substack.com/p/pod256-episode-110-newsletter-april                                                                                                           2/19

4/4/26, 8:37 PM                                 (53) POD256 Episode 110 Newsletter: April Fools? Real Progress – Open Firmware, Open Pools, and the Path to Decentralized Mining


                        Technical Wins Discussed:
                        Unlocking Bitmain control boards and porting Mujina to Amlogic-based
                        Antminers.
                        Model guardrails + AI-assisted workflows speeding up Rust-based development.

                        Non-Bitmain chips (like donated Intel BZM2 ASICs) enabling home-scale, heat-
                        reuse mining.

                        Shoutouts: Hydra Pool hashers and the sleek new Bitaxe Touch.

                        Why It Matters for Techies: Full sovereignty—no dev fees, no vendor lock-in,
                        Stratum V2 support, and self-hosted infrastructure. This stack turns mining from
                        a corporate game into accessible freedom tech.


                  The 256 Foundation’s Open-Source Mining Stack (Renewed
                  Grants)
                  The Foundation funds a complete, modular, GPL/CERN OHL-licensed replacement
                  for proprietary mining. Here’s the breakdown:


https://256foundation.substack.com/p/pod256-episode-110-newsletter-april                                                                                                           3/19

4/4/26, 8:37 PM                                 (53) POD256 Episode 110 Newsletter: April Fools? Real Progress – Open Firmware, Open Pools, and the Path to Decentralized Mining


https://256foundation.substack.com/p/pod256-episode-110-newsletter-april                                                                                                           4/19

4/4/26, 8:37 PM                                 (53) POD256 Episode 110 Newsletter: April Fools? Real Progress – Open Firmware, Open Pools, and the Path to Decentralized Mining


                  Combined impact: Over $400k in prior grants already flowing; these projects form a
                  plug-and-play ecosystem for home miners to megawatt farms.


https://256foundation.substack.com/p/pod256-episode-110-newsletter-april                                                                                                           5/19

4/4/26, 8:37 PM                                 (53) POD256 Episode 110 Newsletter: April Fools? Real Progress – Open Firmware, Open Pools, and the Path to Decentralized Mining


https://256foundation.substack.com/p/pod256-episode-110-newsletter-april                                                                                                           6/19

4/4/26, 8:37 PM                                 (53) POD256 Episode 110 Newsletter: April Fools? Real Progress – Open Firmware, Open Pools, and the Path to Decentralized Mining


                  Open-source mining boards in production (similar to Ember One/Libre prototypes).
                  Community manufacturing is real and accelerating.


                  Deep Dive: Mujina Firmware – The Linux of Mining
                  Mujina is a full-featured, open-source firmware written in Rust for maximum
                  portability and security. Highlights:

                        Multi-driver compatibility: Drop-in support for existing ASICs; extendable to
                        new chips.
                        Stratum V2 native: Better efficiency, privacy, and decentralization vs. legacy
                        Stratum V1.
                        Episode Focus: Unlocking locked Bitmain boards + Amlogic ports. Devs use AI
                        tools with guardrails to accelerate code gen while maintaining auditability.

                        Resilience Example: Community forks prove open code survives leaks and bans.

                  Tech enthusiasts love this because it eliminates manufacturer backdoors and dev fees
                  —pure performance tuning in your hands. GitHub: 256foundation/mujina.


https://256foundation.substack.com/p/pod256-episode-110-newsletter-april                                                                                                           7/19

4/4/26, 8:37 PM                                 (53) POD256 Episode 110 Newsletter: April Fools? Real Progress – Open Firmware, Open Pools, and the Path to Decentralized Mining


                  Deep Dive: Hydra Pool – One-Click Decentralized Mining
                  Centralized pools dominate hashrate. Hydra fixes that:

                        Self-hosted & simple: Stratum server in one easy deploy.
                        Accounting: Solo (full block reward lottery) + PPLNS for steady shares.

                        Future-Proof: Plugin architecture, gamified dashboard, Lightning payouts on the
                        roadmap.

                        Episode Tie-In: Shoutouts to current hashers; positions as default for Ember One
                        systems. See in action here

                  Run your own pool → no KYC, no custody risk, true decentralization. Test instance:
                  test.hydrapool.org.


https://256foundation.substack.com/p/pod256-episode-110-newsletter-april                                                                                                           8/19

4/4/26, 8:37 PM                                 (53) POD256 Episode 110 Newsletter: April Fools? Real Progress – Open Firmware, Open Pools, and the Path to Decentralized Mining


                  Mining pool workflow (Hydra-style self-hosted setup makes every step sovereign).


https://256foundation.substack.com/p/pod256-episode-110-newsletter-april                                                                                                           9/19

4/4/26, 8:37 PM                                 (53) POD256 Episode 110 Newsletter: April Fools? Real Progress – Open Firmware, Open Pools, and the Path to Decentralized Mining


                  Hardware Revolution: Ember One, Libre Board & Bitaxe
                  Bonanza
                        Ember One + Libre Board: Open hashboard + controller combo for DIY rigs.
                        Prototypes already running; next-gen embraces donated Intel chips for heat-reuse
                        projects.
                        Bitaxe Bonanza Show-and-Tell: Skot unveiled this beast—built around 256,000
                        donated Intel BZM2 ASICs (from ProtoMining). Specs target ~1.2 TH/s per unit
                        with robust heatsink, 12V fan, and custom sidecar for Intel’s 9-bit serial protocol.
                        Non-Bitmain chips = no unsoldering ASIC chips, perfect for home miners and
                        waste-heat applications. (Note: Early designs had scaling challenges, but
                        community iteration continues via bitaxeorg/bitaxeBonanza.)


https://256foundation.substack.com/p/pod256-episode-110-newsletter-april                                                                                                           10/19

4/4/26, 8:37 PM                                 (53) POD256 Episode 110 Newsletter: April Fools? Real Progress – Open Firmware, Open Pools, and the Path to Decentralized Mining


                  Classic Bitaxe open-source miner family—Bonanza builds on this ethos with Intel BZM2 chips
                  for higher hashrate sovereignty.


https://256foundation.substack.com/p/pod256-episode-110-newsletter-april                                                                                                           11/19

4/4/26, 8:37 PM                                 (53) POD256 Episode 110 Newsletter: April Fools? Real Progress – Open Firmware, Open Pools, and the Path to Decentralized Mining


https://256foundation.substack.com/p/pod256-episode-110-newsletter-april                                                                                                           12/19

4/4/26, 8:37 PM                                 (53) POD256 Episode 110 Newsletter: April Fools? Real Progress – Open Firmware, Open Pools, and the Path to Decentralized Mining


                  Intel BZM2 ASIC in context: Open chips + open firmware = the future of accessible mining
                  hardware.

                  Bonus Tech Nuggets: - UTXOracle: Bitcoin-native price oracle—no third-party APIs
                  required. Pure on-chain data for treasury and payout logic. Check out the live
                  dashboard here and see how to host it with your own node.

                        AI-Assisted Dev: Guardrails keep LLM-generated code auditable and on-mission.


                  Proprietary vs. Open-Source Mining Stack (Tech
                  Comparison Table)


https://256foundation.substack.com/p/pod256-episode-110-newsletter-april                                                                                                           13/19

4/4/26, 8:37 PM                                 (53) POD256 Episode 110 Newsletter: April Fools? Real Progress – Open Firmware, Open Pools, and the Path to Decentralized Mining


                  Open-source wins on sovereignty, innovation speed, and resilience.


https://256foundation.substack.com/p/pod256-episode-110-newsletter-april                                                                                                           14/19

4/4/26, 8:37 PM                                 (53) POD256 Episode 110 Newsletter: April Fools? Real Progress – Open Firmware, Open Pools, and the Path to Decentralized Mining


                  Community Buzz: Related X Posts
                  Fresh signals from the open-mining ecosystem (post-episode vibes): -
                  @256FOUNDATION (Apr 2, 2026): “Funding for our second round of grants begins
                  today. Congratulations to our team… Mujina Firmware - @ryankuester, Hydra Pool -
                  @jungly, Libre Board - @Schnitzel.” Direct follow-up to the episode’s grant
                  celebration.


                                                    881423
                                                    @256FOUNDATION

                                        Funding for our second round of grants begins today. Congratulations to our
                                        team of developers bringing you an open-source Bitcoin mining ecosystem!

                                        Mujina Firmware - @ryankuester
                                        Hydra Pool - @jungly
                                        Libre Board - @Schnitzel

                                        Links below        👇
                                        9:22 PM · Apr 1, 2026 · 1.3K Views

                                        3 Replies · 4 Reposts · 27 Likes


https://256foundation.substack.com/p/pod256-episode-110-newsletter-april                                                                                                           15/19

4/4/26, 8:37 PM                                 (53) POD256 Episode 110 Newsletter: April Fools? Real Progress – Open Firmware, Open Pools, and the Path to Decentralized Mining


                        @256FOUNDATION (Mar 11, 2026): Deep substack on “Hacking Antminers with
                        Mujina Firmware”—exactly the porting/unlocking discussed.


                                                    881423
                                                    @256FOUNDATION

                                        Assembling Freedom #19: Revolutionizing Bitcoin Mining - Hacking
                                        Antminers with Mujina Firmware

                                        open.substack.com/pub/256foundat…

                                        5:00 PM · Mar 11, 2026 · 1.51K Views

                                        1 Reply · 4 Reposts · 8 Likes


                        Broader chatter ties into Bitaxe/ESP-Miner vs. Mujina (Rust/Linux) differences,
                        showing active dev cross-pollination.


                                                    WantClue
                                                    @wantclue

                                        @Fudmottin @skot9000 @nvk ESP-miner is standalone. It’s written in C and
                                        runs in an embedded microcontroller. Mujina on the otherhand is written in
                                        rust afaik and designed for Linux. So those are two different worlds.

https://256foundation.substack.com/p/pod256-episode-110-newsletter-april                                                                                                           16/19

4/4/26, 8:37 PM                                 (53) POD256 Episode 110 Newsletter: April Fools? Real Progress – Open Firmware, Open Pools, and the Path to Decentralized Mining


                                        Some logic can be used vis versa but a direct port of the firmware is not
                                        possible.

                                        3:21 PM · Mar 8, 2026 · 44 Views

                                        1 Reply · 2 Likes


                  Final Thoughts: The Path Forward
                  This episode isn’t hype—it’s a roadmap. Open firmware + open pools + open hardware
                  = mining anyone can verify, modify, and run privately. Whether you’re flashing Mujina
                  on an old Antminer, spinning up Hydra Pool on a Raspberry Pi, or building a Bitaxe
                  Bonanza for your garage heater, the tools are here.

                  Action Items for Tech Enthusiasts: - Check the 256 foundation GitHub repos. - Point
                  a miner at Hydra pool and donate some hashrate. - Attend Bitcoin 2026 in Vegas. -
                  Donate to 256 Foundation or contribute PRs.

                  Listen to the full episode on Fountain, Podverse, or your favorite player. Next week:
                  more open mining magic. Stay sovereign!                                        ⚡
https://256foundation.substack.com/p/pod256-episode-110-newsletter-april                                                                                                           17/19

4/4/26, 8:37 PM                                 (53) POD256 Episode 110 Newsletter: April Fools? Real Progress – Open Firmware, Open Pools, and the Path to Decentralized Mining


                  This work published under the CC0 1.0 license


                  Discussion about this post


                   Comments           Restacks


                      Write a comment...


                                                     © 2026 The 256 Foundation · Privacy ∙ Terms ∙ Collection notice

https://256foundation.substack.com/p/pod256-episode-110-newsletter-april                                                                                                           18/19

4/4/26, 8:37 PM                                 (53) POD256 Episode 110 Newsletter: April Fools? Real Progress – Open Firmware, Open Pools, and the Path to Decentralized Mining


                                                                           Substack is the home for great culture


https://256foundation.substack.com/p/pod256-episode-110-newsletter-april                                                                                                           19/19


===== DOCUMENT 23 of 27 =====
DATE: 2026-04-08
LABEL: April 8, 2026
TITLE: Assembling Freedom #23
FILE: 260408-assembling-freedom-23.pdf
SOURCE: https://github.com/256foundation/News/blob/main/260408-assembling-freedom-23.pdf

4/15/26, 5:11 PM                                             Assembling Freedom #23 - by 256 Foundation


                   Assembling Freedom #23
                   From POD256 ep111: Open-Source Overdrive: Mujina Breakthroughs, Public Pool’s First
                   Block, and LibreBoard v3
                          256 FOUNDATION
                          APR 11, 2026


                                                                                                          Share


                   April 8, 2026 | Hosted by @econoalchemist, @skot9000, and @tylerkstevens

                   Tech enthusiasts, this episode is pure open-source Bitcoin mining catnip. The crew
                   dives headfirst into the “nerd-sniped” joy of rapid hardware iteration, celebrates a
                   massive week for solo miners (4 blocks in a week!), and drops roadmaps for Mujina
                   firmware, HydraPool, and LibreBoard v3. Everything is GPL/CERN-OHL licensed,
                   community-driven, and aimed at making mining more hackable, transparent, and fun.


https://256foundation.substack.com/p/assembling-freedom-23                                                        1/24

4/15/26, 5:11 PM                                             Assembling Freedom #23 - by 256 Foundation


                   No proprietary black boxes here—just Rust-powered firmware, custom PCBs, and real
                   blocks hitting public pools.


                   1. Hardware Hacks: From $20 USB Miner Concepts to Fan
                   Control Boards
                   The episode opens with the classic open-source trap: one idea leads to another. Hosts
                   sketch the Bitaxe Latte—a jokey but plausible ultra-low-cost USB Bitcoin miner
                   concept (~$20 BOM) that could democratize entry-level solo mining even further. They
                   also unveil a tiny custom adapter board for AC Infinity duct fans, letting miners
                   control high-CFM, low-noise fans via standard 4-pin PWM headers on hashboards.

                   Key Technical Breakdown:

                       Bitaxe Latte concept: Builds on existing Bitaxe ecosystem (BM1366/BM1370
                       chips). Focus on minimalism: USB-powered, open KiCad files, plug-and-play for
                       hobbyists.

                       AC Infinity adapter: Solves noisy stock fans. Uses 4-pin header for PWM speed
                       control + RPM feedback. Pairs perfectly with Ember One or similar open boards.

https://256foundation.substack.com/p/assembling-freedom-23                                                 2/24

4/15/26, 5:11 PM                                             Assembling Freedom #23 - by 256 Foundation


                       Why it matters: Open hardware accelerates iteration—community forks and PRs
                       ship faster than closed-source vendors.


https://256foundation.substack.com/p/assembling-freedom-23                                                3/24

4/15/26, 5:11 PM                                             Assembling Freedom #23 - by 256 Foundation


                   (Bitaxe hardware examples—imagine the Latte as an even smaller USB variant.)


https://256foundation.substack.com/p/assembling-freedom-23                                                4/24

4/15/26, 5:11 PM                                             Assembling Freedom #23 - by 256 Foundation


https://256foundation.substack.com/p/assembling-freedom-23                                                5/24

4/15/26, 5:11 PM                                             Assembling Freedom #23 - by 256 Foundation


                   (Mining setups with AC Infinity-style fan integration and adapter examples.)

https://256foundation.substack.com/p/assembling-freedom-23                                                6/24

4/15/26, 5:11 PM                                             Assembling Freedom #23 - by 256 Foundation


                   2. Firmware Deep Dive: Mujina Breakthroughs & Open
                   Collaboration
                   Mujina (Rust-based, async mining software from 256 Foundation) steals the show. It’s a
                   modern, multi-chip driver firmware running on Debian-based OS, targeting Bitmain,
                   Whatsminer, Avalon, and more. Recent wins include PWM frequency tweaks for better
                   fan control and RPM reporting workarounds.

                   In-Depth Bullet Breakdown:

                       PWM frequency tweaks: Higher/lower frequencies reduce coil whine or improve
                       fan response on hashboards.

                       RPM reporting hack: Custom logic in Mujina bridges missing sensor data—
                       critical for monitoring and auto-tuning.

                       Universal Bitmain-chip driver roadmap (April): One driver to rule them all.
                       Community forks already appearing (e.g., BCB100 support).
                       AxeOS protections: Coinbase verification prevents pool attacks; GPL alignment
                       ensures transparency.

https://256foundation.substack.com/p/assembling-freedom-23                                                  7/24

4/15/26, 5:11 PM                                             Assembling Freedom #23 - by 256 Foundation


                       Collaboration superpowers: Open-source stack (firmware + hardware + pool)
                       means PRs ship in days, not quarters.

                   Mujina vs. Closed Firmware Comparison Table:


https://256foundation.substack.com/p/assembling-freedom-23                                                8/24

4/15/26, 5:11 PM                                             Assembling Freedom #23 - by 256 Foundation


https://256foundation.substack.com/p/assembling-freedom-23                                                9/24

4/15/26, 5:11 PM                                             Assembling Freedom #23 - by 256 Foundation


                   (Firmware dashboard example—visualizing real-time tuning, hashrate, and temps like
                   Mujina/PrismOS-style interfaces.)


                   3. Solo Mining Explosion: Public Pool’s First Block + 4
                   Blocks in Days
                   A banner week for the little guy. Solo miners (using open pools and hardware) found 4
                   blocks recently—proof that probability + open tools = life-changing wins without KYC
                   or custodial drama.

                   Blocks Breakdown (as of episode):

                       CKPool ×2 (old Antminers, 230 TH/s and 70 TH/s)
                       Public Pool’s first hosted-instance block (~18.5 TH/s NerdQaxe)

                       Node Runners pool (~4.8 TH/s NerdQaxe++)

                   Pool Mechanics Spotlight:


https://256foundation.substack.com/p/assembling-freedom-23                                                 10/24

4/15/26, 5:11 PM                                             Assembling Freedom #23 - by 256 Foundation


                       Public Pool: Fully open-source, no fees, stratum+tcp://public-pool.io:21496
                       (username = BTC address.worker).

                       Coinbase verification in AxeOS/Mujina protects against malicious pools.
                       Odds example: One 18.5 TH/s miner beat 1-in-28,000 daily odds for a full block.

                   Solo Mining Wins Table:


https://256foundation.substack.com/p/assembling-freedom-23                                                11/24

4/15/26, 5:11 PM                                             Assembling Freedom #23 - by 256 Foundation


https://256foundation.substack.com/p/assembling-freedom-23                                                12/24

4/15/26, 5:11 PM                                             Assembling Freedom #23 - by 256 Foundation


                   (Public Pool branding and live dashboard—transparent, open-source solo mining.)


https://256foundation.substack.com/p/assembling-freedom-23                                                13/24

4/15/26, 5:11 PM                                             Assembling Freedom #23 - by 256 Foundation


                   (Block-found celebration visuals—pure open-source mining joy.)


                   4. April Roadmaps & LibreBoard v3 Power Design

https://256foundation.substack.com/p/assembling-freedom-23                                                14/24

4/15/26, 5:11 PM                                             Assembling Freedom #23 - by 256 Foundation


                       HydraPool: Password-field difficulty/hashrate hints + improved logging for better
                       UX.

                       Mujina: Push to universal Bitmain driver.
                       LibreBoard v3: Power delivery upgrades for Ember One hashboards (~100W, 2-4
                       TH/s per board). Fully open CERN-OHL-S, versatile I/O, compute module options.


https://256foundation.substack.com/p/assembling-freedom-23                                                 15/24

4/15/26, 5:11 PM                                             Assembling Freedom #23 - by 256 Foundation


https://256foundation.substack.com/p/assembling-freedom-23                                                16/24

4/15/26, 5:11 PM                                             Assembling Freedom #23 - by 256 Foundation


                   (Ember One / LibreBoard-style open hashboards and control boards.)

https://256foundation.substack.com/p/assembling-freedom-23                                                17/24

4/15/26, 5:11 PM                                                          Assembling Freedom #23 - by 256 Foundation


                   Additional shop talk: Stencil printer & solder paste tips, Ember One v6.1 reliability,
                   ASIC RS community growth, Telehash/Austin plans, and upcoming events (Vegas +
                   Bitcoin Park Nashville).


                   5. Related X Buzz from the Community
                   The open-source mining wave is real—here’s what’s lighting up X right now:

                       @skot9000 (Bitaxe instigator): “Make no mistake, what you are looking at here is
                       the future of Bitcoin mining firmware; Mujina. Versatile, customizable, open
                       source freedom.” (quoting a BCB100 Mujina fork).


                                                   skot
                                                   @skot9000

                                       Make no mistake, what you are looking at here is the future of Bitcoin mining
                                       firmware; Mujina. Versatile, customizable, open source freedom.

                                                burn the bridge @econoalchemist

                                          Someone forked Mujina & got it to work on the BCB100. Open-source
                                          Bitcoin mining firmware FTW.


https://256foundation.substack.com/p/assembling-freedom-23                                                             18/24

4/15/26, 5:11 PM                                                              Assembling Freedom #23 - by 256 Foundation


                                          https://t.co/8WW8yZfYYx

                                       6:36 AM · Apr 10, 2026 · 1.71K Views

                                       2 Replies · 5 Reposts · 32 Likes


                       @econoalchemist: Highlighted the same Mujina fork: “Someone forked Mujina &
                       got it to work on the BCB100. Open-source Bitcoin mining firmware FTW.”


                                                   burn the bridge
                                                   @econoalchemist

                                       Someone forked Mujina & got it to work on the BCB100. Open-source
                                       Bitcoin mining firmware FTW.

                                       github.com/aadhi1014/BCB1…

                                       7:43 PM · Apr 9, 2026 · 2.38K Views

                                       4 Replies · 6 Reposts · 15 Likes


https://256foundation.substack.com/p/assembling-freedom-23                                                                 19/24

4/15/26, 5:11 PM                                                            Assembling Freedom #23 - by 256 Foundation


                       @mining_central: “This week #Bitcoin paid out 4 times to solo miners! … Public
                       Pool - (~18.5 TH/s, NerdQaxe) … The network doesn’t care how big you are.”


                                                   Coin Mining Central
                                                   @mining_central

                                       🚨 This week #Bitcoin paid out 4 times to solo miners! No splitting the
                                       reward, just 4 solo operators walking away with a combined ~12.5 BTC +
                                       fees!

                                       🟧 Block 943,411
                                       Solo CK (~230 TH/s, old Antminer)

                                       🟧 Block 943,466
                                       Public Pool - (~18.5 TH/s, NerdQaxe)

                                       🟧 Block 944,078
                                       6:23 AM · Apr 10, 2026 · 404 Views

                                       1 Reply · 1 Repost · 12 Likes


                       @solo_mining: Celebrated “The first Public Pool Bitcoin Block was (finally) found.
                       🥳 Congrats … Open Source wins!”
https://256foundation.substack.com/p/assembling-freedom-23                                                               20/24

4/15/26, 5:11 PM                                                      Assembling Freedom #23 - by 256 Foundation


                                                   Solomining
                                                   @solo_mining

                                       🚨🚨🚨 The first Public Pool Bitcoin Block was (finally) found. 🥳
                                       Congrats to the lucky miner who found it! Well deserved! Open Source wins!


https://256foundation.substack.com/p/assembling-freedom-23                                                          21/24

4/15/26, 5:11 PM                                                              Assembling Freedom #23 - by 256 Foundation


                                       12:54 AM · Apr 3, 2026 · 8.19K Views

                                       6 Replies · 22 Reposts · 296 Likes


https://256foundation.substack.com/p/assembling-freedom-23                                                                 22/24

4/15/26, 5:11 PM                                             Assembling Freedom #23 - by 256 Foundation


                   Final Call to Action
                   Tune in at pod256.org. Dive into the repos: Mujina on GitHub, LibreBoard, Public
                   Pool docs. Build, fork, mine—Bitcoin’s hashrate gets freer one open PR at a time.

                   Stay hashin’!        ⛏️
                   Generated from POD256 Episode 111 for tech enthusiasts.

                   This work published under the CC0 1.0 license


                   Discussion about this post


                    Comments         Restacks


https://256foundation.substack.com/p/assembling-freedom-23                                                23/24

4/15/26, 5:11 PM                                                            Assembling Freedom #23 - by 256 Foundation


                     Write a comment...


                                                    © 2026 The 256 Foundation · Privacy ∙ Terms ∙ Collection notice
                                                                Substack is the home for great culture


https://256foundation.substack.com/p/assembling-freedom-23                                                               24/24


===== DOCUMENT 24 of 27 =====
DATE: 2026-04-15
LABEL: April 15, 2026
TITLE: Assembling Freedom #24
FILE: 260415-assembling-freedom-24.pdf
SOURCE: https://github.com/256foundation/News/blob/main/260415-assembling-freedom-24.pdf

4/15/26, 5:48 PM                                          Assembling Freedom #24 - Bitcoin Mining Renaissance: Stratum V2, Nonce Space, and the DIY Miner Comeback


                   Assembling Freedom #24 - Bitcoin Mining
                   Renaissance: Stratum V2, Nonce Space, and the
                   DIY Miner Comeback
                   From POD256 Episode #112 – Tailored for Tech Enthusiasts April 15, 2026 (Comply or Die
                   on Tax Day Edition)
                          256 FOUNDATION
                          APR 15, 2026


                                                                                                                                                               Share


                   Welcome, hashers and protocol nerds! This week’s POD256 episode—co-hosted by
                   @econoalchemist, @skot9000, and @tylerkstevens —delivers a no-BS, host-led
                   masterclass on the resurgence of home mining, the open-source firmware revolution,
                   and why Stratum V2 is the protocol upgrade Bitcoin mining desperately needs. No
                   guests, just deep technical tangents on nonce space, version rolling, decentralized


https://256foundation.substack.com/p/assembling-freedom-24-bitcoin-mining                                                                                              1/23

4/15/26, 5:48 PM                                          Assembling Freedom #24 - Bitcoin Mining Renaissance: Stratum V2, Nonce Space, and the DIY Miner Comeback


                   pools like HydraPool, ASIC roadmaps, and the cultural shift back to permissionless,
                   DIY Bitcoin production.

                   If you’re into sovereignty, low-level protocol design, or tinkering with ASICs in your
                   garage, this episode (and this newsletter) is your new favorite read. We’ll break it down
                   with bullet-point deep dives, comparison tables, visual diagrams, nonce math, and
                   fresh X chatter from the community. Let’s hash it out.


https://256foundation.substack.com/p/assembling-freedom-24-bitcoin-mining                                                                                            2/23

4/15/26, 5:48 PM                                          Assembling Freedom #24 - Bitcoin Mining Renaissance: Stratum V2, Nonce Space, and the DIY Miner Comeback


                   1. The DIY Miner’s Comeback: History, 2020 Wave, and Why
                   Small Hardware Still Matters


https://256foundation.substack.com/p/assembling-freedom-24-bitcoin-mining                                                                                            3/23

4/15/26, 5:48 PM                                          Assembling Freedom #24 - Bitcoin Mining Renaissance: Stratum V2, Nonce Space, and the DIY Miner Comeback


                   The episode traces Bitcoin mining’s arc from laptop experiments to industrial farms—
                   and back. Key highlights:

                       Early days recap: Solo mining on CPUs/GPUs gave way to ASICs; Chinese
                       dominance followed until the 2021 ban created a global hash-rate diaspora.

                       2020 resurgence: Cheap used ASICs flooded the market post-ban. Guides like
                       Mining for the Streets and Home Mining for Non-KYC Bitcoin ignited a tinkerer
                       movement—non-KYC sats via home rigs became a privacy flex.

                       The Bitaxe effect: Tiny, open-source miners (like the Bitaxe family) aren’t about
                       raw TH/s—they’re about education, community, and proving decentralization at
                       the edge. A single Bitaxe teaches more about consensus than a rack of rented
                       hash.
                       Culture evolution: From sketchy Telegram deals to mature open-source
                       ecosystems with Telegram groups turning into real builders’ networks.

                   Why it matters for tech enthusiasts: Home mining isn’t dead—it’s evolving into a
                   sovereignty tool. Even modest setups contribute to hash-rate distribution and
                   mempool policy signaling.

https://256foundation.substack.com/p/assembling-freedom-24-bitcoin-mining                                                                                            4/23

4/15/26, 5:48 PM                                          Assembling Freedom #24 - Bitcoin Mining Renaissance: Stratum V2, Nonce Space, and the DIY Miner Comeback


https://256foundation.substack.com/p/assembling-freedom-24-bitcoin-mining                                                                                            5/23

4/15/26, 5:48 PM                                          Assembling Freedom #24 - Bitcoin Mining Renaissance: Stratum V2, Nonce Space, and the DIY Miner Comeback


https://256foundation.substack.com/p/assembling-freedom-24-bitcoin-mining                                                                                            6/23

4/15/26, 5:48 PM                                          Assembling Freedom #24 - Bitcoin Mining Renaissance: Stratum V2, Nonce Space, and the DIY Miner Comeback


https://256foundation.substack.com/p/assembling-freedom-24-bitcoin-mining                                                                                            7/23

4/15/26, 5:48 PM                                          Assembling Freedom #24 - Bitcoin Mining Renaissance: Stratum V2, Nonce Space, and the DIY Miner Comeback


                   2. Open-Source Firmware Explosion: Mujina, Braiins
                   BCB100, and S19 Support
                   The hosts geek out on how open hardware + firmware is supercharging DIY mining:

                       Mujina on Braiins BCB100 control board: Expands compatibility to entire
                       generations of Antminer S19s.
                       Stratum V2 + Mujina combo: Enables permissionless iteration—miners run their
                       own nodes, propose templates, and escape pool gatekeeping.
                       Bitaxe & AxeOS momentum: Native Stratum V2 support in open-source firmware
                       lets hobbyists point directly at personal nodes for true solo mining.

                   This isn’t hype; it’s the tooling layer that turns “rented hash” into sovereign
                   infrastructure.


                   3. Stratum V2 Technical Deep Dive: Nonce Space, Header-
                   Only Mining, and Decentralization


https://256foundation.substack.com/p/assembling-freedom-24-bitcoin-mining                                                                                            8/23

4/15/26, 5:48 PM                                          Assembling Freedom #24 - Bitcoin Mining Renaissance: Stratum V2, Nonce Space, and the DIY Miner Comeback


                   Stratum V1’s “poorly specified, closed implementations” created centralization risks.
                   V2 fixes this with binary framing, encryption (Noise Protocol), and miner agency.

                   Core innovations discussed:

                       Job Negotiation: Miners (or proxies) propose block templates to the pool. Pools
                       validate but can’t censor txs. Although the pool operator still controls the
                       coinbase payout tx and they are in charge of share accounting.
                       Header-Only Mining (HOM): Devices work on just the block header—no
                       extranonce/Merkle path recalculation needed on the ASIC.
                       Nonce space math (per nTime value, fixed):
                       Standard Channel search space = ( 2{(\text{NONCE_BITS} +
                       \text{BIP320_VERSION_ROLLING_BITS})} = 2
                                                                                           \approx 280 ) TH.
                       Extended Channels add extranonce bits for massive parallelization. Version
                       rolling (BIP320) + nonce (32-bit) + nTime rolling gives each device a guaranteed
                       slice of the ~2^256 search space.


https://256foundation.substack.com/p/assembling-freedom-24-bitcoin-mining                                                                                            9/23

4/15/26, 5:48 PM                                          Assembling Freedom #24 - Bitcoin Mining Renaissance: Stratum V2, Nonce Space, and the DIY Miner Comeback


                   Stratum V1 vs V2 Comparison Table (pulled from protocol specs and episode
                   context):


                   Visual of Stratum V2 Architecture (proxy + standard channels + group channel to
                   pool):

https://256foundation.substack.com/p/assembling-freedom-24-bitcoin-mining                                                                                            10/23

4/15/26, 5:48 PM                                          Assembling Freedom #24 - Bitcoin Mining Renaissance: Stratum V2, Nonce Space, and the DIY Miner Comeback


https://256foundation.substack.com/p/assembling-freedom-24-bitcoin-mining                                                                                            11/23

4/15/26, 5:48 PM                                          Assembling Freedom #24 - Bitcoin Mining Renaissance: Stratum V2, Nonce Space, and the DIY Miner Comeback


https://256foundation.substack.com/p/assembling-freedom-24-bitcoin-mining                                                                                            12/23

4/15/26, 5:48 PM                                          Assembling Freedom #24 - Bitcoin Mining Renaissance: Stratum V2, Nonce Space, and the DIY Miner Comeback


                   Nonce visualization—how miners iterate nonces inside the candidate block header:


https://256foundation.substack.com/p/assembling-freedom-24-bitcoin-mining                                                                                            13/23

4/15/26, 5:48 PM                                          Assembling Freedom #24 - Bitcoin Mining Renaissance: Stratum V2, Nonce Space, and the DIY Miner Comeback


                   4. Decentralized Pools: HydraPool, P2Pool v2, and Beyond
                   Centralized FPPS


https://256foundation.substack.com/p/assembling-freedom-24-bitcoin-mining                                                                                            14/23

4/15/26, 5:48 PM                                          Assembling Freedom #24 - Bitcoin Mining Renaissance: Stratum V2, Nonce Space, and the DIY Miner Comeback


                       HydraPool goals: Lower the barrier to spinning up your own pool. P2Pool v2-style
                       coordination + new payout mechanics.

                       Reality check: FPPS (pay-per-share) still dominates centralized pools, but V2 +
                       open firmware makes solo/p2pool viable again.

                       BIP-0110 signaling debates: How home miners can influence consensus rules via
                       hash-rate voting.

                   The episode emphasizes: authentic decentralization requires miners who run nodes
                   and care about policy—not just profit.

                   Centralized vs Decentralized Pool Flow (V2 proxy model):


https://256foundation.substack.com/p/assembling-freedom-24-bitcoin-mining                                                                                            15/23

4/15/26, 5:48 PM                                          Assembling Freedom #24 - Bitcoin Mining Renaissance: Stratum V2, Nonce Space, and the DIY Miner Comeback


https://256foundation.substack.com/p/assembling-freedom-24-bitcoin-mining                                                                                            16/23

4/15/26, 5:48 PM                                          Assembling Freedom #24 - Bitcoin Mining Renaissance: Stratum V2, Nonce Space, and the DIY Miner Comeback


                   (classic industrial ASIC contrast)


https://256foundation.substack.com/p/assembling-freedom-24-bitcoin-mining                                                                                            17/23

4/15/26, 5:48 PM                                          Assembling Freedom #24 - Bitcoin Mining Renaissance: Stratum V2, Nonce Space, and the DIY Miner Comeback


                   5. ASIC Market, Big-Miners-to-AI Shift, and Hosted Mining
                   Risks
                   Quick hits from the discussion:

                       Bitmain/WhatsMiner release cadence and tape-out risks.

                       Institutional miners eyeing AI/HPC—could free up hash-rate or create new
                       centralization vectors.

                       Hosted mining vs. hash-rate rentals: sovereignty trade-offs analyzed.

                   DIY ethos wins when big players pivot elsewhere.


                   6. Community Pulse: Related X Posts from the Mining
                   Trenches
                   Fresh signals from the home-mining and Stratum V2 scene (semantic + keyword
                   search, 2025–2026):


https://256foundation.substack.com/p/assembling-freedom-24-bitcoin-mining                                                                                            18/23

4/15/26, 5:48 PM                                          Assembling Freedom #24 - Bitcoin Mining Renaissance: Stratum V2, Nonce Space, and the DIY Miner Comeback


                       @SoloSatoshi on NerdQaxe+ Hydro (May 2025): “They said home mining was
                       dead. They said solo mining was a dream. They were wrong.” (Liquid-cooled 4.8
                       TH/s beast for quiet home ops.)


                                                   Solosatoshi.com          🇺🇲
                                                   @SoloSatoshi

                                       They said home mining was dead.
                                       They said solo mining was a dream.
                                       They were wrong.


                                                                                      🧵👇
                                       Introducing the NerdQaxe+ Hydro, the most radical thing to hit Bitcoin home
                                       mining since the block reward.


                                                  0:00


                                       6:56 AM · May 14, 2025 · 77.3K Views

                                       63 Replies · 72 Reposts · 439 Likes


https://256foundation.substack.com/p/assembling-freedom-24-bitcoin-mining                                                                                            19/23

4/15/26, 5:48 PM                                          Assembling Freedom #24 - Bitcoin Mining Renaissance: Stratum V2, Nonce Space, and the DIY Miner Comeback


                       @pavlenex (Apr 2026): Running Stratum V2 UI + NerdAxe + Braiins hashrate, all
                       solo-mining with his own node. “So much fun.”


                                                   Pavlenex
                                                   @pavlenex

                                       Running @StratumV2 UI with my NerdAxe (sv2 native firmware) and a fleet
                                       of @Braiins hashrate market, all pointed to solo mine with my own node.


                                                  0:00


                                       3:54 AM · Apr 13, 2026 · 1.97K Views

                                       2 Replies · 6 Reposts · 26 Likes


                       @BitcoinNewsCom (Sep 2025): “Home Bitcoin mining has gotten a major
                       upgrade. The NERDQAXE++ HYDRO… Run a miner. Decentralize hashrate.”


https://256foundation.substack.com/p/assembling-freedom-24-bitcoin-mining                                                                                            20/23

4/15/26, 5:48 PM                                          Assembling Freedom #24 - Bitcoin Mining Renaissance: Stratum V2, Nonce Space, and the DIY Miner Comeback


                                                   Bitcoin News
                                                   @BitcoinNewsCom

                                       Home Bitcoin mining has gotten a major upgrade.

                                       The NERDQAXE++ HYDRO from @Pleb_Style gives you 4.8 TH/s of liquid-
                                       cooled hashrate, without the loud noise.

                                       Run a miner. Decentralize hashrate.


                                                  0:00


                                       1:26 PM · Sep 24, 2025 · 77.9K Views

                                       39 Replies · 98 Reposts · 733 Likes


                   These posts show the DIY wave is accelerating with V2-native firmware and
                   solar/liquid-cooling hacks.

https://256foundation.substack.com/p/assembling-freedom-24-bitcoin-mining                                                                                            21/23

4/15/26, 5:48 PM                                          Assembling Freedom #24 - Bitcoin Mining Renaissance: Stratum V2, Nonce Space, and the DIY Miner Comeback


                   7. Get Involved & Support Open Mining R&D
                       Point spare hash to dash.256f.org (the episode’s leaderboard).
                       Attend Telehash #4 on May 19 at Bitcoin Park (Austin).
                       Zap support via Lightning or run a Bitaxe pointed at open pools.

                   Final takeaway from the hosts: Stratum V2 + open hardware isn’t just a protocol
                   upgrade—it’s the comeback story that keeps Bitcoin’s hash-rate decentralized, one
                   garage miner at a time.

                   Subscribe to POD256, fire up your node, and start hashing. The nonce space is waiting.
                   See you on the chain.

                   Built from POD256 #112 show notes + protocol specs. Stay sovereign.

                   All of our newsletters are published under the CC0 1.0 license.


                   Discussion about this post


https://256foundation.substack.com/p/assembling-freedom-24-bitcoin-mining                                                                                            22/23

4/15/26, 5:48 PM                                          Assembling Freedom #24 - Bitcoin Mining Renaissance: Stratum V2, Nonce Space, and the DIY Miner Comeback


                   Comments          Restacks


                     Write a comment...


                                                    © 2026 The 256 Foundation · Privacy ∙ Terms ∙ Collection notice
                                                                Substack is the home for great culture


https://256foundation.substack.com/p/assembling-freedom-24-bitcoin-mining                                                                                            23/23


===== DOCUMENT 25 of 27 =====
DATE: 2026-04-22
LABEL: April 22, 2026
TITLE: Assembling Freedom #25
FILE: 260422-assembling-freedom-25.pdf
SOURCE: https://github.com/256foundation/News/blob/main/260422-assembling-freedom-25.pdf

4/22/26, 4:52 PM                                             (2) Assembling Freedom #25 - by 256 Foundation


                   Assembling Freedom #25
                   Touchscreens, Thermostats, and Doom: A Weekend of Open Mining Hacks
                          256 FOUNDATION
                          APR 22, 2026


                                                                                                              Share


                   April 22, 2026 | Hosted by @econoalchemist, @skot9000, & @tylerkstevens
                   Bitcoin mining, freedom tech, and awesome tangents from POD256 #113

                   Tech enthusiasts, this episode is pure weekend-warrior gold for open-source Bitcoin
                   mining hackers. The 256 Foundation crew breaks down a frenzy of community-driven
                   hardware hacks, firmware breakthroughs, and practical integrations that turn miners
                   into smart home devices, retro gaming rigs, and even heating systems. No fluff—just
                   actionable prototypes, real-world limits, and the open hardware momentum making
                   closed-source tricks obsolete.


https://256foundation.substack.com/p/assembling-freedom-25                                                            1/19

4/22/26, 4:52 PM                                             (2) Assembling Freedom #25 - by 256 Foundation


                   1. Skot’s Touchscreen Miner Retrofit: The Ampminer
                   Prototype on S19j Pro
                   Skot walks through a clean, Wi-Fi-enabled retrofit on a stock Bitmain Antminer S19j
                   Pro using Mujina firmware. Key innovation: tapping the hidden USB port for
                   connectivity without ripping open the case.

                   Core Hack Breakdown (Step-by-Step as Discussed):

                       Firmware: Flash Mujina directly onto the stock control board (Ethernet/USB
                       method).
                       Connectivity: Hidden USB port + USB hub → Wi-Fi dongle for wireless operation.

                       Display: Repurposed open-source touchscreen (sourced from Bitaxe GT Touch
                       ecosystem) wired via USB hub.

                       Dashboard: Live readouts for hashrate, temperatures, fan speeds, and pool stats—
                       right on the miner itself.

                       Bonus: Native support for AC Infinity duct fans for quieter, smarter cooling.


https://256foundation.substack.com/p/assembling-freedom-25                                                    2/19

4/22/26, 4:52 PM                                             (2) Assembling Freedom #25 - by 256 Foundation


                   This creates a “tidy, Wi-Fi-connected touchscreen miner” that feels like a consumer
                   appliance. AI-assisted CAD and browser automation sped up the prototyping loop
                   dramatically.

                   Visual: Bitaxe Touch-style interface concept (the exact screen tech reused here)


https://256foundation.substack.com/p/assembling-freedom-25                                                    3/19

4/22/26, 4:52 PM                                             (2) Assembling Freedom #25 - by 256 Foundation


                   Related X Post Spotlight
                   @skot9000 shared the first working prototype:


https://256foundation.substack.com/p/assembling-freedom-25                                                    4/19

4/22/26, 4:52 PM                                                     (2) Assembling Freedom #25 - by 256 Foundation


                    “First working prototype of The Ampminer: A stock S19j Pro running Mujina
                    firmware with a touchscreen (from the Bitaxe GT Touch). Full WiFi connection.
                    Native AC Infinity duct fan support.”


                                                   skot
                                                   @skot9000

                                       First working prototype of The Ampminer: A stock S19j Pro running Mujina
                                       firmware with a touchscreen (from the Bitaxe GT Touch). Full WiFi
                                       connection. Native AC Infinity duct fan support.


https://256foundation.substack.com/p/assembling-freedom-25                                                            5/19

4/22/26, 4:52 PM                                                             (2) Assembling Freedom #25 - by 256 Foundation


                                       8:23 PM · Apr 17, 2026 · 7.01K Views

                                       25 Replies · 34 Reposts · 176 Likes


                   Components Table


https://256foundation.substack.com/p/assembling-freedom-25                                                                    6/19

4/22/26, 4:52 PM                                             (2) Assembling Freedom #25 - by 256 Foundation


                   2. LibreBoard + Thermostats: Turning Miner Waste Heat
                   into Smart Home Heating
                   The crew brainstorms (and prototypes) using LibreBoard (the 256 Foundation’s open-
                   source mining control board) as a bridge between standard 24V home thermostats and
                   Bitcoin miners.


https://256foundation.substack.com/p/assembling-freedom-25                                                    7/19

4/22/26, 4:52 PM                                             (2) Assembling Freedom #25 - by 256 Foundation


                   Technical Deep Dive:

                       Bridge Logic: LibreBoard translates thermostat “heat calls” into miner ramp-
                       up/down commands.

                   Control Modes Compared:

                       Binary Heat Calls: On/off—simple but inefficient (full power or nothing).
                       Ramp Control: Gradual frequency scaling for smoother heat output.
                       PID Loops: Discussed for precise temperature targeting (Proportional-Integral-
                       Derivative control to minimize overshoot).
                       Firmware Limits: Frequency tuning works differently across Mujina vs. stock vs.
                       LuxOS—real-world testing shows hardware caps on older ASICs.

                   This is perfect for home miners: excess heat warms your house while the miner earns
                   sats. Community builds already include filament dryers heated by hashrate.

                   Visual: Waste-heat reuse in action (3D printer/filament dryer example using miner
                   exhaust)

https://256foundation.substack.com/p/assembling-freedom-25                                                    8/19

4/22/26, 4:52 PM                                             (2) Assembling Freedom #25 - by 256 Foundation


                   Catch the full interview with PizzAndy in this Tom’s Hardware article.

                   Control Modes Table


https://256foundation.substack.com/p/assembling-freedom-25                                                    9/19

4/22/26, 4:52 PM                                             (2) Assembling Freedom #25 - by 256 Foundation


                   3. Schnitzel’s Doom-on-LibreBoard Test (#LibreDOOMAxe)
                   Pure hacker joy: Schnitzel got Doom running on the LibreBoard paired with a Bitaxe
                   hashboard. Mujina firmware treats the Bitaxe like a hashboard via bitaxe-raw, with
                   real-time stats on an OLED display, Qwiic-connected temp sensors, fan RPM control,
                   and even RGB temperature indicators. HDMI output shows the 256 Pool dashboard.

                   Why It Matters: Open firmware (Mujina + LibreBoard) makes proprietary “trick
                   boards” obsolete. The path to full open firmware on WhatsMiners is accelerating—
                   goodbye to vendor lock-in.


https://256foundation.substack.com/p/assembling-freedom-25                                                    10/19

4/22/26, 4:52 PM                                             (2) Assembling Freedom #25 - by 256 Foundation


                   Visual: LibreBoard in action (open hardware control boards)


https://256foundation.substack.com/p/assembling-freedom-25                                                    11/19

4/22/26, 4:52 PM                                                         (2) Assembling Freedom #25 - by 256 Foundation


                   Related X Post Spotlight

                   @Schnitzel (LibreBoard lead engineer):

                     “LibreBoard Revision 1/2 testing continues: I built a LibreBoard-Axe! Mujina
                     running on Libreboard with a Raspberry Pi CM5… And obviously the best:
                     completely open source hardware and software.”


                                                   Michael Schmid   ⚡️
                                                   @Schnitzel

                                       LibreBoard Revision 1/2 testing continues:
                                       I built a LibreBoard-Axe!
                                       - Mujina running on Libreboard with a Raspbeery Pi CM5.
                                       - Connected via USB to a Bitaxe Gamma running Bitaxe RAW Firmware
                                       (allows Mujina to mine on the Bitaxe like it is a hash board)
                                       - Real-time mining stats on


https://256foundation.substack.com/p/assembling-freedom-25                                                                12/19

4/22/26, 4:52 PM                                                             (2) Assembling Freedom #25 - by 256 Foundation


                                                  0:00


                                       6:30 AM · Apr 16, 2026 · 4.5K Views

                                       6 Replies · 8 Reposts · 43 Likes


                   And the Doom tease:

                     “But can it run Doom? #LibreDOOMAxe” (with follow-up tests including MIPI DSI
                     touch displays and full Raspberry Pi HAT support).


                                                   Michael Schmid   ⚡️
                                                   @Schnitzel

                                       24h later we tested more! What should we test next on the LibreBoard by
                                       @256FOUNDATION ?

                                       - MIPI DSI Port with a Display with Touch!


https://256foundation.substack.com/p/assembling-freedom-25                                                                    13/19

4/22/26, 4:52 PM                                                            (2) Assembling Freedom #25 - by 256 Foundation


                                       - Full Raspberry Pi HAT via Sense Hat with joystick, Accelerometer,
                                       Gyroscope, Brightness, Pressure and a fun 8x8 RGB LED Matrix
                                       - Finally powered


                                                  0:00


                                                Michael Schmid   ⚡️ @Schnitzel
                                          LibreBoard Revision 1/2 testing continues:
                                          I built a LibreBoard-Axe!
                                          - Mujina running on Libreboard with a Raspbeery Pi CM5.
                                          - Connected via USB to a Bitaxe Gamma running Bitaxe RAW Firmware
                                          (allows Mujina to mine on the Bitaxe like it is a hash board)
                                          - Real-time mining stats on

                                       6:08 AM · Apr 17, 2026 · 11.3K Views

                                       6 Replies · 6 Reposts · 43 Likes


                   Visual: Bitaxe open-source miner (the hashboard used in the LibreDOOMAxe build)

https://256foundation.substack.com/p/assembling-freedom-25                                                                   14/19

4/22/26, 4:52 PM                                             (2) Assembling Freedom #25 - by 256 Foundation


https://256foundation.substack.com/p/assembling-freedom-25                                                    15/19

4/22/26, 4:52 PM                                             (2) Assembling Freedom #25 - by 256 Foundation


                   4. Firmware, PSU, & Stratum V2 Momentum
                       LuxOS Update: New “ignore PSU link” option—huge for custom PSU mods (120V
                       hacks discussed in detail).


https://256foundation.substack.com/p/assembling-freedom-25                                                    16/19

4/22/26, 4:52 PM                                             (2) Assembling Freedom #25 - by 256 Foundation


                       WhatsMiners: Rapid progress toward open firmware; hardware hacks like trick
                       boards become unnecessary.

                       Stratum V2: BlitzPool’s solo pool + non-custodial PPLNS roadmap. Vision for a
                       node-native, open block-template app that could unlock true decentralized
                       mining.

                   Community Shoutouts: - OpenSats’ Open Hardware Impact Reporthighlighting Bitaxe,
                   BitShoka/BitSoka Nini, and the 256 Foundation.

                       New features on hardestblocks.org and the growing dash.256f.org roster.
                       Wild builds: BitForge Nano, hashrate-heated filament dryers.


                   Key Takeaways for Tech Enthusiasts
                       Open hardware wins: LibreBoard + Mujina turns expensive ASICs into
                       customizable, Wi-Fi, touchscreen, heating, and gaming devices.

                       Rapid iteration: AI CAD + community testing = prototypes in days.


https://256foundation.substack.com/p/assembling-freedom-25                                                    17/19

4/22/26, 4:52 PM                                             (2) Assembling Freedom #25 - by 256 Foundation


                       Practical Freedom: Waste heat reuse, no dev fees, decentralized pools—Bitcoin
                       mining as a true home freedom tech.

                   Catch the full episode on your favorite pod app (Fountain, Apple, Podverse, etc.) or
                   watch the live replay. The 256 crew heads to Bitcoin 2026 in Vegas next week for
                   panels on open hardware and human rights.

                   Stay mining, stay hacking.
                   Support POD256 via Zaprite (Bitcoin or fiat). Follow @256FOUNDATIONand the
                   hosts for prototype drops and next-week live updates.

                   Generated from Episode 113 show notes & community context. All projects 100% open source
                   —fork, build, improve.

                   All of our newsletters are published under the CC0 1.0 license.


                   Discussion about this post


https://256foundation.substack.com/p/assembling-freedom-25                                                    18/19

4/22/26, 4:52 PM                                                           (2) Assembling Freedom #25 - by 256 Foundation


                   Comments          Restacks


                     Write a comment...


                                                    © 2026 The 256 Foundation · Privacy ∙ Terms ∙ Collection notice
                                                                Substack is the home for great culture


https://256foundation.substack.com/p/assembling-freedom-25                                                                  19/19


===== DOCUMENT 26 of 27 =====
DATE: 2026-05-13
LABEL: May 13, 2026
TITLE: Assembling Freedom #26
FILE: 260513-assembling-freedom-26.pdf
SOURCE: https://github.com/256foundation/News/blob/main/260513-assembling-freedom-26.pdf

5/13/26, 5:44 PM                                             (3) Assembling Freedom #26 - by 256 Foundation


                   Assembling Freedom #26
                   Insights from POD256 Episode 114: Open Source Wins in Vegas – $100k Boost, DoomAxe
                   Demo, & Telehash #4
                          256 FOUNDATION
                          MAY 13, 2026


                                                                                                              Share


                   Bitcoin Mining, Freedom Tech, and Awesome Tangents
                   May 13, 2026

                   Hosts: @econoalchemist, @skot9000, @tylerkstevens
                   Streamed live from Bitcoin Park, Nashville, TN

                   Tech enthusiasts, this week’s catch-up episode is pure fire for anyone building,
                   hacking, or just geeking out over decentralized Bitcoin mining. After a whirlwind
                   Vegas trip (Bitcoin 2026 conference), the hosts break down open-source victories: a
                   surprise $100k community-voted grant, live demos that stole the show, and why

https://256foundation.substack.com/p/assembling-freedom-26                                                            1/24

5/13/26, 5:44 PM                                             (3) Assembling Freedom #26 - by 256 Foundation


                   transparent hardware + firmware is the real North Star—even when ASICs stay closed-
                   source. They preview Telehash #4 (May 19 in Austin), drop foundation updates, and
                   share home-mining war stories. No episode next week (TEMS break), but they’ll be live
                   for Telehash #4 and back with POD256 on May 27.

                   Grab the full audio on Fountain, Spotify, or wherever you pod. Support the show: here.


                   1. Vegas Recap: Open Source Mining Debate & Why It
                   Matters
                   The crew recaps panels, debates, and floor demos from Bitcoin 2026 in Las Vegas. The
                   standout: a spirited on-stage debate about open-source mining hardware.

                   Key technical takeaways (bullet breakdown for the nerds):

                       Chip closed-ness ≠ invalidate open-source hardware. ASICs (like those from
                       Bitmain or others) may remain proprietary at the silicon level, but the surrounding
                       hardware design being open-source is the defining aspect. 256F is building the
                       whole ecosystem—control boards, firmware, hashboards, fleet management, and


https://256foundation.substack.com/p/assembling-freedom-26                                                    2/24

5/13/26, 5:44 PM                                             (3) Assembling Freedom #26 - by 256 Foundation


                       pools—all fully open and community-driven. This transparency is the “North
                       Star.”

                       Community tooling wins: rapid PRs, forkable designs, and scam-resistant
                       collaboration beat black-box hardware every time.

                       Real-world proof: live integrations and demos showed how open stacks let anyone
                       add features without vendor approval.

                   Visual: Bitcoin 2026 Conference Energy


https://256foundation.substack.com/p/assembling-freedom-26                                                    3/24

5/13/26, 5:44 PM                                             (3) Assembling Freedom #26 - by 256 Foundation


                   Related X buzz from the floor:


https://256foundation.substack.com/p/assembling-freedom-26                                                    4/24

5/13/26, 5:44 PM                                                       (3) Assembling Freedom #26 - by 256 Foundation


                    “This is what open-source mining looks like. Proto mining demoing live at Bitcoin
                    2026: a compact mining box with FOSS fleet management, a built-in touchscreen,
                    and a PR for Mujina firmware submitted on the conference floor.” —
                    @TFTC21(quoted by @256FOUNDATION)


                                                   256 Foundation
                                                   @256FOUNDATION

                                       Find the DoomAxe at Bitcoin 2026,

                                       Featuring our open-source mining projects:

                                       Control board running open source firmware, hashing with an open source
                                       hash board to an open source pool, all now monitored through open source
                                       fleet management.

                                                TFTC @TFTC21

                                          This is what open-source mining looks like.

                                          Proto mining demoing live at Bitcoin 2026: a compact mining box with
                                          FOSS fleet management, a built-in touchscreen, and a PR for Mujina
                                          firmware submitted on the conference floor.


https://256foundation.substack.com/p/assembling-freedom-26                                                              5/24

5/13/26, 5:44 PM                                                           (3) Assembling Freedom #26 - by 256 Foundation


                                          h/t @256FOUNDATION

                                       3:54 PM · Apr 28, 2026 · 2K Views

                                       2 Replies · 3 Reposts · 29 Likes


                   Mario Kart tournament side event? Filled a 3,000,000-sat prize pot. Pure community
                   vibes.


                                                   Brianna HD
                                                   @briimhd


                                       ⚡️
                                       Thank you @TheBitcoinConf for having us on the Nakamoto stage this week!


                                       @D_plus__plus and I have brought Bitcoin-powered Mario Kart to
                                       conferences and events all over the world, but we’ve never been on a stage
                                       THIS BIG!

                                       Congratulations to the winner @thatsauchward who took


https://256foundation.substack.com/p/assembling-freedom-26                                                                  6/24

5/13/26, 5:44 PM                                                          (3) Assembling Freedom #26 - by 256 Foundation


                                       11:57 AM · May 1, 2026 · 1.61K Views

                                       7 Replies · 7 Reposts · 48 Likes


                   2. Star of the Show: Schnitzel’s DoomAxe Demo
                   Battery-powered portable Bitcoin miner… that also runs Doom. Yes, really. Built on the
                   Bitaxe platform by @Schnitzel, a 256 Foundation contributor, the DoomAxe stole
                   hearts (and hashpower) in Vegas.

                   Deep dive:

https://256foundation.substack.com/p/assembling-freedom-26                                                                 7/24

5/13/26, 5:44 PM                                             (3) Assembling Freedom #26 - by 256 Foundation


                       Hardware specs: Compact, touchscreen-enabled, runs open-source firmware
                       (Mujina), hashes via open hashboard design, connects to open pool (HydraPool),
                       all managed via open fleet software (Proto Fleet integrated on the fly!).
                       Why it’s a flex for open source: Gimmick aside, it proves any feature is now a PR
                       away—add a game, a battery pack, heat-reuse mods, whatever. No waiting for a
                       manufacturer.

                       Ties into prior episodes: Schnitzel’s Doom-on-LibreBoard test + touchscreen
                       hacks.

                   Visuals: The Bitaxe Ecosystem Powering DoomAxe


https://256foundation.substack.com/p/assembling-freedom-26                                                    8/24

5/13/26, 5:44 PM                                             (3) Assembling Freedom #26 - by 256 Foundation


                   (Classic Bitaxe BM1397 board – the open-source heart of DoomAxe)


https://256foundation.substack.com/p/assembling-freedom-26                                                    9/24

5/13/26, 5:44 PM                                             (3) Assembling Freedom #26 - by 256 Foundation


                   (Bitaxe Ultra 204 – compact, hackable, ready for portable mods)

https://256foundation.substack.com/p/assembling-freedom-26                                                    10/24

5/13/26, 5:44 PM                                             (3) Assembling Freedom #26 - by 256 Foundation


                   (Fully assembled Bitaxe with fan/heatsink – the portable foundation)

                   X Post Spotlight:


https://256foundation.substack.com/p/assembling-freedom-26                                                    11/24

5/13/26, 5:44 PM                                                          (3) Assembling Freedom #26 - by 256 Foundation


                    “Meet the ‘DOOMAXE’ — a battery-powered Bitcoin miner running a Bitaxe that
                    can also play DOOM                       🤯 Built by our contribution winners @256FOUNDATION”
                    — @MARAFoundation_ (with video)


                                                   MARA Foundation
                                                   @MARAFoundation_


                                                                      🤯
                                       Meet the “DOOMAXE” — a battery-powered Bitcoin miner running a Bitaxe
                                       that can also play DOOM

                                       Built by our contribution winners @256FOUNDATION


                                                  0:00


                                       1:50 PM · Apr 30, 2026 · 10.6K Views

                                       3 Replies · 6 Reposts · 58 Likes


https://256foundation.substack.com/p/assembling-freedom-26                                                                 12/24

5/13/26, 5:44 PM                                                          (3) Assembling Freedom #26 - by 256 Foundation


                    “Gimmick aside – the DOOMAXE represents the power of an open-source mining
                    stack. Any feature you want… is now just a PR away. Join the 256F team for
                    TELEHASH4 on May 19 in Austin TX!” — @256FOUNDATION


                                                   256 Foundation
                                                   @256FOUNDATION

                                       Gimmick aside - the DOOMAXE represents the power of an open-source
                                       mining stack.

                                       Any feature you want, barrier to overcome, or performance improvement, is
                                       now just a PR away.

                                       Join the 256F team for TELEHASH4 on May 19 in Austin TX to learn more!

                                       256foundation.org/telehash

                                                MARA Foundation @MARAFoundation_


                                                                              🤯
                                          Meet the “DOOMAXE” — a battery-powered Bitcoin miner running a
                                          Bitaxe that can also play DOOM

                                          Built by our contribution winners @256FOUNDATION

                                       1:56 PM · Apr 30, 2026 · 2.16K Views


https://256foundation.substack.com/p/assembling-freedom-26                                                                 13/24

5/13/26, 5:44 PM                                              (3) Assembling Freedom #26 - by 256 Foundation


                                       4 Reposts · 34 Likes


                   3. $100k MARA Foundation Grant Win – Full Breakdown
                   Huge W: 256 Foundation won MARA Foundation’s inaugural community-vote grant
                   ($100k). Funds extend runway for core open-source pillars +
                   storytelling/docs/community work.

                   The Four Core Pillars (table for quick scanning):


https://256foundation.substack.com/p/assembling-freedom-26                                                     14/24

5/13/26, 5:44 PM                                             (3) Assembling Freedom #26 - by 256 Foundation


                   Why this matters for tech enthusiasts: These four create a fully modular, forkable
                   Bitcoin mining stack. $100k keeps devs paid, docs updated, and momentum rolling.

                   X Reaction:

                     “256 Foundation on an absolute heater… Hit a block on livestream last January to
                     winning the community vote this past week in Vegas. Telehash #4 coming up!” —
                     @jacklesser_


https://256foundation.substack.com/p/assembling-freedom-26                                                    15/24

5/13/26, 5:44 PM                                                          (3) Assembling Freedom #26 - by 256 Foundation


                                                             🔋
                                                   jack lesser
                                                   @jacklesser_

                                       256 Foundation on an absolute heater (pun intended) over the last 15
                                       months.

                                       Hit a block on livestream last January to winning the community vote this
                                       past week in Vegas.

                                       Telehash #4 coming up next at @bitcoinpark_ Austin on 5/19!

                                       🤝 @skot9000 @tylerkstevens @econoalchemist
                                                TFTC @TFTC21

                                          MARA Foundation announces @256FOUNDATION as recipient of its
                                          $100,000 inaugural community contribution.

                                       11:15 AM · May 1, 2026 · 1.19K Views

                                       1 Reply · 4 Reposts · 14 Likes


                   4. 256 Foundation Updates
                       Revamped 256foundation.org – cleaner, more discoverable.

https://256foundation.substack.com/p/assembling-freedom-26                                                                 16/24

5/13/26, 5:44 PM                                             (3) Assembling Freedom #26 - by 256 Foundation


                       Self-hosted Discourse forum at forum.256foundation.org – scam-resistant support
                       & collaboration hub.

                       Regular Mujina dev calls to channel contributor energy.

                   Join the conversation: 256foundation.org | forum.256foundation.org


                   5. Upcoming: Telehash #4 – Austin, May 19
                   Live from Bitcoin Park in Austin. Think hashrate donation party + solo-mining
                   attempts.

                   What’s new:
                   - Hashrate donors via HashDash (dash.256f.org)
                   - Wrigley’s Block Party event for pre-buying solo hash
                   - Fresh “loyalty” gamification + leaderboard (thanks to @D_plus__plus & @jungly)
                   tracking total contributed hashes
                   - Attempt to solo-mine a block (again) for FOSS dev

                   X Hype:

https://256foundation.substack.com/p/assembling-freedom-26                                                    17/24

5/13/26, 5:44 PM                                                    (3) Assembling Freedom #26 - by 256 Foundation


                    “Just over one week away from Telehash #4! You can support FOSS mining with
                    hashrate on

                    https://dash.256f.org/

                    And now… we’re tracking total hashes contributed - aka the ‘loyalty leaderboard’!”
                    — @256FOUNDATION


                                                   256 Foundation
                                                   @256FOUNDATION

                                       Just over one week away from Telehash #4!

                                       You can support FOSS mining with hashrate on dash.256f.org

                                       And now, thanks to @D_plus__plus and @jungly, we're tracking total hashes
                                       contributed - aka the "loyalty leaderboard"!


https://256foundation.substack.com/p/assembling-freedom-26                                                           18/24

5/13/26, 5:44 PM                                                          (3) Assembling Freedom #26 - by 256 Foundation


                                       7:37 AM · May 11, 2026 · 1.49K Views

                                       4 Reposts · 17 Likes


https://256foundation.substack.com/p/assembling-freedom-26                                                                 19/24

5/13/26, 5:44 PM                                                            (3) Assembling Freedom #26 - by 256 Foundation


                     “Two weeks away from TELEHASH#4… Join us in person or online while we
                     attempt to solo mine a block (again) for FOSS mining development.” —
                     @tylerkstevens


                                                   Tyler Stevens⚡️🔥
                                                   @tylerkstevens

                                       Two weeks away from TELEHASH#4, live from @bitcoinpark_ in Austin Texas!

                                       Join us in person or online while we attempt to solo mine a block (again) for
                                       FOSS mining development.


                                          256foundation.org
                                          Telehash | 256 Foundation


                                       12:28 PM · May 4, 2026 · 763 Views

                                       5 Reposts · 9 Likes


                   Visual: Open-Source Hashboard Example


https://256foundation.substack.com/p/assembling-freedom-26                                                                   20/24

5/13/26, 5:44 PM                                             (3) Assembling Freedom #26 - by 256 Foundation


https://256foundation.substack.com/p/assembling-freedom-26                                                    21/24

5/13/26, 5:44 PM                                             (3) Assembling Freedom #26 - by 256 Foundation


                   (BM1387 open-source mining board – the kind of hardware the pillars enable)


                   6. Closing Bits: Home-Mining Lore & Node Wisdom
                   Solo-block luck stories, the joy (and heat) of running rigs at home, and a reminder: run
                   your own node. Open source isn’t just hardware—it’s sovereignty.

                   Call to Action
                   - Donate hashrate at dash.256f.org
                   - Join the forum
                   - Follow @256FOUNDATION, @skot9000, @tylerkstevens, @econoalchemist
                   - Next live: Telehash #4 (May 19) visit 256foundation.org/telehash to learn more.

                   Open source is winning. The stack is modular, the community is shipping, and the
                   Vegas grant proves the momentum is real. See you at Telehash #4—or in the next
                   episode.

                   Stay sovereign. Mine transparent. Hash on.    ⚡
                   All of our newsletters are published under the CC0 1.0 license.

https://256foundation.substack.com/p/assembling-freedom-26                                                    22/24

5/13/26, 5:44 PM                                                           (3) Assembling Freedom #26 - by 256 Foundation


                   Discussion about this post


                    Comments         Restacks


                     Write a comment...


                                                    © 2026 The 256 Foundation · Privacy ∙ Terms ∙ Collection notice
                                                                Substack is the home for great culture


https://256foundation.substack.com/p/assembling-freedom-26                                                                  23/24

5/13/26, 5:44 PM                                             (3) Assembling Freedom #26 - by 256 Foundation


https://256foundation.substack.com/p/assembling-freedom-26                                                    24/24


===== DOCUMENT 27 of 27 =====
DATE: 2026-05-27
LABEL: May 27, 2026
TITLE: Assembling Freedom #27
FILE: 260527-assembling-freedom-27.pdf
SOURCE: https://github.com/256foundation/News/blob/main/260527-assembling-freedom-27.pdf

5/27/26, 6:38 PM                                                    (8) Assembling Freedom #27 - by 256 Foundation


                              Assembling Freedom #27
                              From POD256 ep. 115 - Bitaxe to Exahash: Inside HydraPool’s Record Stress Test and
                              What’s Next
                                       256 FOUNDATION
                                       MAY 27, 2026


                                                                                                                     Share


                              Tech Enthusiast Edition – Deep Dive into Open-Source Bitcoin Mining, Pool Scalability, and
                              Hardware Innovation

                              Welcome to this in-depth newsletter recap of POD256 Episode 115 (streamed live from
                              Bitcoin Park). Hosts @econoalchemist, @skot9000, and @tylerkstevens break down the
                              open-source Bitcoin mining ecosystem’s biggest recent milestone: HydraPool’s record
                              live stress test during Telehash #4. They explore how hobbyist-grade single-chip
                              Bitaxe miners can coexist with exahash-scale renters, the technical wizardry behind
                              ultra-low rejection rates and server efficiency, cooling tech shifts, and the push for
                              industry-wide open standards via the 256 Foundation.

                              This episode is a masterclass in decentralized mining infrastructure. Expect detailed
                              metrics, protocol deep dives, hardware specs, and actionable insights for anyone
                              building, hacking, or scaling Bitcoin miners.


https://256foundation.substack.com/p/assembling-freedom-27                                                                   1/16

5/27/26, 6:38 PM                                                   (8) Assembling Freedom #27 - by 256 Foundation


                              1. The Record-Breaking HydraPool Stress Test: Raw Metrics
                              & Why They Matter
                              HydraPool (part of the 256 Foundation’s open-source stack) handled a 6.5-hour live
                              stress test that pushed real-world limits while staying rock-solid. Key takeaway: a self-
                              hosted pool can scale from tiny hobby rigs to massive fleets with minimal overhead.

                              Stress Test Breakdown Table


https://256foundation.substack.com/p/assembling-freedom-27                                                                2/16

5/27/26, 6:38 PM                                                     (8) Assembling Freedom #27 - by 256 Foundation


                              Key Technical Insights (Bullet Breakdown):

                                    Rejection rates matter: In pooled mining, stale shares (late submissions) and
                                    “difficulty too low” shares waste bandwidth and reduce payouts. Sub-2% keeps
                                    efficiency sky-high vs. solo mining’s higher variance.

                                    Scalability win: >2,000 simultaneous connections at ~1% CPU proves HydraPool’s
                                    lightweight design (P2Pool v2-inspired with modern payout strategies). Perfect for
                                    self-hosting on modest hardware.

                                    Inclusivity engineering: Stratum “suggest difficulty” + custom password
                                    parameters (d= for starting difficulty, h= for hashrate hint) dynamically right-size
                                    difficulty. A 1 TH/s Bitaxe and a 1 EH/s fleet both connect seamlessly without
                                    manual tweaks.


https://256foundation.substack.com/p/assembling-freedom-27                                                                 3/16

5/27/26, 6:38 PM                                                      (8) Assembling Freedom #27 - by 256 Foundation


                              (Example of a modern mining pool dashboard showing real-time hashrate, shares efficiency,
                              and worker stats – HydraPool’s HashDash delivers similar live visibility.)


https://256foundation.substack.com/p/assembling-freedom-27                                                                4/16

5/27/26, 6:38 PM                                                  (8) Assembling Freedom #27 - by 256 Foundation


                              2. From Bitaxe to Exahash: Hardware Spectrum & Open-
                              Source UX Upgrades
                              Bitaxe represents the democratization of mining: affordable, Wi-Fi-enabled, fully
                              open-source design anyone can mod or build. The episode highlights how these tiny
                              rigs fit into exahash pools.

                              Bitaxe Model Comparison Table (Current Generation Examples)


                              Bullet Deep Dive:

                                    UX revolution: New LVGL-based UI (Figma-designed) + support for external
                                    displays/knobs. No more clunky web dashboards – plug-and-play like consumer

https://256foundation.substack.com/p/assembling-freedom-27                                                         5/16

5/27/26, 6:38 PM                                                                       (8) Assembling Freedom #27 - by 256 Foundation


                                    electronics.

                                    DOOMAXE fun: Community easter eggs show the playful hacker spirit behind
                                    serious infrastructure.

                                    Scale math: 1 EH/s ≈ 1.4 million Bitaxe Supra units. These home miners are debt-
                                    free, electricity-neutral, and censorship-resistant.


                                                             skot
                                                             @skot9000

                                                 1 EH/s hashrate would solve (on average, currently) a block every 4 days.
                                                 solochance.com

                                                 1 EH/s is 1 million TH/s, or about 1.4M #Bitaxe Supra

                                                 That's a legion of miners that;
                                                 - didn't take on debt to finance their hardware
                                                 - have no noticeable change in their
                                                 11:03 AM · May 9, 2024 · 30.8K Views

                                                 19 Replies · 44 Reposts · 204 Likes


https://256foundation.substack.com/p/assembling-freedom-27                                                                              6/16

5/27/26, 6:38 PM                                             (8) Assembling Freedom #27 - by 256 Foundation


https://256foundation.substack.com/p/assembling-freedom-27                                                    7/16

5/27/26, 6:38 PM                                                      (8) Assembling Freedom #27 - by 256 Foundation


                              (Upper: Bitaxe Gamma 602 in orange stand – compact, fan-cooled. Lower: Classic Bitaxe Duo
                              setup with clear open-source PCB visibility.)


                              3. Cooling Wars: Why Hydro Is Winning Over Immersion
                              The episode contrasts declining immersion cooling (dielectric fluid baths) with rising
                              hydro (water-based) solutions.


https://256foundation.substack.com/p/assembling-freedom-27                                                                8/16

5/27/26, 6:38 PM                                                  (8) Assembling Freedom #27 - by 256 Foundation


                              Pros/Cons Table


                              Insights: - Hydro enables quieter, more modular deployments – ideal for both home
                              Bitaxe rigs and industrial fleets. - Example: NerdQaxe Hydro variants hit sustained
                              high hashrates with integrated radiators and glowing aesthetics.


https://256foundation.substack.com/p/assembling-freedom-27                                                          9/16

5/27/26, 6:38 PM                                             (8) Assembling Freedom #27 - by 256 Foundation


https://256foundation.substack.com/p/assembling-freedom-27                                                    10/16

5/27/26, 6:38 PM                                                   (8) Assembling Freedom #27 - by 256 Foundation


                              (Upper: NerdQaxe Hydro – glowing water-cooled Bitaxe variant. Lower: Industrial immersion
                              farm tanks for contrast.)


                              4. Industry Standardization & The 256 Foundation Vision
                              Open reference designs for firmware (Mujina), control boards (LibreBoard),
                              hashboards (Ember One), and pools (HydraPool) slash costs and vendor lock-in risks.


https://256foundation.substack.com/p/assembling-freedom-27                                                                11/16

5/27/26, 6:38 PM                                                              (8) Assembling Freedom #27 - by 256 Foundation


                              Key Initiatives:

                                    GridPool “winners list”: Decentralized variance smoothing.

                                    Vardiff dynamics & Patoshi story: Historical context on nonce handling and
                                    difficulty adjustment.

                                    Security angle: FCC Wi-Fi rules, avoiding vendor backdoors – open firmware is
                                    critical.

                                    Privacy: VPN mining options for anonymity.

                                    Roadmap: Slowing ASIC efficiency gains mean software/infra innovation is the
                                    new frontier. Telehash #5 incoming; 256 Foundation’s Discourse forum and dev
                                    calls for collaboration.

                              Related X Posts (Community Pulse):

                                    From 256 Foundation (Jan 2026): “Lots of working going on behind the scenes…
                                    @D_plus__plus built this amazing public facing hashdash for us, you can start
                                    helping us stress test Hydra Pool now: https://dash.256f.org/”– Direct tie-in to the
                                    stress test prep.


                                                             256 Foundation
                                                             @256FOUNDATION


https://256foundation.substack.com/p/assembling-freedom-27                                                                     12/16

5/27/26, 6:38 PM                                                                  (8) Assembling Freedom #27 - by 256 Foundation


                                                 Lots of working going on behind the scenes to put together a very special
                                                 Telehash fundraiser, happening in just 9 days!

                                                 @D_plus__plus built this amazing public facing hashdash for us, you can start
                                                 helping us stress test Hydra Pool now:

                                                    dash.256f.org
                                                    256 Foundation • Hashdash


                                                 6:33 PM · Jan 12, 2026 · 3.61K Views

                                                 1 Reply · 3 Reposts · 8 Likes


                                    From @skot9000 (Bitaxe project instigator): “1 EH/s hashrate would solve (on
                                    average, currently) a block every 4 days… That’s a legion of miners that; - didn’t
                                    take on debt… are undetectable…” – Perfect encapsulation of the Bitaxe-to-exahash
                                    ethos.


                                                             skot
                                                             @skot9000

                                                 1 EH/s hashrate would solve (on average, currently) a block every 4 days.
                                                 solochance.com

                                                 1 EH/s is 1 million TH/s, or about 1.4M #Bitaxe Supra

                                                 That's a legion of miners that;


https://256foundation.substack.com/p/assembling-freedom-27                                                                         13/16

5/27/26, 6:38 PM                                                                       (8) Assembling Freedom #27 - by 256 Foundation


                                                 - didn't take on debt to finance their hardware
                                                 - have no noticeable change in their
                                                 11:03 AM · May 9, 2024 · 30.8K Views

                                                 19 Replies · 44 Reposts · 204 Likes


https://256foundation.substack.com/p/assembling-freedom-27                                                                              14/16

5/27/26, 6:38 PM                                                       (8) Assembling Freedom #27 - by 256 Foundation


                              (Aerial view of massive Bitcoin mining farm – visualizing the exahash end of the spectrum.)


                              What’s Next?
                                    Telehash #5 and expanded gamification (leaderboards, loyalty uptime).

                                    Call to ASIC makers and big miners: Adopt open standards for firmware, racks,
                                    cooling, and power.

                                    256 Foundation’s four pillars (Ember One, Mujina, LibreBoard, HydraPool) get
                                    runway extension via community grants.

                              This episode proves open-source Bitcoin mining isn’t niche anymore – it’s the scalable,
                              resilient future. Whether you run a single Bitaxe on your desk or rent exahash, the
                              tools are here.

                              Tune in: Full episode on Fountain, Spotify, or pod256.org. Support via zaprite link in
                              show notes.

                              Stay hashin’ – the open future is being built one pull request at a time.

                              (Newsletter generated directly from episode page and related sources for maximum technical
                              accuracy.)

                              All of our newsletters are published under the CC0 1.0 license.


https://256foundation.substack.com/p/assembling-freedom-27                                                                  15/16

5/27/26, 6:38 PM                                                                   (8) Assembling Freedom #27 - by 256 Foundation


                              Discussion about this post


                                Comments        Restacks


                   Write a comment...


                                                             © 2026 The 256 Foundation · Privacy ∙ Terms ∙ Collection notice
                                                                         Substack is the home for great culture


https://256foundation.substack.com/p/assembling-freedom-27                                                                          16/16
