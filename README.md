# TiFastlane

Building apps for iOS it's all great until you have to deal with Certificates, Provisioning Profiles and sending iTunes Connect. Then came [fastlane.tools](https://fastlane.tools/) a collection of 9 tools that enable Continuous Deployment of iOS Apps.


* [Check out Documentation Folder](./docs/README.md)


## TODO

* Check `sudo` issue to have the fastlane gem installed automatically when installing TiFastlane
* Finalize and document `snapshot`
* Allow configuration of team id, team name, and specification of the default certificate to use

##  Collaborators

* [Uriel Lizama](https://github.com/ulizama)
* [Douglas Hennrich](https://github.com/DouglasHennrich)

##  Thanks

* [Felix Krause](https://github.com/KrauseFx) for creating the awesome fastlane.tools
* [Jason Kneen](https://github.com/jasonkneen) for creating some awesome CLI tools from which I'm basing this one

## Changelog
* 0.3.3 Update app version on send
* 0.3.2 Correct functionality of `tifast register [platform]`
* 0.3.1 You can now setup TiFastlane from the command line and you can choose which CLI to use. More documentation.
* 0.3.0 Added new tools [snapshot](https://github.com/KrauseFx/snapshot), [PEM](https://github.com/fastlane/PEM), [Pilot](https://github.com/fastlane/pilot)
* 0.2.3 Removed SKU delivery, automatic one will be generated by produce.
* 0.2.1 Send version on produce. Update SKU generator
* 0.2.0 Now you can upload your app update.
* 0.1.0 Now you can update your iTunes Connect metadata and screenshots (deliver)
* 0.0.3 Added register - Register App (produce + sigh)
* 0.0.1 Initial Commit

## License

<pre>
Copyright 2015 Uriel Lizama

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
</pre>
