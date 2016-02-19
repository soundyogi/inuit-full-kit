# inuit-full-kit

I found it hard to get an overview of all the inuit modules via github / npm 
so here are all modules from https://github.com/inuitcss as npm modules.

To get them clone this repo:

    git clone https://github.com/soundyogi/inuit-full-kit.git

then:

    cd inuit-full-kit
    npm i
    
## Import Order (tbd)

    @import "node_modules/inuit-defaults/settings.defaults";

    @import "node_modules/inuit-functions/tools.functions";
    @import "node_modules/inuit-mixins/tools.mixins";

    @import "node_modules/inuit-normalize/generic.normalize";
    @import "node_modules/inuit-box-sizing/generic.box-sizing";

    @import "node_modules/inuit-page/base.page";