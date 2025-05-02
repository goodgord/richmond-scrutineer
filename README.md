# Richmond Election Scrutineer Practice Tool

A simple web-based tool to help election scrutineers practice identifying preference flows in Australian preferential voting ballots for the Richmond electorate.

![Screenshot of the practice tool](https://i.imgur.com/placeholder.png) <!-- Replace with an actual screenshot once hosted -->

## About This Tool

This tool was created to help scrutineers prepare for the federal election in the Richmond electorate. It simulates the process of analyzing ballot papers to determine which party (Labor, Greens, or Nationals) the preferences will flow to based on Australia's preferential voting system.

### Features

- **Real Ballot Simulation**: Uses the actual candidate list and ballot order for the Richmond electorate
- **Preference Flow Training**: Practice identifying where preferences flow when a voter's first choice isn't one of the major parties
- **Multiple Difficulty Levels**: Adjust the time pressure to match your skill level
- **Detailed Feedback**: Receive immediate feedback and explanations when you make a mistake
- **Works Offline**: Can be downloaded and used without an internet connection

## How to Use

1. Visit the [live demo][(https://goodgord.github.io/richmond-scrutineer/)]() or download the HTML file to use offline
2. Choose your difficulty level and click "Start Practice"
3. Analyze the ballot paper and click on which party you think the preferences will flow to
4. Review your results and explanations
5. Track your score and improve your accuracy over time

## Understanding Preference Flows

In Australian preferential voting, if no candidate receives more than 50% of first-preference votes, the candidate with the fewest votes is eliminated. Their votes are then distributed to the remaining candidates according to the second preferences shown on those ballots. This process continues until a candidate has more than 50% of votes.

As a scrutineer, your job is to quickly determine which of the three major parties (Labor, Greens, or Nationals) will receive the vote after following the preference chain.

The preference flow logic works like this:
1. Start with the #1 preference on the ballot
2. If it's not one of three target parties (Labor, Greens, Nationals), move to #2
3. Continue following the preference chain until reaching one of the target parties
4. That's where the preference flows to

## Downloading and Running Locally

To use this tool offline:

1. Download the `index.html` file
2. Open it in any modern web browser
3. No internet connection required after initial download

## Technical Details

This tool is built using:
- HTML5
- CSS3
- JavaScript
- React (loaded from CDN)
- No server required - everything runs in the browser

## License

This project is available under the MIT License. Feel free to use, modify, and share it.

## Contributing

If you'd like to improve this tool, feel free to submit a pull request!

---

Created for the Australian federal election to help scrutineers in the Richmond electorate.
