# TableViewAnimation
Available for Swift 3+
A Swift extension for UITableView which makes animation easy


all you have to do for it to work is:

1. download the classes put them in your project

2. implement the func:
    > func tableView(_ tableView: UITableView, willDisplay cell: UITableViewCell, forRowAt indexPath: IndexPath)

3. call the func:
 > tableView.animateCells(AnimationFactory.makeMoveUpWithFade(rowHeight: cell.frame.height, duration: 0.5, delayFactor: 0.05), tableView: tableView, cell: cell, indexPath: indexPath)
 
 with the proper variables u want this is an example of moving the cells with fade animation
