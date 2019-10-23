------------------------------------------
     
<p align="center">
 <img src="https://github.com/ctosp/manifest/blob/pie/Logo.png" > 
</p>

------------------------------------------

------------------------------------------
# CTos-p #
------------------------------------------

To get started with the building process, you'll need to get familiar with [Git and Repo](http://source.android.com/source/using-repo.html).


# To initialize your local repository, use a command like this:-

```bash
repo init -u git://github.com/ctosp/manifest.git -b pie
```

# To initialize a shallow clone, which will save even more space, use a command like this:-

```bash
repo init --depth=1 -u git://github.com/ctosp/manifest.git -b pie
```

# Then to sync up:- 

```bash
repo sync -c -j16 --force-sync --no-clone-bundle --no-tags
```

# Start the build:-

```bash
. build/envsetup.sh
lunch ctosp_<devicecodename>-userdebug
mka bacon -jx
 ```
---------------------------------------

Credits:
=======
 * [**AOSP**](https://android.googlesource.com)
 * [**PixelExperience**](https://github.com/PixelExperience)
 
----------------------------------------------

Stay tune to Telegram

* CTOSP Group Public : [**@Ctosp**](https://t.me/CTOSP)
* CTOSP-Announcement : [**@ctosp_feed**](https://t.me/ctosp_feed)
-----------------------------------------------
Copyright CTos-p  @copyright to Ctos-p author

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

     http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.
