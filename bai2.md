## Canvas Ve Hinh Chu Nha

    context.fillStyle = "green";
      context.fillRect(20, 20, 200, 200);
      context.strokeStyle = "rgba(0, 0, 255, 1)";
      context.lineWidth = 5;
      context.strokeRect(20, 20, 200, 200);

## Canvas Ve Duong Thang

    context.moveTo(0, 0);
      context.lineTo(500, 200);
      context.stroke();

## Canvas Hinh tron

context.beginPath();
context.arc(300, 150, 100, 0, 2 \* Math.PI);
context.stroke();

## Canvas Text

context.font = "24px Arial";
context.fillText("Xin chao cac ban", 100, 60);
