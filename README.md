![ezgif-4-873ad5c363](https://user-images.githubusercontent.com/28798918/196344576-28892c1f-6c5a-4749-83ea-54e12d633d36.gif)

Welcome To The Hentai Diffusion GitHub

Hentai Diffusion has been made to focus not only on hentai, but better hands and better obscure poses. 


# Better Animation:

We've improved animation abilities. Now subsequent images will be more coherent.

![monnotdonefiir](https://user-images.githubusercontent.com/28798918/196336931-5b245973-b62a-45f6-b51d-2354409bebda.gif)


# Better Obscure Camera Angles:

![00093-1765832306-best quality, {{{nsfw}}}, {{{masterpiece}}}, 1girl, monika _(doki doki literature club_, (breasts_0 984), (brown hair_0 989), (c](https://user-images.githubusercontent.com/28798918/196337316-1e6ada59-ad19-4b99-b72e-ad50a1aed32c.png)

![00092-1765832305-best quality, {{{nsfw}}}, {{{masterpiece}}}, 1girl, monika _(doki doki literature club_, (breasts_0 984), (brown hair_0 989), (c](https://user-images.githubusercontent.com/28798918/196337327-4269e706-ec74-43ea-ad1e-18cb36b078a8.png)

# Improving Style Consistency and Results:

We've been working on improving style consistency. In the upcomig release of HD-17 characters will look more cohesive. This can be easily changed by using any embeddings or hypernetworks. HD-17 also accepts style changes a bit easier, though that might be placebo.

![34342478](https://user-images.githubusercontent.com/28798918/197039065-5c0fe95c-7179-4585-874c-c9c39f5e5397.png)


# Better Real Photograph To Anime:

Effort has been put into getting HD working better with iti using real photographs as references. 

![645646](https://user-images.githubusercontent.com/28798918/196337131-46f89c57-0c85-477f-a03a-759f1ccc224a.gif)


# Small Study In The Wild:

Recently I've released a few images into the wild on different reddit accounts and pages. While most people seem indifferent or unable to tell the difference, a small group of users have been incredibly hostile. No posts were ever removed and it seems the more vocally negative user are an extreme minority, and most users are happy to get more art. The reasons for hostility range from inferiority or jealousy to something more of a perceived justice of "You didn't do that". Though given the vocality of some users I do feel it comes from a much deeper place than just not liking the produced art.

Seeing as the majority of users enjoy the content, reaching the top of a few pages, I feel this experiment was a success, but I do warn against doing this outside of collecting data. Since no harm was done, nothing was stolen, and overall it was a net gain to the communities as they gained some new art of their favorite characters, I am happy with leaving the art up. If you plan to post art generated by this A.I I recommend labeling it as such.

Below is one of the most successful examples.

![Screenshot (16089)](https://user-images.githubusercontent.com/28798918/196340759-24f40817-4db6-4f11-a38e-b1d8bb37ae9d.png)


# CFG Scale Testing:

Below is a graph to help guide you on which CFG scale works best for the style you need.

![xy_grid-0112-4283462332-1girl, monika _(doki doki literature club_, (breasts_0 984), (brown hair_0 989), (cleavage_0 586), (collarbone_0 746), (eyebrows](https://user-images.githubusercontent.com/28798918/196337574-809d51a6-15e8-497f-bd50-d832da29b265.png)

Euler ancestral provides the best results, and doesn't need to be changed.


# !!!! IMPORTANT | READ BEFORE DOWNLOADING !!!!
This model was built with the universal negative prompt in mind.
The text file can be found on Huggingface as well, copy and paste or save the text file and enter it as the negaive promp, which I would suggest you save as a style in WebUI.


## False Virus Flagging Update:

Windows defender, and only windows defender has chosen to flag some checkpoint files as false positives. I know it's shocking the king of false positives gave a false positive , but to the few people concerned, no it's not a virus, and I reccomend using MalwareByes or anything other than Windows Defender.


## Downloads:

Current Version HD-16: [Download](https://huggingface.co/Deltaadams/Hentai-Diffusion/resolve/main/HD-16.ckpt)

Negative Prompt [Download](https://huggingface.co/Deltaadams/Hentai-Diffusion/resolve/main/Universal%20Negative%20Prompt%20Text.txt)

Copy and paste into Neg Prompt area, save as style

# Getting Started:

### Step 1:

You'll need a way to run the chkpt file.
We reccomend using AUTOMATIC1111's UI
[Download](https://github.com/AUTOMATIC1111/stable-diffusion-webui/archive/refs/heads/master.zip)

Once you have the stable_diffusion_webui zip file, unzip it into the directory you want to use for Hentai Diffusion.

### Step 2:

Open the folder containing the files you just extracted, and go to this folder.

stable-diffusion-webui-master\models\Stable-diffusion

Place the .chkp file you downloaded into the folder.

### Step 3:

Return to the main directory.

stable-diffusion-webui-master\

On windows run webui-user.sh For linux use webui.sh

Let it run and download all the needed requirments. It may seem frozen at times but it is doing fine, just don't close the terminal.

### Step 4:

Open your browser to the local address shown in the terminal. It should be something like 127.0.0.1.

### Step 5:

Make sure to select Hentai Diffusion (or whatever the currect ckpt file name is) in the dropdown menu here.
![Screenshot (36)](https://user-images.githubusercontent.com/28798918/199120043-43101b77-3ca1-4d0c-a405-f79883525154.png)

### Step 6:

Take the negative prompt you downloaded and paste it into the negative prompt section.

Make sure the prompt field above it is empty.

![Screenshot (36)](https://user-images.githubusercontent.com/28798918/199120415-feeabca6-653b-45ec-a29a-bd8b8cf49aed.png)

### Step 7:

Click the save icon and name it whatever you want. Something like "Master Negative" is a good choice.

![Screenshot (34)](https://user-images.githubusercontent.com/28798918/199120627-d733b97c-43b6-4220-825b-054478a20c45.png)

### Step 8:

Whenever you start up the webui, select style one, and then the name of the master negative. You then click on the clipboard icon and it will add it to the field.

This is only needed once per session and as long as the browser isn't closed.

![Screenshot (34)](https://user-images.githubusercontent.com/28798918/199120705-4a377f21-309e-4865-ab0b-a3a60b130277.png)

### For best results:

Add "1girl, anime," without the quotes to the biggining of your prompt.


# Coming Soon

- Merged model with WF using the Inverse Sigmoid interpolation method with a 0.25 merger value.
- More Characters. Current supported characters include most characters with over 5,000 results on R34 and Gelbooru. Suggestions welcome on the "Issues" tab on this page.
