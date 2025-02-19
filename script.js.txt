setTimeout(function() {
    let button = document.querySelector("a#getLinkBtn, button");
    if (button) {
        button.click();
        console.log("تم الضغط على الزر!");
    } else {
        console.log("لم يتم العثور على الزر!");
    }
}, 5000);
