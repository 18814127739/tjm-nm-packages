## Available Scripts

In the project directory, you can run to install:

### `npm install compress-imgs -S`

how to use compress-imgs in your code? 

import { compressImgs } from "compress-imgs";

....
compressImgs(files, 300, 800, 800)
.then(compressFiles => {
    console.log(compressFiles)
})
.catch(err => {
    this.$message.error(err);
});


/*Method statement
 *@method compressImgs
 *@param{Array} files   An array of filesObj
 *@param{Integer} mSize   When file size is larger than mSize needs to compress
 *@param{Integer} maxWidth   The max width of image after compress 
 *@param{Integer} maxHeight   The max height of image after compress 
 *@return {Array} compressFiles  An array of filesObj after compress
*/