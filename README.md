# Spring AI Image

    curl -X POST http://localhost:8080/image \
     -H "Content-Type: application/json" \
     -d '{"question": "a beautiful sunset over the mountains"}' \
     --output image.png


    curl -X POST http://localhost:8080/vision \
     -F "file=@//Users/Emmett/dev/juniemvc/spring-ai-image/image.png" \
     -F "name=MyImageName"
    
