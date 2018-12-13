# libtorch-mnist


cmake -DCUDA_HOST_COMPILER=/usr/bin/gcc-5 -DCMAKE_PREFIX_PATH=/path/to/libtorch ..

You need to call the fuction as follow
train(epoch, options, model, device, *train_loader, optimizer, **dataset_size.value()**);
test(model, device, *test_loader, **dataset_size.value()**);
